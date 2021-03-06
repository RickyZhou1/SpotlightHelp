---
title: Tempdb Version Store Size alarm
tags: [sqlserver_alarms]
last_updated: July 29, 2016
summary: "This alarm is raised when the Tempdb version store is too large for your environment."
sidebar: c_sqlserver_sidebar
permalink: sqlserver_alarm_tempdb_versionstoresize.html
id: alarm_TempDB_VersionStoreSize
folder: ConnectSQLServer
---



There are two version stores in Tempdb. The online index build version store is used for online index builds in all databases. The common version store is used for all other data modification operations in all databases.

{% include note.html content="This alarm is disabled by default. Ensure the thresholds for this alarm are configured appropriate to your environment before enabling the alarm. Use a Spotlight Client to **Configure \| Alarms**." %}

{% include links.html %}
