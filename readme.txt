Tools Used:

IDE		: Eclipse Neon
In scope browser: chrome browser
Framework	: BDD Framework,Selenium, Gherkin
Language	: Java

In total, 7 test cases are written.
In BDD feature file,I have used "Background" which is used to fetch common inputs for all scenarios of the feature file such as  locators properties file , web drivers and  getting right URL from User by using Data table concept.

Testcases:

#TC_001:
The testcase checks whether the user is able to get forecast details for a given city 

#TC_002
Negative Scenario- Checking that the forecast details should not be loaded when non-listed city name is given and validating error message

#TC_003:
Negative Scenario- Checking that the forecast details should not be loaded when no city name is given and validating error message.

#TC_004:
In the application, summary for each day is displayed that includes temperature, rainfall and windspeed which are calcluated from all 5 days' forecast data.

This testcases is to check summary details for temperature for all 5 days and for all 6 cities.
As the applicationg is static, i have stored the data in properties files and considered it as DB. Then validating dispayed temperature details are correct. 

#TC_005:

Same as TC_004; but tested wind speed

#TC_006:

same as TC_004; but tested rainfall.

#TC_007:
show and hide 3 hourly forecast details.





Framework Structure:


Objects files are available in  :"src/main/java/ObjectRepo

Feature file is available in	: src/test

Chromedriver			: src/main/java

StepDefinition files		: src/main/java

pom.xml file







