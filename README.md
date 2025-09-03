# RPA-Project
Robotic Process Automation (RPA) is a Year 2 Module in TP.  It introduces students to the techniques of using an automation tool to automate tasks within a business process. It touches on the various use cases of RPA and provides a platform for students to creatively apply the concepts. It also discusses the challenges and limitations of RPA


## What does my RPA Project do?
[Read through my 'Presentation' Slides for a better understanding]

**1. Automated Data Handling**
- Pull data from MySQL.
- Clean it (remove special characters via Regex).
- Segment into buyers, non-buyers, and incomplete records → store in Excel.

**2. Automated Personalized Communication**
- Use Outlook to send customized emails to buyers & non-buyers (based on Excel).
- Reduce human effort, ensure consistency.

**3. Resilient Error-Handled Workflow**
- Retry loops + Try/Catch for database and email failures.
- Handles exceptions like SQLException, TimeOutException.

**4. Analytics Integration with Google Cloud**
- Authenticate with JWT & OAuth2.
- Connect to Google Analytics API v4.
- Retrieve customer session data by country.
- Save results automatically for reporting.
