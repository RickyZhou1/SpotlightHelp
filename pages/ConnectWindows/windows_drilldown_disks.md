---
title: Disks drilldown
last_updated: July 29, 2016
summary: "Drilldown on the Windows server logical and physical disks."
sidebar: c_windows_sidebar
permalink: windows_drilldown_disks.html
folder: ConnectWindows
---


## How to open the Disks drilldown

From the Spotlight Client

1. Select the connection from the left Connections pane.
2. Click **Monitor \| Disks** from the ribbon.
   {% include imageClient.html file="tb_drilldown_disks.png" alt="Disks drilldown for Windows servers" %}

{% include tip.html content="Click for more information on using [Spotlight Charts][enterprise_display_charts] and [Spotlight Grids][enterprise_display_grids]." %}


## About the Disks drilldown


### Logical Disk activity

Investigate Logical Disk Activity

####  Disk Reads chart
Shows a recent summary of the rate at which read requests have been sent to each logical disk.

#### Disk Writes chart
Shows a recent summary of the rate at which write requests have been sent to each logical disk.

#### Disk I/O chart
Shows a recent summary of the number of read and write requests that have been sent to each logical disk. This chart is the sum of the Disk Reads and Disk Writes.

#### Disk Queue Length chart
Shows the number of I/O requests that were queued for each logical disk.

Disk queue length indicates how heavily loaded a disk subsystem is. High queue lengths mean the disks are struggling to process the I/O load being put on them.

#### Transfer Time chart
Shows how long it is taking for data to be transferred between disk and memory, and includes both Disk Reads and Disk Writes.

If disk transfers are taking consistently longer than 50 ms, a disk bottleneck may be developing.

#### Disk Load chart
Shows how busy overall the individual logical disks are.

Right-click the grid data and select **View as Grid** to view the data as a grid.


### Physical Disk activity

Investigate Physical Disk Activity

#### Disk Reads chart (physical disk)
Shows a recent summary of the rate at which read requests have been sent to each physical disk.

#### Disk Writes chart (physical disk)
Shows a recent summary of the rate at which write requests have been sent to each physical disk.

#### Disk I/O chart (physical disk)
Shows a recent summary of the number of read and write requests that have been sent to each physical disk.

#### Disk Queue Length chart (physical disk)
Shows the number of I/O requests that were queued for each physical disk.

Disk Queue Length indicates how heavily loaded a disk subsystem is. High queue lengths mean the disks are struggling to process the I/O load being put on them.

#### Transfer Time chart (physical disk)
Shows how long it is taking for data to be transferred between disk and memory. This graph includes Disk Reads and Disk Writes.

If disk transfers are taking consistently longer than 50 ms, a disk bottleneck may be developing.

#### Disk Load chart (physical disk)
Shows how busy overall the individual physical disks are.

Right-click the grid data and select **View as Grid** to view the data as a grid.



### Logical Disk Space usage

Investigate Logical Disk Space Usage

#### Disk Space by Gigabytes/Percentage chart
Shows a graphical view of used and available space on all logical drives.

To switch between Disk Space by Gigabytes and Disk Space by Percentage view, click the arrow next to the chart name.



### Disk summary

Investigate the relationship between physical and logical disks and view summary information for each disk.

#### Physical Disks grid
Shows summary information about the physical disks on the current system.

For each physical disk detected, disk summary information is displayed in the columns of a single table (grid).

To see information about the logical disks associated with each physical disk, click the disk's entry in the grid.

#### Logical Disks grid
Shows summary information on the logical disk(s) associated with each physical hard disk on the system.

Select a disk in the Physical Disks grid to see information about the associated logical disk.


### Files Sizes
Shows information on the size of files. For more information, see **Windows Server \| Spotlight Overview page \| Files panel**.



{% include links.html %}
