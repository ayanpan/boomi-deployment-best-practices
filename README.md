# Boomi Best Practices - Deployment
Below are some of the best practces which can be followed while deploying a Process or other component in Boomi iPaaS.

:point_right: Specify the Version of the initially created Package as 1.0

:point_right: For the packages created subsequently, specify the Package Version as 1.1, 1.2, and so on, if there are minor changes in the mapping/logic.

:point_right: If there's a major change in the mapping/logic of a Process, then specify the Package Version as 2.0, 3.0, and so on.

:point_right: Always put Notes while creating a new Package. The naming convention could be in the format - <Jira-Story/Ticket/CR Number>: <One-liner description>. For example, BOOMI-101: Added the required new fields in the Salesforce SOQL Query and added the required mapping in the "Map: Salesforce to NetSuite Case Upsert" Map shape.

:point_right: Always put Deployment Notes while deploying a Package in an Environment. The naming convention could be in the format, ideally same as the Package Notes - <Jira-Story/Ticket/CR Number>: <One-liner description>. For example, BOOMI-101: Added the required new fields in the Salesforce SOQL Query and added the required mapping in the "Map: Salesforce to NetSuite Case Upsert" Map shape.

:point_right: While deploying a Package in Production, the naming convention should be in the format - <Change Request Number>: <Jira-Story/Ticket/CR Number>: <One-liner description>. For example, CHG10010101: BOOMI-101: Added the required new fields in the Salesforce SOQL Query and added the required mapping in the "Map: Salesforce to NetSuite Case Upsert" Map shape.
