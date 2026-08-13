
# About {{ vars.product_names.products_AWA }}

what is {{ vars.product_names.products_AWA }}

{{ vars.product_names.products_AWA }} is a product suite that provides workload automation for IT services across diverse platforms, applications, and Operation Systems. This includes batch processing and job scheduling, among other capabilities. {{ vars.product_names.products_AWA_short }} is technology-agnostic and can therefore interface and interact with virtually any IT ecosystem.

{{ #if vars.productVersionConditions_24_1_0 }}
Over the years, enterprises engineer extensive customized IT infrastructures that create islands of automation that are not connected and that require manual input and output. In this fragmented landscape, sharing data, business processes and computing resources across systems requires an enormous effort and is usually unsuccessful. The lack of transparency and visibility prevents efficient monitoring and an early identification of potential problems in your processes. Without an end-to-end view of the entire system, you can neither react quickly nor optimize your operations. {{ vars.product_names.products_AWA }} provides the visibility, scalability and flexibility needed to respond to these challenges.
{{ /if }}

{{#if vars.guideConditions_AWA}}Many tables have an **Export Table** option that lets you extract their contents as comma-separated values in a CSV file. You can export large lists to CSV files to get an overview of the data, to sort them according to your needs, to compare them, and so on.{{/if}}

{{#if vars.guideConditions_AWA}}**Export All Columns / Visible Columns**{{/if}}

{{#if vars.guideConditions_AWA}}Some lists have many columns. While mandatory columns are always visible, you can show or hide non-mandatory columns. After you click **Export Table**, a dialog prompts you to select whether to export all columns or the visible ones only.{{/if}}

{{#if vars.guideConditions_AWA}}**Filtered Tables**{{/if}}

{{#if vars.guideConditions_AWA}}If you have filtered the data in the list, the exported CSV contains the filtered entries only.{{/if}}

{{#if vars.guideConditions_AWA}}**Sort Order**{{/if}}

{{#if vars.guideConditions_AWA}}The sort order of the entries in the CSV file is identical to the sort order in the list.{{/if}}

{{#if vars.guideConditions_AWA}}**Exporting Parent and Children Tasks**{{/if}}

{{#if vars.guideConditions_AWA}}If there are tasks with a parent/child relationship, to export both the parents and their children you must expand them. Otherwise, only the parents are exported. For example, in the list of **Tasks** in the {{ vars.product_names.uIElements_ProcessMonitoring }} perspective, Workflows, Schedules, and C_PERIODs are examples of tasks with a parent/child relationship; if you export the collapsed list of tasks, the CSV will contain the parent tasks.{{/if}}

{{#if vars.guideConditions_AWA}}**Number of Exported Records**{{/if}}

{{#if vars.guideConditions_AWA}}The number of entries in some lists is restricted by either a user setting or by a variable that is specified by your administrator. This limit also applies to the entries that are exported to the CSV.{{/if}}
