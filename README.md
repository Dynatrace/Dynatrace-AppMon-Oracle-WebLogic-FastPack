<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>Oracle WebLogic FastPack</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
                <h1>Oracle WebLogic FastPack</h1>
    <div class="section-2"  id="45383813_OracleWebLogicFastPack-Overview"  >
        <h2>Overview</h2>
    <p>
            <img src="images_community/download/attachments/45383813/OracleSmall.png" alt="images_community/download/attachments/45383813/OracleSmall.png" class="confluence-embedded-image image-left" />
            </p>
    <p>
    </p>
    <p>
The dynaTrace FastPack for Oracle WebLogic 11g+ enables deep insight into the Oracle WebLogic Application Server and the enclosing platform. This FastPack provides essential metrics which are visualized on different dashboards.    </p>
    <p>
The FastPack was developed in close co-operation with the Swiss dynaTrace customer BIT (Federal Office of Information Technology and Telecommunication). Special thanks to Sascha Koerner for sharing his production monitoring know-how and supporting the dynaTrace Community.    </p>
    <p>
            <img src="images_community/download/attachments/45383813/bit.png" alt="images_community/download/attachments/45383813/bit.png" class="confluence-embedded-image image-left" />
            </p>
    </div>
    <div class="section-2"  id="45383813_OracleWebLogicFastPack-FastPackDetails"  >
        <h2>Fast Pack Details</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Christian Grimm (christian.grimm@dynatrace.com)    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
dynaTrace Versions    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
dynaTrace 4.1<br/>dynaTrace 3.5    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/display/DL/Support+Levels">Not Supported</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Known Problems    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Some features are currently only available on UNIX platforms (*only the UNIX Monitoring Plugin is currently used to provide OS metrics)    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Release History    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
2011-04-11 Initial Release<br/>2011-04-19 Optimized Dashboards added<br/>2011-04-27 Added JRockit / Sun JVM Memory Diagnostics Dashboards<br/>2012-01-16 Added FastPack for dynaTrace 4.1    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
FastPack Contents    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
1 System Profile<br/>1 Plugin<br/>7 Dashboards    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Download    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
dynaTrace 4.1:<br/><a href="attachments_70516738_1_dynaTrace_Oracle_WebLogic_FastPack-4.1.dtp">dynaTrace Oracle WebLogic FastPack</a> (Please rename to .dtp if the file is downloaded as .zip)<br/><a href="attachments_47972389_1_Optimized_Oracle_WebLogic_Dashboards.zip">Optimized dynaTrace Oracle WebLogic Dashboards</a> (optimized for displaying up to four WebLogic instances on one Dashboard)<br/><br/>dynaTrace 3.5:<br/><a href="attachments_47611949_1_com.dynatrace.weblogic.extended_1.0.0.0.jar">dynaTrace Oracle WebLogic Extended Metrics Plugin</a><br/><a href="attachments_47972468_1_dynaTrace_Oracle_WebLogic_FastPack.dtp">dynaTrace Oracle WebLogic FastPack</a> (Please rename to .dtp if the file is downloaded as .zip)<br/><a href="attachments_47972389_1_Optimized_Oracle_WebLogic_Dashboards.zip">Optimized dynaTrace Oracle WebLogic Dashboards</a> (optimized for displaying up to four WebLogic instances on one Dashboard)    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Documentation    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_47972353_1_FastPack_Documentation_(German).pdf">FastPack Documentation (German).pdf</a>    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="45383813_OracleWebLogicFastPack-Content"  >
        <h2>Content</h2>
    <p>
The following components are part of this FastPack:    </p>
    <div class="section-3"  id="45383813_OracleWebLogicFastPack-WebLogicSystemProfile"  >
        <h3>WebLogic System Profile</h3>
    <p>
