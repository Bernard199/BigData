# Big Data AS1

---
tags:
  - CSU
  - Big_Data
  - Assignment
---

# Lab 1 on Web Data Processing for Information Extraction

- [Lab Assignment 1](https://eecs.csuohio.edu/~sschung/CIS593/CIS593_Lab1_InformationExtractionWebData_DOMXpath.pdf)
- [FAQs for Lab1 on Information Extraction from Webpages](https://eecs.csuohio.edu/~sschung/CIS593/CIS593_Lab1_FAQs.pdf)
- [Lab Report Example for Lab1](https://eecs.csuohio.edu/~sschung/CIS593/DSA469CIS492_593_ExampleLabReportOutput.pdf) 
- [The Simplified html file of the Info site](https://eecs.csuohio.edu/~sschung/CIS593/SimplifiedInfoUnionAddress.htm)(For Inspection. Not For Use.)
- [Info please site of State Union Addresses of US Presidents](https://www.infoplease.com/homework-help/history/collected-state-union-addresses-us-presidents)
- [Correct page of Address of John Adams December 3 1799](https://www.infoplease.com/homework-help/us-documents/state-union-address-john-adams-december-3-1799)
   
  ---
## Important Notes: 

#Important_Notes

1. Part 2 (on Combining all the address texts in one text file) Is Required For CIS593 Students. Part 2 Is NOT Required for CIS492 Students but It is for extra credit for CIS492 Students.  
  
2. If there is a Link that Does NOT Have Any Web Page Contents, Add NULL Values for the corresponding Columns for the link  
  
3. Do not Assume that every sites has an identical URL format. This is semi-structured data. Nothing is regular in Big data. For the irregular parts, use regular expressions or Xpath as necessary.  
  
---
### There are two ways to do Information Extraction from Webpages:  
  
- Method 1: Webpage as Semi-Structured HTML DOM Tree Using XPATH -- BETTER WAY to Learn For Lab1 !!  

- Method 2: Webpage as Unstructured Text Using Parsing API like Beautiful Soup  

- The Lab1 is to learn HTML DOM Processing using XPATH !  

---
### Set Up Guides for Important Platform with Python, XPath, Beautiful Soup, and MySQL:

#Setup 
  
> You Need To Set UP DOM and XPATH for Any Server-side Scripts/Languages for Applications such as Lab1.
  
- [Platforms Set up Guides with Python, MySql, XPath, PyCharm Debugging IDE for Big Data Labs](https://eecs.csuohio.edu/~sschung/CIS593/CIS492_593_DSA469_Lab1_Environment_Setup.pdf)
> You don't Need to Do Any Extra Set Up to Use XPATH in a JavaScript in a Client side Codes for HTML DOM Processing which will be executed by your Web browser. All the Recent Web Browsers Have XPATH Features in their Debugger by Default (Since 2017).  

---
## Lab1 Implementation Guides: 

#Implementation
  
- [Lab1 Guides: What to Need to Know in the Lab1 Section to Do Lab1](https://eecs.csuohio.edu/~sschung/CIS593/Lab1Guides_Links for XPath_Pyodbc_BLOBDataType.pdf)  
  
> ***Note:*** that the Code Examples of the Lab1 Guides below Do NOT Contain the Complete Codes to Be Executed. These are ONLY for the guides for Lab1.The Environment Configuration and the Versions of APIs Varies. Do Not Copy the Entire Codes Blindly to Do Your Lab1 since it will not work depending on the version of your python and setting up for DOM and XPath.

---
### How to Write Xpath in Demo in Web browser:  

- [Example of Xpath Execution in Web browser](https://eecs.csuohio.edu/~sschung/CIS593/Lab1_Xpath_Syntax_WebpageDemo.pdf) 
- [Xpath Example 2](https://eecs.csuohio.edu/~sschung/CIS593/Lab1_Xpath_WebpageDemo2.pdf)

  ---
### Code Examples with DOM and XPATH:  

- [Example of Lab1: General Guide in Python with DOM and XPath, and pyodbc for database operations for Information Extraction](https://eecs.csuohio.edu/~sschung/CIS593/CIS593_Lab1_Guide_InfoExtraction_WebPageEmery_Partial.pdf) 
- [Example of Lab1: Guide in Python with DOM and XPath in lxml for Information Extraction](https://eecs.csuohio.edu/~sschung/CIS593/CIS593_Lab1_Guide_Web_InformationExtractionDOMXpath_A.pdf) 
- [Example of Lab1: Guide in PHP with DOM and XPath for Webscapping](https://eecs.csuohio.edu/~sschung/CIS593/CIS469_569_Lab1_GuideWebScrappingDOMXpathwithPHP.pdf)
- [Example of Lab1: Guide in Python on Linux for Webscapping](https://eecs.csuohio.edu/~sschung/CIS593/CIS593_Lab1_WebscrapDOMXpathGuideLinux_CFord.pdf)
  
---
### Code Examples with Beautiful Soup Text Processing API:  

- [Example of Lab1: Guide in Python with Beautiful Soup for Information Extraction](https://eecs.csuohio.edu/~sschung/CIS593/CIS469_569_Lab1_GuideWebScrapping.pdf)  

  ---
## DOM with XPATH Set Up in Any Script/Programming Languages for Server Side Applications  


> ***Note:*** that You don't Need to Do Any Extra Set Up to Use XPATH in your Serverside JavaScript in NodeJS. 
 
 All the labs of CIS492/593 are Server-side data processing in a server-side script/programming language with file I/O and DOM parser with Xpath. They are NOT a clientside Javascript executed by your Webbrowser. 

 For the Labs to Write an Application Server in this course, You Need To Add DOM Parser related APIs for Your Scripts/Programming Languages To Do the following steps:  

- to Call a DOM Parser API  
- to Build a DOM Tree and  
- to Use XPATH Methods for Retrival to Extract information 
---
### XPATH Examples:

#### Any Modern Script/Programming Languages Have the DOM Parser and XPath Features. You Need to Set up to Use.  

- [Setting Up lxml parser for DOM with XPath for Python](http://docs.python-guide.org/en/latest/scenarios/scrape/)  
- [Node.JS XPath Setup Guide and XML Parser in JavaScript based Node JS](https://eecs.csuohio.edu/~sschung/CIS593/NodeJSSetupXPathXMLInJS_2.pdf)  
- [XPath Setup Guide for JavaScript](https://github.com/goto100/xpath)  
- [XPath Setup with npm in JavaScript for Node JS](https://www.npmjs.com/package/xpath)
  
#### Set Up DOM with XPath for HTML and XML:  

- [How to Debug HTML with JavaScript, DOM, XPath](https://eecs.csuohio.edu/~sschung/CIS593/HowtoDebugHTMLJAVAScriptXPath.pdf)  
- [Learn How to Inspect Element in Chrome to Debug HTML with for DOM and XPath](https://search.yahoo.com/search?fr=mcafee&type=E211US1289G0&p=how+to+inspect+element+in+chrome)
  
#### JavaScript:

- [JavaScript Debugger](https://www.w3schools.com/js/js_debugging.asp)  
- [XPath Examples in Javascript](https://www.w3schools.com/xml/xpath_intro.asp)  
- [MDN Site for DOM with XPath in JavaScript](https://developer.mozilla.org/en-US/docs/Introduction_to_using_XPath_in_JavaScript)  
- [DOM with XPath Setup Guide for JavaScript](https://github.com/goto100/xpath)  
- [XPath Methods](https://github.com/goto100/xpath/blob/master/docs/xpath%20methods.md)  
- [Node.JS XPath Setup Guide](https://eecs.csuohio.edu/~sschung/CIS593/NodeJSSetupXPathXMLInJS.pdf)  
- [npm Node.JS XPath Setup Guide](https://www.npmjs.com/package/xpath)  
- [Google Crome XPath Helper Setup](https://chrome.google.com/webstore/detail/xpath-helper/hgimnogjllphhhkhlmebbmlgjoejdpjl)
  
#### Python:  

- [Setting Up DOM with XPath for Python](http://docs.python-guide.org/en/latest/scenarios/scrape/)  
- [BeautifulSoup Documentation for HTML, XML for Python](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)  
- [Webscapping with DOM, XPath for Python with BeautifulSoup (From the Stanford Class)](http://web.stanford.edu/~zlotnick/TextAsData/Web_Scraping_with_Beautiful_Soup.html)  
- [Python XPath Guide](https://github.com/helloitsim/InstAnalytics/blob/fdec9d27896f4b6e61acd9dc56134ad556144057/InstAnalytics.py)
  
---

### Automatic Table Creation in a SQL Server:  
  
After installing a SQL server (See the step-by-step installation guides in [CIS430/530 Lab Section](https://eecs.csuohio.edu/~sschung/cis430/CIS430IDS.html#Lab)  
Add the codes in pyodbc as below for a Connection for the Anaconda Python Framework to Connect to Your SQL Database Server  

#### For a connection with SQL Server with server name and database name using pyodbc in Python:  

```
conn = pyodbc.connect('Driver={SQL Server};Server=YOUR_SQL_SERVERNAME\SQLEXPRESS;Database=YOUR_DATABASE_NAME;Trusted_Connection=yes;')  
```

#### pyodbc(Open Database Connectivity) to Connect a MySql Server in Python:  

- [How to Connect to MySql Server with pyodbc in Python](https://docs.devart.com/odbc/mysql/python.htm)  
- [Stackoverflow site for pyodbc: Examples to Connect to MySQL](https://stackoverflow.com/questions/3982174/pyodbc-and-mysql)
  
#### pyodbc(Open Database Connectivity) to Connect MS SQL Server in Python:  
  
- [How to Connect to MS SQL Server in Python](https://docs.devart.com/odbc/sqlserver/python.htm)  
- [How to Connect to MS SQL Server in Python](https://datatofish.com/how-to-connect-python-to-sql-server-using-pyodbc/)  
- [pyodbc: Examples of ODBC in Python](https://stackoverflow.com/questions/33725862/connecting-to-microsoft-sql-server-using-python)  
- [Installation pyodbc to Connect to MS SQL Server in Python](https://docs.microsoft.com/en-us/sql/connect/python/pyodbc/step-1-configure-development-environment-for-pyodbc-python-development?view=sql-server-ver15)  
- [Stackoverflow site for pyodbc to Connect to MS SQL Server in Python](https://docs.microsoft.com/en-us/sql/connect/python/pyodbc/step-3-proof-of-concept-connecting-to-sql-using-pyodbc?view=sql-server-ver15)  
- [Column Data Types to store a Large Text data to Create a Table with in MS SQL Server or other database server](http://www.sqlines.com/oracle/datatypes/clob)
  
#### How to Create a Table in a SQL Server from CSV/TSV Text files  
  
- [How to Create a Table from a File with Bulk Insert with MS SQL Server](https://docs.microsoft.com/en-us/sql/t-sql/statements/bulk-insert-transact-sql?view=sql-server-2017)  
- [How to Create a Table from a file with Bulk Insert in MySQL Server](https://stackoverflow.com/questions/14330314/bulk-insert-in-mysql)  
- [Example of a Script to Create Multiple Tables from different files with Bulk Insert in MS SQL Server](https://eecs.csuohio.edu/~sschung/CIS593/FullBulkImportAWIDSQLServer.sql)
  
#### Earlier Features to Handle Big Data in Relational Database Server  
  
- Advanced Data Types: BLOB (Binary Large Object) or Text/CLOB (Character Large Object) in MySQL or MS SQL Server  

#### How to Create and Insert to a Table with a Column of Large Text Data or Image Data in a Relational Database Server:  

- [Text Data Type in MySQL](https://www.mysqltutorial.org/mysql-text/)  
- [What is TEXT data type in MySQL](https://www.tutorialspoint.com/What-is-TEXT-data-type-in-MySQL)  
- [Difference between blob and clob datatypes](https://www.tutorialspoint.com/what-is-the-difference-between-blob-and-clob-datatypes)  
- [Blob Data type in MySQL](https://dev.mysql.com/doc/refman/8.0/en/blob.html)  
- [how to insert blob and clob from files in mysql](https://stackoverflow.com/questions/10729824/how-to-insert-blob-and-clob-files-in-mysql)  
- [how to insert text column in mysql](https://stackoverflow.com/questions/752277/cannot-insert-string-into-mysql-text-column)  
- [Trouble Shooting Error Resolutions When Set Up SQL Server with ODBC/JDBC](https://eecs.csuohio.edu/~sschung/CIS593/TroubleShootingErrorResolutionsPlatformSetUp.pdf)
  
#### For Those Who Want to Use CLR Table Function to Create a Table in SQL Server -- This is NOT For CIS492/593  

- [How to Set Up ASP.NET with SQL Server](https://eecs.csuohio.edu/~sschung/CIS593/HowtoSETUPUDTASPNET.pdf)  
- [How to Debug CLR UDF, CLR UDT, CLR TVF](https://eecs.csuohio.edu/~sschung/CIS593/HowToDebugSQCLRNOExamples.pdf)  

---
