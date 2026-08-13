<!--
Document metadata (from the original MadCap Flare source):
  Source: Content/_Common/Welcome/AWA/About_AWA.htm
  Title: About Automic Automation
  toc.xml <toc> label: AA_for_ICE
  Breadcrumb: Welcome
  xmlns:madcap: http://www.madcapsoftware.com/Schemas/MadCap.xsd
  lang: en-us
  xml:lang: en-us
  data-mc-search-type: Stem
  data-mc-help-system-file-name: help.xml
  data-mc-path-to-help-system: ../../../../
  data-mc-has-content-body: True
  data-mc-target-type: WebHelp2
  data-mc-runtime-file-type: Topic;Default
  data-mc-preload-images: false
  data-mc-in-preview-mode: false
  skin: _Skins_HTML5___Side_Navigation
  meta:viewport: width=device-width, initial-scale=1.0
  meta:charset: utf-8
  meta:Cache-Control: must-revalidate
  meta:X-UA-Compatible: IE=edge
  meta:Content-Type: text/html; charset=utf-8
-->

# About {{ vars.product_names.products_AWA }}

what is {{ vars.product_names.products_AWA }}

{{ vars.product_names.products_AWA }} is a product suite that provides workload automation for IT services across diverse platforms, applications, and Operation Systems. This includes batch processing and job scheduling, among other capabilities. {{ vars.product_names.products_AWA_short }} is technology-agnostic and can therefore interface and interact with virtually any IT ecosystem.

Over the years, enterprises engineer extensive customized IT infrastructures that create islands of automation that are not connected and that require manual input and output. In this fragmented landscape, sharing data, business processes and computing resources across systems requires an enormous effort and is usually unsuccessful. The lack of transparency and visibility prevents efficient monitoring and an early identification of potential problems in your processes. Without an end-to-end view of the entire system, you can neither react quickly nor optimize your operations. {{ vars.product_names.products_AWA }} provides the visibility, scalability and flexibility needed to respond to these challenges.

## Native Clustered Architecture

{{ vars.product_names.products_AWA }} architecture

The {{ vars.product_names.products_AE }} ({{ vars.product_names.products_AE_short }}) is {{ vars.product_names.products_AWA }}'s backend. In charge of the automation logic, the {{ vars.product_names.products_AE }} handles millions of automated tasks per day and stores the data in a centralized database. Because the automation core is centralized and it provides extensive auditing and reporting functionality, {{ vars.product_names.products_AWA }} ensures transparency and real time information as to what is happening at any given time across the enterprise.

The {{ vars.product_names.products_AE }} is connected to Agents, a distributed set of integrations to existing applications (on-premises and cloud). Agents are programs that are installed on the host where automation is required (the automation island, whether this is a platform, an application, an Operation System, and so forth). They run in the background and do not have a user interface.

The Agents execute the commands sent by the {{ vars.product_names.products_AE }} and create log files that record what is happening. For example, if the {{ vars.product_names.products_AE }} starts a Job in an Operating System Agent (a Windows Agent, for instance), the Job is executed in the Windows system. The Agent monitors the Job and reports its status to the {{ vars.product_names.products_AE }}. The communication between the {{ vars.product_names.products_AE }} and its Agents is bidirectional.

The {{ vars.product_names.products_AWI }} ({{ vars.product_names.products_AWI_short }}) is {{ vars.product_names.products_AWA }}'s web-based graphical user interface. In addition to standard browser functions, {{ vars.product_names.products_AWI_short }} provides proprietary tools that assist end users in their daily work. Created with the end users in mind, {{ vars.product_names.products_AWI_short }} is an intuitive, easy-to-use interface that helps reduce the complexity of designing and configuring automation processes.

For more information about {{ vars.product_names.products_AWA }}'s architecture, see:

- [Automic Automation Architecture](awaarchitecture.md.hbs)
- [Multi-Server Operations](../../../awa/admin/admin_multi_server_operation.md.hbs)
- [Understanding the Automic Web Interface](../../gettingstarted/gs_overviewawi.md.hbs)

## Multitenancy

{{ vars.product_names.products_AWA }} tenants, clients in {{ vars.product_names.products_AWA }},{{ vars.product_names.products_AWA }} multitenancy

{{ vars.product_names.products_AWA_short }} provides out-of-the-box multitenancy. A single instance of the software centrally serves multiple tenants (called Clients). System administrators assign Clients to Agents. Thus, Clients are segregated, self-contained environments that can be configured to depict different business and operational areas.

For more information about the multitenancy capabilities of {{ vars.product_names.products_AWA_short }}, see:

- [Clients](../../../awa/administrationperspective/ag_clients.md.hbs)
- [Example: Creating a Basic Client/User Landscape](../../../awa/usecases/usermanagement/creatingbasicuserlandscape.md.hbs)

## Object-Oriented Design

{{ vars.product_names.products_AWA }} objects

With its object-oriented design, {{ vars.product_names.products_AWA }} allows a single task definition to run with different parameters on hundreds of target systems as many times as needed. An object is a template that contains configuration settings for a self-contained process (a Job, for example) or for a part of a process (a task that sends an email to the stakeholders in a Workflow).

You define an object only once and reuse it across your system. Suppose you have a backup process that must run on all database servers, which can be located on-premise, in a private cloud or a mix of both. A full backup runs once a week and an incremental backup runs every second day. Instead of having to create hundreds of individual tasks, {{ vars.product_names.products_AWA }} lets you create and run a single object and reuse it (and, if necessary, customize each usage) in as many processes as needed.

For more information about {{ vars.product_names.products_AWA }}'s objects, see:

