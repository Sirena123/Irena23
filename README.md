# Irena23
1.	Introduction
This document provides the Testing Strategy for the <Application Name> system.  It includes the following components:
	Testing Strategy Overview
	Background
	Scope
	Constraints
	Key Inputs
	Task Overview
	Key Deliverables
	Acceptance Criteria
	Problem Management
	Critical Success Factors
	Risk and Contingency Plans
	Metrics

1.1.	Audience
The audience for this document includes system development team members, <Company Long Name> project team members, and members of the Project Name steering committee.

2.	Testing Strategy Overview
The <Application Name> Testing Strategy determines the project’s approach to testing.  The strategy looks at the characteristics of the system to be built, the project time line and budget, and plans the breadth and depth of the testing effort.  The Testing Strategy will influence tasks related to test planning, test types, test script development, and test execution.

2.1.	Objectives
The key objectives are as follows:
•	Determine the significance, or critical nature, of the application system to the business.
•	Determine the types of tests required by each testing task.
•	Identify the need for converted data from legacy systems or other sources.
•	Determine the need for a systems integration test by identifying key system interfaces.
•	Identify performance assurance requirements.

2.2.	Deliverable Audience
The <Application Name> Testing Strategy is intended for the following audience:
•	<Development Contractor> and <Company Short Name> analysts and designers
•	<Development Contractor> and <Company Short Name> testers
•	conversion and interface teams
•	operations
•	other team members that may be involved in the systems integration test

2.3.	Benefits
The Testing Strategy can provide the following benefits:
•	faster development of testing requirements by directly using key project deliverables
•	earlier identification of testing requirements
•	independence of testing from development tasks and resources
•	well-defined tests
•	progressive and additive test tasks

3.	Background

4.	Scope
To define the testing scope of <Application Name>, the following areas were examined:
•	testing tasks
•	test types by task
•	converted data sources
•	system interfaces
•	testing environments
•	testing tools

4.1.	Testing Tasks
This project includes the following testing tasks:
•	module test
•	module integration test
•	system test
•	systems integration test
•	acceptance test

4.2.	Test Types by Task
The following list identifies, by testing task, the types of testing that will be conducted:
Module Test
system process step
validation
calculation
error handling
database auditing
security
volume data
help text
checkpoint restart
user interface
report layout
screen layout
Module Integration Test
system process script
security
volume data
System Test
initial system documentation
manual data load
system process sequence using scripted data
interface using scripted data
converted data load
converted data inspection
system process sequence using converted data
interface using converted data
parallel legacy reconciliation
job stream
backup and recovery
database auditing
data archival
security
locking
batch response time
online response time
Systems Integration Test
systems integration process sequence using converted data
network stress
security
locking
batch response time
online response time
Acceptance Test
batch response time
online response time
parallel running
live data
live environment
final system documentation sign-off

4.3.	Converted Data Sources
The following table identifies legacy or other sources of converted data that will be used for testing:
Legacy System or Source Name	Description of Converted Data
			
			
			
			
			

4.4.	System Interfaces
The following table identifies key system interfaces that will be integral to the testing of <Application Name>:
System Interface Name	Type (input, output, two-way)
			
			
			
4.5.	Testing Environments
The following table documents the testing environment criteria for each testing task:
Testing Task	Platform	Database Name
	Module Test				
	Module Integration Test				
	System Test				
	Systems Integration Test				
	Acceptance Test				

4.6.	Testing Tools
The following testing tools will be used:
Testing Tool	Purpose
			
			
			

5.	Constraints
The project must operate within the following limits:
Time
Testing tasks will be constrained by time, affecting the following activities:
•	
•	
Required System Resources
The <Application Name> testing effort is restricted by the availability of the following system resources:
•	
•	
Business
The <Application Name> testing effort is restricted by the following business policies:
•	
•	
Technical
The <Application Name> testing effort is restricted by the following technical constraints:
•	
•	

