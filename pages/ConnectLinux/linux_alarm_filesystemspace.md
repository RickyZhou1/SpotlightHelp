---
title: File System Space Alarm
last_updated: July 29, 2016
summary: "The File System Space alarm indicates that the file system is full or filling up."
sidebar: c_linux_sidebar
permalink: linux_alarm_filesystemspace.html
id:
folder: ConnectLinux
---

If the file system fills up completely, no more data can be written to it. For example:

* If the /var file system fills, you may have problems with system activities such as e-mail or printing.
* If the /home file system fills, user applications may be affected.
* If the /tmp file system fills, any applications that use temporary files may be affected.


The data displayed in the Least Space / Disk Space container is collected from the file system that has the least amount of free space, OR a user-specified file system on the Unix host. To choose the file system whose details are displayed in the container, right-click the container and select **Disk Options**.


{% include links.html %}
