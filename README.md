# Google Summer of Code 2019 - OWASP (Final Submission)

## Table of Contents

- [Overview](#overview)
    - [About me](#about-me)
    - [Project details](#project-details)
    - [Proposed summary](#proposed-summary)
    - [Work done](#work-done)

- [Contributions](#contributions)

    - [Detailed view in Google docs (with links to the PR)](https://docs.google.com/document/d/1uo3cSa9vl_1SGgTObOoUuq192n4Zs4Fz1dHxwatitdQ/edit?usp=sharing)
    - [View here](#view-here)
    - [Commits](#commits)
    - [Contribution graph and status](#contribution-graph-and-status)


- [Screenshots & Screenscasts](#screenshots-screenscasts-and-tutorial-videos)

- [Future work](#future-work)

- [Conclusion](#conclusion)

## Overview

### About Me

- **Name:** Azhar Ahamed
- **Major:** Computer Science
- **University:** University of Westminster
- **Institution:** Informatics Institute of Technology
- **GitHub:** [@azharanees](https://github.com/azharanees)
- **E-mail:** zhranees@live.com, azharanees1@gmail.com, azhar.2017815@iit.ac.lk
- **Telegram ID:** @azharanees
- **Project URL:** https://github.com/OWASP/RiskAssessmentFramework<br>

### Project details

The OWASP Risk Assessment Framework consist of Static application security testing and Risk Assessment tools, Even Though there are many SAST tools available for testers, but the compatibility and the Environment setup process is complex. By using OWASP Risk Assessment Framework's Static Application Security Testing tool Testers will be able to analyse and review their code quality and vulnerabilities without any additional setup. OWASP Risk Assessment Framework can be integrated in the DevSecOps toolchain to help developers to write and produce secure code.

Currently the following features are supported:



- [x] Web Deface Detection
- [x] Risk Assessment Tools
- [x] Static Application security Testing
- [x] Scanning Tools based on OWASP Top 10

**Organisation:** OWASP Foundation<br>
**Project URL:** https://github.com/OWASP/RiskAssessmentFramework<br>
**IRC channel:** https://t.me/joinchat/IjCM_BRrcPYPC3X0DZ4Rog<br>
**Mentor:** Ade Yoseman Putra [(@adeyosemanputra)](https://github.com/adeyosemanputra), AZZEDDINE Ramrami [(@aramrami)](https://github.com/aramrami)<br>
**Proposal Title:** Building an API to stage the results of Static Application Security Testing<br>
**Tag:** securetea tools<br>

### Proposed summary

**Proposed summary as per proposal**:

Building an API for the dashboard which will help the testers to Assess the Risk by
uploading the result from their SAST tools. There are many branches to the SAST tool projects provided by OWASP mainly, Building an API for the dashboard which will help the testers to Assess the Risk by uploading the result from their SAST tools. There are many branches to the SAST tool projects
provided by OWASP mainly,
- OWASP SonarQube Project
- OWASP Orizon Project
- OWASP LAPSE Project
- OWASP O2 Platform
- OWASP WAP-Web Application Protection
So Implementing the API which provides relevant inputs for Risk Rating which will be
staged in the dashboard with graphs and charts and which provides access to SAST tools

### Work done

**Summary of the work done during the GSoC :**

- **Phase I : Dashboard Implementation**
    - [Designed the mockups for the dashboard](https://github.com/azharanees/RiskAssessmentFramework/commit/13fa088329ed0592e9a76a01ab01c675667ac9a7)
    - [Initialized the Angular Development Environment](https://github.com/azharanees/RiskAssessmentFramework/commit/13fa088329ed0592e9a76a01ab01c675667ac9a7)
    - [Created the folder structure based on MVC](https://github.com/azharanees/RiskAssessmentFramework/commit/13fa088329ed0592e9a76a01ab01c675667ac9a7)
    - [Mapped the components based on mockups](https://github.com/azharanees/RiskAssessmentFramework/commit/13fa088329ed0592e9a76a01ab01c675667ac9a7)
    - [Initialized the components](https://github.com/azharanees/RiskAssessmentFramework/commit/13fa088329ed0592e9a76a01ab01c675667ac9a7)
    - [Added the routing for the components](https://github.com/azharanees/RiskAssessmentFramework/commit/13fa088329ed0592e9a76a01ab01c675667ac9a7)
    - [Added the project configuration files](https://github.com/azharanees/RiskAssessmentFramework/commit/13fa088329ed0592e9a76a01ab01c675667ac9a7)
    - [Added Angular Material](https://github.com/azharanees/RiskAssessmentFramework/commit/ff9dc287de7e99e2aa4cca4333697f69d60fc4a8)
    - [Initial Development of the resource page](https://github.com/azharanees/RiskAssessmentFramework/commit/b57404e79db58350613a218a9a082876a55ead50)
    - [Structured the Support component](https://github.com/azharanees/RiskAssessmentFramework/commit/2986d7cc8455826eae4862d7516771e9d1f18fee)
    - [Constructed the profile component](https://github.com/azharanees/RiskAssessmentFramework/commit/bbffb576b7a0851958f73b910f9712cde97c2ce2)
    - [Built the Settings component](https://github.com/azharanees/RiskAssessmentFramework/commit/9215a6df88b27bbe6c13ed0dfc532eb34829efd6)
    - [Initialized the Home component](https://github.com/azharanees/RiskAssessmentFramework/commit/16ff2765d83637b191e69424b2f3ffaec47d69c6)
    - [Added summary cards and graphs to the home component](https://github.com/azharanees/RiskAssessmentFramework/commit/4d23b6423eab5a72f0506da258d15cc21123e15f)
    - [Initialized the tools component](https://github.com/azharanees/RiskAssessmentFramework/commit/e87195c695a7d739afa8f587d347a0f15172a37d)
    - [Created the History component](https://github.com/azharanees/RiskAssessmentFramework/commit/83031fee8b2bf748c077ec9c0d49770292c9da8b)
    - [Added Charts to the History components](https://github.com/azharanees/RiskAssessmentFramework/commit/83031fee8b2bf748c077ec9c0d49770292c9da8b)
    - [Initiated the Authentication feature](https://github.com/azharanees/RiskAssessmentFramework/commit/3bffbac408d716e7c41fe7a4fd3a7e72a81d6cb6)
    - [Redesigned the Resource page made it more user friendly](https://github.com/azharanees/RiskAssessmentFramework/commit/0e16dbd36d6a73d97908d53af82cf7a507ae6f09)
    - [Created a registration component](https://github.com/azharanees/RiskAssessmentFramework/commit/db3912f582a9a00774fced578a67bbca4b0becc1)
    - [Created login component](https://github.com/azharanees/RiskAssessmentFramework/commit/4ff168c05d9f0bdf973e2b9165c9d3ae2c52c5a7)
    - [AddedAuth Guard to the components](https://github.com/azharanees/RiskAssessmentFramework/commit/2a61269ece9ce0f31f11f33257fdca6fb4dad2bd)

    - [Added Upload File Feature](https://github.com/azharanees/RiskAssessmentFramework/commit/cdd7c7d204ea8ec8e98ff724e92e06cd6ca92d19)

- **Phase II : API Implementation**

    - [Initiated the API development setting up the environment for NodeJs ](https://github.com/azharanees/RiskAssessmentFramework/commit/10399aaac9009015a75167c9ef90f5dbabbeffa7)

    - [Added Mongo-Memory Server as a temporary database](https://github.com/azharanees/RiskAssessmentFramework/commit/10399aaac9009015a75167c9ef90f5dbabbeffa7)

    - [Created Models for the database](https://github.com/azharanees/RiskAssessmentFramework/commit/10399aaac9009015a75167c9ef90f5dbabbeffa7)
    - [linked nodejs app with mongodb](https://github.com/azharanees/RiskAssessmentFramework/commit/10399aaac9009015a75167c9ef90f5dbabbeffa7)
    - [Created the user model](https://github.com/azharanees/RiskAssessmentFramework/commit/10399aaac9009015a75167c9ef90f5dbabbeffa7)
    - [Initial development of CRUD operations for the `user` model](https://github.com/azharanees/RiskAssessmentFramework/commit/10399aaac9009015a75167c9ef90f5dbabbeffa7)
    - [Added the required packages for the development of the API (Express,helmet,morgan,body-parser)](https://github.com/azharanees/RiskAssessmentFramework/commit/10399aaac9009015a75167c9ef90f5dbabbeffa7)
    - [Added the required packages for file upload (multer)](https://github.com/azharanees/RiskAssessmentFramework/commit/10399aaac9009015a75167c9ef90f5dbabbeffa7)
    - [Added the file upload functionality to store project files in the server](https://github.com/azharanees/RiskAssessmentFramework/commit/10399aaac9009015a75167c9ef90f5dbabbeffa7)
    - [Exposed File Upload API with file type validation](https://github.com/azharanees/RiskAssessmentFramework/commit/10399aaac9009015a75167c9ef90f5dbabbeffa7)
    - [Added the feature to process the uploaded files](https://github.com/azharanees/RiskAssessmentFramework/commit/3f8dd6756e941780de54549649451d341d027abb)
    - [Added File Extraction and validation](https://github.com/azharanees/RiskAssessmentFramework/commit/9f65f22c6e2a02b32ab0cc60f66b4895acc82bf7)
    - [Added feature to generate `sonar-project.properties` file dynamically](https://github.com/azharanees/RiskAssessmentFramework/commit/74c1e02c3948db502d8e17e1860c4b1d8d5be11a)
    - [Added feature to create sonarqube project through the sonarqube-api](https://github.com/azharanees/RiskAssessmentFramework/commit/74c1e02c3948db502d8e17e1860c4b1d8d5be11a)
    - [Exposing the `runScan` API end-point](https://github.com/azharanees/RiskAssessmentFramework/commit/74c1e02c3948db502d8e17e1860c4b1d8d5be11a)
    - [Added SonarQube function set](https://github.com/azharanees/RiskAssessmentFramework/commit/5677327940654f1f713b2a52a153f7ed817e1bb1)
    - [Added Logging for the sonar-scanner results](https://github.com/azharanees/RiskAssessmentFramework/commit/5677327940654f1f713b2a52a153f7ed817e1bb1)
    - [Validated API requests and handling invalid requests](https://github.com/azharanees/RiskAssessmentFramework/commit/5677327940654f1f713b2a52a153f7ed817e1bb1)
    - [Added functionality to fetch the project analysis results](https://github.com/azharanees/RiskAssessmentFramework/commit/2ccad1a71ed5381a14f26741d64fa03c715f03fa)
    - [Structuring the fetched result from sonarqube api](https://github.com/azharanees/RiskAssessmentFramework/commit/2ccad1a71ed5381a14f26741d64fa03c715f03fa)
    - [Filtered Issue Types from the fetched results](https://github.com/azharanees/RiskAssessmentFramework/commit/2ccad1a71ed5381a14f26741d64fa03c715f03fa)
    - [Exposed the `getResultsById` api end-point](https://github.com/azharanees/RiskAssessmentFramework/commit/2ccad1a71ed5381a14f26741d64fa03c715f03fa)
    - [Classified the results by type and frequency](https://github.com/azharanees/RiskAssessmentFramework/commit/15f708728a020caa5e43e5eac42bb5eadaf9f60d)
    - [Restructured files based as MVC model](https://github.com/azharanees/RiskAssessmentFramework/commit/d52d509f62bd7301cd1bb133c8ec998d90ca3d63)
    - [Added authentication process](https://github.com/azharanees/RiskAssessmentFramework/commit/d52d509f62bd7301cd1bb133c8ec998d90ca3d63)
    - [Validated user authentications](https://github.com/azharanees/RiskAssessmentFramework/commit/d52d509f62bd7301cd1bb133c8ec998d90ca3d63)
    - [Added `user` schema through mongoose](https://github.com/azharanees/RiskAssessmentFramework/commit/d52d509f62bd7301cd1bb133c8ec998d90ca3d63)
    - [Exposing user creation api end-point](https://github.com/azharanees/RiskAssessmentFramework/commit/d52d509f62bd7301cd1bb133c8ec998d90ca3d63)
    - [Added `mongodb atlas` connection for cloud database](https://github.com/azharanees/RiskAssessmentFramework/commit/64ea44cd331454aaec6df1e6e384deab8b5a3c90)
    - [Created Schema for `projects`](https://github.com/azharanees/RiskAssessmentFramework/commit/64ea44cd331454aaec6df1e6e384deab8b5a3c90)
    - [Created Schema for `projects`](https://github.com/azharanees/RiskAssessmentFramework/commit/64ea44cd331454aaec6df1e6e384deab8b5a3c90)

- **Phase III : API-DASHBOARD Connection**

    - [Connected Upload File to the API endpoint](https://github.com/azharanees/RiskAssessmentFramework/commit/6a13402fc49e458154f76d6ab2617f93a433884b)

    - [Connected User details to the getUser endpoint](https://github.com/azharanees/RiskAssessmentFramework/commit/d2be174d596c0e654fe9d3ecf47e8bb18cfbdb3f)
    - [Updated Profile Component and handling api requests and responses](https://github.com/azharanees/RiskAssessmentFramework/commit/ec7ed2eb5cf333c89cd2da1707f776ba60c24880)
    - [Updated Profile Component and handling api requests and responses](https://github.com/azharanees/RiskAssessmentFramework/commit/ec7ed2eb5cf333c89cd2da1707f776ba60c24880)
    - [Implemented REST-API services to fetch analysis results](https://github.com/azharanees/RiskAssessmentFramework/commit/1f4efe2b7e8c7fc39ed3269f35ea22b74c70ce59)
    - [Updated Charts to fit data fetched from the api](https://github.com/azharanees/RiskAssessmentFramework/commit/1f4efe2b7e8c7fc39ed3269f35ea22b74c70ce59)
    - [Implemented Capturing and reusing the projectId generated from the api](https://github.com/azharanees/RiskAssessmentFramework/commit/28852f104b0d0764feec9a9f8a17ca2946fd4d3e)
    - [Updated tools component for better useability](https://github.com/azharanees/RiskAssessmentFramework/commit/28852f104b0d0764feec9a9f8a17ca2946fd4d3e)
    - [Added Result View immediately after scan completes](https://github.com/azharanees/RiskAssessmentFramework/commit/4d58d0d9be407194551e194ca16b3942c5e974b5)
    - [Added analysis-report component for each project analysed](https://github.com/azharanees/RiskAssessmentFramework/commit/3e7f26172bb2537ac3b5a0fa391df33c6c595423)
    - [Added analysis-report component for each project analysed](https://github.com/azharanees/RiskAssessmentFramework/commit/3e7f26172bb2537ac3b5a0fa391df33c6c595423)
    - [GUI updates for analysis-report component](https://github.com/azharanees/RiskAssessmentFramework/commit/95195b45ddf7e7166e5e5f3e9867976c77624565)
    - Dockerized the NodeJs API
    - Dockerized the Dashboard



## Contributions
### Pull requests and issues

- [Detailed view in Google docs (with links to the commits)](https://docs.google.com/document/d/1uo3cSa9vl_1SGgTObOoUuq192n4Zs4Fz1dHxwatitdQ/edit?usp=sharing)

- [View here](#view-here)

- [Commits](#commits)
    
#### View here

|                                                                                                                    |                 |                                                                                                       |
|--------------------------------------------------------------------------------------------------------------------|-----------------|-------------------------------------------------------------------------------------------------------|
| Commits                                                                                                         | Completion Date | URL                                                                                                   |
| Built the side nav/drawer                                                                                          | 10/5/2019       | https://github.com/azharanees/RiskAssessmentFramework/commit/13fa088329ed0592e9a76a01ab01c675667ac9a7 |
| Made custom theme                                                                                                  | 11/5/2019       | https://github.com/azharanees/RiskAssessmentFramework/commit/13fa088329ed0592e9a76a01ab01c675667ac9a7 |
| Built the routing                                                                                                  | 12/5/2019       | https://github.com/azharanees/RiskAssessmentFramework/commit/13fa088329ed0592e9a76a01ab01c675667ac9a7 |
| Built a basic login UI                                                                                             | 13/5/2019       | https://github.com/azharanees/RiskAssessmentFramework/commit/7a81629d70f1b2da213a5b4ef9779b0a79ae1d33 |
| Resolved some issues related to theming                                                                            | 13/5/2019       | https://github.com/azharanees/RiskAssessmentFramework/commit/7a81629d70f1b2da213a5b4ef9779b0a79ae1d33 |
| Started developing the resource page                                                                               | 14/5/2019       | https://github.com/azharanees/RiskAssessmentFramework/commit/b57404e79db58350613a218a9a082876a55ead50 |
| Altered the theme and background of the drawer/toolbar                                                             | 15/5/2019       | https://github.com/azharanees/RiskAssessmentFramework/commit/b57404e79db58350613a218a9a082876a55ead50 |
| Fix issues related to styles.css                                                                                   | 15/5/2019       | https://github.com/azharanees/RiskAssessmentFramework/commit/b57404e79db58350613a218a9a082876a55ead50 |
| Added the links to top 10 owasp 2017 based on -https://www.owasp.org/index.php/Category:OWASP_Top_Ten_2017_Project | 15/5/2019       | https://github.com/azharanees/RiskAssessmentFramework/commit/b57404e79db58350613a218a9a082876a55ead50 |
| Fixing tsling issues                                                                                               | 16/05/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/7a81629d70f1b2da213a5b4ef9779b0a79ae1d33 |
| initial development of the resource page                                                                           | 16/05/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/b57404e79db58350613a218a9a082876a55ead50 |
| Updated the readme                                                                                                 | 16/05/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/a5e4fe68de145007ef0d55f83239239dc76e99b9 |
| Minor changes in resource component                                                                                | 19/05/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/2a8239e5e8bd5275a9b435dc4ecdcafc5e9839ad |
| initial structure for components of support page                                                                   | 21/05/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/2986d7cc8455826eae4862d7516771e9d1f18fee |
| added card and resized the expansion panel                                                                         | 21/05/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/8fff482475011583fbf67ab9d01d349da7f3e758 |
| constructed the profile component                                                                                  | 23/05/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/bbffb576b7a0851958f73b910f9712cde97c2ce2 |
| Updated the profile component and support component                                                                | 23/05/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/9a24d592efb6d3baf5c91cea3f71f786f0cd84f1 |
| Addition of Avatar Icon                                                                                            | 24/05/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/191a4f026e69ce82063305d40a3a26e164810bda |
| Initializing the Settings page                                                                                     | 25/05/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/9215a6df88b27bbe6c13ed0dfc532eb34829efd6 |
| fixing issues in settings component and profile component                                                          | 25/05/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/04d71bd2173fea8719e67f69882b06ede8e5f6d0 |
| Updated Settings Component                                                                                         | 27/05/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/21ecd12d4efebab2729a8ec6e597b6804008a16f |
| Initial Home Page without charts                                                                                   | 31/05/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/16ff2765d83637b191e69424b2f3ffaec47d69c6 |
| Addition of Summary Cards                                                                                          | 01/06/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/4d23b6423eab5a72f0506da258d15cc21123e15f |
| Addition of Line Graph                                                                                             | 01/06/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/4d23b6423eab5a72f0506da258d15cc21123e15f |
| Updated home page                                                                                                  | 04/06/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/a85c0fd9cd4eb200b3500b5cd82ffc141a0c30f8 |
| Initial tool page                                                                                                  | 08/06/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/84e55cd051513c62ed4b014864942c2ce9959615 |
| Updatedtools page                                                                                                  | 12/06/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/e87195c695a7d739afa8f587d347a0f15172a37d |
| Added more charts and table to History Component                                                                   | 15/06/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/83031fee8b2bf748c077ec9c0d49770292c9da8b |
| initiated the authentication feature                                                                               | 20/06/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/3bffbac408d716e7c41fe7a4fd3a7e72a81d6cb6 |
| Redesigning of Resource page with dialog popup                                                                     | 23/06/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/0e16dbd36d6a73d97908d53af82cf7a507ae6f09 |
| Updated Readme                                                                                                     | 23/06/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/b09643fa60e4482ff8536d84e93ffd978af05dbd |
| Initial Registration Form                                                                                          | 26/06/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/db3912f582a9a00774fced578a67bbca4b0becc1 |
| Validating Registration Form                                                                                       | 26/06/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/db3912f582a9a00774fced578a67bbca4b0becc1 |
| Adding Loading Spinner                                                                                             | 26/06/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/db3912f582a9a00774fced578a67bbca4b0becc1 |
| Adding validation for the form fields                                                                              | 27/076/2019     | https://github.com/azharanees/RiskAssessmentFramework/commit/d540ab42bc4b3de3266f3ffc82426de0efa996a1 |
| Managing routing for the register component                                                                        | 27/06/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/d540ab42bc4b3de3266f3ffc82426de0efa996a1 |
| Structuring the registration component                                                                             | 27/06/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/5a5850f731064f131824f243912f8587bf8b2d40 |
| Updating the login component                                                                                       | 27/06/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/4ff168c05d9f0bdf973e2b9165c9d3ae2c52c5a7 |
| Structuring the login component                                                                                    | 27/06/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/4ff168c05d9f0bdf973e2b9165c9d3ae2c52c5a7 |
| Added Authentication guard                                                                                         | 27/06/2019      | https://github.com/azharanees/RiskAssessmentFramework/commit/2a61269ece9ce0f31f11f33257fdca6fb4dad2bd |
| Generating user Id for each registered user                                                                        | 27/06/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/2a61269ece9ce0f31f11f33257fdca6fb4dad2bd |
| Adding SANS 25 resources to the resource component                                                                 | 03/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/0c64d0faefca290f896408411f6060bd84404e49 |
| Updated the sans 25 resources                                                                                      | 04/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/fecfbaf8d2ef89cc380dc3e25ce14c78d3748feb |
| Making the sans 25 resource rendering static                                                                       | 04/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/4b5ecbe7f67f12c3f39368041fd04d8d470d3916 |
| Adding Dialog Modal to display more information on resources                                                       | 04/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/c5430d7a53f3ec6c635ffbcaee689417a8ef07a2 |
| Adding the Upload File form field to upload project files to analyze                                               | 06/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/cdd7c7d204ea8ec8e98ff724e92e06cd6ca92d19 |
| Adding drag and drop feature for the upload project form field                                                     | 06/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/cdd7c7d204ea8ec8e98ff724e92e06cd6ca92d19 |
| Validating file input using file type                                                                              | 06/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/cdd7c7d204ea8ec8e98ff724e92e06cd6ca92d19 |
| Updating readme with upload component features                                                                     | 06/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/336068b1f2e0d817d6a6effa14d9eee0fc490af1 |
| Phase 2 REST-API implementation                                                                                    |                 |                                                                                                       |
| Initializing the nodejs environment for the rest api development                                                   | 07/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/10399aaac9009015a75167c9ef90f5dbabbeffa7 |
| Adding project dependencies                                                                                        | 07/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/10399aaac9009015a75167c9ef90f5dbabbeffa7 |
| Adding mongodb connection from the api                                                                             | 07/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/10399aaac9009015a75167c9ef90f5dbabbeffa7 |
| Adding CRUD functions for the user model from the api                                                              | 07/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/10399aaac9009015a75167c9ef90f5dbabbeffa7 |
| Exposing the getUser api                                                                                           | 07/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/10399aaac9009015a75167c9ef90f5dbabbeffa7 |
| Exposing the deleteUser api                                                                                        | 07/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/10399aaac9009015a75167c9ef90f5dbabbeffa7 |
| Exposing the updateUser api                                                                                        | 07/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/10399aaac9009015a75167c9ef90f5dbabbeffa7 |
| Updated readme file for the api development                                                                        | 07/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/ea0f51b30666698dc158f0140d95ed6ce665f24a |
| Fixing lint issues                                                                                                 | 07/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/23bc1bae3f4c103b692057dec261ec8efc46d1ad |
| Implemented file upload endpoint                                                                                   | 10/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/22ee6c7675ed1f279fb20a631ab3266efd35e7b3 |
| Zip validation                                                                                                     | 10/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/22ee6c7675ed1f279fb20a631ab3266efd35e7b3 |
| Cleaning the code and project files                                                                                | 10/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/494825764c04acde1841f20389267d082d61ca5e |
| Adding the file extraction feature for uploaded file processing                                                    | 10/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/3f8dd6756e941780de54549649451d341d027abb |
| Updating the response for the fileUpload endpoint                                                                  | 11/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/ac0d133b5dfb77f7f45b7c6bd6482795d1cbf8ff |
| Fixing lint issues                                                                                                 | 11/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/236aef6fa92fc5a905a264c95b29a64c58f7823f |
| Updating the upload/code endpoint                                                                                  | 11/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/7f278bb044e524f9759bd2378d062769d971cd0e |
| Created scanFile endpoint to scan the uploaded files                                                               | 11/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/74c1e02c3948db502d8e17e1860c4b1d8d5be11a |
| Adding sonarqube api connectivity                                                                                  | 11/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/74c1e02c3948db502d8e17e1860c4b1d8d5be11a |
| Creating sonarqube properties file dynamically when runScan request is made                                        | 11/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/74c1e02c3948db502d8e17e1860c4b1d8d5be11a |
| Exposing the api scanById endpoint                                                                                 | 11/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/74c1e02c3948db502d8e17e1860c4b1d8d5be11a |
| Added scan-project function to scan a project using sonar-scanner                                                  | 12/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/5677327940654f1f713b2a52a153f7ed817e1bb1 |
| Added fetchResult endpoint to fetch the results from sonar-qube api                                                | 12/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/2ccad1a71ed5381a14f26741d64fa03c715f03fa |
| Filtering the results obtained from sonarqube api                                                                  | 12/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/2ccad1a71ed5381a14f26741d64fa03c715f03fa |
| Classification of fetched results and preparing the results for response                                           | 12/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/2ccad1a71ed5381a14f26741d64fa03c715f03fa |
| Updated readme adding fetchResult api details                                                                      | 12/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/56cf63189ef3ad7d39729dd513f674144991b802 |
| Fixing lint issues                                                                                                 | 12/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/3cbbc947f485c21a6d0dbc7eac7ac73044f24da7 |
| Classifying the result by Type and frequency which was obtained from the sonar-qube web api                        | 17/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/15f708728a020caa5e43e5eac42bb5eadaf9f60d |
| Structuring the files as MVC                                                                                       | 21/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/d52d509f62bd7301cd1bb133c8ec998d90ca3d63 |
| Creating models for user                                                                                           | 21/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/d52d509f62bd7301cd1bb133c8ec998d90ca3d63 |
| Adding mongodb atlas connection to store data in the cloud                                                         | 21/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/64ea44cd331454aaec6df1e6e384deab8b5a3c90 |
| Updating dependencies                                                                                              | 21/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/295507c4d41bcdad01c7dc4db2c91a1f706b868f |
| Switching back to local mongodb from cloud                                                                         | 22/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/e35c008f35bd23377259cae353d0a46028732407 |
| Fixing lint issues                                                                                                 | 22/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/7b04f4c8ce9ad1a8071175ca53fe8a429265460f |
| Phase 3 REST-API - Dashboard connection                                                                            |                 |                                                                                                       |
| Connecting upload file to the rest api                                                                             | 29/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/6a13402fc49e458154f76d6ab2617f93a433884b |
| Connecting the profile component to the getUser details endpoint                                                   | 29/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/d2be174d596c0e654fe9d3ecf47e8bb18cfbdb3f |
| Updating the profile component                                                                                     | 31/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/ec7ed2eb5cf333c89cd2da1707f776ba60c24880 |
| Fixing render issues in profile component                                                                          | 31/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/ec7ed2eb5cf333c89cd2da1707f776ba60c24880 |
| Merging master branch of the project to the forked branch                                                          | 31/07/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/3bdab665e85020b606e0906118f0aaf802885f71 |
| Populating chart data from the fetchResult endPoint                                                                | 01/08/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/1f4efe2b7e8c7fc39ed3269f35ea22b74c70ce59 |
| Added feature to create project on the sonarqube server with auto generated projectId                              | 05/08/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/28852f104b0d0764feec9a9f8a17ca2946fd4d3e |
| Added feature to display the result dialog after each completed scan                                               | 06/08/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/4d58d0d9be407194551e194ca16b3942c5e974b5 |
| Added analysis-report component for each project analyzed                                                          | 09/08/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/3e7f26172bb2537ac3b5a0fa391df33c6c595423 |
| Updated analysis report component                                                                                  | 15/08/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/58e67a2396483ae8ee253ec7c35cd92f00be0555 |
| Updated the gui of the analysis-report component                                                                   | 15/08/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/95195b45ddf7e7166e5e5f3e9867976c77624565 |
| Adding information regarding the issues found on analysis to the report-analysis component                         | 18/08/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/dde3c7f2b641f06c028131167873083a6702017a |
| Code Refactor on GUI                                                                                               | 18/08/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/dde3c7f2b641f06c028131167873083a6702017a |
| Code Refactor on API                                                                                               | 18/08/19        | https://github.com/azharanees/RiskAssessmentFramework/commit/22db5a6334cb9eb30466fdb2da2e8fc4e94ff75f |

### Commits
View list of commits [here](https://github.com/OWASP/RiskAssessmentFramework/commits?author=azharanees).

### Contribution graph and status

**Commits:**

![graph](https://user-images.githubusercontent.com/36698676/63648721-758d8c80-c751-11e9-9ff0-43b53c6a81ca.png)

## Screenshots screenscasts and tutorial videos

**Angular GUI dashboard**

![Login dashboard](https://user-images.githubusercontent.com/36698676/63649189-43cbf400-c758-11e9-925a-79f0c64e8b7a.png)

![Home](https://user-images.githubusercontent.com/36698676/63649229-b63cd400-c758-11e9-9fa7-7db3de5cad06.png)

![Tools](https://user-images.githubusercontent.com/36698676/63649252-fdc36000-c758-11e9-9979-f867c7454f8f.png) 

![History](https://user-images.githubusercontent.com/36698676/63649359-2009ad80-c75a-11e9-966d-de3a01e4c6b0.png)

![Profile](https://user-images.githubusercontent.com/36698676/63649421-e4231800-c75a-11e9-9288-8b3783889f59.png)

![Resources](https://user-images.githubusercontent.com/36698676/63649426-0ae14e80-c75b-11e9-8a88-cfdd9e830d9f.png)

![Settings](https://user-images.githubusercontent.com/36698676/63649432-2a787700-c75b-11e9-8655-f11cb65f90a2.png)

![Support](https://user-images.githubusercontent.com/36698676/63649440-4ed45380-c75b-11e9-87b8-59a556e223c5.png)

![Upload](https://user-images.githubusercontent.com/36698676/63649450-87742d00-c75b-11e9-9b9d-5982bd0157d0.png)




**Demo**
![Demo-1](https://user-images.githubusercontent.com/36698676/63649995-a32f0180-c762-11e9-999c-2b50f32340fd.gif)

![Demo-2](https://user-images.githubusercontent.com/36698676/63650087-649a4680-c764-11e9-9fca-86ccc4880f18.gif)
## Future Work

The followings are the projected milestone for next releases:

- Creating Virtual Image for the stack
- Project analysis through repository links
- Performing bug fixes
- Integrating other SAST tools
- Bundling all the dependencies
- Improving the UI/UX of the dashboard
- Hosting as distributed micro services


## Conclusion

Working on this project was one of the best experience I got which made me learn many things technical and non-technical also helped my network to grow. My mentors were very supportive and almost everyday they were checking on me and provided me with resources that helped me successfully complete this project. GSoC helped me get started on contributing to the open source even though this year's GSoC period is coming to an end It's just the beginning of a new journey. Looking forward to work on open source projects and the OWASP organization.