The reference System Profile contains a set of basic metrics required by the Dashboards of this FastPack. In addition, the UNIX Monitor Plugin and the Web Transaction Monitor Plugin are used to fetch additional metrics.    </p>
    </div>
    <div class="section-3"  id="45383813_OracleWebLogicFastPack-WebLogicExtendedPlugin"  >
        <h3>WebLogic Extended Plugin</h3>
    <p>
The &quot;WebLogic Extended&quot; plugin is an essential part of this FastPack. This Plugin is a metric group plugin which retrieves additional JMX values from the Oracle WebLogic Application Server. The Plugin has to be manually installed before the FastPack can be used.    </p>
    </div>
    <div class="section-3"  id="45383813_OracleWebLogicFastPack-WebLogicApplicationDashboard"  >
        <h3>WebLogic Application Dashboard</h3>
    <p>
            <img src="images_community/download/attachments/45383813/ApplicationDashboard.png" alt="images_community/download/attachments/45383813/ApplicationDashboard.png" class="" />
            </p>
    <p>
The Application Dashboard gives a quick overview of the following metrics:    </p>
<ul class=" "><li class=" ">    <p>
Synthetic Web Transaction (*needs to be configured in the System Profile settings)    </p>
</li><li class=" ">    <p>
API Layer Breakdown (gives a quick overview of the most time consuming application layers)    </p>
</li><li class=" ">    <p>
Transactions (How many Transactions are currently processed by the WebLogic Application Server and how is the Response Time)    </p>
</li><li class=" ">    <p>
Database (Quantity of Database operations and time spent on DB layer)    </p>
</li></ul>    </div>
    <div class="section-3"  id="45383813_OracleWebLogicFastPack-WebLogicHealthDashboard"  >
        <h3>WebLogic Health Dashboard</h3>
    <p>
            <img src="images_community/download/attachments/45383813/HealthDashboard.png" alt="images_community/download/attachments/45383813/HealthDashboard.png" class="" />
            </p>
    <p>
The WebLogic Health Dashboard gives insight into the Oracle WebLogic Application server's internal metrics.    </p>
<ul class=" "><li class=" ">    <p>
Sessions (Current Web Sessions and the configured Servlet Pool Size)    </p>
</li><li class=" ">    <p>
JTA (Active Transactions. Additional graph for committed and abandoned Transactions)    </p>
</li><li class=" ">    <p>
EJB (EJB Cache Miss Count in relation to the total EJB Access Count. Second graph for committed, rolled back and timed out EJB Transactions)    </p>
</li><li class=" ">    <p>
JDBC (Current JDBC Connection Count in relation to the JDBC Connection Count High Count. Second graph shows the current JDBC Connections Delay)    </p>
</li><li class=" ">    <p>
Execution Queue (Current number of pending requests in the Execution Queue. Additional metrics for the Execution Queue Threads)    </p>
</li><li class=" ">    <p>
CPU / Thread (CPU usage of the WebLogic process. Additional threading infos)    </p>
</li></ul>    </div>
    <div class="section-3"  id="45383813_OracleWebLogicFastPack-WebLogicJMSDashboard"  >
        <h3>WebLogic JMS Dashboard</h3>
    <p>
            <img src="images_community/download/attachments/45383813/JMSDashboard.png" alt="images_community/download/attachments/45383813/JMSDashboard.png" class="" />
            </p>
    <p>
The JMS Dashboard gives insight into the messaging subsystem of the Oracle WebLogic Application Server.    </p>
<ul class=" "><li class=" ">    <p>
JMS (Current JMS Connections in relation to the highest number of parallel JMS Connections. Second graphs for total sent and received JMS Messages)    </p>
</li><li class=" ">    <p>
Producer (Pending JMS Messages)    </p>
</li><li class=" ">    <p>
Destination (Pending JMS Messages)    </p>
</li><li class=" ">    <p>
Consumer (Pending JMS Messages)    </p>
</li></ul>    </div>
    <div class="section-3"  id="45383813_OracleWebLogicFastPack-WebLogicOperatingSystemDashboard"  >
        <h3>WebLogic Operating System Dashboard</h3>
    <p>
            <img src="images_community/download/attachments/45383813/OperatingSystemDashboard.png" alt="images_community/download/attachments/45383813/OperatingSystemDashboard.png" class="" />
            </p>
    <p>
