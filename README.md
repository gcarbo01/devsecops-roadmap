# devsecops-roadmap

Intro:<br>
Listed in no particular order. Do your research. Most of these tools are open-sourced and may flourish or die without notice.
Each tool may be applicable for one or more capabilities. So they are tagged by "Category".
<br>
<br>
<br>
**Sonarqube (JavaScript and many languages)**	
<br>
Category: 
Static Code Analyzer
<br>
Comments:
Source code quality	Open source static code analyser	
<br>
Resources:
Sonarqube JavaScript
https://docs.sonarqube.org/display/PLUG/SonarJS
<br>
<br>
<br>
**Sonarqube (.net framework)**	

Category: 
Static Code Analyzer

Comments: 
Source code quality	Open source static code analyser	

Resources:
Sonarqube .net framework
https://docs.sonarqube.org/display/SCAN/Analyzing+with+SonarQube+Scanner+for+MSBuild


**Sonarqube (Java)**

Category: 
Static Code Analyzer

Comments: 
Source code quality	Open source static code analyser.

Resources:
Sonarqube Java
https://docs.sonarqube.org/display/PLUG/SonarJava


**HTMLhint**
Category: 
Static Code Analyzer

Comments: 
Source code quality	Static Code analyser for Web applications and Single Page Applications	https://htmlhint.io/

Resources:
https://github.com/htmlhint/HTMLHint
This applies only if the project uses this language.


**Flow**	
Category: 
Static Code Analyzer

Comments: 
Source code quality	Flow is a static type checker for JavaScript. The overall mission of Flow is to deliver an immersive coding experience for JavaScript developers—a fast edit-refresh cycle—even as the codebase evolves and grows.	

Resources:
https://flow.org/
https://github.com/facebook/flow


SQL Fluff
Category: 
Source code quality	SQL int
Comments: 
Source code linter specialising in SQL statements.	It helps you write good SQL and catch errors and bad SQL before it hits your database.
Resources:
https://docs.sqlfluff.com/en/stable/  


**SQL Lint**
Category: 
Source code quality

Comments: 
Source code linter specialising in SQL statements. It helps you write good SQL and catch errors and bad SQL before it hits your database.	

Resources:
SQL Linter
https://github.com/joereynolds/sql-lint



**SQL TSQLLint**	
Category: 
Source code quality

Comments:
Source code linter specialising in SQL statements. It helps you write good SQL and catch errors and bad SQL before it hits your database.

Resources:
SQL Linter
https://github.com/tsqllint/tsqllint 


**CSV Lint**
Category: 
Source code quality

Comments: 
Source code quality, Automated Testing	Check CSV files to see whether they contain the columns and types of values they should. It helps you write good SQL and catch errors and bad SQL before it hits your database.	

Resources:
CSV Lint
https://csvlint.io/


**Conftest**

Category:	
Source code quality. Conftest test and verifies configuration files.

Comments: 
It is a tool for writing tests against structured configuration data. It relies on Open Policy Agent's Rego language to write configuration tests. For example, Kubernetes configurations, Tekton pipeline definitions or even Terraform plans. Or any other JSON file.	

Resources:
https://www.conftest.dev/


**Accessibility Design linter practice**

Category:	
Source code quality		

Comments: 
Automate accessibility design verification

Resources:
https://www.microsoft.com/design/inclusive/
https://www.digitala11y.com/free-accessibility-linters-to-automate-accessibility-workflow/


**Google Lighthouse**

Category: 
Source code quality

Comments: 
It is a tool written by Google to assess web applications and web pages, collecting performance metrics and insights on good development practices.

Resources:
https://developer.chrome.com/docs/lighthouse/overview/
https://github.com/GoogleChrome/lighthouse


**Bazel**	

Category: 
Interoperability

Comments: 
CI-CD scripting pipeline language. Build portable pipelines and configurations using a scripting language that allows changing the underlying CI-CD technology.	

Resources:
CI-CD tool and platform-independent scripting language.
https://bazel.build/


**Elastic APM	Open Telemetry**

Category: 
Dashboard.

Comments: 
Elastic Search provides a protocol to inject and display open telemetry to a dashboard. 
This is useful for the case it is required to create a custom dashboard from the CI-CD pipeline execution itself. 

Resources:
For example, when the pipeline is implemented in Jenkins 
https://plugins.jenkins.io/opentelemetry/	
https://www.elastic.co/apm 


**Cloud Cost** 

Category: 
Optimisation Cost, Infrastructure Architecture Cost Calculation Simulation, Infrastructure Architecture Cost Optimisation 
Infrastructure Architecture Budget control 

Comments: 
CI-CD pipeline component: 
1.	create or modify budgets
2.	run cost forecasting calculation considering the already consumed budget
3.	verify, alert or deny deployments depending on budget progression and forecasting. Because of an error, a script can instantiate unnecessary resources. 
User interface component: 
1.	create or modify budgets.
2.	assign responsible per budget/application.
3.	verify and limit the cost increase
Monitoring component: 
1.	monitoring real-time.
2.	run cost forecasting calculation considering the already consumed budget
3.	alert to responsible per budget/application.
This capability may be in the same group as the one provided by:
•	Microsoft Azure cost management API
•	Harness.io

Resources:
Microsoft has recently implemented cost and budget APIs and built-in functions in Azure Portal that could help to develop this capability.	https://www.thoughtworks.com/radar/techniques/run-cost-as-architecture-fitness-function
https://docs.microsoft.com/en-us/azure/cost-management/tutorial-forecast-spending
https://docs.microsoft.com/en-us/rest/api/consumption/forecasts/list
https://docs.microsoft.com/en-us/rest/api/consumption/budgets
Create a budget to monitor your spending with Azure Cost Management example
https://www.youtube.com/watch?v=ExIVG_Gr45A


