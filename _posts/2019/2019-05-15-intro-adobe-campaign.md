---
title: Quick Adobe Campaign intro (awesome-adobe-campaign)
categories: [opensource,adobe campaign]
permalink: /awesome-adobe-campaign
redirect_from: /2019-05-15-intro-adobe-campaign
---

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Adobe Campaign universe can be overwhelming and information is sparse. Here's a quick recap of resources. Based on the [Awesome Github lists](https://github.com/sindresorhus/awesome) concept.

This list only concerns Adobe Campaign Classic (and not the web-based version *Adobe Campaign Standard*).

<p class="text-center">🌟👓📧</p>

<!--more-->

## Table of Contents
- [Overview](#overview)
- [Tutorials](#tutorials)
- [Workspace](#workspace)
- [Basic objects](#basic-objects)
- [Javascript help](#javascript-help)
- [Changelog](#changelog)
- [Marketing Campaigns & Deliveries](#marketing-campaigns--deliveries)
- [Community](#community)
- [Support](#support)
- [Installation](#installation)
- [](#)

## Overview
- [Adobe Campaign Product Page on adobe.com](https://www.adobe.com/marketing/campaign.html)
- [About Adobe Campaign Classic](https://docs.campaign.adobe.com/doc/AC/en/PTF_Starting_with_Adobe_Campaign_About_Adobe_Campaign_Classic.html)
- [Main documentation portal](https://helpx.adobe.com/support/campaign/classic.html)
- [On-prem VS Hybrid VS Hosted](https://docs.adobe.com/content/help/en/campaign-classic/using/installing-campaign-classic/architecture-and-hosting-models/hosting-models.html) and [details as a table](https://helpx.adobe.com/campaign/kb/acc-on-prem-vs-hosted.html)
- [Architecture and Deployment types](https://docs.adobe.com/content/help/en/campaign-classic/using/installing-campaign-classic/deployment-types-/enterprise-deployment.html)
- [Global Search](https://docs.campaign.adobe.com/doc/AC/en/browseAC.html) - search in the ACC tutorials, the videos, the Knowledge Base and the Community Forum

## Tutorials
- [Official ACC tutorials](https://docs.campaign.adobe.com/doc/AC/en/PTF_Starting_with_Adobe_Campaign_Tutorials.html) - Tutorials as web pages
- [Official "How-To" videos](https://helpx.adobe.com/campaign/tutorials.html) - Video tutorials
- [Official "Using ACC" videos](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html) - Video tutorials NEW!
- [Official Knowledge base (kb)](https://helpx.adobe.com/campaign/kb/article-list.html)
- [Official workflow Use cases](https://docs.campaign.adobe.com/doc/AC/en/WKF_Use_cases_Using_the_local_approval_activity.html) - Business cases
- [Official workflow Best Practices](https://docs.campaign.adobe.com/doc/AC/en/WKF__General_operation_Workflow_best_practices.html)
- [Official Database Model Best Practices](https://helpx.adobe.com/campaign/kb/acc-data-model-best-practices.html)
- [Official FAQ](https://docs.campaign.adobe.com/doc/AC/en/PTF_Starting_with_Adobe_Campaign_Common_questions.html) - more than 85 questions and answers
- [floriancourgey.com tutorials](https://blog.floriancourgey.com/categories?id=adobe%20campaign)

## Workspace
- [Browsing Lists](https://docs.campaign.adobe.com/doc/AC/en/PTF_Starting_with_Adobe_Campaign_Adobe_Campaign_workspace.html#Browsing_lists) - Add/Remove a field in a list, count records, sort, search
- [Formats and Units](https://docs.adobe.com/content/help/en/campaign-classic/using/getting-started/starting-with-adobe-campaign/adobe-campaign-workspace.html#formats-and-units) - Date & time formats (US %2M/%2D/%4Y vs EN %2D/%2M/%4Y) and time units (s-seconds, mn-minute, h-hour, d-day)
- [Format dates](https://docs.campaign.adobe.com/doc/AC/en/DLV_Content_management_Formatting.html#Date_display)
- [Format Prices with NL.Locale](/2019/05/adobe-campaign-locale)
- [Folders organization Best Practices](https://helpx.adobe.com/campaign/kb/organization-folders-explorer.html)

## Basic objects
- [All about Recipients](https://docs.campaign.adobe.com/doc/AC/en/PTF_Profile_management_About_profiles.html)
- [All about Marketing Campaigns & Deliveries](https://docs.campaign.adobe.com/doc/AC/en/CMP_Orchestrate_campaigns_Setting_up_marketing_campaigns.html)
- [Data Schemas Reference](https://docs.campaign.adobe.com/doc/AC/en/CFG_Schema_Reference_Elements_and_attributes.html)
- [Input Forms Reference](https://docs.campaign.adobe.com/doc/AC/en/CFG_Input_forms_Form_structure.html)
- [Physical data Model & tables relations](https://docs.campaign.adobe.com/doc/AC/en/technicalResources/_Datamodel_Description_of_the_main_tables.html) - Relational diagrams between objects with primary keys, foreign keys and fields
- Repository of Activities: [Targeting](https://docs.campaign.adobe.com/doc/AC/en/WKF_Repository_of_activities_Targeting_activities.html), [Flow Control](https://docs.campaign.adobe.com/doc/AC/en/WKF_Repository_of_activities_Flow_control_activities.html), [Action](https://docs.campaign.adobe.com/doc/AC/en/WKF_Repository_of_activities_Action_activities.html), [Event](https://docs.campaign.adobe.com/doc/AC/en/WKF_Repository_of_activities_Event_activities.html)
- [External accounts](https://docs.campaign.adobe.com/doc/AC/en/PTF_Administration_basics_External_accounts.html)
- [Navigation hierarchy](https://docs.campaign.adobe.com/doc/AC/en/CFG_Navigation_hierarchy_Configuration.html)

## Cubes & Reports
- [Email a report as a PDF to a recipients list](https://docs.campaign.adobe.com/doc/AC/en/WKF_Use_cases_Sending_a_report_to_a_list.html)

## Marketing Campaigns & Deliveries
- [Delivery Best Practices - Marketing](https://docs.campaign.adobe.com/doc/AC/getting_started/EN/deliveryBestPractices.html)
- [Delivery Best Practices - Technical](https://docs.campaign.adobe.com/doc/AC/getting_started/EN/deliverability.html)
- [Multi-channel campaigns](https://helpx.adobe.com/campaign/kt/acc/using/acc-multi-channel-campaigns-feature-video-set-up.html)
- [Recurring vs Continuous deliveries - Adobe Doc](https://helpx.adobe.com/campaign/kt/acc/using/acc-recurring-delivery-tutorial-set-up.html)
- [Recurring vs Continuous deliveries - Adobe Forum](https://forums.adobe.com/thread/2204509)
- [Recurring vs Continuous deliveries - marketingcloudblog.com](https://marketingcloudblog.com/mcb_faq/difference-continuous-delivery-recurring-delivery-adobe-campaign/)
- [Javascript templating langage (JST) in deliveries](https://docs.campaign.adobe.com/doc/AC/en/DLV_Content_management_Formatting.html)
- [XSL templating langage (XSLT) for HTML and XML](https://docs.campaign.adobe.com/doc/AC/en/DLV_Content_management_Formatting.html#XSL_Stylesheets)
- [Workflows and deliveries](https://docs.campaign.adobe.com/doc/AC/en/WKF__General_operation_How_to_use_workflow_data.html#Sending_via_a_workflow) and [Enrich a Delivery with `targetData`](https://docs.campaign.adobe.com/doc/AC/en/WKF__General_operation_Executing_a_workflow.html#Target_data)

## Javascript help
- [Online Javascript API (JSAPI)](https://final-docs.campaign.adobe.com/doc/AC/en/jsapi/)
- [queryDef](https://blog.floriancourgey.com/2018/08/use-querydef-the-database-toolkit-in-adobe-campaign)
- [Web apps](https://blog.floriancourgey.com/2018/07/use-the-context-in-web-apps-in-adobe-campaign)
- [JSSP - Javascript Server Pages](https://blog.floriancourgey.com/2018/11/create-jssp-dynamic-javascript-server-page-in-acc/)

## Server help
- [serverConf.xml doc](https://docs.campaign.adobe.com/doc/AC/en/INS_Appendices_The_server_configuration_file.html)
- [serverConf.xml content](https://blog.floriancourgey.com/2018/10/get-the-content-of-your-serverconf-xml-in-adobe-campaign/)
- [SOAP API & web services](https://docs.campaign.adobe.com/doc/AC/en/CFG_API_About_web_services.html)
- [WSDL doc](https://docs.campaign.adobe.com/doc/AC/en/CFG_API_Web_service_calls.html#Web_service_description-_WSDL)
- [Database cleanup task (cleanup workflow)](https://docs.campaign.adobe.com/doc/AC/en/PRO_Data_processing_Database_cleanup_workflow.html)
- [nlserver doc](https://docs.campaign.adobe.com/doc/AC/en/PRO_Production_procedures_Operating_principle.html)
- [Logs - log files and folders](https://docs.campaign.adobe.com/doc/AC/en/PRO_Production_procedures_Log_files.html)

## Changelog
- [Latest Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - Changelog since the GDPR Update on 2018-04-24 (18.4 update - Build 8931)
- [Old Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN_legacy.html) - Changelog from ACC 6.11 8552 on 2014-05-21 to the GDPR update
- [Deprecated Features](https://helpx.adobe.com/campaign/kb/deprecated-and-removed-features.html) - Don't use those features, javascript calls and activities anymore as they might present a risk or a future malfunction

## Security & Privacy
- [Security Checklist](https://docs.campaign.adobe.com/doc/AC/getting_started/EN/security.html)
- [Getting Started with GDPR](https://docs.campaign.adobe.com/doc/AC/getting_started/EN/ACC_GDPR.html)

## Community
- [Official homepage for Campaign](https://forums.adobe.com/community/experience-cloud/marketing-cloud/campaign)
- [Official homepage for Campaign Classic](https://forums.adobe.com/community/experience-cloud/marketing-cloud/campaign/classic)
- [Official Forum](https://forums.adobe.com/community/experience-cloud/marketing-cloud/campaign/classic/content?filterID=contentstatus%5Bpublished%5D~objecttype~objecttype%5Bthread%5D&sortKey=score)
- [Submit an Idea](https://forums.adobe.com/create-idea!input.jspa?containerType=14&containerID=5724)
- [Browse Ideas](https://forums.adobe.com/community/experience-cloud/marketing-cloud/campaign/classic/content?filterID=contentstatus%5Bpublished%5D~objecttype~objecttype%5Bidea%5D&sortKey=score)
- [Get any new content on the Community](https://forums.adobe.com/search.jspa?after=week&place=%2Fplaces%2F17564959&depth=children&q=e*&sort=updatedDesc)
- [Official Youtube channel](https://www.youtube.com/channel/UCWU3Pm6LMcJRQHr375ZY5lw)

## Support
- [Certification, training & courses](https://training.adobe.com/training/courses.html#solution=adobeCampaign)
- [Errors codes and translations](https://docs.campaign.adobe.com/doc/AC/en/technicalResources/error_messages/error_codes.html)

*Links below require access from Adobe.*
- [Support tickets](https://support.neolane.net/ops/dashboardExtranet.jssp) - Create and manage communication with Adobe dedicated Support
- [Download center](https://support.neolane.net/webApp/downloadCenter) - Download installation RPM/EXE, Client EXE, JS API as CHM..

## Installation
- [Official prerequisites](https://docs.campaign.adobe.com/doc/AC/en/INS_Prerequisites_and_recommendations__Before_starting.html)
- [Official install for Linux](https://docs.campaign.adobe.com/doc/AC/en/INS_Installing_Campaign_in_Linux__Prerequisites.html)
- [Official install for Windows](https://docs.campaign.adobe.com/doc/AC/en/INS_Installing_Campaign_in_Windows__Prerequisites.html)
- [Install by floriancourgey.com on Virtualbox](https://blog.floriancourgey.com/2019/01/installing-adobe-campaign-locally)
- [Compatibility matrix](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html) - OS, web & database (RDBMS) servers, JDK  compatible versions

## Javascript Best Practices
- [Lightweight by W3schools](https://www.w3schools.com/js/js_best_practices.asp)
- [Straightforward by w3.org](https://www.w3.org/wiki/JavaScript_best_practices)
- [In-depth by Google](https://google.github.io/styleguide/javascriptguide.xml)
- [Collection of links on jstherightway.org](https://jstherightway.org)

## External tools
- [Excel column to CSV with delim.co](https://delim.co/)
- [Reverse Adobe Campaign log with FCO string tools](https://floriancourgey.github.io/tools/string/index.html)
- [Compare 2 files with diffchecker](https://www.diffchecker.com)
- [Rename multiple files with regex, prefixes, etc, with Bulk Rename Utility](https://www.bulkrenameutility.co.uk)
- [SMS Length Calculator on messente.com](https://messente.com/documentation/tools/sms-length-calculator)
- [Find brands using Adobe Campaign with Google dorks](https://www.google.com/search?q=inurl%3A%2Fnl%2Fjsp%2Fm.jsp) - doc on [Google dorks](/2018/12/crack-and-hack-cheatsheet#google)

<script>
  $(function(){
    $('main article a[href^=http]').attr('target', '_blank');
  });
</script>