The Operating System Dashboard displays important information about the machine's performance metrics.    </p>
<ul class=" "><li class=" ">    <p>
CPU Usage (Current CPU Usage)    </p>
</li><li class=" ">    <p>
Processes (Number of Blocked / Run Queue Current processes in relation to total process count)    </p>
</li><li class=" ">    <p>
Memory (Used and Free Memory)    </p>
</li><li class=" ">    <p>
Disk I/O (Current Disk activity)    </p>
</li><li class=" ">    <p>
Pages I/O (Paging activity)    </p>
</li><li class=" ">    <p>
Disk Space (Used Disk Space in relation to the Total Disk Space)    </p>
</li><li class=" ">    <p>
Network (Network Activity and Errors)    </p>
</li></ul>    </div>
    <div class="section-3"  id="45383813_OracleWebLogicFastPack-WebLogicJVMOverviewDashboard"  >
        <h3>WebLogic JVM Overview Dashboard</h3>
    <p>
            <img src="images_community/download/attachments/45383813/JVMDashboard.png" alt="images_community/download/attachments/45383813/JVMDashboard.png" class="" />
            </p>
    <p>
The JVM Dashboard provides some basic metrics for monitoring the Java Virtual Machine.    </p>
<ul class=" "><li class=" ">    <p>
Overview (CPU Usage of the JVM process in relation to the machine's total CPU Usage. Additional metrics for Memory Usage, currently Loaded Classes and number of Threads)    </p>
</li><li class=" ">    <p>
Suspension (Displays the current PurePath durations with and without Runtime Suspensions)    </p>
</li><li class=" ">    <p>
Heap (Shows the Old Generation Space in percent)    </p>
</li><li class=" ">    <p>
Garbage Collection (Displays the different GC runs)    </p>
</li></ul>    </div>
    <div class="section-3"  id="45383813_OracleWebLogicFastPack-WebLogicJVMMemoryDiagnosticsDashboards"  >
        <h3>WebLogic JVM Memory Diagnostics Dashboards</h3>
    <p>
            <img src="images_community/download/attachments/45383813/JVMJRockitDashboard.png" alt="images_community/download/attachments/45383813/JVMJRockitDashboard.png" class="" />
                 <img src="images_community/download/attachments/45383813/JVMSunDashboard.png" alt="images_community/download/attachments/45383813/JVMSunDashboard.png" class="" />
            </p>
    <p>
The JVM Memory Diagnostics Dashboards provides details about the memory usage of the Sun JVM and Oracle JRockit JVM.    </p>
<ul class=" "><li class=" ">    <p>
Heap Generations    </p>
</li><li class=" ">    <p>
Garbage Collection Behaviour    </p>
</li><li class=" ">    <p>
Suspension (Displays the current PurePath durations with and without Runtime Suspensions)    </p>
</li><li class=" ">    <p>
Runtime Suspensions (Affected Method and Function Calls) in PurePaths    </p>
</li><li class=" ">    <p>
Memory Allocations in PurePaths    </p>
</li><li class=" ">    <p>
Memory Dump Analysis    </p>
</li></ul>    <p>
For more information about how to use the dashboards and learn how to diagnose memory problems, please either read<br/>a) the german book from our COE team.<br/>Book: <a href="http://entwickler-press.de/ep/psecom,id,2,buchid,199,p,0,_language,de.html">Java Enterprise Performance</a>. The memory diagnostics Dashboards are described in chapter 2.2 Performance Analysis.<br/>b) read the english Java Performance Online Book: <a href="http://book.dynatracde.com">http://book.dynatracde.com</a>. Memory diagnostics is discussed in the chapter Memory Management.    </p>
    </div>
    </div>
    <div class="section-2"  id="45383813_OracleWebLogicFastPack-OptimizedDashboards"  >
        <h2>Optimized Dashboards</h2>
    <p>
