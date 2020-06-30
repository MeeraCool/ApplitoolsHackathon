## Applitools Hackathon 2020

Used Selenium Webdriver with Java

## Prerequisites

- Selenium-Java Version 3 or above
- JUnit Version 4 or above for ModernTests
- TestNG Version 6 or above for TraditionalTests
- Maven 3.6.0


## Getting Started

### 1) Ensure that the drivers for Chrome,Firefox and Edge browsers were installed and excecutable  in Local Machine
    2) Clone the repository `www.url.com`

## Run Modern Tests

- Version 1

   - Open the ModernTestV1 Project Folder(Used ChromeDriver)
   - Open the terminal in  Project Path and run `'mvn -Dtest=TestSuiteV1.java test'`
     (Refer Note 1)
 
- Version 2

   - Open the ModernTestV2 Project Folder(Used ChromeDriver)
   - Open the terminal in Project Path and run `'mvn -Dtest=TestSuiteV2.java test'`
     (Refer Note 1)

## Modern Test Results

- Test Results for Modern Approach - click [Test Results Dashboard](https://eyes.applitools.com/app/test-results/00000251808807805774/?accountId=GAbcV77hvkmxJ5HytTJaag~~)
  
## Traditional Tests:

- Version 1

  - Open the TraditionalTestV1 Project Folder.
  - Open the terminal in Project Path and run `'mvn -PTraditionalTestsV1'`.
  - Check the `TestResults/TraditionalTestResultsV1.txt` file for the Test Results
    of Traditional test-Version 1's result.
      (Refer Note 1)

- Version 2

   - Open the TraditionalTestV2 Project Folder
   - Open the terminal in Project Path and run `'mvn -PTraditionalTestsV2'`
   - Check the `TestResults/TraditionalTestResultsV2.txt` file for the Test Results
     of Traditional test-Version 2's result.
      (Refer Note 1).

### Notes:
	
- Note 1: Incase of Error occurs on Starting the tests, follow the steps given below
  
   - Open the terminal in project path and run `'mvn clean'`
   - Run `'mvn compile'`
   - In case of any error occurs Import the project in Eclipse IDE and Update the Project with latest dependencies
    (Project (Right Click) ->Maven -> Update Project -> Check the Force Update of Snapshots/Releases option ->Click OK )

- Note 2: While running Individual Tests from Eclipse IDE, follow the steps given below
	
  - Install TestNG from Eclipse MarketPlace while running Individual Traditional Tests in Eclipse IDE.
  - Incase of any error occurs in Project Level change the `Java Compiler version to 1.8` 
	 (JRE System Library(Right Click) -> Classpath Container -> Execution Environment -> JavaSE-1.8 -> Click Apply and Close).
 


