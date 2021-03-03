# hafnium-exchange-splunk-csvs
IOCs (IP addresses, hashes of web shell .aspx files, names of .aspx files, user-agents) used in exploiting CVE-2021-26855 
courtesy of Volexity, Microsoft, and Huntresslabs. 

See https://www.volexity.com/blog/2021/03/02/active-exploitation-of-microsoft-exchange-zero-day-vulnerabilities/ and 
https://www.microsoft.com/security/blog/2021/03/02/hafnium-targeting-exchange-servers/ and https://www.reddit.com/r/msp/comments/lwmo5c/mass_exploitation_of_onprem_exchange_servers/.

Use these as lookup tables in Splunk for simple IOC matching. Note: if you want to use these with ES, you need to use the versions
in the EnterpriseSecurity directory. See blog post here for guidance: https://www.splunk.com/en_us/blog/security/smoothing-the-bumps-of-onboarding-threat-indicators-into-splunk-enterprise-security.html

If you wish to add more IOCs to this repo, please send a PR!

brodsky@splunk.com

4MAR2021
