**Time spent:** 13 hours spent in total

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

Milestone 0: To the Cloud!

Milestone 1: Create MHN Admin VM

Milestone 2: Install the MHN Admin Application

Milestone 3: Create a MHN Honeypot VM

Milestone 4: Install the Honeypot Application

Milestone 5: Attack!



<img src="mhn-admin.gif">
Any Issue Encountered
Configuration of mhn and vm instances actually took a lot of time but overall all the issues had been resolved.

ERROR 1: couldn't get my GCP to download python magic properly.
ERROR 2: my attacks weren't working so i had to delete everything twice and setup my GCP to try and get it to work.
ERROR 3: When connect honeypots to mhn-admin always return a failure message: connection time out. (solution: check/rebuild mhn-admin and mhn-honeypot firewall. Also try to run [$ sudo apt-get update] and [$ sudo apt-get install software-properties-common -y] in mhn-honeypot ssh)


Summary of data collected
(Collection time: 5:42 PM 5/2/20190)

TOP 5 Attacker IPs:
103.213.208.26 (366 attacks)
46.101.105.47 (196 attacks)
111.230.113.70 (182 attacks)
185.176.27.186 (130 attacks)
51.38.221.54 (126 attacks)
TOP 5 Attacked ports:
23 (802 times)
5060 (748 times)
445 (635 times)
8088 (488 times)
1433 (264 times)



<img src="Sensors.png">



## Notes

Describe any challenges encountered while doing the assignment.
