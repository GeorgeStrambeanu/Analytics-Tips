-- Link for Oracle DB 21c XE download and install guide
-- https://www.oracle.com/database/technologies/appdev/xe.html

-- Link to download Oracle SQL Developer
-- https://www.oracle.com/database/sqldeveloper/technologies/download/

-- Link for GitHub
-- https://github.com/GeorgeStrambeanu/Analytics-Tips/tree/Oracle-DB-21c-XE


-- Finding ORACLE HOME directory
-- (1) Start SQL Plus and login as sysdba. Enter in the user name prompt the below code:
/ as sysdba
-- (2) Run the below comments to see what is the path to ORACLE HOME
var OHM varchar2(200);
EXEC dbms_system.get_env('ORACLE_HOME', :OHM);
PRINT OHM


-- Check the Listner
-- Open Command Prompt and type
lnsrctl status 
-- After this statement you should be able to see the service details