**harness**
Category: 
Cloud Cost Optimisation	Cost	Infrastructure Architecture Cost Calculation Simulation,  Infrastructure Architecture Cost Optimisation 

Comments: 
Infrastructure Architecture Budget control 

Resources:
https://harness.io/ 


**Infracost**

Category: 
Cost management	

Comments:
It makes cost trade-offs visible in Terraform pull requests. It's open-source software and supports pricing for AWS, GCP and Microsoft Azure out of the box. It also provides a public API that can be queried for current cost data. Note: There has to be a bridge integration program to get the cost and publish it in MS Teams or Slack for approval.

Resources:
https://www.infracost.io/
https://github.com/infracost/infracost 

**Terracost**
Category:	
Cost management.

Comments: 
Cloud cost estimation for Terraform as cli tool.

Resources:
https://github.com/cycloidio


**Kanban wall issues integration**	

Category: 
Continue Delivery, Integration of the CI pipeline with Kanban wall issues.

Comments:
Enable a full Continuous Delivery lifecycle to open/update issues automatically from the Continue Integration pipeline. These are provided as an example:

Resources:
Jenkins:
https://wiki.jenkins.io/display/JENKINS/Jira+Issue+Updater+Plugin
Atlassian Jira:
https://developer.atlassian.com/server/jira/platform/jira-rest-api-examples/
https://developer.atlassian.com/server/jira/platform/jira-rest-api-example-create-issue-7897248/
Azure DevOps:
It is understood that in the case of Azure DevOps, the build pipeline failure can be configured to create issues automatically in the Azure DevOps Kanban wall.
https://docs.microsoft.com/en-us/rest/api/azure/devops/?view=azure-devops-rest-5.0
See the “Work Item Tracking” section.


**OpenSCAP**	

Category: 
Container scanning

Comments:
SCAP stand for Security Content Automation Protocol (from the National Institute of Standards and Technology – NIST –)
It is a tool that provides built-in support for this industry-standard, open-source compliance assessment tool that enables users to quickly add compliance scanning and automated report generation to their pipelines. OpenSCAP executes CIS Benchmarks against hardened images. The benchmarks request different levels of hardening for different types of industries. The benchmark applies to open-sourced software and commercial software images also. They extend to Operating Systems, Server Software, Cloud Providers, Mobile Devices, Network Devices, Desktop Software Multi-Function Print Devices.	

Resources:
OpenSCAP 
https://www.open-scap.org/tools/ 
OpenSCAP Github
https://github.com/OpenSCAP/openscap 
Center for Internet Security (CIS) – Benchmarks
https://www.cisecurity.org/cis-benchmarks/ 
Free Hardened Images CIS
https://www.cisecurity.org/cis-hardened-image-list/ 
Read more about Hardening images
https://medium.com/swlh/hardening-images-on-cloud-b4269944ee6c 


**ServerSpec** 

Category: 
Test Driven Design	ServerSpec - Test Driven Design for containers