- [Understanding the Object Types in Automic Automation](../../../awa/objects/obj_classesandtypes.md.hbs)
- [Defining Automic Automation Objects](../../../awa/objects/obj_defining_objects.md.hbs)

### Jobs

{{ vars.product_names.products_AWA }} jobs,what are {{ vars.product_names.products_AWA }} jobs

Jobs are basic building blocks of automation. An {{ vars.product_names.products_AWA }} Job is a unit of work that is Agent-specific. There are Windows Jobs, UNIX Jobs, SAP Jobs, and so forth. A Job issues an instruction, which is a script, a command, or something else. The execution of a Job triggers some sort of work being performed on a system.

For more information about {{ vars.product_names.products_AWA }} Jobs, see [Jobs (JOBS)](../../../awa/objects/obj_job.md.hbs).

### Automating Data Transfer: File Transfers

{{ vars.product_names.products_AWA }} file transfers

{{> _file_transfers_similar_jobs_but_they}}

For more information about {{ vars.product_names.products_AWA }}'s file transfer capabilities, see:

- [File Transfers (JOBF)](../../../awa/objects/obj_file_transfer_defining.md.hbs)
- [Secure File Transfer Protocol](../../security/security_filetransfers.md.hbs)

### Orchestrating Processes: Workflows

{{ vars.product_names.products_AWA }} workflows,process orchestration in {{ vars.product_names.products_AWA }}

{{> _workflows_key_players_process_automation_they}}

{{> _example_workflow_could_do_following_stop}}

For more information about Workflows, see [Workflows (JOBP)](../../../awa/workflows/wf_overview.md.hbs).

### Automating Processes: Schedules

{{ vars.product_names.products_AWA }} schedules,time-driven task management through schedules in {{ vars.product_names.products_AWA }}

{{> _schedules_core_automation_objects_too_through}}

For more information about Schedules, see:

- [Schedules (JSCH)](../../../awa/objects/obj_schedule.md.hbs)
- [Example: Scheduling Tasks with Time and Calendar Conditions](../../../awa/objects/obj_jsch_example.md.hbs)

### Calendars

{{ vars.product_names.products_AWA }} calendars

So far, we have described some of the most important executable objects in {{ vars.product_names.products_AWA }}. However, there are other objects that are not executable but that play an important role in process automation.

Calendars are static objects that provide cycle calculation services. You create a Calendar in which you define cycles (every day, every Monday, first of the month, last day of the year, and so on). You then apply the Calendar to your executable object, which is then automated in accordance with those cycles.

For more information, see:

- [Calendars (CALE)](../../../awa/objects/obj_calendar.md.hbs)
- [Defining Calendar Events](../../../awa/objects/obj_calendarevents.md.hbs)
- [Examples of Useful Calendar Events](../../../awa/objects/obj_cale_examples.md.hbs)

## {{ vars.product_names.products_AE }} Scripting

{{ vars.product_names.products_AWA }} has its own proprietary scripting language to help you code workload processes. For more information about the {{ vars.product_names.products_AE }} scripting language, see:

- [Scripting and the Automation Engine Scripting Language](../../../script/writing/ae_scripting_language.md.hbs)
- [Automation Engine Script Reference](../../../script/reference.md.hbs)

## Automatic Processing (Executing)

Once automated processes are designed and scheduled, you execute them. Object execution can be triggered manually or automatically.

For more information, see:

- [Executing Objects](../../../awa/executions/obj_executing_overview.md.hbs)
- [Execution Options](../../../awa/executions/obj_executionoptions.md.hbs)

## Monitoring and Auditing

{{ vars.product_names.products_AWA }} provides full reporting and auditing capabilities. When executing objects, the {{ vars.product_names.products_AE }} writes comprehensive output files and reports that track all processes. The reports are organized to show what is happening across the enterprise. The can be easily accessed from the UI.

For more information about {{ vars.product_names.products_AWA }}'s auditing capabilities, see:

- [Tasks](../../../awa/procmonitoring/pm_tasksoverview.md.hbs)
- [Walkthrough of the Process Monitoring Perspective](../../../awa/procmonitoring/processmonitoring.md.hbs)
- [Monitoring Tasks](../../../awa/procmonitoring/pm_monitoringtasksoverview.md.hbs)
- [Understanding the Reports](../../../awa/reports/reports_overview.md.hbs)
- [Execution Data](../../../awa/reports/executions_overview.md.hbs)

## {{ vars.product_names.products_AaaS }}

While {{ vars.product_names.products_AWA }}'s reporting and auditing features provide a detailed representation of the status quo of your business processes, {{ vars.product_names.products_AaaS }} transforms that data into business intelligence. Using {{ vars.product_names.products_AWA }}'s powerful automation objects in dynamic dashboards, {{ vars.product_names.products_AaaS }} explores and interprets your business data. With this analysis, you can base your decision making on data-driven insight.

For more information, see [Analytics and Reporting](../../../analytics/anop_user/analyticsandreporting.md.hbs)

## Service Orchestration Capabilities

{{ vars.product_names.products_AWA }} service orchestration

With its powerful, reliable, and scalable Workflow capabilities and its extensive integration options, {{ vars.product_names.products_AWA }} can support even the most complex service orchestration scenarios. *Service orchestration* is the automated coordination of processes that span multiple domains or applications and may also include manual steps, such as human approval or intervention, to provide a service. At the heart of service orchestration is the Workflow. The overall process typically involves multiple Workflows for individual tasks. Nevertheless, one main Workflow orchestrates the tasks across the entire infrastructure. For more information, see [About Service Orchestration](../../../serviceorchestration/aso_about_service_orchestration.md.hbs).

See also:

[Watch the Video: Product Overview](welcome_productoverview_video.md.hbs)
