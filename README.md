# PickJiraItems
[![PickJiraItems on fuget.org](https://www.fuget.org/packages/PickJiraItems/badge.svg)](https://www.fuget.org/packages/PickJiraItems)

1.  jira routines based on REST API
2.   Returns a list of JIRA, users, groups, name, emailadress matching a specific string
3.   //Kind of regex matching and grep search  JIRA users & groups 
4. Based on REST API JIRA
 
3. is used with C# code 

 https://github.com/guihen01/Pick-Jira-Items/blob/main/How%20TO/Solution%20view.PNG

![alt text](https://github.com/guihen01/Pick-Jira-Items/blob/main/How%20TO/Solution%20view.PNG "Logo Title Text 1")

# Publication

Package distributed as a nuget package at :  https://www.nuget.org/packages/PickJiraItems/

# Dependency 


. Packages referenced in the Library 

![alt text](https://github.com/guihen01/Pick-Jira-Items/blob/main/How%20TO/Dependency%20.GIF "Logo Title Text 1")


# How to use

1. Download the nuget package at : https://www.nuget.org/packages/PickJiraItems/
2. using PickJiraItems in your project, reference this package; in your project, (package name : PickJiraItems)
3. using Newtonsoft.Json; in your project, reference this package
4. in your C# project , use the routine PickItems()
5. using System.Threading.Tasks; Routines are async methods and need the use of await and async Task declaration instruction
6. 

![alt text](https://github.com/guihen01/Pick-Jira-Items/blob/main/How%20TO/Capture%20HowtoUSe.PNG "Logo Title Text 1")

See How to use it , in : https://github.com/guihen01/Pick-Jira-Items/tree/main/How%20TO

routines are async . so use await instruction for some routines 

routine will be included in a .DLL library soon. So all that will be needed is to include the library in your code ( in visual studio code, make a reference to this library in your project, and for this,  use nuget package manager to include the library nuget package) 

see Jiralib.dll in https://github.com/guihen01/RestApi-JIRA-Lib  


# Download
1. Download the nuget package at : https://www.nuget.org/packages/PickJiraItems/

# Results 

1. json formated file : List-items.json  (https://github.com/guihen01/Pick-Jira-Items/blob/main/How%20TO/List-items.json )

2. text formated file : List-items.txt  (https://github.com/guihen01/Pick-Jira-Items/blob/main/How%20TO/List-items.txt)

![alt text](https://github.com/guihen01/Pick-Jira-Items/blob/main/How%20TO/Snapshot-2.PNG  "Logo Title Text 1")


# Verify

1. results can be veryfied with the Postman tool (https://www.postman.com/) 
2. and of course with Jira itself ( need to be jira administrator and to go to jira administration panel). 

https://github.com/guihen01/Pick-Jira-Items/blob/main/How%20TO/Verify%20with%20Postman.pdf

See : 

![alt text](https://github.com/guihen01/Pick-Jira-Items/blob/main/How%20TO/Capture%20postman.PNG "Logo Title Text 1")

