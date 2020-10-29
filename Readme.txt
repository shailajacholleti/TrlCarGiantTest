Highlights to be considered:
Kindly ensure to run this test on local machine with certain parameters

Please consider downloading the below:
Java
InteliJ Idea
Maven & Cucumber Plugins & relevant dependencies

In case of ChromeDriver or other Drivers do not respond then it may have to be downloaded .exe path need to
 be provided within the BasePage (scr >> main >> BasePage)
 config.properties path need to be declared within the BasePage

Project Structure:
 src.test.java.utils.BasePage : Has browser and Driver setup
 src.test.Features : Has Feature file written in Gherkin format (Given When Then)
 src.test.java.stepDefs : Has feature step_Definitions and Hooks (Before and After Test setup)
 src.test.java.TestRunner : All the test will be executed with cucumber Option.
 In Order to run the particular Test ""@tagname" should be entered.
 src.test.java.pageObjects : Has all the Page Objects methods
 pom.xml : This file has all the required dependencies for the project.

target: It will be generated automatically once test is run. Generated cucumber html report,
screen shots will be stored within this folder