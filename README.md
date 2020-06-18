# Case Study: Oracle Applications

Developing a GUI for online banking using Oracle Forms Builder 10g, Oracle Database 10g and Oracle EBS (E-Business Suite)

    1. SQLScript.sql: SQL script for table creation 
    2. Forms Folder: contains the Oracle Forms (.fmb files) with implementation of required GUI
    3. plsql_trigger_func.pdf : PDF file with detailed listing of the pages and the trigger functionalities implemented
    

## Requirements for Design & Development of the UI pages:

    1. Customers should be able to open the account online.
    2. They can also register for Online banking and avail the e-banking services.
    3. Interest Calculator to be provided for Interest Calculations.
    4. Generate a Statement for User Transactions.
    5. Create separate login pages for Users and Managers.
  
## Instructions:

- Source form (. fmb) needs to be compiled into a platform-specific "executable" (. fmx), that is run (interpreted) by the forms runtime module.
    
- WinSCP and PuTTY have been used for interaction with server:     

        WINSCP: For adding the .fmb files to the server (file transfer)
        PuTTY: For creating .fmx files 
        
- Finally, create Menu and define Responsibility in the Oracle Applications prior to running the forms to get the GUI
