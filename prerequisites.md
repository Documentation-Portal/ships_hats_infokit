# Prerequisites and requirements
-----------------------------------------

# Prerequisites and requirements

## i) Build agent
- Microsoft Windows 10 / Windows Server 2016 or 2019
- Linux (Recommended Ubuntu 18.04 or RHEL 7)
- MacOS High Sierra and above (Supported for remote<sup>1</sup> only)  

<i><small><sup>1</sup>Remote refers to agents provide their own. Elastic refers to agents provided by SHIP</small></i>

## ii) Browser
Supported on Apple Macintosh / Microsoft Windows:
- Chrome, Safari
- Internet Explorer 11, Microsoft Edge, Firefox*

 > \* The new DSS stated agency only need to ensure web-based digital services are compatible with the latest version of Chrome and Safari. As such, the specific end of support for Internet Explorer 11, Microsoft Edge and Firefox will be at end of September 2020. From October 2020 onwards, only Chrome and Safari would be supported and available. This is applicable to our remote agents and device farms.

## iii) .Net & Java Projects
### .Net Projects
- .Net Framework 4.7.2
- .Net Core 3.1
- MSBuild version 15 (Visual Studio 2017)
- MSBuild version 16 (Visual Studio 2019)
- Nuget Package Manager Trusted Sources
    - Nuget v2
    - Other source locations please highlight to agency PM/BA for evaluation on the need

### Java Projects
- Ant 1.10
- JDK 8, 9, 11, 12
- Maven 3

***

# Green HATS
### i) Functional Test Automation
<strong><u>Major browsers and mobile platforms</u></strong>
1. <strong>Web Browsers</strong>
 - Chrome, Safari
 - Internet Explorer 11, Microsoft Edge and Firefox*
 - Testing Framework: Robot Framework with Selenium2Library Or Selenium+Java

 > \* The new DSS stated agency only need to ensure web-based digital services are compatible with the latest version of Chrome and Safari. As such, the specific end of support for Internet Explorer 11, Microsoft Edge and Firefox will be at end of September 2020. From October 2020 onwards, only Chrome and Safari would be supported and available. This is applicable to our remote agents and device farms.

2. <strong>Android</strong>
    - Supported mobile app testing versions: Android Marshmallow 6.0 to 9.0 Pie 
    - Testing Framework: Robot Framework with AppiumLibrary
3. <strong>iOS</strong>
    - Supported mobile app testing versions: iOS 12
    - Testing Framework: Xcode 10 with Robot Framework and AppiumLibrary

<strong><u>Development tools support</u></strong>  
 - Eclipse Integrated Development Environment with RED plugin, or any text editor like PyCharm

<strong><u>Emulators supported for Devs</u></strong>
- Google Android Emulator
- Xcode iOS Simulator

<strong><u>Device Farm</u></strong>
- Apple iPhone 6, 7, 8
- Google Android platform Various Android 6.x, 7.x, 8.x, 9.x, 10.x by Samsung,
Xiaomi, Sony, HTC, OnePlus etc
- Android – Live manual and automated app testing o iOS – Command-line Appium XCUI tests
- Cloud device farm (Coming soon!)
>_For full list of devices, please email <a href="mailto:enquiries_HATS@tech.gov.com">HATS team</a>._

### ii) Service Virtualisation
<strong><u>Supported Transport Protocols</u></strong>
- HTTP/S Transport Protocol
- IBM MQ Native Transport Protocol
- IBM WebSphere MQ Transport Protocol
- JMS Transport Protocol
- Standard JMS Transport Protocol
- RabbitMQ Transport Protocol
- Java Transport Protocol
- JDBC Transport Protocol
- TCP Transport Protocol
- CICS (LINK DTP MRO) Transport Protocol
- CICS Transaction Gateway (ECI) Transport Protocol o IMS Connect Transport Protocol
- SAP RFC via JCo Transport Protocol
- JCo IDoc Transport Protocol
- Opaque Data Processing Transport Protocol

> _For more info on the protocols, please refer to Broadcom Service Virtualisation [page](https://techdocs.broadcom.com/content/broadcom/techdocs/us/en/ca-enterprise-software/continuous-testing/devtest-solutions/10-5/using/using-service-virtualization.html)._

***

# White HATS

<table>
  <tr>
    <th style="width:358px"><strong><u>SonarQube Supported Languages</u></strong></th>  
    <th><strong><u>Fortify SCA Supported Languages</u></strong></th>
  </tr>

  <tr>

   <td>
    <ul>
     <li>Java</li>
     <li>JavaScript</li>
     <li>C#</li>
     <li>TypeScript</li>
     <li>Kotlin</li>
     <li>Ruby</li>
     <li>Go</li>
     <li>Scala</li>
     <li>Flex</li>
     <li>Python</li>
     <li>PHP</li>
     <li>HTML</li>
     <li>CSS</li>
     <li>XML</li>
     <li>VB.NET</li>
     <li>C</li>
     <li>C++</li>
     <li>Obj-C</li>
     <li>Swift</li>
     <li>ABAP</li>
     <li>T-SQL</li>
     <li>PL/SQL Support</li>
    </ul>   
   </td>


   <td valign="top">
    <ul>
      <li> .NET MSBuild </li>
      <li> .NET Core </li>
      <li> Gradle 4.x
      <li> Java 9, 10, 11 & 12 </li>
      <li> Ruby (multiple versions) </li>
      <li> Python 2.x and 3.x </li>
      <li> Angular 2, 4, 5, 6 & 7 </li>
      <li> Node.js 10.x </li>
      <li> TypeScript 3.0, 3.1 and 3.2 o Swift 4.2 / XCode 10 </li>
      <li> Objective<li>C/C++ </li>
      <li> GoLang </li>
      <li> React 16.5 Java Script </li>
    </ul>
   </td>

  </tr>
</table>


>_For more info on the product info, please refer to Fortify Static Code Analyzer [page](https://www.microfocus.com/en-us/products/static-code-analysis-sast/overview) and SonarQube [page](https://www.sonarsource.com/products/sonarqube/)._

***

