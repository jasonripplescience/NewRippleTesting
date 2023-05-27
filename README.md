This document will try to highlight the development process in selenium-tests/RippleScienceSmokeTestAutomation.

Instructions to run tests via command line:

1. Install Java SDK and set classpath on your machine.
2. Clone Repository: git clone https://github.com/RippleScience/ripple-testing.git .
3. Navigate to RippleScienceTests folder.
4. To Run tests locally : "mvn clean test -Denvironment=local -Dsurefire.suiteXmlFiles=./src/test/resources/TestFiles/ParticipantLogsTests.xml"
5. To Run tests on browserstack: "mvn clean test -Denvironment=remote -Dsurefire.suiteXmlFiles=./src/test/resources/TestFiles/ParticipantLogsTests.xml"
5. Above command triggers testng suite (Default test suite is - testFiles.xml). 
6. Tests run in browserstack's cloud - https://automate.browserstack.com/dashboard/.
7. Once tests are done results will be stored in test-output-customReport folder

Tests suites 
1. ParticipantLogsTests.xml - all browsers (Firefox, Chrome, Safari and Edge)
2. ParticipantProfileCardTests.xml - all browsers (Firefox, Chrome, Safari and Edge)
3. RegistryTests.xml - all browsers (Firefox, Chrome, Safari and Edge)
4. SiteAdminPageTests.xml - all browsers (Firefox, Chrome, Safari and Edge)
5. StudySettingsPageTests.xml - all browsers (Firefox, Chrome, Safari and Edge)
6. SurveyOnlyTests.xml - all browsers (Firefox, Chrome, Safari and Edge)
7. TaskAndRecruitmentPageTests.xml - all browsers (Firefox, Chrome, Safari and Edge)
8. TopNavBarPagesTests.xml - all browsers (Firefox, Chrome, Safari and Edge)
