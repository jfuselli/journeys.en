---
product: adobe campaign
user-guide-title: Journey Orchestration
title: Journey Orchestration Guide
user-guide-description: Provides how-to instructions for implementing and building journeys.
index: yes
feature: Journeys
---

# [!DNL Journey Orchestration] Guide {#using}

+ [Product documentation](journey-orchestration-home.md)
+ What's new {#release-notes}
  + [Release Notes](using/release-notes/release-notes.md)
  + [Documentation Updates](using/release-notes/documentation-updates.md)
  + [Upgrade to Journey Optimizer](using/release-notes/upgrade-to-ajo.md)
+ Starting with [!DNL Journey Orchestration] {#starting-with-journeys}
  + [About [!DNL Journey Orchestration]](using/about/about-journey-orchestration.md)
  + [Limitations](using/about/limitations.md)
  + [Get started](using/about/get-started.md)
  + [User interface](using/about/user-interface.md)
  + [Access management](using/about/access-management.md)
  + [Troubleshooting](using/about/troubleshooting.md)
  + [Integrating with external systems](using/about/external-systems.md)
+ Configuring an event {#events-journeys}
  + About events {#about-events}
    + [General principle](using/event/about-events.md)
    + [Data cycle](using/event/about-data-cycle.md)
    + [Creating an event](using/event/about-creating.md)
    + [Leveraging Adobe Analytics](using/event/about-analytics.md)
    + [About ExperienceEvent Schemas](using/event/experience-event-schema.md)
    + [Additional steps to send events](using/event/additional-steps-to-send-events-to-journey-orchestration.md)
  + [Defining the payload fields](using/event/defining-the-payload-fields.md)
  + [Selecting the namespace](using/event/selecting-the-namespace.md)
  + [Defining the event key](using/event/defining-the-event-key.md)
  + [Previewing the payload](using/event/previewing-the-payload.md)
+ Configuring a data source {#data-source-journeys}
  + [About data sources](using/datasource/about-data-sources.md)
  + [Field groups](using/datasource/field-groups.md)
  + [Adobe Experience Platform data source](using/datasource/adobe-experience-platform-data-source.md)
  + [External data sources](using/datasource/external-data-sources.md)
+ Configuring an action {#action-journeys}
  + [About actions](using/action/action.md)
  + [Working with Adobe Campaign Standard](using/action/working-with-adobe-campaign.md)
  + [Working with Adobe Campaign v7/v8](using/action/acc-action.md)
  + Using a third-party system {#action-third-party}
    + [About custom action configuration](using/action/about-custom-action-configuration.md)
    + [URL configuration](using/action/url-configuration.md)
    + [Defining the action parameters](using/action/defining-the-message-parameters.md)
+ Using segments {#configuring-segment}
  + [About segments](using/segment/about-segments.md)
  + [Creating a segment](using/segment/creating-a-segment.md)
  + [Using segments in conditions](using/segment/using-a-segment.md)
+ Building a journey {#building-journeys}
  + About journey building {#about-journey-building}
    + [Creating a journey](using/building-journeys/journey.md)
    + [Using the journey designer](using/building-journeys/using-the-journey-designer.md)
    + [Changing properties](using/building-journeys/changing-properties.md)
    + [Journey versions](using/building-journeys/journey-versions.md)
    + [Terminating a journey](using/building-journeys/terminating-a-journey.md)
    + [Time zone management](using/building-journeys/timezone-management.md)
    + [Test profiles](using/building-journeys/creating-test-profiles.md)   
  + Activities {#about-journey-building}
    + Events activities {#events-activities}
      + [About events activities](using/building-journeys/event-activities.md)
      + [General events](using/building-journeys/general-events.md)
      + [Reaction events](using/building-journeys/reaction-events.md)
      + [Segment qualification events](using/building-journeys/segment-qualification-events.md)
    + Orchestration activities {#orchestration-activities}
      + [About orchestration activities](using/building-journeys/about-orchestration-activities.md)
      + [Condition activity](using/building-journeys/condition-activity.md)
      + [End activity](using/building-journeys/end-activity.md)
      + [Wait activity](using/building-journeys/wait-activity.md)
    + Action activities {#action-activities}
      + [About action activities](using/building-journeys/about-action-activities.md)
      + [Using Adobe Campaign Standard](using/building-journeys/using-adobe-campaign-actions.md)
      + [Using Adobe Campaign v7/v8](using/building-journeys/using-adobe-campaign-classic.md)
      + [Using custom actions](using/building-journeys/using-custom-actions.md)
      + [Jumping from one journey to another](using/building-journeys/jump.md)
      + [Update profile](using/building-journeys/update-profiles.md)
  + [Testing the journey](using/building-journeys/testing-the-journey.md)
  + [Publishing the journey](using/building-journeys/publishing-the-journey.md)
  + Sharing journey steps with Adobe Experience Platform {#sharing-journey-steps}
      + [Journey step sharing overview](using/building-journeys/sharing-overview.md)
      + [Step event field list](using/building-journeys/sharing-field-list.md)
      + Legacy step event fields {#legacy-step-event-fields}
          + [About legacy fields](using/building-journeys/sharing-legacy-fields.md)
          + [journeySteps events common fields](using/building-journeys/sharing-common-fields.md)
          + [journeyStep events action execution fields](using/building-journeys/sharing-execution-fields.md)
          + [journeyStep events data fetch fields](using/building-journeys/sharing-fetch-fields.md)
          + [journeyStep event identity fields](using/building-journeys/sharing-identity-fields.md)
          + [journey fields](using/building-journeys/sharing-journey-fields.md)
      + [Examples of queries](using/building-journeys/query-examples.md)
+ Build expressions {#building-advanced-conditions-journeys}
  + [Overview](using/expression/expressionadvanced.md)
  + Syntax {#syntax}
      + [Generalities](using/expression/generalities.md)
      + [Conditional instruction](using/expression/conditional-instruction.md)
      + [Data types](using/expression/data-types.md)
      + [Field references](using/expression/field-references.md)
      + [Collection management functions](using/expression/collection-management-functions.md)
      + [Operators](using/expression/operators.md)
      + [Journey properties](using/expression/journey-properties.md)
      + [Examples](using/expression/advanced-editor-use-cases.md)
  + Functions {#main-functions-journey}
    + [Main Functions](using/expression/functions.md)
    + Adobe Experience Platform {#adobe-experience-platform}
      + [inSegment](using/functions/functioninsegment.md)
    + Aggregation {#aggregation}
      + [avg](using/functions/functionavg.md)
      + [count](using/functions/functioncount.md)
      + [countOnlyNull](using/functions/functioncountonlynull.md)
      + [countWithNull](using/functions/functioncountwithnull.md)
      + [distinctCount](using/functions/functiondistinctcount.md)
      + [distinctCountWithNull](using/functions/functiondistinctcountwithnull.md)
      + [max](using/functions/functionmax.md)
      + [min](using/functions/functionmin.md)
      + [sum](using/functions/functionsum.md)
    + Conversion {#conversion}
      + [toBool](using/functions/functiontobool.md)
      + [toDateOnly](using/functions/functiontodateonly.md)
      + [toDateTime](using/functions/functiontodatetime.md)
      + [toDateTimeOnly](using/functions/functiontodatetimeonly.md)
      + [toDecimal](using/functions/functiontodecimal.md)
      + [toDuration](using/functions/functiontoduration.md)
      + [toInteger](using/functions/functiontointeger.md)
      + [toString](using/functions/functiontostring.md)
    + Date {#date}
      + [currentTime​InMillis](using/functions/functioncurrenttimeinmillis.md)
      + [inLastDays](using/functions/functioninlastdays.md)
      + [inLastHours](using/functions/functioninlasthours.md)
      + [inLastMonths](using/functions/functioninlastmonths.md)
      + [inLastYears](using/functions/functioninlastyears.md)
      + [inNextDays](using/functions/functioninnextdays.md)
      + [inNextHours](using/functions/functioninnexthours.md)
      + [inNextMonths](using/functions/functioninnextmonths.md)
      + [inNextYears](using/functions/functioninnextyears.md)
      + [now](using/functions/functionnow.md)
      + [nowWithDelta](using/functions/functionnowwithdelta.md)
      + [setHours](using/functions/functionsethours.md)
      + [setDays](using/functions/functionsetdays.md)
      + [updateTimeZone](using/functions/functionupdatetimezone.md)
    + List {#list}
      + [distinct](using/functions/functiondistinct.md)
      + [distinctWithNull](using/functions/functiondistinctwithnull.md)
      + [filter](using/functions/functionfilter.md)
      + [getListItem](using/functions/functiongetlistitem.md)
      + [in](using/functions/functionin.md)
      + [intersect](using/functions/functionintersect.md)
      + [limit](using/functions/functionlimit.md)
      + [listSize](using/functions/functionlistsize.md)
      + [serializeList](using/functions/functionserializelist.md)
      + [sort](using/functions/functionsort.md)
    + Math {#math}
      + [random](using/functions/functionrandom.md)
      + [round](using/functions/functionround.md)
    + String {#string}
      + [concat](using/functions/functionconcat.md)
      + [contain](using/functions/functioncontain.md)
      + [containIgnoreCase](using/functions/functioncontainwithignorecase.md)
      + [endWith](using/functions/functionendwith.md)
      + [endWithIgnorecase](using/functions/functionendwithignorecase.md)
      + [equalIgnoreCase](using/functions/functionequalignorecase.md)
      + [indexOf](using/functions/functionindexof.md)
      + [isEmpty](using/functions/functionisempty.md)
      + [isNotEmpty](using/functions/functionisnotempty.md)
      + [lastIndexOf](using/functions/functionlastindexof.md)
      + [length](using/functions/functionlength.md)
      + [lower](using/functions/functionlower.md)
      + [matchRegExp](using/functions/functionmatchregexp.md)
      + [notequalIgnoreCase](using/functions/functionnotequalignorecase.md)
      + [replace](using/functions/functionreplace.md)
      + [replaceAll](using/functions/functionreplaceall.md)
      + [split](using/functions/functionsplit.md)
      + [startWith](using/functions/functionstartwith.md)
      + [startWithIgnoreCase](using/functions/functionstartwithignorecase.md)
      + [substr](using/functions/functionsubstr.md)
      + [trim](using/functions/functiontrim.md)
      + [upper](using/functions/functionupper.md)
      + [uuid](using/functions/functionuuid.md)
+ Building your reports{#journey-reports}
  + [About journey reports](using/reporting/about-journey-reports.md)
  + [Creating your journey reports](using/reporting/creating-your-journey-reports.md)
  + [Metrics and dimensions](using/reporting/metrics-and-dimensions.md)
+ Integrating with Intelligent Services{#use-case-advanced}
    + [About AI integration](using/ai-services/ai-services-overview.md)
    + [Leveraging Customer AI](using/ai-services/leveraging-customer-ai.md)
+ Use cases{#use-cases-journeys}
  + Sending a personalized email{#use-case-simple}
    + [About the simple use case](using/usecase/about-the-simple-use-case.md)
    + [Configuring the event](using/usecase/configuring-the-event.md)
    + [Configuring the data source](using/usecase/configuring-the-data-source.md)
    + [Building the journey](using/usecase/simple-uc-building-the-journey.md)
  + Building a cross-channel journey{#use-case-advanced}
    + [About the advanced use case](using/usecase/about-the-advanced-use-case.md)
    + [Configuring the events](using/usecase/configuring-the-events.md)
    + [Configuring the data sources](using/usecase/configuring-the-data-sources.md)
    + [Building the journey](using/usecase/building-the-journey.md)
  + [Sending a message using Campaign v7/v8](using/usecase/campaign-classic-use-case.md)
  + [Passing collections dynamically using custom actions](using/usecase/collections.md)
+ Working with APIs{#working-with-apis}
  + [Capping APIs](using/api/capping.md)
