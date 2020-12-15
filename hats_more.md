# HATS
------

# Services by Green HATS

## Functional Test Automation

- Leverage on RobotFramework scripting methodology, a “English-style” scripting language for non-technical roles to create and execute automated test cases.
- Robotcorder – a Google Chrome extension, helps user to script faster using the recording and playback feature.
- Device farm, consisting of multiple browsers and mobile devices to run your manual or automated functional testing.
- Parallel execution of tests across multiple devices and platforms.
- Detailed reporting on points of failure and screenshots for debugging.

### How it Works
<strong><u>Test Scripts Development</u></strong>  
- Integrated development environment (IDE) with syntax and
keyword highlighting feature
- Supports emulators (Xcode iOS and Android) during
development
- Training can be provided upon request (at a cost)  

<strong><u>Continuous Integration (CI) Process</u></strong>
- Check-in your test scripts into SHIP (Bitbucket), together with
your application source codes.
- Automate the build using SHIP (Bamboo), and then deploy your
application to a test environment.
- Triggered the automated test from SHIP (Bamboo), and
execute your test cases in the device farm.
- Test reports are pushed to SHIP (Bamboo) as artifacts.

## Service Virtualisation
- Create mock services to simulate external systems behavior. o Decouple the dependency on the availability of the external
- systems, thereby speed up the development and testing effort needed to manage external systems.

### How it Works
- Create the virtualise service behavior and model to stand in for the actual service during development and testing.
- Configure the service via a web portal. 
- Access your target end-point.

---

# Services by White HATS

## Static Application Security Testing (SAST) & Code Quality
- Leveraging on Micro Focus Fortify SCA and SonarQube tool to scan source codes for code quality, security flaws or vulnerabilities.
- Helps to drive quality secured coding practices.
- Lower the development effort, as the findings could be fixed as
soon as they are detected.
- Detecting code “smells” quality issues.
- Dashboard provided to help you manage the findings.

### How it Works
- Using SHIP (Bamboo), trigger the Build and Scan in CI Environment, either by scheduling job or upon any code commit.
- At end of scanning, results are uploaded into a hats dashboard. 
- User can manage the findings/issues in the dashboard.
- Possibility to enable the automated tickets creation in SHIP (Jira) for the findings.
- Generate PDF and CSV reports for analysis.
