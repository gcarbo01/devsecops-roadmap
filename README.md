# devsecops-roadmap

Intro:<br>
Listed in no particular order. Do your research. Most of these tools are open-sourced and may flourish or die without notice.
Each tool may be applicable for one or more capabilities. So they are tagged by "Category".
<br>
<br>
<br>
**Sonarqube (JavaScript and many languages)**	
<br><br>
Category:<br> 
Static Code Analyzer
<br><br>
Comments:<br>
Source code quality	Open source static code analyser	
<br><br>
Resources:<br>
Sonarqube JavaScript
https://docs.sonarqube.org/display/PLUG/SonarJS
<br>
<br>
<br>
**Sonarqube (.net framework)**	
<br><br>
Category:<br> 
Static Code Analyzer
<br><br>
Comments:<br> 
Source code quality	Open source static code analyser	
<br><br>
Resources:<br>
Sonarqube .net framework
https://docs.sonarqube.org/display/SCAN/Analyzing+with+SonarQube+Scanner+for+MSBuild
<be>
<br>
<br>
**Sonarqube (Java)**
<br><br>
Category:<br> 
Static Code Analyzer
<br><br>
Comments:<br> 
Source code quality. Open source static code analyser.
<br><br>
Resources:<br>
Sonarqube Java
https://docs.sonarqube.org/display/PLUG/SonarJava
<br>
<br>
<br>
**HTMLhint**
<br><br>
Category:<br> 
Static Code Analyzer
<br><br>
Comments:<br> 
Source code quality. Static Code analyser for Web applications and Single Page Applications	
<br><br>
Resources:<br>
https://htmlhint.io/
https://github.com/htmlhint/HTMLHint
<br>
<br>
<br>
**Flow**	
<br><br>
Category:<br> 
Static Code Analyzer
<br><br>
Comments:<br> 
Source code quality. Flow is a static type checker for JavaScript. The overall mission of Flow is to deliver an immersive coding experience for JavaScript developers—a fast edit-refresh cycle—even as the codebase evolves and grows.	
<br><br>
Resources:<br>
https://flow.org/
https://github.com/facebook/flow
<be>
<be>
<br>
**SQL Fluff**
<br><br>
Category:<br> 
Source code quality. SQL Lint
<br><br>
Comments:<br> 
Source code linter specialising in SQL statements. It helps you write good SQL and catch errors and bad SQL before it hits your database.
<br><br>
Resources:<br>
https://docs.sqlfluff.com/en/stable/  
<br>
<br>
<br>
**SQL Lint**
<br><br>
Category:<br> 
Source code quality
<br><br>
Comments:<br> 
Source code linter specialising in SQL statements. It helps you write good SQL and catch errors and bad SQL before it hits your database.	
<br><br>
Resources:<br>
SQL Linter
https://github.com/joereynolds/sql-lint
<br>
<br>
<br>
**SQL TSQLLint**	
<br><br>
Category:<br> 
Source code quality
<br><br>
Comments:<br>
Source code linter specialising in SQL statements. It helps you write good SQL and catch errors and bad SQL before it hits your database.
<br><br>
Resources:<br>
SQL Linter
https://github.com/tsqllint/tsqllint 
<br>
<br>
<br>
**CSV Lint**
<br><br>
Category:<br> 
Source code quality
<br><br>
Comments:<br> 
Source code quality, Automated Testing	Check CSV files to see whether they contain the columns and types of values they should. It helps you write good SQL and catch errors and bad SQL before it hits your database.	
<br><br>
Resources:<br>
CSV Lint
https://csvlint.io/
<br>
<br>
<br>
**Conftest**
<br><br>
Category:<br>	
Source code quality. Conftest tests and verifies configuration files.
<br><br>
Comments:<br> 
It is a tool for writing tests against structured configuration data. It relies on Open Policy Agent's Rego language to write configuration tests. For example, Kubernetes configurations, Tekton pipeline definitions or even Terraform plans. Or any other JSON file.	
<br><br>
Resources:<br>
https://www.conftest.dev/
<br>
<br>
<br>
**Accessibility Design linter practice**
<br><br>
Category:<br>	
Source code quality		
<br><br>
Comments:<br> 
Automate accessibility design verification
<br><br>
Resources:<br>
https://www.microsoft.com/design/inclusive/
https://www.digitala11y.com/free-accessibility-linters-to-automate-accessibility-workflow/
<br>
<br>
<br>
**Google Lighthouse**
<br><br>
Category:<br> 
Source code quality
<br><br>
Comments:<br> 
It is a tool written by Google to assess web applications and web pages, collecting performance metrics and insights on good development practices.
<br><br>
Resources:<br>
https://developer.chrome.com/docs/lighthouse/overview/
https://github.com/GoogleChrome/lighthouse
<br>
<br>
<br>
**Bazel**	
<br><br>
Category:<br> 
Interoperability
<br><br>
Comments:<br> 
CI-CD scripting pipeline language. Build portable pipelines and configurations using a scripting language that allows changing the underlying CI-CD technology.	
<br><br>
Resources:<br>
CI-CD tool and platform-independent scripting language.
https://bazel.build/
<br>
<br>
<br>
**Elastic APM	Open Telemetry**
<br><br>
Category:<br> 
Dashboard.
<br><br>
Comments:<br> 
Elastic Search provides a protocol to inject and display open telemetry to a dashboard. 
This is useful for the case it is required to create a custom dashboard from the CI-CD pipeline execution itself. 
<br><br>
Resources:<br>
For example, when the pipeline is implemented in Jenkins 
https://plugins.jenkins.io/opentelemetry/	
https://www.elastic.co/apm 
<br>
<br>
<br>
**Cloud Cost** 
<br><br>
Category:<br> 
Optimisation Cost, Infrastructure Architecture Cost Calculation Simulation, Infrastructure Architecture Cost Optimisation 
Infrastructure Architecture Budget control 
<br><br>
Comments:<br> 
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
<br><br>
Resources:<br>
Microsoft has recently implemented cost and budget APIs and built-in functions in Azure Portal that could help to develop this capability.	https://www.thoughtworks.com/radar/techniques/run-cost-as-architecture-fitness-function
https://docs.microsoft.com/en-us/azure/cost-management/tutorial-forecast-spending
https://docs.microsoft.com/en-us/rest/api/consumption/forecasts/list
https://docs.microsoft.com/en-us/rest/api/consumption/budgets
<br>
<br>
<br>
**harness**
<br><br>
Category:<br> 
Cloud Cost Optimisation	Cost	Infrastructure Architecture Cost Calculation Simulation,  Infrastructure Architecture Cost Optimisation 
<br><br>
Comments:<br> 
Infrastructure Architecture Budget control 
<br><br>
Resources:<br>
https://harness.io/ 
<br>
<br>
<br>
**Infracost**
<br><br>
Category:<br> 
Cost management	
<br><br>
Comments:<br>
It makes cost trade-offs visible in Terraform pull requests. It's open-source software and supports pricing for AWS, GCP and Microsoft Azure out of the box. It also provides a public API that can be queried for current cost data. Note: There has to be a bridge integration program to get the cost and publish it in MS Teams or Slack for approval.
<br><br>
Resources:<br>
https://www.infracost.io/
https://github.com/infracost/infracost 
<br><br>
**Terracost**
<br><br>
Category:<br>	
Cost management.
<br><br>
Comments:<br> 
Cloud cost estimation for Terraform as cli tool.
<br><br>
Resources:<br>
https://github.com/cycloidio
<br>
<br>
<br>
**Kanban wall issues integration**	
<br><br>
Category:<br> 
Continue Delivery, Integration of the CI pipeline with Kanban wall issues.
<br><br>
Comments:<br>
Enable a full Continuous Delivery lifecycle to open/update issues automatically from the Continue Integration pipeline. These are provided as an example:
<br><br>
Resources:<br>
Jenkins:
https://wiki.jenkins.io/display/JENKINS/Jira+Issue+Updater+Plugin
Atlassian Jira:
https://developer.atlassian.com/server/jira/platform/jira-rest-api-examples/
https://developer.atlassian.com/server/jira/platform/jira-rest-api-example-create-issue-7897248/
Azure DevOps:
It is understood that in the case of Azure DevOps, the build pipeline failure can be configured to create issues automatically in the Azure DevOps Kanban wall.
https://docs.microsoft.com/en-us/rest/api/azure/devops/?view=azure-devops-rest-5.0
See the “Work Item Tracking” section.
<br>
<br>
<br>
**OpenSCAP**	
<br><br>
Category:<br> 
Container scanning
<br><br>
Comments:<br>
SCAP stand for Security Content Automation Protocol (from the National Institute of Standards and Technology – NIST –)
It is a tool that provides built-in support for this industry-standard, open-source compliance assessment tool that enables users to quickly add compliance scanning and automated report generation to their pipelines. OpenSCAP executes CIS Benchmarks against hardened images. The benchmarks request different levels of hardening for different types of industries. The benchmark applies to open-sourced software and commercial software images also. They extend to Operating Systems, Server Software, Cloud Providers, Mobile Devices, Network Devices, Desktop Software Multi-Function Print Devices.	
<br><br>
Resources:<br>
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
<br>
<br>
<br>
**ServerSpec** 
<br><br>
Category:<br> 
Test Driven Design. ServerSpec - Test Driven Design for containers
<br><br>
Comments:<br>
Test the configurations of containers. Allow fast refactoring of infrastructure. It tests your servers’ actual state by executing commands locally via SSH, WinRM, Docker API, etc. So you don’t need to install any agent software on your servers and can use any configuration management tools, Puppet, Ansible, CFEngine, Itamae, etc.
For example:
- Verify that the container is rootless
- Verify the correct configuration of AppArmor
(AppArmor is a Mandatory Access Control (MAC) system which is a kernel (LSM) enhancement to confine programs to a limited set of resources. AppArmor's security model is to bind access control attributes to programs rather than to users)	
<br><br>
Resources:<br>
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
<br>
<br>
<br>
**Anchore**
<br><br>
Category:<br> 
Security, Reliability, Docker container vulnerability scanning, 
<br><br>
Comments:<br>
This capability may be in the same group as the one provided by:
•	Anchore
•	Clair
<br><br>
Resources:<br>
https://anchore.com/opensource/
<br>
<br>
<br>
**Clair**
<br><br>
Category:<br> Security, Reliability, Docker containers vulnerability scanning.
<br><br>
Comments:<br>
This capability may be in the same group as the one provided by:
•	Anchore
•	Clair
<br><br>
Resources:<br>
https://github.com/coreos/clair
<br>
<br>
<br>
**kubectl-kubesec**
<br><br>
Category:<br> 
Security, Reliability
<br><br>
Comments:<br>
It is a security risk analysis for Kubernetes resources	kubectl-kubesec
<br><br>
Resources:<br>
https://github.com/controlplaneio/kubectl-kubesec
<br>
<br>
<br>
**Kube bench**	
<br><br>
Category:<br> 
Security, Reliability
<br><br>
Comments:<br>
It is a tool for Running Kubernetes Center for Internet Security (CIS) 
This capability may be in the same group as the one provided by:
•	Kube bench 
•	Kube score
•	Kube hunter
<br><br>
Resources:<br>
Benchmark Tests	
https://github.com/aquasecurity/kube-bench
https://www.cisecurity.org/cis-benchmarks/
<br>
<br>
<br>
**Kube score**	
<br><br>
Category:<br> 
Reliability, Security
<br><br>
Comments:<br>
Kubernetes object analysis with recommendations for improved reliability and security.	
This capability may be in the same group as the one provided by:
•	Kube bench 
•	Kube score
•	Kube hunter
<br><br>
Resources:<br>
https://kube-score.com/
https://github.com/zegl/kube-score
<br>
<br>
<br>
**Falco**	
<br><br>
Category:<br> 
Threat detection, Runtime detection engine.	
<br><br>
Comments:<br>
Package Hunter is a tool to analyze a program's dependencies for malicious code and other unexpected behaviour by installing the dependencies in a sandbox environment and monitoring system calls executed during the installation. Package Hunter, you could find out that a package attempted to open a network connection on installing a package.	
The cloud-native runtime security project is the de facto Kubernetes threat detection engine. GitLab integrates this capability into their Pipeline offering as ‘Package Hunter’.
<br><br>
Resources:<br>
https://falco.org/
https://about.gitlab.com/blog/2021/07/23/announcing-package-hunter/
<br>
<br>
<br>
**Kube hunter**	
<br><br>
Category:<br> 
Reliability, Security
<br><br>
Comments:<br>
It hunts for security weaknesses in Kubernetes clusters	
This capability may be in the same group as the one provided by:
•	Kube bench 
•	Kube score
•	Kube hunter
<br><br>
Resources:<br>
https://github.com/aquasecurity/kube-hunter
<br>
<br>
<br>
**Binary Repository Manager**	
<br><br>
Category:<br> 
Business Continuity	
<br><br>
Comments:<br> 
This is fundamental to reproducing an already deployed environment if it needs to be reconstructed. Keep the packages and binaries that have been deployed. 
<br><br>
Resources:<br>
https://azure.microsoft.com/en-au/services/devops/artifacts/
https://www.sonatype.com/nexus-repository-sonatype
https://inedo.com/proget
Others:
https://binary-repositories-comparison.github.io/
https://xebialabs.com/the-ultimate-devops-tool-chest/repository-management/
<br>
<br>
<br>
**Pact**
<br><br>
Category:<br> 
Contract tests - Integration test alternative	pact - contract testing tool (only for HTTP messages)
<br><br>
Comments:<br> 
Pact is a code-first tool for testing HTTP and message integrations using contract tests. Contract tests assert that inter-application messages conform to a shared understanding documented in a contract. Without contract testing, the only way to ensure that applications will work correctly is by using expensive and brittle integration tests.	
<br><br>
Resources:<br>
https://github.com/pact-foundation
https://docs.pact.io/
Kafka integration automated regression test	Regression test	Automate Integration, Unit and End to End testing programmatically. 	https://kafka.apache.org/20/documentation/streams/developer-guide/testing.html
https://dzone.com/articles/a-quick-and-practical-example-of-kafka-testing
https://dzone.com/articles/quick-overview-of-concepts-for-kafka-testing
https://platform.deloitte.com.au/articles/automate-kafka-testing
<br>
<br>
<br>
**Karate**
<br><br>
Category:<br> 
Regression test
<br><br>
Comments:<br> 
Kafka integration automated regression test. Regression test. Automate Integration, Unit and End to End testing programmatically. 	
This capability may be in the same group as the one provided by:
•	Kafka automates testing
•	Karate end-to-end testing tool
<br><br>
Resources:<br>
https://github.com/intuit/karate/ 
<br>
<br>
<br>
**Microcks**
<br><br>
Category:<br> 
Kafka integration automated regression test.
<br><br>
Comments:<br>
Regression test	Automate Publisher and subscriber regression testing	
<br><br>
Resources:<br>
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
<br>
<br>
<br>
**Testcontainers**
<br><br>
Category 
Regression test	Testcontainers 
<br><br>
Comments:<br> 
Useful for creating a reliable environment for running regression tests.
It creates containerized instances of any database (MySQL, PostgreSQL, Oracle, etc) with data. So that it is possible to run regression tests starting with a known DB state. 
This concept can also be applied to message queues, caching services, vault secret management, etc.	
<br><br>
Resources:<br>
Testcontainers
https://www.testcontainers.org/ 
MS SQL
https://www.testcontainers.org/modules/databases/mssqlserver/
Kafka
https://www.testcontainers.org/modules/kafka/ 
Selenium
https://www.testcontainers.org/modules/webdriver_containers/ 
<br>
<br>
<br>
**Mobile test automation**
<br><br>
Category:<br> 
Quality assurance
<br><br>
Comments:<br> 
Test automation for a mobile native application, hybrid and reactive application
<br><br>
Resources:<br>
http://appium.io/
https://www.seleniumhq.org/
Others: 
https://www.testingexcellence.com/open-source-mobile-test-automation-tools/
<br>
<br>
<br>
**Load Test**	
<br><br>
Category:<br> 
Quality Assurance
<br><br>
Comments:<br> 
Load testing an application generally means measuring performance with a specific predetermined amount of load. This is a good way to ensure you have yet to introduce a change that has impacted your overall application. For example, a 20 per cent increase in response time probably doesn’t generate a monitoring alert, but it may be killing your business.	
<br><br>
Resources:<br>
https://www.microfocus.com/en-us/products/loadrunner-load-testing/overview
https://blazemeter.com/
Open Source alternatives:
http://jmeter.apache.org/
https://gatling.io/
https://locust.io/
Cloud-based:
https://flood.io/
<br>
<br>
<br>
**Smoke testing**	
<br><br>
Category:<br> 
Quality Assurance
<br><br>
Comments:<br> 
After the application is deployed, it’s ideal to have a series of automated sets of basic functionality tests to ensure that the system is up and functional.	Run unit tests after deployments.
<br>
<br>
<br>
**Stress testing**	
<br><br>
Category:<br> 
Quality assurance
<br><br>
Comments:<br> 
This test determines how much load your system can take before it fails. Same as the Load Test tools list.
<br>
<br>
<br>
**Soak testing**	
<br><br>
Category:<br> 
Quality Assurance.	
<br><br>
Comments:<br> 
This test ensures that your system keeps running under a sustained load. I saw a system once that seemed to perform well on a short performance test, but growing message queues added up over time, making it slower and slower. Memory leaks are also a common cause of issues on soak tests.	Same as the Load Test tools list
<br>
<br>
<br>
**Spike testing**	
<br><br>
Category:<br> 
Quality Assurance	
<br><br>
Comments:<br> 
This test is done by suddenly increasing the load on a system and seeing what happens. This is the type of testing that can be very important when the infrastructure is using dynamic containers. Same as the Load Test tools list
<br>
<br>
<br>
**Fuzz Testing**	
<br><br>
Category:<br> 
Quality Assurance	
<br><br>
Comments:<br> 
This type of testing is about using invalid and unpredictable input parameters. There are tools for APIs for code. Some of the tools also implement a scripting language that helps the tool validate the expected conditions and results. It is a must-have when developing smart contracts with solidity. This type of tool is applied to a library, and it will instrument it to know at runtime the parameters and the execution paths that can take. With this data, the tool invents its parameters and tries to execute all the possible execution paths. The tool can affect performance. Therefore should not be deployed in production permanently. 	
<br><br>
Resources:<br>
OWASP – Fuzz testing
https://owasp.org/www-community/Fuzzing
<br>
<br>
<br>
**FuzzyTesting – javascript**
<br><br>
Category:<br> 
Quality Assurance	
<br><br>
Comments:<br>  
Fuzzy testing tool.
<br><br>
Resources:<br>
https://www.npmjs.com/package/fuzzy-testing
JSFuzz – javascript: https://www.npmjs.com/package/jsfuzz
Solidity Scribble: https://docs.scribble.codes/ 
<br>
<br>
<br>
**ZAP (OWASP) Penetration test**
<br><br>
Category:<br> 
Security.	
<br><br>
Comments:<br> OWASP ZAP is a free penetration testing tool. Web Application Vulnerability Scanners are automated tools that scan web applications from the outside to look for security vulnerabilities such as Cross-site scripting, SQL Injection, Command Injection, Path Traversal and insecure server configuration. This tool category is frequently called Dynamic Application Security Testing (DAST) Tools.	
<br><br>
Resources:<br>
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
<br>
<br>
<br>
**Automatic API Attack Tool**	
<br><br>
Category:<br> 
Security, Penetration test
<br><br>
Comments:<br> 
It is a customizable API attack tool that takes an API specification as an input and generates and runs attacks based on it as an output.
<br><br>
Resources:<br>
Imperva’s Automatic API Attack Tool – Github
https://github.com/imperva/automatic-api-attack-tool 
<br>
<br>
<br>
**PentestGPT**
<br><br>
Category:<br> 
Penetration test. Security.	
<br><br>
Comments:<br> 
PentestGPT is a penetration testing tool empowered by ChatGPT. It is designed to automate the penetration testing process. It is built on ChatGPT and operates in an interactive mode to guide penetration testers in overall progress and specific operations.	
This capability may be in the same group as the one provided by:
•	ImmuniWeb
•	ZAP (OWASP)
•	Burp Suite
<br><br>
Resources:<br>
https://github.com/GreyDGL/PentestGPT
<br>
<br>
<br>
**Burp Suite**	
<br><br>
Category:<br> 
Quality Assurance. Security	 
<br><br>
Comments:<br> 
Burp Suite is a penetration testing tool. It is the preferred tool by Apple Store to test Applications before they are listed in the Apple Store.	
This capability may be in the same group as the one provided by:
•	ImmuniWeb
•	ZAP (OWASP)
•	Burp Suite
<br><br>
Resources:<br>
Burp Suite
https://portswigger.net/
<br>
<br>
<br>
**ImmuniWeb**	
<br><br>
Category:<br> 
Security. Pentest. 
<br><br>
Comments:<br> 
Minimalistic and simple web server validation for security-related configuration. ImmuniWeb provides a free API to test your web server for security-related configuration.
ImmuniWeb
•	ZAP (OWASP)
•	Burp Suite
<br><br>
Resources:<br>
Free and paid API versions are available.	 
https://www.immuniweb.com/websec/#api
This capability may be in the same group as the one provided by:
<br>
<br>
<br>
**growthbook**	
<br><br>
Category:<br> 
Feature Flagging. A/B Testing Platform	Open Sourced
<br><br>
Comments:<br>
It is a Feature Flagging tool similar to LaunchDarkly.
<br><br>
Resources:<br>
A/B Testing Platform	
https://github.com/growthbook/growthbook
<br>
<br>
<br>
**Checkov**
<br><br>
Category:<br> 
Security. CSPM.	
<br><br>
Comments:<br> 
It scans cloud infrastructure configurations. IaaC security validation. Static configuration scanning. It finds misconfigurations before they are deployed.	Platform and cloud-independent tool. It can scan cloud infrastructure configurations to find misconfigurations before they're deployed. Checkov uses a command-line interface to manage and analyze infrastructure as code (IaC) scans results across platforms such as Terraform, CloudFormation, Kubernetes, Helm, ARM Templates and Serverless framework.
<br><br>
Resources:<br>
https://www.checkov.io/ 
<br>
<br>
<br>
**Cloud Custodian**	
<br><br>
Category:<br> 
Security. CSPM. 
<br><br>
Comments:<br> 
It scans cloud infrastructure configurations. IaaC security validation. Static configuration scanning. It finds misconfigurations before they are deployed. Platform and cloud-independent tool.
<br><br>
Resources:<br>
https://cloudcustodian.io/
https://cloudcustodian.io/docs/azure/resources/index.html
<br>
<br>
<br>
**Secure DevOps Kit for Azure**
<br><br>
Category:<br> 
Security, Scan cloud infrastructure configurations.
<br><br>
Comments:<br>
The "Secure DevOps Kit for Azure" (will be referred to as 'AzSK') is a collection of scripts, tools, extensions, automation, etc. that caters to the end-to-end Azure subscription and resource security needs for dev ops teams using extensive automation and smoothly integrating security into native dev-ops workflows helping accomplish secure dev-ops.
This capability may be in the same group as the one provided by:
•	Secure DevOps Kit for Azure
•	Microsoft Security Analysis
<br><br>
Resources:<br>
Secure DevOps Kit for Azure
https://azsk.azurewebsites.net/
Getting started with the Secure DevOps Kit for Azure (AzSK)
https://azure.microsoft.com/en-au/resources/videos/azure-friday-getting-started-with-the-secure-devops-kit-for-azure-azsk/
azsdk/azsdk-docs
https://github.com/azsdk/azsdk-docs
<br>
<br>
<br>
**Microsoft Security Code Analysis**
<br><br>
Category:<br>	
Security.  It scans cloud infrastructure configurations.
<br><br>
Comments:<br> The Microsoft Security Code Analysis Extension is an Azure DevOps Services platform task collection. These tasks automatically download and run secure development tools in the build pipeline. The extension is now in a Private Preview (by invitation).	
This capability may be in the same group as the one provided by:
•	Secure DevOps Kit for Azure
•	Microsoft Security Analysis
<br><br>
Resources:<br>
https://secdevtools.azurewebsites.net/
<br>
<br>
<br>
**Slack - Integration** 
<br><br>
Category:<br> 
Productivity, Governance, Integration with workplace collaboration tools
<br><br>
Comments:<br> 
Build-pipelines' output can be associated with Slack channels to inform about fails and pass runs. 
It can also provide visibility to architects and managers about the build process to exercise governance. 	
<br><br>
Resources:<br>
https://api.slack.com/
https://docs.microsoft.com/en-us/azure/devops/service-hooks/services/slack?view=azure-devops
https://docs.microsoft.com/en-us/azure/devops/pipelines/integrations/slack?view=azure-devops
<br>
<br>
<br>
**ServiceNow - Integration**	
<br><br>
Category:<br> 
Incident management. Governance	Integration with Incident Management
<br><br>
Comments:<br> 
Set up and manage subscriptions for completed builds, releases, pending approvals and more from the app and get notifications for these events in your Slack channels.	
<br><br>
Resources:<br>
https://docs.microsoft.com/en-us/azure/devops/pipelines/release/approvals/servicenow?view=azure-devops
<br>
<br>
<br>
**Kube Hunter**	
<br><br>
Category:<br> 
Security, Penetration testing. 
<br><br>
Comments:<br> 
This tool is specific for containers running in Kubernetes 	Kubernetes specific Penetration Test – PenTest
<br><br>
Resources:<br>
http://techgenix.com/kubernetes-security-tools/ 
https://blog.aquasec.com/kube-hunter-kubernetes-penetration-testing
https://github.com/aquasecurity/kube-hunter 
<br>
<br>
<br>
**Kube bench**
<br><br>
Category:<br> 
Security	
<br><br>
Comments:<br>
Kube-bench is a Go application that checks whether Kubernetes is deployed securely by running the checks documented in the CIS Kubernetes Benchmark.
<br><br>
Resources:<br>
Kubernetes-specific vulnerability tool – Vulnerability tool
http://techgenix.com/kubernetes-security-tools/
https://github.com/aquasecurity/kube-bench
https://www.cisecurity.org/benchmark/kubernetes/ 
<br>
<br>
<br>
**LiquidBase**
<br><br>
Category:<br> 
DataOps, Source code quality. CI-CD for Database Changes 
<br><br>
Comments:<br> 
Liquid base is a database-independent library for tracking, managing and applying database schema changes.	
<br><br>
Resources:<br>
https://github.com/liquibase/liquibase/ 
<br>
<br>
<br>
**Renovate**
<br><br>
Category:<br> Source code quality
<br><br>
Comments:<br> It is an enhanced version of what dependabot does. It is an open-source tool that automatically creates pull requests for all dependency updates. Includes crowdsourced test and package adoption data used to flag potentially risky updates and enable auto-merging for those that meet user-defined conditions.
It Scans your repos to detect dependencies (wide package manager support). It Checks if any newer versions exist. And then Raises PRs for available updates.
Save time and reduce risk by automating dependency updates in software projects. Fully customizable with a setting to suit every workflow.	
<br><br>
Resources:<br>
https://www.npmjs.com/package/renovate 
https://renovatebot.com/
https://github.com/renovatebot/renovate
<br>
<br>
<br>
**Dependabot**
<br><br>
Category:<br> 
Security. Source code quality
<br><br>
Comments:<br> 
Dependabot is a GitHub app that automates dependency updates. Every day, Dependabot pulls down your dependency files and looks for outdated requirements. If any dependencies are out-of-date, Dependabot opens individual pull requests to bump each one.	
<br><br>
Resources:<br>
https://dependabot.com/
https://dependabot.com/blog/introducing-dependabot/
<br>
<br>
<br>
**Sentry**
<br><br>
Category:<br> 
Source code quality. Quality assurance
<br><br>
Comments:<br> 
It is an Open-source error tracking that helps developers monitor and fix crashes in real-time. Iterate continuously. Boost efficiency. Improve user experience.	
<br><br>
Resources:<br>
https://docs.sentry.io/
Sentry + Microsoft Azure DevOps: Error-Tracking, Crash-Reporting, & More
https://blog.sentry.io/2018/09/18/sentry-azure-devops-integration-update
<br>
<br>
<br>
**Code forensics**
<br><br>
Category:<br> 
Security, Governance
<br><br>
Comments:<br> 
Source code quality	Toolset for analysing codebases stored in a version control system. It leverages the repository logs, or version history data, to perform deep analyses regarding complexity, logical coupling, and authors coupling and to inspect the evolution in time of different parts of a software system concerning metrics like code churn and the number of revisions.	
<br><br>
Resources:<br>
https://www.npmjs.com/package/code-forensics
https://github.com/smontanari/code-forensics
<br>
<br>
<br>
**Architecture Unit**	
<br><br>
Category:<br> 
Governance. Source code quality.
<br><br>
Comments:<br>
It implements compilation assertion rules to static code packages.
Application architecture and Project structure code analyser based on flexible architecture principle rules. It can check that packages do not include or have static dependencies with libraries from other packages. Each of the packages is meant to be deployable code based for different modules of the architecture.	
<br><br>
Resources:<br>
Java Library (Original Project)
https://www.archunit.org/  
.Net Library 
https://github.com/BenMorris/NetArchTest/tree/master  
NodeJS Library
https://github.com/manjericao/ArchUnitNode 
<br>
<br>
<br>
**Binskim**
<br><br>
Category:<br> 
Security, Package analyser for NuGet packages.
<br><br>
Comments:<br>
A binary static analysis tool that provides security and correctness results for Windows Portable Executable and *nix ELF binary formats (.Net framework NuGet packages)	
<br><br>
Resources:<br>
https://github.com/Microsoft/binskim
<br>
<br>
<br>
**Powerfulseal**
<br><br>
Category:<br> 
Reliability	
<br><br>
Comments:<br>
These tools inject failure into your Kubernetes clusters so that you can detect problems as early as possible. It allows for writing scenarios describing complete chaos experiments.
<br><br>
Resources:<br>
https://dzone.com/articles/chaos-mesh-a-chaos-engineering-solution-for-system
https://medium.com/faun/failures-are-inevitable-even-a-strongest-platform-with-concrete-operations-infrastructure-can-7d0c016430c6 
https://github.com/powerfulseal/powerfulseal
https://github.com/bloomberg/goldpinger
https://docs.locust.io/en/latest/running-locust-distributed.html 
https://github.com/asobti/kube-monkey
https://github.com/target/pod-reaper 
<br>
<br>
<br>
**Chaos Toolkit**	
<br><br>
Category:<br> 
Reliability, Infrastructure resiliency.
<br><br>
Comments:<br>
The Chaos Toolkit is a toolkit to describe and then run repeatable experiments on your infrastructure to understand its resilience in the event of failure. It is an open-source project dedicated to the practice. The toolkit already has drivers for AWS, Azure Service Fabric and GCE (among others) and plays nicely with build tools that let you experiment with automation. The usual caveats apply; Chaos Engineering is a powerful technique best used on resilience-aware systems, systems built to cope with failure. Therefore, we recommend using Chaos Toolkit in your nonproduction environments first.	Based on the recommendations for chaos engineering for Kubernetes book: “The DevOps Toolkit Kubernetes Chaos Engineering (2020)” by Viktor Farcic and Darin Pope. Gremlin Reliability. Gremlin provides a unique tool that allows infiltrating the Kafka brokers to produce artificial instability that allows an understanding of how the system recovers.	
<br><br>
Resources:<br>
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
<br>
<br>
<br>
**CodeScene**
<br><br>
Category:<br> 
Source code quality	
<br><br>
Comments:<br> 
CodeScene is a behavioural code analysis tool. It provides code visualizations based on version-control data and machine-learning algorithms that identify social patterns and hidden risks in code. It detects hotspots—complex code that an organization has to work with frequently—and prioritizes technical debt based on how the developers work with the code.	
<br><br>
Resources:<br>
https://codescene.io/
<br>
<br>
<br>
**Letsencrypt**
<br><br>
Category:<br> 
Cost Management, Security. 
<br><br>
Comments:<br> Integrate letsencrypt certificates to the CI-CD. Fastrack the creation and the management of certificates for new environments by having a secure, cheaper and faster process to request, deploy and operate lifecycle management of digital certificates using letsencrypt certificates lifecycle management APIs.	
<br><br>
Resources:<br>
https://letsencrypt.org/
https://letsencrypt.org/docs/client-options/
https://certbot.eff.org/
https://marketplace.visualstudio.com/items?itemName=cboroson.cboroson-VSTS-LetsEncrypt
https://medium.com/@brentrobinson5/automating-certificate-management-with-azure-and-lets-encrypt-fee6729e2b78
https://blogs.msdn.microsoft.com/mihansen/2018/01/25/azure-web-app-with-lets-encrypt-certificate-powershell-automation/
https://dev.to/ianknighton/deploying-a-microservice-on-azure-kubernetes-with-lets-encrypt-4eon
https://docs.microsoft.com/en-us/azure/aks/ingress-tls
https://github.com/jetstack/cert-manager
<br>
<br>
<br>
**Fossology**
<br><br>
Category:<br> 
Compliance	
<br><br>
Comments:<br>
Open Source License compliance checker. The FOSSology Project is a Free Open Source Software (FOSS) project built around an open and modular architecture for analyzing software for open-source software governance. Existing modules include license scanning, copyright and user identification, license classification and metadata extraction.
This capability may be in the same group as the one provided by:
•	Fossology
•	WhiteSource
<br><br>
Resources:<br>
Read more about open-source license concerns:
https://softwareengineering.stackexchange.com/questions/47032/can-i-use-gpl-software-in-a-commercial-application 
https://fossa.com/
https://www.fossology.org/
https://sourceforge.net/projects/fossology/
<br>
<br>
<br>
**WhiteSource**
<br><br>
Category:<br> 
Compliance	
<br><br>
Comments:<br>
Open Source License compliance checker.. WhiteSource automates the entire open source component selection process, approval and management, including detection and remediation of security and compliance issues. It integrates with all stages of your software development lifecycle (SDLC) to alert you in real time and help you fix issues faster and easier.
This capability may be in the same group as the one provided by:
•	Fossology
•	WhiteSource
<br><br>
Resources:<br>
Read more about open-source license concerns:
https://softwareengineering.stackexchange.com/questions/47032/can-i-use-gpl-software-in-a-commercial-application
https://www.whitesourcesoftware.com/
<br>
<br>
<br>
**Operation automation**
<br><br>
Category:<br> 
Operation automation. Operation events automation
<br><br>
Comments:<br>
This is an IFTTT specialised tool for CI/CD automation. Capture incidents and events from environments and automate actions.	
<br><br>
Resources:<br>
https://stackstorm.com/
https://www.rundeck.com/
<br>
<br>
<br>
**CI/CD Standards**
<br><br>
Category:<br> 
Tools interoperability.	CI/CD standards.  Standardisation
<br><br>
Comments:<br>
Adopt CI/CD emerging standards to avoid vendor locking, portability and interoperability. Linux Foundation has recently created a project called “CD Foundation”, which industry leaders have backed up. This is recent news, and nothing has come up yet from this forum. Vendors also are coming with open technologies to allow CD components interoperability. CDEvents is a common specification for Continuous Delivery events, enabling interoperability in the complete software production ecosystem. It's an incubated project at the Continuous Delivery Foundation (CDF). 	
<br><br>
Resources:<br>
https://www.linuxfoundation.org/Projects/cd-foundation/
Others:
https://cloud.google.com/tekton/
https://jenkins-x.io/
https://www.spinnaker.io/
<br>
<br>
<br>
**PlantUML**
<br><br>
Category:<br> 
Diagrams as code. Productivity. Governance.
<br><br>
Comments:<br>
It is a library that allows the creation of UML diagrams using a scripted language. PlantUML uses a graphic rendering engine Graphviz. There has to be implemented a bridge program that interprets the source an translate it to the graphical scripting language. The idea is to hook this tool into the CI-CD pipeline so that each deployment's basic diagrams and documentation are self-generated.
<br><br>
Resources:<br>
PlantUML 
https://plantuml.com/ 
Graphviz
http://www.graphviz.org/
Node-plantuml
https://www.npmjs.com/package/node-plantuml 
<br>
<br>
<br>
**K8s-diagrams**
<br><br>
Category:<br> 
Diagrams as code, Productivity, Governance
<br><br>
Comments:<br>
Documentation	K8s-diagrams. A tool that allows creating diagrams by pointing them to a Kubernetes cluster or Kubernetes namespace. 
It uses the PlantUML engine, although it does not conform to UML but its standards. It uses the official Kubernetes master icon set.
The idea is to hook this tool into the CI-CD pipeline so that each deployment's basic diagrams and documentation are self-generated.	
<br><br>
Resources:<br>
K8s-diagrams
https://github.com/cloudogu/k8s-diagrams
Kubernetes icons
https://github.com/kubernetes/community/tree/master/icons 
<br>
<br>
<br>
**mingrammer**	
<br><br>
Category:<br> 
Diagrams as code, Productivity, Governance
<br><br>
Comments:<br>
It is a tool to automatically create diagrams from cloud infrastructure, including Azure and Kubernetes. 
It recommends extracting the data from the infrastructure using cloudiscovery tool. There has been implemented bridge program that interprets the source and translates it to the graphical scripting language. The idea is to hook this tool into the CI-CD pipeline so that each deployment's basic diagrams and documentation are self-generated.	
<br><br>
Resources:<br>
Diagrams mingrammer
https://diagrams.mingrammer.com/ 
Kubernetes example
https://diagrams.mingrammer.com/docs/getting-started/examples#stateful-architecture-on-kubernetes 
Cloudiscovery
https://github.com/Cloud-Architects/cloudiscovery 
<br>
<br>
<br>
**Mermaid-js**
<br><br>
Category:<br> 
Diagrams as code, Productivity, Governance.
<br><br>
Comments:<br>
The tool generates UML diagrams, and other project management diagrams (Gantt) from a scripting language. There has been implemented bridge program that interprets the source and translates it to the graphical scripting language. The idea is to hook this tool into the CI-CD pipeline so that each deployment's basic diagrams and documentation are self-generated.	
<br><br>
Resources:<br>
Mermaid-js
https://mermaid-js.github.io/ 
Mermaid-js editor live
https://mermaid.live/ 
Mermaid-js npm package
https://www.npmjs.com/package/mermaid 
<br>
<br>
<br>
**Enterprise asset management (EAM) - Diagrams as code - iServer**
<br><br>
Category:<br> 
Productivity, Governance. Documentation	
<br><br>
Comments:<br> Integrate CI/CD and build the pipeline to the iServer metadata repository. 
All these can be captured and fed to the iServer repository while processing in CI-CD. This information can be translated to enterprise model standards (TOGAF, ArchiMate, UML).
You may need to do a POC for this. Achieve having updated data in the EAM to have “living documents”
At the time of building application components and systems, it is possible to capture valuable information about:
-	 Infrastructure configuration
-	Applications components
-	Application deployment
-	Application composition 
-	Application dependencies 
All languages have manifest files that this information can be obtained.
<br><br>
Resources:<br>
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
<br>
<br>
<br>
**DoBetterAsCode**
<br><br>
Category:<br> 
Source code quality
<br><br>
Comments:<br>
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
<br><br>
Resources:<br>
DoBetterAsCode: https://dobetterascode.com/
DoBetterAsCode  Github: https://github.com/DoBetterAsCode/DoBetterAsCode
DoBetterAsCode  Tools and Resources:<br>  https://dobetterascode.com/resources/ 
<br>
<br>
<br>
**Sigstore**
<br><br>
Category:<br> 
Security, Supply chain security	Sigstore
<br><br>
Comments:<br>
It is a set of free-to-use and open-source tools, including fulcio, cosign and rekor, handling digital signing, verification and checks for provenance needed to make it safer to distribute and use open-source software	
<br><br>
Resources:<br>
Sigstore
https://www.sigstore.dev/ 
<br>
<br>
<br>
**Preflight**
<br><br>
Category:<br> 
Security. Supply chain security	Preflight
<br><br>
Comments:<br>
It helps you verify scripts and executables to mitigate chain of supply attacks such as the recent Codecov hack	
<br><br>
Resources:<br>
Preflight
https://github.com/spectralops/preflight 
<br>
<br>
<br>
**Open Raven**
<br><br>
Category:<br> 
Magpie	Security. CSPM	Cloud Security Posture Management (CSPM)	
<br><br>
Comments:<br> 
CSPM	Cloud Security Posture Management (CSPM) Open source
<br><br>
Resources:<br>
Open Raven Magpie
https://github.com/openraven/magpie 
<br>
<br>
<br>
**Cloud Query**
<br><br>
Category:<br> 
CSPM	Cloud Security Posture Management (CSPM)	
<br><br>
Comments:<br> 
CSPM	Cloud Security Posture Management (CSPM) Open source
<br><br>
Resources:<br>
Cloud Query
https://www.cloudquery.io/ 
<br>
<br>
<br>
**Cloudsploit**
<br><br>
Category:<br> 
CSPM	Cloud Security Posture Management (CSPM)	
<br><br>
Comments:<br> 
Detection of security risks in cloud infrastructure
<br><br>
Resources:<br>
https://github.com/aquasecurity/cloudsploit
<br>
<br>
<br>
**ScoutSuite**
<br><br>
Category:<br> Security, CSPM Cloud Security Posture Management (CSPM)	
<br><br>
Comments:<br> NCCgroup is a multi-cloud scanning tool. 
<br><br>
Resources:<br>
https://github.com/nccgroup/ScoutSuite 
<br>
<br>
<br>
**CloudCustodian**
<br><br>
Category:<br> 
Security, CSPM	Cloud Security Posture Management (CSPM)		
<br><br>
Comments:<br>
Multi-cloud security analysis framework
<br><br>
Resources:<br>
CloudCustodian
https://github.com/cloud-custodian/cloud-custodian/	
<br>
<br>
<br>
**CloudGraph**
<br><br>
Category:<br> 
Security, CSPM	Cloud Security Posture Management (CSPM)	
<br><br>
Comments:<br> 
GraphQL API + Security for AWS, Azure, GCP, and K8s
<br><br>
Resources:<br>
https://github.com/cloudgraphdev/cli 
<br>
<br>
<br>
**Cosign**
<br><br>
Category:<br> 
Deployment Digital Signature Digest. 	
<br><br>
Comments:<br>
Container image signing	Deployment Object Digital Signature Digest
<br><br>
Resources:<br>
https://github.com/sigstore/cosign
<br>
<br>
<br>
**Notary**
<br><br>
Category:<br> 
Deployment Digital Signature Digest	
<br><br>
Comments:<br> 
Docker image signing	Deployment Object Digital Signature Digest
<br><br>
Resources:<br>
https://github.com/notaryproject/notary
<br>
<br>
<br>
**terracognita**
<br><br>
Category:<br> 
Governance, Documentation. Reverse engineer Terraform templates.
<br><br>
Comments:<br>
Reads from existing public and private cloud providers (reverse Terraform) and generates your infrastructure as code on Terraform configuration	
<br><br>
Resources:<br>
terracognita.
https://github.com/cycloidio
<br>
<br>
<br>
**inframap**
<br><br>
Category:<br> 
Documentation, Governance
<br><br>
Comments:<br>
It generates a graph with the most important resources of your infrastructure. Reads from a “.tfstate” file (created when you do a `terraform import`) or HCL (HashiCorp Configuration Language). It generates a DOT format.	
<br><br>
Resources:<br>
inframap
https://github.com/cycloidio
DOT Format
https://graphviz.org/doc/info/lang.html
<br>
<br>
<br>
**Data Linter**
<br><br>
Category:<br> 
Data quality control.	Data quality Linter.
<br><br>
Comments:<br>
A tool that could be more suitable for data pipelines. However, it can be used as a quality assurance tool in the DevSecOps pipeline to ensure the integrity of an environment and to test and ensure that previous data inconsistencies are not affecting the system before deploying a new package. It is designed to read in and validate tabular data against a given schema for the data. The schemas provided adhere to our metadata schemas standards for data. Based on the validation result, this package can also manage data movement from a landing area (s3 or locally) to a new location.	
<br><br>
Resources:<br>
Data quality control linter
https://pypi.org/project/data-linter/
<br>
<br>
<br>
**Great Expectations**
<br><br>
Category:<br> 
Data quality control. Data quality Linter.
<br><br>
Comments:<br>
A tool that could be more suitable for data pipelines. However, it can be used as a quality assurance tool in the DevSecOps pipeline to ensure the integrity of an environment and to test and ensure that previous data inconsistencies are not affecting the system before deploying a new package. 	
<br><br>
Resources:<br>
Great Expectations 
https://github.com/great-expectations/great_expectations
<br>
<br>
<br>
**DbUnit**
<br><br>
Category:<br> 
Data quality control
<br><br>
Comments:<br>
DbUnit is a JUnit extension (also usable with Ant) targeted at database-driven projects that, among other things, puts your database into a known state between test runs. This is an excellent way to avoid the myriad of problems when one test case corrupts the database and causes subsequent tests to fail or exacerbate the damage.
DbUnit can export and import your database data to and from XML datasets. Since version 2.0, DbUnit can also work with large datasets in streaming mode. DbUnit can also help you to verify that your database data match an expected set of values.	
<br><br>
Resources:<br>
DBUni
https://www.dbunit.org/intro.html
<br>
<br>
<br>
--End of the file--
