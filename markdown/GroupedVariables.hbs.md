<!--
Document metadata (from the original MadCap Flare source):
  Source: Content/_Common/Welcome/AWA/AWAArchitecture.htm
  Title: Automic Automation Architecture
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

# {{ vars.product_names.Products_AWA }} Architecture

Knowing the different modules and additional components that make {{ vars.product_names.Products_AWA }} and understanding their interaction and dependencies is essential, especially if you are a system administrator.

The core of an {{ vars.product_names.Products_AWA }} system is the {{ vars.product_names.Products_AE }}. An {{ vars.product_names.Products_AE }} system is a combination of the following modules:

- The {{ vars.product_names.Products_AE }} itself on a server
- The database (DB2, Oracle, MS SQL or {{ vars.product_names.3rdPartyNames_PostgreSQL }}), on the same or a different server of your choice
- The Agents, which communicate either through communication processes (CPs) or Java communication processes (JCPs) with the {{ vars.product_names.Products_AE }}
- The {{ vars.product_names.Products_AutomationAI }} component, which communicates with the {{ vars.product_names.Products_AE }} through the REST process
- The {{ vars.product_names.Products_AWI }}

![AA NEW Architecture Overview](../../../../Images/AA_NEW_ArchitectureOverview.png)

A number of ports must be open for {{ vars.product_names.Products_AWA }} communication. For detailed information on the default port definition, see [Configuring Firewall and Ports](../../Security/Security_Hardening_AEFirewallPorts.md.hbs).

In addition, {{ vars.product_names.Products_AWA }} as a bundle also contains products that enhance or support the setup you choose with various features. The following additional components are supplied with {{ vars.product_names.Products_AWA }}:

- {{ vars.product_names.Products_AaaS }}

    Collects and compiles large amounts of historical data about your {{ vars.product_names.Products_AE }} system for analysis and reporting.
- Package Manager

    Command line tool to retrieve, install or update packages on top of the {{ vars.product_names.Products_PlatformName }}.
- {{ vars.product_names.Products_PluginManager }}

    Extension to the {{ vars.product_names.Products_AWI_short }} that can be used to install, upgrade and remove Packs in order to extend the functionality of the {{ vars.product_names.Products_AWA }} system.
- {{ vars.product_names.Products_ActionBuilder }}

    Extension to the {{ vars.product_names.Products_AWI_short }} that allows users to create new Actions (sets of objects) for common operations to be used in workflows.
- {{ vars.product_names.Products_LdapSync }}

    TLS-supported user permission and credential management that integrates Microsoft Active Directory (AD) or Oracle Directory Services (ODS).
- {{ vars.product_names.Products_PROXY }}

    Small but efficient application to connect separate installations and systems by centrally configured ports, securely.
- Service Manager

    Allows you to centrally manage all your system's services.

**More information:**

- [Analytics and Reporting](../../../Analytics/ANOP_User/AnalyticsAndReporting.md.hbs)
- [About Package Manager](../../../PackageManager/aboutAPM.md.hbs)
- [About the Plugin Manager](../../../PluginManager/PM_About.md.hbs)
- [About Action Builder](../../../ActionBuilder/AB_AboutPlugin.md.hbs)
- [LDAP Sync - Synchronizing LDAP and Automic system Users](../../../LdapSync/AdministeringLDAPSync.md.hbs)
- [About Proxy](../../../Proxy/about_proxy.md.hbs)
- [ServiceManager](../../../ServiceManager/ServiceManager.md.hbs)

See also:

- [Requirements and Installation Types](../../../Installation_Common/Requirements_InstallationTypes.md.hbs)
- [Types of Server Processes](../../../AWA/Admin/admin_types_of_server_processes.md.hbs)
