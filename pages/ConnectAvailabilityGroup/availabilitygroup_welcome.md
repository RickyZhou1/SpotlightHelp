---
title: SQL Server Availability Group
last_updated: July 29, 2016
sidebar: c_availabilitygroup_sidebar
toc: false
permalink: availabilitygroup_welcome.html
folder: ConnectAvailabilityGroup
---
<div class="row">
        <h2 class="page-header">Use Spotlight to monitor SQL Server Availability Groups</h2>
        <p>An availability group is a set of user databases that fail over together. An availability group consists of a primary availability replica and one to four secondary replicas that are maintained through SQL Server log-based data movement for data protection without the need for shared storage. Each replica is hosted by an instance of SQL Server on a different node of the Windows Server Failover Cluster (WSFC). The availability group and a corresponding virtual network name are registered as resources in the WSFC.</p>
        <div class="col-md-3 col-sm-6">
            <div class="panel panel-default text-center">
                <div class="panel-body">
                    <h4>Connect</h4>
                    <p>Connect to SQL Server Availability Groups.</p>
                    <a href="availabilitygroup_connect_details.html" class="btn btn-primary">Learn More</a>
                </div>
            </div>
        </div>
        <div class="col-md-3 col-sm-6">
            <div class="panel panel-default text-center">
                <div class="panel-body">
                    <h4>Alarms</h4>
                    <p>Respond to raised alarms.</p>
                    <a href="availabilitygroup_alarms.html" class="btn btn-primary">Learn More</a>
                </div>
            </div>
        </div>
        <div class="col-md-3 col-sm-6">
            <div class="panel panel-default text-center">
                <div class="panel-body">
                    <h4>Overview</h4>
                    <p>Diagnose bottlenecks and problem areas.</p>
                    <a href="availabilitygroup_drilldown_overview.html" class="btn btn-primary">Learn More</a>
                </div>
            </div>
        </div>
    </div>



{% include tip.html content="The collections used by Spotlight Enterprise to monitor Availability Group connections are documented at: [Collections](availabilitygroup_collections.html)." %}