6.	Key Inputs
Key inputs to <Application Name> testing are as follows:
•	System Process Model
•	System Function Model
•	System Data Model
•	Existing System Interfaces
•	System Interfaces Requirements
•	Detailed System Interfaces Requirements
•	User Interface Style Definition
•	Recovery and Fallback Strategy
•	Database Object Authorization Scheme
•	Module Process Model
•	Menu Structure
•	Module Functional Documentation
•	Module Technical Documentation
•	Installation Plan
•	System Operations Guide
•	User Reference Manual
•	User Guide
•	Technical Reference Manual
•	Runtime Online Help
•	business analysts
•	operations staff

7.	Task Overview
The key testing tasks for <Application Name> are as follows:
•	Develop Testing Strategy
•	Develop System Process Test Model
•	Develop Module and Module Integration Test Plan
•	Perform Module Test and Module Integration Test
•	Develop System Test Plan
•	Prepare System Test Environment
•	Perform System Test
•	Develop Systems Integration Test Plan
•	Develop Systems Integration Test Sequences
•	Perform Systems Integration Test
•	Prepare Acceptance Test Environment
•	Support Acceptance Test

8.	Key Deliverables
The key testing deliverables for <Application Name> are as follows:
•	Testing Strategy
•	System Process Test Model
•	Module and Module Integration Test Plan
•	Module and Module Integration Test Results
•	System Test Plan
•	System Test Environment
•	System Test Results
•	Systems Integration Test Plan
•	Systems Integration Test Sequences
•	Systems Integration Test Results
•	Acceptance Test Environment
•	Acceptance Test Results

9.	Acceptance Criteria
This acceptance criteria for the testing task deliverables will be measured by the completion and sign-off of each deliverable which has been listed.  Deliverables for test scripts and test results will be subject to quality reviews.

10.	Problem Management
The assessment and prioritization of defects found during testing will be strictly controlled using the Problem Management process described in the Master Project Plan.  

11.	Critical Success Factors
In addition to the Project Name overall critical success factors, the following critical success factors are specific to the Testing process:
•	Testing considerations must begin in the early phases of the project.
•	Test script development must be based on key project deliverables.
•	Testing must be objective and must be performed by an independent test team (other than the programmers responsible for the application software).
•	The problem management process must be functional as soon as testing begins, and must ensure that only valid and non-duplicated defects are processed.
•	Multiple iterations for each testing task should be planned to allow for a higher density of testing for the current test iteration and scheduled fixes for the next iteration.
•	Planning for the systems integration test should start early, as it will involve multiple projects, systems, and organizations.
•	The scope of the regression test should be well defined.
•	An automated tool should be used to perform regression testing.
•	Locking, response time, and stress testing should use process-based testing scripts.
•	Modules should be categorized by their relative importance to the business for defect prioritization and performance testing.

12.	Risk and Contingency Plans
Identified testing risks and their associated contingency plans include the following:
ID	Rank	Risk Statement	Probability	Impact	Mitigation
	1						Lo/Med/Hi		Lo/Med/Hi		
	2										
	3										
	4										
	5										

13.	Metrics
Key testing metrics are as follows:
•	number of test iterations planned for each test task
•	relative importance of the application system to the business
•	complexity of the application system under test
•	number of functional areas involved in the module and module integration test
•	number of system processes
•	number of scenarios per system process
•	number of test steps per scenario
•	complexity of the module under test
•	complexity of the scenario under test
•	number of other application systems in the systems integration test
•	required online response time for critical modules
•	batch nightly window response time
•	number of end users required for the stress test

Revision Log
Date	Version	Change Reference	Author	Reviewed by
	[yyyy-mm-dd]		0.1						
									
									
									
									
									


Appendices
Enter content here.
Approval
This document has been approved as the official Testing Strategy for the Project Name project.
Following approval of this document, changes will be governed by the project’s change management process, including impact analysis, appropriate reviews and approvals, under the general control of the Master Project Plan and according to Project Support Office policy.
