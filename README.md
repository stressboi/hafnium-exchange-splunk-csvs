# hafnium-exchange-splunk-csvs
IOCs (IP addresses, hashes of web shell .aspx files, names of .aspx files, user-agents) used in exploiting CVE-2021-26855 
courtesy of Volexity and Microsoft. 

See https://www.volexity.com/blog/2021/03/02/active-exploitation-of-microsoft-exchange-zero-day-vulnerabilities/ and 
https://www.microsoft.com/security/blog/2021/03/02/hafnium-targeting-exchange-servers/ 

Use these as lookup tables in Splunk for simple IOC matching. Note: if you want to use these with ES, you may have to reformat 
them, see https://docs.splunk.com/Documentation/ES/6.4.1/Admin/Supportedthreatinteltypes for proper headers.

brodsky@splunk.com
3MAR2021
