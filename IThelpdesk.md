# Organization IT Help Desk
- Support for a specific organization
- User identity security checks
- Unresolved issues may be escalated

1. User Contact 2. Create Ticket 3. Resolution or Escalation 4. Edit ticket based on the outcome

# Incident Tracking
* Triage an Incident Ticket
  - Think if it impacts one or fewer employees OR all employees
    - one or fewer
      - Low or medium priority
      - create ticket
      - contact user
      - resolve
    - all
      - high priority
      - create ticket
      - escalate as needed
      - resolve
     
# Real World Application
- An unknown virus breaks out. There is talk that data files are being deleted by the thousands from computers and servers.
  1. Escalate conversations
  2. Inform everyone
  3. Disconnect all network switches
  4. Shut down equipment
  5. Isolate a computer to send a sample file
  6. Apply an updated patch
  7. Document
  8. DO NOT corporate functions until the issue is resolved

# Incident tracking
- spiceworks

# Critical Thinking practice
The power goes out. What do you do?
1. Shut down equipment
2. Contact the power company
3. Escalate conversations
4. Tell everyone to unplug equipment
5. Create a monitoring group
6. Bring all the equipments up when the power is restored
7. Document

# Common problems and solutions
* User can not login
  - Check for caps lock
  - Expired pw
  - Suspended acc
  - reset pw
* Deleted Files Need to be restored
  - check bin
  - restore the file from a server backup or volume shadow
    
* Their computer is slow
  - check CPU usage
  - remove temporary files from the windows folder
  - check to see if the hard drive is full
  - check the computer for viruses or malware
* Slow internet connection
  - how many people are affected?
  - check ip addressing and DNS
  - maybe : static ip address or lack of DHCP
* User with printer problems
  - power on
  - paper jam or ink outage
  - add or replace the driver
* User cannot access shared Drive
  - ping the server to check connection issues and remap the drive
* Possible Malware
  - immediately remove the machine from the network
  - determine the actual virus or malware
  - next steps may require an on-site tech
  - shut down computer
  - check the hard driver
* Wireless keyboard or mouse not working
  - check the bluetooth connection and check the batteries
* blue screen of death
  - a system crash
  - hardware failure
  - a driver failure
  - may require only a system reboot
  - may need to disconnect unnecessary hardware
  - may need to deploy a tech to repair or replace
* Computer won't start
  - not plugged in
  - reset
  - deploy a tech

# Hardware problems
Windows 11
Start button right click
Task manager
If any one is 100%, click the column
and maybe end the biggest memory task

performance

Services

Open resource monitor
Disk, Network, Memory

Computer management
Run admin
Task scheduler - maybe too many tasks are running at the same time.
Event viewer - yellow or red. googling
Performance monitor
Device manager - update driver or disk

# Software problems
vendor bugs
os update issue

task manager

computer management - find the error logs w process ID. 
get the error log's ProcessID
Find the processID in the task manager
see the details <-> service page

# Networking basics
Decision tree for network problems
1. Did IP tools fix the problem?
2. No. escalate to the appropriate team
 corporate networking team
 home networking team
 wired or wireless?

IP tools
open powershell windows terminal
ipconfig - to know user's ip address
make them read the IPv4 address
does it match with subnet mask?
255.255.255.0
three times, then the first three octets should match

ping 8.8.8.8
if it's too slow ms, wireless network problem

ping google.com
test DNS system

cls

ipconfig /alㅣ
DNS servers

tracert google.com
little stars

# Security vulnerability
- phishing email
- game sites
- USB drives
- social engineering

hidden code in the email, forensic
MS outlook
follwup-properties
check out the received
spf=fail
dkim=fail

# when to suspect Malware
task manager

# when to replace equipment

# software installation
Notepad++ install
check if's secure
run as admin

# End User training
- Learn how to talk to non-technical users

# How to create successful user training

# Management Tools for help desk staff
## Ticketing systems inventory demo
device inventory
create a new environment
enter device data

download a collection agent

## Malware best practices
windows defender
virus and threat protection
quick scan
virus and threat protection setting
protection history

## Remote control tools
quick assist

## Active dir tools for user management
active directory

























  
