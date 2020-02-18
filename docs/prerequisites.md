# Prerequisites, requirements and support
-----------------------------------------

# Prerequisites and requirements

## i) Build agent
- Microsoft Windows 10 / Windows Server 2016 or 2019
- Linux (Recommended Ubuntu 18.04 or RHEL 7)
- MacOS High Sierra and above (Supported for remote<sup>1</sup> only)  

<i><small><sup>1</sup>Remote refers to agents provide their own. Elastic refers to agents provided by SHIP</small></i>

## ii) Browser
Supported on Apple Macintosh / Microsoft Windows:
- Internet Explorer 11 
- Microsoft Edge
- Chrome
- Firefox

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
 - Internet Explorer 11, Microsoft Edge, Firefox and Chrome
 - Testing Framework: Robot Framework with Selenium2Library Or Selenium+Java
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
<strong><u>Fortify SCA Supported Languages</u></strong>
- .NET MSBuild
- .NET Core
- Gradle 4.x
- Java 9, 10, 11 & 12
- Ruby (multiple versions)
- Python 2.x and 3.x
- Angular 2, 4, 5, 6 & 7
- Node.js 10.x
- TypeScript 3.0, 3.1 and 3.2 o Swift 4.2 / XCode 10
- Objective-C/C++
- GoLang
- React 16.5 Java Script

<strong><u>SonarQube Supported Languages</u></strong>
- Java, JavaScript, C#, TypeScript, Kotlin, Ruby, Go, Scala, Flex, Python, PHP,
HTML, CSS, XML, VB.NET & Swift

>_For more info on the product info, please refer to Fortify Static Code Analyzer [page](https://www.microfocus.com/en-us/products/static-code-analysis-sast/overview) and SonarQube [page](https://www.sonarsource.com/products/sonarqube/)._

***

# Migration from existing workload

### i) Bamboo
- Supports migration from Bamboo v.6.4.0<strong><sup>*</sup></strong>only
- Migration from other CI tools will not be supported

<i><small>*SHIP Team will attempt to port over other Bamboo versions through best effort. Take note that the it may not be successfully migrated.</small></i>

### ii) Bitbucket
- Any Git-based version control system can be ported to Bitbucket
- Non-Git-based code can be checked into Bitbucket, but commit history will not be preserved

### iii) Confluence
- Spaces can be imported from Confluence versions 6.13 to 6.15<strong><sup>*</sup></strong>
- Exports to PDF and Word documents can be directly imported into Confluence

### iv) JIRA
- Jira tickets can be exported from existing systems and imported into SHIP 
- Existing Projects and Workflows will not be ported over

<i><small>*Versions indicated may be updated over time, and subjected to product availability. For more information, please contact <a href="mailto:enquiries_SHIP@tech.gov.com">SHIP team</a>.</small></i>

***

# Support

| Severity level | Description                                    | Examples                         | Resolution Time                              |
|----------------|------------------------------------------------|----------------------------------|----------------------------------------------|
| 1              | Error prevents all use of Service              | VPN goes down                    | 1-3 business days                            |
| 2              | Error disables major functions of the Services | Technical issues involving tools | 4-6 business days                            |
| 3              | Error disables minor functions of the Services |                                  | Subjected to GovTech's reasonable discretion |


<strong>Service Request, User Manual & On-boarding Documents</strong>
- [Service Desk](https://jira.ship.gov.sg/servicedesk/customer/portal/11)
- [User Manual & On-boarding Documents](https://confluence.ship.gov.sg/display/SHIP/SHIP+Home)
