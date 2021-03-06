---
title: Linux connection requirements and initial configuration
tags: [connection_requirements]
summary: "Spotlight can monitor Linux Servers / Linux hosts of database connections according to the following requirements."
sidebar: c_linux_sidebar
permalink: linux_connect_requirements.html
folder: ConnectLinux
---


## Linux Servers
Spotlight can monitor the following operating systems:

* Red Hat® operating system based on Linux® 2.4, 2.6 and 3.10 kernels
* SUSE® operating system based on Linux® 2.4, 2.6 and 3.0 kernels
* Oracle® Enterprise Linux® (OEL) based on Linux® 2.4, 2.6 and 3.8 kernels


## Linux Server Software
Ensure the following programs are accessible to the user logged on to the Linux machine.

* Perl 5.x
* awk
* cat
* date
* df
* grep
* ifconfig
* iostat
* netstat
* ps
* sar
* sed
* tr
* uname
* uptime
* vmstat
* wc
* who

## Linux User Permissions

* The Unix user should have no special processing on log-on. In particular there must be no input required from the user, and nor should any special login banners be displayed.
* The sysstat package must be installed to enable the user to get detailed disk I/O information.
* The /proc filesystem must be present.
* The sshd daemon must be installed and running and configured to receive remote connections.
* The Unix user must have read/write access to /tmp

## Remote Connectivity: SSH

* The connection type SSH is supported.
* Commands to observe system activity (for example, netstat, vmstat, iostat, sar) must be accessible to SSH sessions for Spotlight to observe Unix activity. Ensure these commands are located in the search path for SSH sessions. If not, Spotlight will display an error.

* Spotlight supports both SSH1 and SSH2 protocols.
* To allow Spotlight to make SSH connections to any Unix or Linux hosts that permit SSH connections, you may need to alter the PasswordAuthentication configuration item in the sshd_config file. Set the value of PasswordAuthentication to yes. Once you have modified the sshd_config file you must restart the sshd process to apply the new setting.
* Public-key encryption is supported under SSH2 only. DSA and RSA are supported.


 {% include links.html %}
