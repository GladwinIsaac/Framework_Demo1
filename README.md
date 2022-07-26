# Framework_Demo1

Framework_Demo1 is a Datadriven framework where I've implemented generating html report through Extent Report,page object model using pom.xml where the required dependencies gets dwonloaded for the ease of compatability across other machines


1. Under src/main/java/resources package-->Properties file,log4j.xml,base.java and ExtentReportersNG.java

  - Properties file used as a global variable where Browser Details ,Test URL,etc can be used
  - Log4j.xml needs to be configured for creating logs which will be useful after validation of scripts 
  - Above properties file called in base class which initiates the browser,scripted screenshot function through Listeners class(ITestListener),Implicit wait can be used
  - After execution ,HTML reports to be generated which is configured in ExtentReportersNG.java using extent reports (reportname,target directory,customising the template also can be done)


2. Under src/main/java package -->Pageobject model been used(Landingpage,Loginpage)

3. Under src/test/java/E2E package --> Acts like a Functional Libraries where all validation for each module happens 