Comments:
Test the configurations of containers. Allow fast refactoring of infrastructure. It tests your servers’ actual state by executing commands locally via SSH, WinRM, Docker API, etc. So you don’t need to install any agent software on your servers and can use any configuration management tools, Puppet, Ansible, CFEngine, Itamae, etc.
For example:
- Verify that the container is rootless
- Verify the correct configuration of AppArmor
(AppArmor is a Mandatory Access Control (MAC) system which is a kernel (LSM) enhancement to confine programs to a limited set of resources. AppArmor's security model is to bind access control attributes to programs rather than to users)	

Resources:
serverspec
https://serverspec.org/
Getting started with chef cookbooks as an app dev with test-kitchen + docker, part 1
https://www.intricatecloud.io/2018/04/cookbook-testing-with-test-kitchen-chefspec-serverspec-part-1/ 
Testing your cookbooks with test-kitchen + chefspec + serverspec, part 2
https://www.intricatecloud.io/2018/05/cookbook-testing-with-test-kitchen-chefspec-serverspec-part-2/ 
Verify that the container is rootless
https://github.com/opencontainers/runc#rootless-containers 
Verify the correct configuration of AppArmor
AppArmor is a Mandatory Access Control (MAC) system, a kernel (LSM) enhancement to confine programs to a limited set of resources.
AppArmor's security model is to bind access control attributes to programs rather than to users. 
https://documentation.suse.com/sles/12-SP4/html/SLES-all/cha-apparmor-intro.html 


**Anchore**

Category: 
Security, Reliability, Docker container vulnerability scanning, 

Comments:
This capability may be in the same group as the one provided by:
•	Anchore
•	Clair

Resources:
https://anchore.com/opensource/


**Clair**
Category: Security, Reliability, Docker containers vulnerability scanning.
Comments:
This capability may be in the same group as the one provided by:
•	Anchore
•	Clair
Resources:
https://github.com/coreos/clair


**kubectl-kubesec**

Category: 
Security, Reliability

Comments:
It is a security risk analysis for Kubernetes resources	kubectl-kubesec

Resources:
https://github.com/controlplaneio/kubectl-kubesec


**Kube bench**	

Category: 
Security, Reliability

Comments:
It is a tool for Running Kubernetes Center for Internet Security (CIS) 
This capability may be in the same group as the one provided by:
•	Kube bench 
•	Kube score
•	Kube hunter

Resources:
Benchmark Tests	
https://github.com/aquasecurity/kube-bench
https://www.cisecurity.org/cis-benchmarks/


**Kube score**	

Category: 
Reliability, Security

Comments:
Kubernetes object analysis with recommendations for improved reliability and security.	
This capability may be in the same group as the one provided by:
•	Kube bench 
•	Kube score
•	Kube hunter

Resources:
https://kube-score.com/
https://github.com/zegl/kube-score


**Falco**	

Category: 
Threat detection, Runtime detection engine.	

Comments:
Package Hunter is a tool to analyze a program's dependencies for malicious code and other unexpected behaviour by installing the dependencies in a sandbox environment and monitoring system calls executed during the installation. Package Hunter, you could find out that a package attempted to open a network connection on installing a package.	
The cloud-native runtime security project is the de facto Kubernetes threat detection engine. GitLab integrates this capability into their Pipeline offering as ‘Package Hunter’.

Resources:
https://falco.org/
https://about.gitlab.com/blog/2021/07/23/announcing-package-hunter/


**Kube hunter**	

Category: 
Reliability, Security

Comments:
It hunts for security weaknesses in Kubernetes clusters	
This capability may be in the same group as the one provided by:
•	Kube bench 
•	Kube score
•	Kube hunter
Resources:
https://github.com/aquasecurity/kube-hunter


**Binary Repository Manager**	

Category: 
Business Continuity	

Comments: 
This is fundamental to reproducing an already deployed environment if it needs to be reconstructed. Keep the packages and binaries that have been deployed. 

Resources:
https://azure.microsoft.com/en-au/services/devops/artifacts/
https://www.sonatype.com/nexus-repository-sonatype
https://inedo.com/proget
Others:
https://binary-repositories-comparison.github.io/
https://xebialabs.com/the-ultimate-devops-tool-chest/repository-management/

**Pact**

Category: 
Contract tests - Integration test alternative	pact - contract testing tool (only for HTTP messages)

Comments: 
Pact is a code-first tool for testing HTTP and message integrations using contract tests. Contract tests assert that inter-application messages conform to a shared understanding documented in a contract. Without contract testing, the only way to ensure that applications will work correctly is by using expensive and brittle integration tests.	

Resources:
https://github.com/pact-foundation
https://docs.pact.io/
Kafka integration automated regression test	Regression test	Automate Integration, Unit and End to End testing programmatically. 	https://kafka.apache.org/20/documentation/streams/developer-guide/testing.html
https://dzone.com/articles/a-quick-and-practical-example-of-kafka-testing
https://dzone.com/articles/quick-overview-of-concepts-for-kafka-testing
https://platform.deloitte.com.au/articles/automate-kafka-testing


**Karate**

Category: 
Regression test

Comments: 
Kafka integration automated regression test. Regression test. Automate Integration, Unit and End to End testing programmatically. 	
This capability may be in the same group as the one provided by:
•	Kafka automates testing
•	Karate end-to-end testing tool

Resources:
https://github.com/intuit/karate/ 


**Microcks**

Category: 
Kafka integration automated regression test.

Comments:
Regression test	Automate Publisher and subscriber regression testing	

Resources:
Microcks
https://microcks.io/blog/apache-kafka-mocking-testing/
AsyncAPI integration automated regression test	
Regression test	Automate Publisher and subscriber regression testing	Microcks:
https://microcks.io/documentation/using/asyncapi/
UI Test & Regression test	Regression test	Automate UI regression test programmatically.
This type of testing is functional.
Tosca: https://documentation.tricentis.com/en/1020/content/continuous_integration/concept.htm
Microsoft: https://docs.microsoft.com/en-us/azure/devops/pipelines/languages/javascript?view=azure-devops 
Open-source options 
Selenium 
https://docs.microsoft.com/en-us/azure/devops/pipelines/test/continuous-test-selenium?view=azure-devops
https://junit.org/junit4/ 
https://site.mockito.org/


**Testcontainers**

Category 
Regression test	Testcontainers 

Comments: 
Useful for creating a reliable environment for running regression tests.
It creates containerized instances of any database (MySQL, PostgreSQL, Oracle, etc) with data. So that it is possible to run regression tests starting with a known DB state. 
This concept can also be applied to message queues, caching services, vault secret management, etc.	

Resources:
Testcontainers
https://www.testcontainers.org/ 
MS SQL
https://www.testcontainers.org/modules/databases/mssqlserver/
Kafka
https://www.testcontainers.org/modules/kafka/ 
Selenium
https://www.testcontainers.org/modules/webdriver_containers/ 


**Mobile test automation**

Category: 
Quality assurance

Comments: 
Test automation for a mobile native application, hybrid and reactive application

Resources:
http://appium.io/
https://www.seleniumhq.org/
Others: 
https://www.testingexcellence.com/open-source-mobile-test-automation-tools/


**Load Test**	

Category: 
Quality Assurance

Comments: 
Load testing an application generally means measuring performance with a specific predetermined amount of load. This is a good way to ensure you have yet to introduce a change that has impacted your overall application. For example, a 20 per cent increase in response time probably doesn’t generate a monitoring alert, but it may be killing your business.	

Resources:
https://www.microfocus.com/en-us/products/loadrunner-load-testing/overview
https://blazemeter.com/
Open Source alternatives:
http://jmeter.apache.org/
https://gatling.io/
https://locust.io/
Cloud-based:
https://flood.io/


**Smoke testing**	

Category: 
Quality Assurance

Comments: 
After the application is deployed, it’s ideal to have a series of automated sets of basic functionality tests to ensure that the system is up and functional.	Run unit tests after deployments.


**Stress testing**	

Category: 
Quality assurance

Comments: 
This test determines how much load your system can take before it fails. Same as the Load Test tools list.


**Soak testing**	

Category: 
Quality Assurance.	

Comments: 
This test ensures that your system keeps running under a sustained load. I saw a system once that seemed to perform well on a short performance test, but growing message queues added up over time, making it slower and slower. Memory leaks are also a common cause of issues on soak tests.	Same as the Load Test tools list


**Spike testing**	

Category: 
Quality Assurance	

Comments: 
This test is done by suddenly increasing the load on a system and seeing what happens. This is the type of testing that can be very important when the infrastructure is using dynamic containers. Same as the Load Test tools list


**Fuzz Testing**	

Category: 
Quality Assurance	

Comments: 
This type of testing is about using invalid and unpredictable input parameters. There are tools for APIs for code. Some of the tools also implement a scripting language that helps the tool validate the expected conditions and results. It is a must-have when developing smart contracts with solidity. This type of tool is applied to a library, and it will instrument it to know at runtime the parameters and the execution paths that can take. With this data, the tool invents its parameters and tries to execute all the possible execution paths. The tool can affect performance. Therefore should not be deployed in production permanently. 	

Resources:
OWASP – Fuzz testing
https://owasp.org/www-community/Fuzzing


**FuzzyTesting – javascript**

Category: 
Quality Assurance	

Comments:  
Fuzzy testing tool.

Resources:
https://www.npmjs.com/package/fuzzy-testing
JSFuzz – javascript: https://www.npmjs.com/package/jsfuzz
Solidity Scribble: https://docs.scribble.codes/ 


**ZAP (OWASP) Penetration test**
Category: 
Security.	

Comments: OWASP ZAP is a free penetration testing tool. Web Application Vulnerability Scanners are automated tools that scan web applications from the outside to look for security vulnerabilities such as Cross-site scripting, SQL Injection, Command Injection, Path Traversal and insecure server configuration. This tool category is frequently called Dynamic Application Security Testing (DAST) Tools.	

Resources:
OWASP Zed Attack Proxy Project - PenTest
https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project
How to add continuous security validation to your CI/CD pipeline
https://docs.microsoft.com/en-us/azure/devops/migrate/security-validation-cicd-pipeline?view=azure-devops
This is an example of how to integrate ZAP into the Jenkins pipeline
https://www.we45.com/blog/how-to-integrate-zap-into-jenkins-ci-pipeline-we45-blog
This capability may be in the same group as the one provided by:
•	ImmuniWeb
•	ZAP (OWASP)
•	Burp Suite


**Automatic API Attack Tool**	

Category: 
Security, Penetration test

Comments: 
It is a customizable API attack tool that takes an API specification as an input and generates and runs attacks based on it as an output.

Resources:
Imperva’s Automatic API Attack Tool – Github
https://github.com/imperva/automatic-api-attack-tool 


**PentestGPT**

Category: 
Penetration test. Security.	

Comments: 
PentestGPT is a penetration testing tool empowered by ChatGPT. It is designed to automate the penetration testing process. It is built on ChatGPT and operates in an interactive mode to guide penetration testers in overall progress and specific operations.	
This capability may be in the same group as the one provided by:
•	ImmuniWeb
•	ZAP (OWASP)
•	Burp Suite

Resources:
https://github.com/GreyDGL/PentestGPT


**Burp Suite**	
Category: 
Quality Assurance. Security	 

Comments: 
Burp Suite is a penetration testing tool. It is the preferred tool by Apple Store to test Applications before they are listed in the Apple Store.	
This capability may be in the same group as the one provided by:
•	ImmuniWeb
•	ZAP (OWASP)
•	Burp Suite

Resources:
Burp Suite
https://portswigger.net/


**ImmuniWeb**	

Category: 
Security. Pentest. 

Comments: 
Minimalistic and simple web server validation for security-related configuration. ImmuniWeb provides a free API to test your web server for security-related configuration.
ImmuniWeb
•	ZAP (OWASP)
•	Burp Suite

Resources:
Free and paid API versions are available.	 
https://www.immuniweb.com/websec/#api
This capability may be in the same group as the one provided by:


**growthbook**	

Category: 
Feature Flagging. A/B Testing Platform	Open Sourced

Comments:
It is a Feature Flagging tool similar to LaunchDarkly.

Resources:
A/B Testing Platform	
https://github.com/growthbook/growthbook


**Checkov**

Category: 
Security. CSPM.	

Comments: 
It scans cloud infrastructure configurations. IaaC security validation. Static configuration scanning. It finds misconfigurations before they are deployed.	Platform and cloud-independent tool. It can scan cloud infrastructure configurations to find misconfigurations before they're deployed. Checkov uses a command-line interface to manage and analyze infrastructure as code (IaC) scans results across platforms such as Terraform, CloudFormation, Kubernetes, Helm, ARM Templates and Serverless framework.

Resources:
https://www.checkov.io/ 


**Cloud Custodian**	

Category: 
Security. CSPM. 

Comments: 
It scans cloud infrastructure configurations. IaaC security validation. Static configuration scanning. It finds misconfigurations before they are deployed. Platform and cloud-independent tool.

Resources:
https://cloudcustodian.io/
https://cloudcustodian.io/docs/azure/resources/index.html


**Secure DevOps Kit for Azure**

Category: 
Security, Scan cloud infrastructure configurations.

Comments:
The "Secure DevOps Kit for Azure" (will be referred to as 'AzSK') is a collection of scripts, tools, extensions, automation, etc. that caters to the end-to-end Azure subscription and resource security needs for dev ops teams using extensive automation and smoothly integrating security into native dev-ops workflows helping accomplish secure dev-ops.
This capability may be in the same group as the one provided by:
•	Secure DevOps Kit for Azure
•	Microsoft Security Analysis

Resources:
Secure DevOps Kit for Azure
https://azsk.azurewebsites.net/
Getting started with the Secure DevOps Kit for Azure (AzSK)
https://azure.microsoft.com/en-au/resources/videos/azure-friday-getting-started-with-the-secure-devops-kit-for-azure-azsk/
azsdk/azsdk-docs
https://github.com/azsdk/azsdk-docs


**Microsoft Security Code Analysis**

Category:	
Security.  It scans cloud infrastructure configurations.

Comments: The Microsoft Security Code Analysis Extension is an Azure DevOps Services platform task collection. These tasks automatically download and run secure development tools in the build pipeline. The extension is now in a Private Preview (by invitation).	
This capability may be in the same group as the one provided by:
•	Secure DevOps Kit for Azure
•	Microsoft Security Analysis

Resources:
https://secdevtools.azurewebsites.net/


**Slack - Integration** 

Category: 
Productivity, Governance, Integration with workplace collaboration tools

Comments: 
Build-pipelines' output can be associated with Slack channels to inform about fails and pass runs. 
It can also provide visibility to architects and managers about the build process to exercise governance. 	

Resources:
https://api.slack.com/
https://docs.microsoft.com/en-us/azure/devops/service-hooks/services/slack?view=azure-devops
https://docs.microsoft.com/en-us/azure/devops/pipelines/integrations/slack?view=azure-devops

**ServiceNow - Integration**	
Category: 
Incident management. Governance	Integration with Incident Management
Comments: 
Set up and manage subscriptions for completed builds, releases, pending approvals and more from the app and get notifications for these events in your Slack channels.	
Resources:
https://docs.microsoft.com/en-us/azure/devops/pipelines/release/approvals/servicenow?view=azure-devops


**Kube Hunter**	
Category: 
Security, Penetration testing. 

Comments: 
This tool is specific for containers running in Kubernetes 	Kubernetes specific Penetration Test – PenTest

Resources:
http://techgenix.com/kubernetes-security-tools/ 
https://blog.aquasec.com/kube-hunter-kubernetes-penetration-testing
https://github.com/aquasecurity/kube-hunter 

**Kube bench**

Category: 
Security	

Comments:
Kube-bench is a Go application that checks whether Kubernetes is deployed securely by running the checks documented in the CIS Kubernetes Benchmark.

Resources:
Kubernetes-specific vulnerability tool – Vulnerability tool
http://techgenix.com/kubernetes-security-tools/
https://github.com/aquasecurity/kube-bench
https://www.cisecurity.org/benchmark/kubernetes/ 


**LiquidBase**

Category: 
DataOps, Source code quality. CI-CD for Database Changes 

Comments: 
Liquid base is a database-independent library for tracking, managing and applying database schema changes.	

Resources:
https://github.com/liquibase/liquibase/ 


**Renovate**

Category: Source code quality

Comments: It is an enhanced version of what dependabot does. It is an open-source tool that automatically creates pull requests for all dependency updates. Includes crowdsourced test and package adoption data used to flag potentially risky updates and enable auto-merging for those that meet user-defined conditions.
It Scans your repos to detect dependencies (wide package manager support). It Checks if any newer versions exist. And then Raises PRs for available updates.
Save time and reduce risk by automating dependency updates in software projects. Fully customizable with a setting to suit every workflow.	

Resources:
https://www.npmjs.com/package/renovate 
https://renovatebot.com/
https://github.com/renovatebot/renovate


**Dependabot**

Category: 
Security. Source code quality

Comments: 
Dependabot is a GitHub app that automates dependency updates. Every day, Dependabot pulls down your dependency files and looks for outdated requirements. If any dependencies are out-of-date, Dependabot opens individual pull requests to bump each one.	

Resources:
https://dependabot.com/
https://dependabot.com/blog/introducing-dependabot/


**Sentry**

Category: 
Source code quality. Quality assurance

Comments: 
It is an Open-source error tracking that helps developers monitor and fix crashes in real-time. Iterate continuously. Boost efficiency. Improve user experience.	

Resources:
https://docs.sentry.io/
Sentry + Microsoft Azure DevOps: Error-Tracking, Crash-Reporting, & More
https://blog.sentry.io/2018/09/18/sentry-azure-devops-integration-update


**Code forensics**

Category: 
Security, Governance

Comments: 
Source code quality	Toolset for analysing codebases stored in a version control system. It leverages the repository logs, or version history data, to perform deep analyses regarding complexity, logical coupling, and authors coupling and to inspect the evolution in time of different parts of a software system concerning metrics like code churn and the number of revisions.	

Resources:
https://www.npmjs.com/package/code-forensics
https://github.com/smontanari/code-forensics


**Architecture Unit**	

Category: 
Governance. Source code quality.

Comments:
It implements compilation assertion rules to static code packages.
Application architecture and Project structure code analyser based on flexible architecture principle rules. It can check that packages do not include or have static dependencies with libraries from other packages. Each of the packages is meant to be deployable code based for different modules of the architecture.	

Resources:
Java Library (Original Project)
https://www.archunit.org/  
.Net Library 
https://github.com/BenMorris/NetArchTest/tree/master  
NodeJS Library
https://github.com/manjericao/ArchUnitNode 


**Binskim**

Category: 
Security, Package analyser for NuGet packages.

Comments:
A binary static analysis tool that provides security and correctness results for Windows Portable Executable and *nix ELF binary formats (.Net framework NuGet packages)	

Resources:
https://github.com/Microsoft/binskim


**Powerfulseal**

Category: 
Reliability	

Comments:
These tools inject failure into your Kubernetes clusters so that you can detect problems as early as possible. It allows for writing scenarios describing complete chaos experiments.

Resources:
https://dzone.com/articles/chaos-mesh-a-chaos-engineering-solution-for-system
https://medium.com/faun/failures-are-inevitable-even-a-strongest-platform-with-concrete-operations-infrastructure-can-7d0c016430c6 
https://github.com/powerfulseal/powerfulseal
https://github.com/bloomberg/goldpinger
https://docs.locust.io/en/latest/running-locust-distributed.html 
https://github.com/asobti/kube-monkey
https://github.com/target/pod-reaper 


**Chaos Toolkit**	

Category: 
Reliability, Infrastructure resiliency.

Comments:
The Chaos Toolkit is a toolkit to describe and then run repeatable experiments on your infrastructure to understand its resilience in the event of failure. It is an open-source project dedicated to the practice. The toolkit already has drivers for AWS, Azure Service Fabric and GCE (among others) and plays nicely with build tools that let you experiment with automation. The usual caveats apply; Chaos Engineering is a powerful technique best used on resilience-aware systems, systems built to cope with failure. Therefore, we recommend using Chaos Toolkit in your nonproduction environments first.	Based on the recommendations for chaos engineering for Kubernetes book: “The DevOps Toolkit Kubernetes Chaos Engineering (2020)” by Viktor Farcic and Darin Pope. Gremlin Reliability. Gremlin provides a unique tool that allows infiltrating the Kafka brokers to produce artificial instability that allows an understanding of how the system recovers.	

Resources:
https://chaostoolkit.org/
Chaos experiments to run on Apache Kafka
https://www.gremlin.com/community/tutorials/the-first-4-chaos-experiments-to-run-on-apache-kafka/
For example:
Experiment 1: Impact of broker load on processing latency
https://www.gremlin.com/community/tutorials/the-first-4-chaos-experiments-to-run-on-apache-kafka/#experiment-1-impact-of-broker-load-on-processing-latency 
Experiment 2: Risk of data loss due to dropped messages
https://www.gremlin.com/community/tutorials/the-first-4-chaos-experiments-to-run-on-apache-kafka/#experiment-2-risk-of-data-loss-due-to-dropped-messages 
Experiment 3: Avoiding a split-brain cluster
https://www.gremlin.com/community/tutorials/the-first-4-chaos-experiments-to-run-on-apache-kafka/#experiment-3-avoiding-a-split-brain-cluster 
Experiment 4: ZooKeeper outage
https://www.gremlin.com/community/tutorials/the-first-4-chaos-experiments-to-run-on-apache-kafka/#experiment-4-zookeeper-outage


**CodeScene**

Category: 
Source code quality	

Comments: 
CodeScene is a behavioural code analysis tool. It provides code visualizations based on version-control data and machine-learning algorithms that identify social patterns and hidden risks in code. It detects hotspots—complex code that an organization has to work with frequently—and prioritizes technical debt based on how the developers work with the code.	

Resources:
https://codescene.io/


**Letsencrypt**

Category: 
Cost Management, Security. 

Comments: Integrate letsencrypt certificates to the CI-CD. Fastrack the creation and the management of certificates for new environments by having a secure, cheaper and faster process to request, deploy and operate lifecycle management of digital certificates using letsencrypt certificates lifecycle management APIs.	

Resources:
https://letsencrypt.org/
https://letsencrypt.org/docs/client-options/
https://certbot.eff.org/
https://marketplace.visualstudio.com/items?itemName=cboroson.cboroson-VSTS-LetsEncrypt
https://medium.com/@brentrobinson5/automating-certificate-management-with-azure-and-lets-encrypt-fee6729e2b78
https://blogs.msdn.microsoft.com/mihansen/2018/01/25/azure-web-app-with-lets-encrypt-certificate-powershell-automation/
https://dev.to/ianknighton/deploying-a-microservice-on-azure-kubernetes-with-lets-encrypt-4eon
https://docs.microsoft.com/en-us/azure/aks/ingress-tls
https://github.com/jetstack/cert-manager


**Fossology**

Category: 
Compliance	

Comments:
Open Source License compliance checker. The FOSSology Project is a Free Open Source Software (FOSS) project built around an open and modular architecture for analyzing software for open-source software governance. Existing modules include license scanning, copyright and user identification, license classification and metadata extraction.
This capability may be in the same group as the one provided by:
•	Fossology
•	WhiteSource

Resources:
Read more about open-source license concerns:
https://softwareengineering.stackexchange.com/questions/47032/can-i-use-gpl-software-in-a-commercial-application 
https://fossa.com/
https://www.fossology.org/
https://sourceforge.net/projects/fossology/


**WhiteSource**

Category: 
Compliance	

Comments:
Open Source License compliance checker.. WhiteSource automates the entire open source component selection process, approval and management, including detection and remediation of security and compliance issues. It integrates with all stages of your software development lifecycle (SDLC) to alert you in real time and help you fix issues faster and easier.
This capability may be in the same group as the one provided by:
•	Fossology
•	WhiteSource

Resources:
Read more about open-source license concerns:
https://softwareengineering.stackexchange.com/questions/47032/can-i-use-gpl-software-in-a-commercial-application
https://www.whitesourcesoftware.com/


**Operation automation**

Category: 
Operation automation 	Operation events automation

Comments:
This is an IFTTT specialised tool for CI/CD automation. Capture incidents and events from environments and automate actions.	

Resources:
https://stackstorm.com/
https://www.rundeck.com/


**CI/CD Standards**

Category: 
Tools interoperability 	CI/CD standards.  Standardisation

Comments:
Adopt CI/CD emerging standards to avoid vendor locking, portability and interoperability. Linux Foundation has recently created a project called “CD Foundation”, which industry leaders have backed up. This is recent news, and nothing has come up yet from this forum. Vendors also are coming with open technologies to allow CD components interoperability. CDEvents is a common specification for Continuous Delivery events, enabling interoperability in the complete software production ecosystem. It's an incubated project at the Continuous Delivery Foundation (CDF). 	

Resources:
https://www.linuxfoundation.org/Projects/cd-foundation/
Others:
https://cloud.google.com/tekton/
https://jenkins-x.io/
https://www.spinnaker.io/


**PlantUML**

Category: 
Diagrams as code. Productivity. Governance.

Comments:
It is a library that allows the creation of UML diagrams using a scripted language. PlantUML uses a graphic rendering engine Graphviz. There has to be implemented a bridge program that interprets the source an translate it to the graphical scripting language. The idea is to hook this tool into the CI-CD pipeline so that each deployment's basic diagrams and documentation are self-generated.

Resources:
PlantUML 
https://plantuml.com/ 
Graphviz
http://www.graphviz.org/
Node-plantuml
https://www.npmjs.com/package/node-plantuml 


**K8s-diagrams**
Category: 
Diagrams as code, Productivity, Governance

Comments:
Documentation	K8s-diagrams. A tool that allows creating diagrams by pointing them to a Kubernetes cluster or Kubernetes namespace. 
It uses the PlantUML engine, although it does not conform to UML but its standards. It uses the official Kubernetes master icon set.
The idea is to hook this tool into the CI-CD pipeline so that each deployment's basic diagrams and documentation are self-generated.	

Resources:
K8s-diagrams
https://github.com/cloudogu/k8s-diagrams
Kubernetes icons
https://github.com/kubernetes/community/tree/master/icons 


**mingrammer**	

Category: 
Diagrams as code, Productivity, Governance

Comments:
It is a tool to automatically create diagrams from cloud infrastructure, including Azure and Kubernetes. 
It recommends extracting the data from the infrastructure using cloudiscovery tool. There has been implemented bridge program that interprets the source and translates it to the graphical scripting language. The idea is to hook this tool into the CI-CD pipeline so that each deployment's basic diagrams and documentation are self-generated.	

Resources:
Diagrams mingrammer
https://diagrams.mingrammer.com/ 
Kubernetes example
https://diagrams.mingrammer.com/docs/getting-started/examples#stateful-architecture-on-kubernetes 
Cloudiscovery
https://github.com/Cloud-Architects/cloudiscovery 


**Mermaid-js**

Category: 
Diagrams as code, Productivity, Governance.

Comments:
The tool generates UML diagrams, and other project management diagrams (Gantt) from a scripting language. There has been implemented bridge program that interprets the source and translates it to the graphical scripting language. The idea is to hook this tool into the CI-CD pipeline so that each deployment's basic diagrams and documentation are self-generated.	

Resources:
Mermaid-js
https://mermaid-js.github.io/ 
Mermaid-js editor live
https://mermaid.live/ 
Mermaid-js npm package
https://www.npmjs.com/package/mermaid 


**Enterprise asset management (EAM) - Diagrams as code - iServer**

Category: 
Productivity, Governance. Documentation	

Comments: Integrate CI/CD and build the pipeline to the iServer metadata repository. 
All these can be captured and fed to the iServer repository while processing in CI-CD. This information can be translated to enterprise model standards (TOGAF, ArchiMate, UML).
You may need to do a POC for this. Achieve having updated data in the EAM to have “living documents”
At the time of building application components and systems, it is possible to capture valuable information about:
-	 Infrastructure configuration
-	Applications components
-	Application deployment
-	Application composition 
-	Application dependencies 
All languages have manifest files that this information can be obtained.

Resources:
Node.js application composition descriptor
https://docs.npmjs.com/files/package.json
https://www.orbussoftware.com/us/iserver/communicate/live-documents/
Being able to streamline impact analysis and use iServer
https://www.orbussoftware.com/us/iserver/analysis-decision-making/ 
https://www.orbussoftware.com/us/business-process-analysis/capabilities/
User Orbus iServer Data Exchange API
https://www.orbussoftware.com/us/iserver/integrate/data-exchange/
IServer supports these three models:
These target models that we are expecting to use in iServer:
ArchiMate (Open Group)
https://pubs.opengroup.org/architecture/archimate3-doc/
Application Layer Metamodel
https://pubs.opengroup.org/architecture/archimate3-doc/chap09.html#_Toc489946063
Technology Layer Metamodel
https://pubs.opengroup.org/architecture/archimate3-doc/chap10.html#_Toc489946081
Physical Elements Metamodel
https://pubs.opengroup.org/architecture/archimate3-doc/chap11.html#_Toc489946104
UML Deployment Model
https://www.tutorialspoint.com/uml/uml_deployment_diagram.htm
Terraform Azure provider examples
https://github.com/terraform-providers/terraform-provider-azurerm/tree/master/examples
      

**DoBetterAsCode**

Category: 
Source code quality

Comments:
This capability aligns with the one presented in the “Infrastructure as a Code” book by Kief Morris. They propose incorporating coding excellency into the code that creates infrastructure in the cloud due to running. They use the standards of the “Clean Code” book from 2008 as the guiding principle for these coding standards. All this initiative tries to follow the master idea of Continuous Delivery which is described in the book “Continuous Delivery (2011)”
-	Clean Code (2008)
-	Infrastructure as Code Managing Servers in the Cloud (2016)
-	Continuous Delivery - Reliable Software Releases Through Build, Test And Deployment Automation (2011)
	Some additional notes:
-	They use Terraform mostly as the standard for this 
-	Apply good coding standards
  Modularity
  Source version control
  Etc…, any other standards from the book's “Clean code” that apply.
-	Check the syntax of the scripts
-	Validate pipeline
-	Run and debug the pipeline
-	Be able to emulate results locally before running for real. Mock the cloud provider in a local machine or contained environment
-	Have a convention to validate the IaC scripts
-	Create docker images as a result
-	Be able to create a unit test for the infrastructure
-	Be able to run integration tests for the infrastructure
-	etc
Some of the challenges and tips they described:
-	Use pre-commit hooks to validate the commit. Select what hooks you want to run for the change being committed 

Resources:
DoBetterAsCode: https://dobetterascode.com/
DoBetterAsCode  Github: https://github.com/DoBetterAsCode/DoBetterAsCode
DoBetterAsCode  Tools and resources:  https://dobetterascode.com/resources/ 


**Sigstore**

Category: 
Security, Supply chain security	Sigstore

Comments:
It is a set of free-to-use and open-source tools, including fulcio, cosign and rekor, handling digital signing, verification and checks for provenance needed to make it safer to distribute and use open-source software	

Resources:
Sigstore
https://www.sigstore.dev/ 


**Preflight**

Category: 
Security. Supply chain security	Preflight

Comments:
It helps you verify scripts and executables to mitigate chain of supply attacks such as the recent Codecov hack	

Resources:
Preflight
https://github.com/spectralops/preflight 


**Open Raven**

Category: 
Magpie	Security. CSPM	Cloud Security Posture Management (CSPM)	

Comments: 
CSPM	Cloud Security Posture Management (CSPM) Open source

Resources:
Open Raven Magpie
https://github.com/openraven/magpie 


**Cloud Query**

Category: 
CSPM	Cloud Security Posture Management (CSPM)	

Comments: 
CSPM	Cloud Security Posture Management (CSPM) Open source

Resources:
Cloud Query
https://www.cloudquery.io/ 


**Cloudsploit**

Category: 
CSPM	Cloud Security Posture Management (CSPM)	

Comments: 
Detection of security risks in cloud infrastructure

Resources:
https://github.com/aquasecurity/cloudsploit


**ScoutSuite**
Category: Security, CSPM Cloud Security Posture Management (CSPM)	

Comments: NCCgroup is a multi-cloud scanning tool. 

Resources:
https://github.com/nccgroup/ScoutSuite 


**CloudCustodian**
Category: 
Security, CSPM	Cloud Security Posture Management (CSPM)		

Comments:
Multicloud security analysis framework

Resources:
CloudCustodian
https://github.com/cloud-custodian/cloud-custodian/	


**CloudGraph**

Category: 
Security, CSPM	Cloud Security Posture Management (CSPM)	

Comments: 
GraphQL API + Security for AWS, Azure, GCP, and K8s

Resources:
https://github.com/cloudgraphdev/cli 


**Cosign**

Category: 
Deployment Digital Signature Digest. 	

Comments:
Container image signing	Deployment Object Digital Signature Digest

Resources:
https://github.com/sigstore/cosign


**Notary**

Category: 
Deployment Digital Signature Digest	

Comments: 
Docker image signing	Deployment Object Digital Signature Digest

Resources:
https://github.com/notaryproject/notary


**terracognita**

Category: 
Documentation. Reverse engineer Terraform templates.

Comments:
Reads from existing public and private cloud providers (reverse Terraform) and generates your infrastructure as code on Terraform configuration	

Resources:
terracognita.
https://github.com/cycloidio


**inframap**

Category: 
Documentation, Governance

Comments:
It generates a graph with the most important resources of your infrastructure. Reads from a “.tfstate” file (created when you do a `terraform import`) or HCL (HashiCorp Configuration Language). It generates a DOT format.	

Resources:
inframap
https://github.com/cycloidio
DOT Format
https://graphviz.org/doc/info/lang.html


**Data Linter**

Category: 
Data quality control.	Data quality Linter.

Comments:
A tool that could be more suitable for data pipelines. However, it can be used as a quality assurance tool in the DevSecOps pipeline to ensure the integrity of an environment and to test and ensure that previous data inconsistencies are not affecting the system before deploying a new package. It is designed to read in and validate tabular data against a given schema for the data. The schemas provided adhere to our metadata schemas standards for data. Based on the validation result, this package can also manage data movement from a landing area (s3 or locally) to a new location.	

Resources:
Data quality control linter
https://pypi.org/project/data-linter/


**Great Expectations**

Category: 
Data quality control. Data quality Linter.

Comments:
A tool that could be more suitable for data pipelines. However, it can be used as a quality assurance tool in the DevSecOps pipeline to ensure the integrity of an environment and to test and ensure that previous data inconsistencies are not affecting the system before deploying a new package. 	

Resources:
Great Expectations 
https://github.com/great-expectations/great_expectations


**DbUnit**

Category: 
Data quality control

Comments:
DbUnit is a JUnit extension (also usable with Ant) targeted at database-driven projects that, among other things, puts your database into a known state between test runs. This is an excellent way to avoid the myriad of problems when one test case corrupts the database and causes subsequent tests to fail or exacerbate the damage.
DbUnit can export and import your database data to and from XML datasets. Since version 2.0, DbUnit can also work with large datasets in streaming mode. DbUnit can also help you to verify that your database data match an expected set of values.	

Resources:
DBUni
https://www.dbunit.org/intro.html


--End of the file--
