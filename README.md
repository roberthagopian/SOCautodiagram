<h1>SOC Automation Lab Logical Diagram.</h1>

![alt text](https://i.imgur.com/eCbBHsp.png)

 This is the logical diagram for the SOC Automation lab playbook. I'll outline the steps heren in straightforward terms.
 1. Windows 10 send events
 2. Wazuh Manager - Trigger Alerts & Perform Response Actions
 3. Shuffle Receive Wazuh Alerts & Send Responsive Actions
 4. Enrich IOC's
 5. Shuffle will send alerts to theHive to create case management alert
 6. Shuffle sends alertS email to SOC analyst with responsive prompt
 7. prompt SOC analyst with email / alert
 8. Responsive action back to shuffle, wazuh

  And that's the playbook. 

  TOOLS USED

VULTR servers
Draw.io Diagram 
