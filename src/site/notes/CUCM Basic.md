---
{"dg-publish":true,"permalink":"/cucm-basic/","title":"CUCM Basic"}
---


- Cisco IP Phones use "SEPXXXXX" (Selsius Ethere Phone) to idtenty themselves, where "XXXXX" is their MAC address.

- SCCP and SIP are used or Cisco Phones, older phones use SCCP. This can be viewed under "CUCM -> Device -> Phone"

- CM has two types of accounts: OS and application levels. System level can only be used by TAC for troubleshooting. We mainly use application level accounts.

- The most used module is CUCM Administration.

- Self care portal is used by end-users to change their own settings.

- OS Admin portal is for managing OS level settings, which has a separated credential

- CU Serviceability is for checking service status

- CTI (Computer Telephony Integration) Route Point is mainly used by call centers

- virwsapp359 is email to fax converting, the app is called RightFax

- RTMT (Real Time Monitoring Tool) is a very useful tool that can be installed on host to trace activity of calls.

- All writings to DB are done by the publisher, subscribers are read only. If the publisher is down, then no config change is not possible.

- Route-pattern is for outgoing calls. Route-Patter -> Route-list -> Route-Group(s) -> GW(s)/Trunk(s). Configuration should be in a reversed order: GW(s) & Trunk(s) first.
 - Hunt group, and Media resource are in the similar structure.
- CSS -> Partition(s) -> Ext(s)/Route Pattern(s)
- Pickup Group is often used with Hunt Group
- Route Plan Report is useful to find calling pattern system-wide
- Transformation only change the numbers displayed on phones, translation change the numbers
