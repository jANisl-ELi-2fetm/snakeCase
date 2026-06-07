ServerMonitor Plugin: System Metrics Dashboard
===========================

A remote server monitoring plugin for tracking Linux system performance using the ServerConnect Plugin SDK.

![screenshot](http://i.imgur.com/uDSJRIr.png?1)

This plugin establishes connection to your selected ServerConnect session and executes diagnostic commands to monitor server performance metrics.

For implementation details of metric collection, review the following classes:

[CPU checks](Plugin/src/main/java/com/monitoring/servermonitor/controllers/CpuUsageController.java)

[RAM checks](Plugin/src/main/java/com/monitoring/servermonitor/controllers/FreeRamController.java)

[Load Avg checks](Plugin/src/main/java/com/monitoring/servermonitor/controllers/LoadAverageController.java)

[Network checks](Plugin/src/main/java/com/monitoring/servermonitor/controllers/NetworkUsageController.java)

[Disk checks](Plugin/src/main/java/com/monitoring/servermonitor/controllers/DiskUsageController.java)


For comprehensive ServerConnect Plugin SDK documentation, capabilities, security considerations and development quickstart, consult our [FAQ](http://serverconnect.io/faq)

Feel free to fork/extend/contribute to this plugin!