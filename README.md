# CVE-2019-0708

This module checks a range of hosts for the CVE-2019-0708 vulnerability by binding
the MS_T120 channel outside of its normal slot and sending DoS packets.

I just modified the initial metasploit module for this vuln to produce a denial of service attack.

![alt text][module_info]

![alt text][module_demo]

![alt text][module_crash]

[module_info]: https://raw.githubusercontent.com/mekhalleh/cve-2019-0708/master/pictures/demo-01.png "Module: info"
[module_demo]: https://raw.githubusercontent.com/mekhalleh/cve-2019-0708/master/pictures/demo-02.png "Module: demo"
[module_crash]: https://raw.githubusercontent.com/mekhalleh/cve-2019-0708/master/pictures/demo-03.png "Module: crash"
