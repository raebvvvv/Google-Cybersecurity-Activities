# 02 File Hash

FILE HASH

Investigate a suspicious file hash

SHA256 file hash: 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b

Here is a timeline of the events leading up to this alert:

1:11 p.m.: An employee receives an email containing a file attachment.

1:13 p.m.: The employee successfully downloads and opens the file.

1:15 p.m.: Multiple unauthorized executable files are created on the employee's computer.

1:20 p.m.: An intrusion detection system detects the executable files and sends out an alert to the SOC.

I entered the file hash into VirusTotal. I decided that the file is malicious by looking at the information from the VirusTotal report. Most of the vendors have flagged this file as malware flagpro. I identified IoCs(Indicators of compromise) that are associated with this file. First one is a MD5 hash 287d612e29b71c90aa54947313810a25 in Details tab. Second, the domain name, org.misecure.com, is flagged as malicious by 13/92 security vendors. Lastly, 207.148.109.242 is one of the many IP addresses if found in Relations tab that is associated with with org.misecure.com domain.
