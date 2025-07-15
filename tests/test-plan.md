
📘 Initial Test Plan & Strategy Document

1. 🎯 Purpose and Scope

•	Multiple user flows and pages
•	Form validation and error handling
•	UI accessibility issues
•	Boundary testing scenarios
•	Filtering and sorting functionality
•	Simulated admin workflows
•	Responsive design testing
•	Intentional bugs and inconsistencies
   validate functionality, identify defects early


2. 🧩 **Test Objectives**
Verify all features meet the specified requirements.

Ensure system performance, reliability, and security.

Identify usability issues.

3. 🗂️  **Test Items**

   **Pages & Functionality**
1.	**Home Page (/)**
o	Waste pickup request form
o	Form validation (with intentional flaws)
o	Success message display
2.	**Dashboard (/dashboard)**
o	Table of all pickup requests
o	Filtering by status and location
o	Status badges and responsive design
3.	**Feedback Page (/feedback)**
o	Report missed pickups
o	Feedback submission form
o	Request ID validation
4.	**Awareness Page (/awareness)**
o	Educational content about waste management
o	Images with missing alt-text (accessibility testing)
o	Responsive grid layout
5.	**Admin Panel (/admin)**
o	Request management interface
o	Status update functionality
o	Data persistence testing

List modules, features, or user stories to be tested.

Specify version or build information for the software under test.

4. 🛠️ **Test Strategy**

Testing Types: Unit, integration, system, etc.

Approach: Manual vs. automated testing 

Environments: Specify test environments (dev, staging, etc.).

**Functional Testing**
Manual Testing: Browser developer tools, manual test execution
API Testing: Postman (if backend endpoints exist)
Database Testing: Browser localStorage inspection
**Performance Testing**
Page Speed: Google PageSpeed Insights, Lighthouse
Load Testing: Browser network throttling
Memory Usage: Browser memory profiling
**Accessibility Testing**
Screen Readers: NVDA, JAWS, VoiceOver
Accessibility Tools: axe DevTools, WAVE, Lighthouse Accessibility
Keyboard Navigation: Manual testing
**Compatibility Testing**
Browsers: Chrome, Firefox, Safari, Edge
Devices: Desktop, tablet, mobile
Responsive Design: Browser responsive mode
**Project Management**
Jira or GitHub Kanban (Projects): Issue tracking and project management (GitHub Kanban is free and recommended for student use)
Google Drive: File sharing and collaboration
Communication: Teams/Zoom for meetings

5. 🧪 Test Deliverables
Test cases, scripts, test data, test summary reports, defect logs.
Deliverables
1. **Comprehensive Test Report (PDF)**
**Structure:**

Executive Summary
Test Strategy and Approach
Test Environment Details
Test Execution Summary
Defect Analysis and Categorization
Risk Assessment
Recommendations and Improvements
Test Metrics and KPIs
Jira/Github Kanban Reports: Include screenshots of Jira dashboards and reports
2. **5-Minute Video Presentation**
Content:

Project overview and testing approach
Key findings and critical defects
Demo of major issues discovered
Recommendations for improvement
Team collaboration insights
Jira/Github Demonstration: Show Jira usage and project management
3. **Supporting Documentation**
Detailed test cases and results
Bug reports with screenshots/videos
Test data and scenarios used
Tool configurations and setup guides
Jira/Github Export: Complete project export with all issues and comments

6. 👥 Roles and Responsibilities
Define the team structure and individual roles (Test Lead, Testers, Developers, QA Analysts).

       Role	                          Key Responsibilities

🧠  Aghwe Akpome	-                   Setup the Repo, Performance testing,
                                      verify defect, Analyse Performance Bottleneck 
                                      Validate Requirement, Communication with
                                      Stakeholders, Assist unit and integration testing

    James Nyamai                      Doucumentation, Ensure Compliance to standard
                                      Assit in unit and integration testing,validate
                                      functionality

    Zamazizi Zinhle Mabe              Fix bug, Assit in unit and integration testing
                                      Report track and verify defect. Prepare bug Report


7. 📅 Schedule and Milestones

 Testing Strategy & STLC Implementation

**Phase 1: Test Planning (Days 1-2)**
**Test Strategy Development**

Define testing scope and objectives
Identify test environments and tools
Create test data requirements
Establish defect reporting standards
Jira Setup: Create project, configure workflows
**Test Environment Setup**

Browser compatibility matrix (Chrome, Firefox, Safari, Edge)
Device testing (Desktop, Tablet, Mobile)
Network conditions (3G, 4G, WiFi)
Accessibility testing tools
**Phase 2: Test Design (Days 3-4)**
**Test Case Development**

Functional test cases for all features
Non-functional test cases (Performance, Security, Usability)
Accessibility test cases (WCAG 2.1 compliance)
Cross-browser compatibility test cases
Jira Tasks: Create stories for each testing area
**Test Data Preparation**

User accounts (regular users, admins)
Sample content (blog posts, community posts)
Test scenarios for edge cases

**Phase 3: Test Execution (Days 5-8)**
**Functional Testing**

User registration and authentication flows
Waste pickup scheduling and management
Blog and community features
Admin panel functionality
Form validation and error handling
Jira Updates: Log all testing activities and findings
**Non-Functional Testing**

Performance testing (load times, responsiveness)
Security testing (data validation, XSS prevention)
Usability testing (user experience, navigation)
Accessibility testing (screen readers, keyboard navigation)
**Compatibility Testing**

Cross-browser testing
Responsive design validation
Mobile device testing
**Phase 4: Test Closure (Days 9-10)**
**Defect Analysis and Reporting**

Categorize and prioritize defects
Create detailed bug reports in Jira
Provide recommendations for improvements
Jira Reports: Generate defect summary reports

**Test Metrics and Documentation**
Test execution summary
Defect density analysis
Risk assessment
User registration and authentication flows
Waste pickup scheduling and management	


8. 🕵️ **Entry and Exit Criteria**
Entry: Completion of development, availability of environment, etc.

Exit: All critical defects resolved, test cases executed with acceptable pass rate.

9. 📈 **Risk Management**
Identify potential risks (e.g., resource shortage, unclear requirements).

Plan mitigation strategies.

10. 🔁 **Change Management Process**
Procedure for handling changes in requirements or scope during testing.

1. 🧭 Identify and Document the Change
Capture the change request formally (via change request forms, emails, or ticketing systems).

Include details like who requested it, what’s changing, and why.

2. 🧠 Impact Analysis
Assess how the change affects:

Requirements and specifications

Existing test cases and scripts

Test data and environments

Project timelines and resources




Role and Key Responsibilities 


   Role	                          Key Responsibilities

🧠  Aghwe Akpome	-                Setup the Repo, Performance testing,
                                      verify defect, Analyse Performance Bottleneck 
                                      Validate Requirement, Communication with
                                      Stakeholders, Assist unit and integration testing

    James Nyamai                      Doucumentation, Ensure Compliance to standard
                                      Assit in unit and integration testing,validate
                                      functionality

    Zamazizi Zinhle Mabe              Fix bug, Assit in unit and integration testing
                                      Report track and verify defect. Prepare bug Report



     