These additional Dashboards are optimized for displaying multiple (up to four) Oracle WebLogic Server instances per Dashboard. The Dashboards are basically the same as in the standard FastPack, but optimized for viewing load-bbalanced instances of Oracle WebLogic Servers.    </p>
    <p>
            <img src="images_community/download/attachments/45383813/ApplicationDashboard-4Hosts.png" alt="images_community/download/attachments/45383813/ApplicationDashboard-4Hosts.png" class="" />
                    <img src="images_community/download/attachments/45383813/HealthDashboard-4Hosts.png" alt="images_community/download/attachments/45383813/HealthDashboard-4Hosts.png" class="" />
                    <img src="images_community/download/attachments/45383813/JMSDashboard-4Hosts.png" alt="images_community/download/attachments/45383813/JMSDashboard-4Hosts.png" class="" />
                    <img src="images_community/download/attachments/45383813/JVMDashboard-4Hosts.png" alt="images_community/download/attachments/45383813/JVMDashboard-4Hosts.png" class="" />
                    <img src="images_community/download/attachments/45383813/OperatingSystemDashboard-4Hosts.png" alt="images_community/download/attachments/45383813/OperatingSystemDashboard-4Hosts.png" class="" />
            </p>
    </div>
    <div class="section-2"  id="45383813_OracleWebLogicFastPack-Installation"  >
        <h2>Installation</h2>
    <div class="section-3"  id="45383813_OracleWebLogicFastPack-dynaTrace4.1%3A"  >
        <h3>dynaTrace 4.1:</h3>
    <p>
<strong class=" ">Step 1:</strong> Import the <a href="attachments_70516738_1_dynaTrace_Oracle_WebLogic_FastPack-4.1.dtp">dynaTrace Oracle WebLogic FastPack</a> Plugin into your dynaTrace Server. This FastPack Plugin automatically installs the referenced System Profile, Extended Metrics Plugin and the seven Dashboards.    </p>
    <p>
<strong class=" ">Step 2: (Optional):</strong> Install the <a href="attachments_47972389_1_Optimized_Oracle_WebLogic_Dashboards.zip">Optimized Oracle WebLogic Dashboards</a> by unzipping the archive and opening them in the dynaTrace client.    </p>
    </div>
    <div class="section-3"  id="45383813_OracleWebLogicFastPack-dynaTrace3.5%3A"  >
        <h3>dynaTrace 3.5:</h3>
    <p>
<strong class=" ">Step 1:</strong> Import the <a href="attachments_47611949_1_com.dynatrace.weblogic.extended_1.0.0.0.jar">dynaTrace Oracle WebLogic Extended Metrics Plugin</a> into your dynaTrace Server. For details on how to do this please refer to the <a href="Oracle_WebLogic_FastPack.html">Online Documentation on Plugin Management</a>.    </p>
    <p>
<strong class=" ">Step 2:</strong> Import the <a href="attachments_47972468_1_dynaTrace_Oracle_WebLogic_FastPack.dtp">dynaTrace Oracle WebLogic FastPack</a> Plugin into your dynaTrace Server. This FastPack Plugin automatically installs the referenced System Profile and the seven Dashboards.    </p>
    <p>
<strong class=" ">Step 3: (Optional):</strong> Install the <a href="attachments_47972389_1_Optimized_Oracle_WebLogic_Dashboards.zip">Optimized Oracle WebLogic Dashboards</a> by unzipping the archive and opening them in the dynaTrace client.    </p>
    </div>
    </div>
    <div class="section-2"  id="45383813_OracleWebLogicFastPack-Configuration"  >
        <h2>Configuration</h2>
    <p>
The Unix Monitor Plugin needs to be configured properly in the System Profile to get operation system relevant metrics. In addition, the Web Transaction Monitor Plugin needs to be configured to get results for the synthetic transaction metrics.    </p>
    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>
