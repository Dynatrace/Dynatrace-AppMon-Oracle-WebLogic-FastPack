# Oracle WebLogic FastPack

## Overview

![images_community/download/attachments/45383813/OracleSmall.png](images_community/download/attachments/45383813/OracleSmall.png)

The dynaTrace FastPack for Oracle WebLogic 11g+ enables deep insight into the Oracle WebLogic Application Server and the enclosing platform. This FastPack provides essential metrics which are
visualized on different dashboards.

The FastPack was developed in close co-operation with the Swiss dynaTrace customer BIT (Federal Office of Information Technology and Telecommunication). Special thanks to Sascha Koerner for sharing
his production monitoring know-how and supporting the dynaTrace Community.

![images_community/download/attachments/45383813/bit.png](images_community/download/attachments/45383813/bit.png)

## Fast Pack Details

| Name | Oracle WebLogic FastPack
| :--- | :---
|Author | Christian Grimm (christian.grimm@dynatrace.com)
| Supported dynaTrace Versions | >= 5.5
| License | [dynaTrace BSD](dynaTraceBSD.txt)
| Support | [Not Supported](https://community.compuwareapm.com/community/display/DL/Support+Levels)
| Known Problems | Some features are currently only available on UNIX platforms (*only the UNIX Monitoring Plugin is currently used to provide OS metrics)
|Release History|2011-04-11 Initial Release  
||2011-04-19 Optimized Dashboards added  
||2011-04-27 Added JRockit / Sun JVM Memory Diagnostics Dashboards  
||2012-01-16 Added FastPack for dynaTrace 4.1
| FastPack Contents
|| 1 System Profile  
|| 1 Plugin  
||7 Dashboards
|Download | [dynaTrace Oracle WebLogic FastPack](dynaTrace_Oracle_WebLogic_FastPack-4.1.dtp) 
| | [Optimized dynaTrace Oracle WebLogic Dashboards](Optimized_Oracle_WebLogic_Dashboards.zip) (optimized for displaying up to four WebLogic instances on one Dashboard)  
|| [dynaTrace Oracle WebLogic Extended Metrics Plugin](attachments_47611949_1_com.dynatrace.weblogic.extended_1.0.0.0.jar)


## Documentation

[FastPack Documentation (German)](FastPack_Documentation_German.pdf)

## Content

The following components are part of this FastPack:

### WebLogic System Profile

The reference System Profile contains a set of basic metrics required by the Dashboards of this FastPack. In addition, the UNIX Monitor Plugin and the Web Transaction Monitor Plugin are used to fetch
additional metrics.

### WebLogic Extended Plugin

The "WebLogic Extended" plugin is an essential part of this FastPack. This Plugin is a metric group plugin which retrieves additional JMX values from the Oracle WebLogic Application Server. The Plugin
has to be manually installed before the FastPack can be used.

### WebLogic Application Dashboard

![images_community/download/attachments/45383813/ApplicationDashboard.png](images_community/download/attachments/45383813/ApplicationDashboard.png)

The Application Dashboard gives a quick overview of the following metrics:

  * Synthetic Web Transaction (*needs to be configured in the System Profile settings) 

  * API Layer Breakdown (gives a quick overview of the most time consuming application layers) 

  * Transactions (How many Transactions are currently processed by the WebLogic Application Server and how is the Response Time) 

  * Database (Quantity of Database operations and time spent on DB layer) 

### WebLogic Health Dashboard

![images_community/download/attachments/45383813/HealthDashboard.png](images_community/download/attachments/45383813/HealthDashboard.png)

The WebLogic Health Dashboard gives insight into the Oracle WebLogic Application server's internal metrics.

  * Sessions (Current Web Sessions and the configured Servlet Pool Size) 

  * JTA (Active Transactions. Additional graph for committed and abandoned Transactions) 

  * EJB (EJB Cache Miss Count in relation to the total EJB Access Count. Second graph for committed, rolled back and timed out EJB Transactions) 

  * JDBC (Current JDBC Connection Count in relation to the JDBC Connection Count High Count. Second graph shows the current JDBC Connections Delay) 

  * Execution Queue (Current number of pending requests in the Execution Queue. Additional metrics for the Execution Queue Threads) 

  * CPU / Thread (CPU usage of the WebLogic process. Additional threading infos) 

### WebLogic JMS Dashboard

![images_community/download/attachments/45383813/JMSDashboard.png](images_community/download/attachments/45383813/JMSDashboard.png)

The JMS Dashboard gives insight into the messaging subsystem of the Oracle WebLogic Application Server.

  * JMS (Current JMS Connections in relation to the highest number of parallel JMS Connections. Second graphs for total sent and received JMS Messages) 

  * Producer (Pending JMS Messages) 

  * Destination (Pending JMS Messages) 

  * Consumer (Pending JMS Messages) 

### WebLogic Operating System Dashboard

![images_community/download/attachments/45383813/OperatingSystemDashboard.png](images_community/download/attachments/45383813/OperatingSystemDashboard.png)

The Operating System Dashboard displays important information about the machine's performance metrics.

  * CPU Usage (Current CPU Usage) 

  * Processes (Number of Blocked / Run Queue Current processes in relation to total process count) 

  * Memory (Used and Free Memory) 

  * Disk I/O (Current Disk activity) 

  * Pages I/O (Paging activity) 

  * Disk Space (Used Disk Space in relation to the Total Disk Space) 

  * Network (Network Activity and Errors) 

### WebLogic JVM Overview Dashboard

![images_community/download/attachments/45383813/JVMDashboard.png](images_community/download/attachments/45383813/JVMDashboard.png)

The JVM Dashboard provides some basic metrics for monitoring the Java Virtual Machine.

  * Overview (CPU Usage of the JVM process in relation to the machine's total CPU Usage. Additional metrics for Memory Usage, currently Loaded Classes and number of Threads) 

  * Suspension (Displays the current PurePath durations with and without Runtime Suspensions) 

  * Heap (Shows the Old Generation Space in percent) 

  * Garbage Collection (Displays the different GC runs) 

### WebLogic JVM Memory Diagnostics Dashboards

![images_community/download/attachments/45383813/JVMJRockitDashboard.png](images_community/download/attachments/45383813/JVMJRockitDashboard.png)
![images_community/download/attachments/45383813/JVMSunDashboard.png](images_community/download/attachments/45383813/JVMSunDashboard.png)

The JVM Memory Diagnostics Dashboards provides details about the memory usage of the Sun JVM and Oracle JRockit JVM.

  * Heap Generations 

  * Garbage Collection Behaviour 

  * Suspension (Displays the current PurePath durations with and without Runtime Suspensions) 

  * Runtime Suspensions (Affected Method and Function Calls) in PurePaths 

  * Memory Allocations in PurePaths 

  * Memory Dump Analysis 

For more information about how to use the dashboards and learn how to diagnose memory problems, please either read  
a) the german book from our COE team.  
Book: [Java Enterprise Performance](http://entwickler-press.de/ep/psecom,id,2,buchid,199,p,0,_language,de.html). The memory diagnostics Dashboards are described in chapter 2.2 Performance Analysis.  
b) read the english Java Performance Online Book: <http://book.dynatracde.com>. Memory diagnostics is discussed in the chapter Memory Management.

## Optimized Dashboards

These additional Dashboards are optimized for displaying multiple (up to four) Oracle WebLogic Server instances per Dashboard. The Dashboards are basically the same as in the standard FastPack, but
optimized for viewing load-bbalanced instances of Oracle WebLogic Servers.

![images_community/download/attachments/45383813/ApplicationDashboard-4Hosts.png](images_community/download/attachments/45383813/ApplicationDashboard-4Hosts.png)
![images_community/download/attachments/45383813/HealthDashboard-4Hosts.png](images_community/download/attachments/45383813/HealthDashboard-4Hosts.png) ![images_community/download/attachments/45383813
/JMSDashboard-4Hosts.png](images_community/download/attachments/45383813/JMSDashboard-4Hosts.png) ![images_community/download/attachments/45383813/JVMDashboard-
4Hosts.png](images_community/download/attachments/45383813/JVMDashboard-4Hosts.png) ![images_community/download/attachments/45383813/OperatingSystemDashboard-
4Hosts.png](images_community/download/attachments/45383813/OperatingSystemDashboard-4Hosts.png)

## Installation

### dynaTrace >= 5.5:

**Step 1:** Import the [dynaTrace Oracle WebLogic FastPack](dynaTrace_Oracle_WebLogic_FastPack-4.1.dtp) Plugin into your dynaTrace Server. This FastPack Plugin automatically installs the referenced System Profile, Extended Metrics Plugin and the seven Dashboards. 

**Step 2: (Optional):** Install the [Optimized Oracle WebLogic Dashboards](Optimized_Oracle_WebLogic_Dashboards.zip) by unzipping the archive and opening them in the dynaTrace client. 


## Configuration

The Unix Monitor Plugin needs to be configured properly in the System Profile to get operation system relevant metrics. In addition, the Web Transaction Monitor Plugin needs to be configured to get
results for the synthetic transaction metrics.

