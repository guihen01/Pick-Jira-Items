# Pick-Jira-Items

1.  jira routines based on REST API
2. Returns a list of JIRA, users, groups, name, emailadress matching a specific string
            //Kind of regex matching and grep search  JIRA users & groups 
Based on REST API JIRA
 
3. is used with C# code 

 

![alt text](https://github.com/guihen01/RestApi-JIRA-Lib/blob/main/Library%20view%20v1.2.0.PNG "Logo Title Text 1")

# Publication

Package distributed as a nuget package at : https://www.nuget.org/packages/RestAPI-JIRA-Lib/

Is distributed as a .DLL library file

# How to use

in your C# project , do a reference in your project to this DLL   using JiraLib;

using JiraLib;

![alt text](https://github.com/guihen01/RestApi-JIRA-Lib/blob/main/Get%20Users%20From%20Group/Screenshots/Capture%20How%20to%20use.PNG "Logo Title Text 1")

See How to use it , in : https://github.com/guihen01/RestApi-JIRA-Lib/tree/main/Get-All-Jira-Groups

Also in : https://github.com/guihen01/RestApi-JIRA-Lib/blob/main/Get%20Users%20From%20Group/Screenshots/Capture%20How%20to%20use.PNG

routines are async . so use await instruction for some routines 

# Download
1. Download the nuget package at : https://www.nuget.org/packages/RestAPI-JIRA-Lib/

OR

2. Download the .DLL and others items at https://github.com/guihen01/RestApi-JIRA-Lib/releases/
 
# Routines inside the Library : 
1. GetAllGroups
2. GetUSersFromGroup
3. Post1
4. ConverJsontoString
