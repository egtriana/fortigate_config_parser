# fortigate_config_parser
Fortigate firewall configuration parser

I build this parser to be able to export and document the firewall configuration. It is a PCI requirement to document firewal configuration changes. The Fortigate
does not have a buil-in tool to do a friendly export.

How to use it:

Open the html file in the browser
Open the fortigate configuration file, select the whole content with Ctl+A, copy and paste the text into the HTML box
Click on "Parse Configuration"
The result will be divided in sections. Every section can be exported as a CSV file.

Sections:

General: device hostname and Serial Number

Security Policies: disabled policies are shown in red

Virtual VIP: shows all defines Virtual IP's. If shows in red, it has port forwarding enabled

Firewall interfaces: tunnel interfaces are shown in red

Address Objects: all network objects

Address Groups: shows the groups and group members

Service Groups: your customized port definitions

IP Pools

VPN SSL Portals and associated IP Pools

VPN SSL Portal Assigments

SD-WAN Zones

SD-WAn Zones Members

Local Custom Categories ID (Web filtering override)

Local Ratings


Future work:

Time permits, I will work on a version to parse the configuration of Fortigates used as Switch and WiFi Controller.

You can use, distribute and/or modify the code as you wish. I will appreciate a reference to credit me for the work.

Eduardo Garcia Triana
egt_mail@yahoo.com
