# 2016ServerAgnostic
Microsoft Windows Server Operating System 2016 Monitoring Addendum v1.0.5.9

Download [here](https://github.com/theKevinJustin/2016ServerAgnostic/blob/main/Microsoft.Windows.Server.Operating.System.2016.Monitoring.Addendum.xml)

### Microsoft Windows Server Operating System 2016 Monitoring Addendum
2016+ server agnostic pack with Event count logic monitor type, Disk cleanup, Group Policy, and eventLog full logic and reports.  Additional monitors reducing alert noise for StorPort storage errors, Group Policy 1096 identification and rebuild.  Disk Cleanup & EventLog service recovery, which includes Event Log file expansion and rollover.

Blog [https://kevinjustin.com/blog/2023/08/28/os-addendum-packs/](https://kevinjustin.com/blog/2023/08/28/os-addendum-packs/)

# Version History:
```
v1.0.6.0 18 Jan 2024 New AutomaticServices workflow DS/WA for monitor/rules.  Includes alerts, recovery rules
v1.0.5.9  4 Jan 2024 Resolution State logic improvements for large environments
v1.0.5.8 27 Dec 2023 Updated whitespace and monitor/rule reset logic updates, Recovery WA like TopProcess
v1.0.5.7 16 Nov 2023 Commented logical disk workflows, correct powershell quote erorrs
v1.0.5.6 18 Jul 2023 Updated reports to informational, OS addendum version sync to 2016
v1.0.5.3 27 Apr 2023 EventLog is full rule/DS and alert
v1.0.5.2 24 Apr 2023 GP report DS missing a + for $Test, overrides for MaxConcurrentAPI
v1.0.5.0 30 Jan 2023 Added GroupPolicy report, alerts, cleanup report with Andrew's logic
v1.0.4.9 30 Jan 2023 Updated with EventLog rules/task/WA/Recovery
v1.0.4.8 23 Jan 2023 Updated disk cleanup, EventLog Service recovery, GPO1096 event to 5, NTFS, Storport severity to warning
v1.0.4.5  7 Dec 2022 Updated to include SQL Backup example
v1.0.4.0 10 Oct 2022 Updates for 1096 GPO monitor error
v1.0.3.9 30 Aug 2022 Updates for GPO System EventID 1096 monitor and recovery
v1.0.3.5 21 Mar 2023 Group Policy report
v1.0.3.4  3 Aug 2022 Updates for Monitor Type, Logical Disk, GPO event 1096 w recovery
v1.0.3.0 19 Jul 2022 Updated for OS cleanup, Recoveries
v1.0.2.7  6 Apr 2022 Updated Event Description for alert parameter errors
v1.0.2.5 10 Mar 2022 Updated StorportMiniportDriverTimedout monitors
v1.0.2.3 22 Feb 2022 Updated Monitor patterns
v1.0.1.9 28 Jan 2022 Updated 153 StorPort event logic, alert message
v1.0.1.3 10 Sep 2021 Update with MatchCount for StorPort monitor
v1.0.0.0  6 Apr 2021 Created management pack for auto closure cleanup
```
