## DBA Commands  

<br>  


```sql

CREATE USER PROD1 IDENTIFIED BY password;
CREATE USER PROD2 IDENTIFIED BY password;
CREATE USER PROD3 IDENTIFIED BY password;
CREATE USER PROD4 IDENTIFIED BY password;
CREATE USER PROD5 IDENTIFIED BY password;
CREATE USER PREPROD1 IDENTIFIED BY password;
CREATE USER PREPROD2 IDENTIFIED BY password;
CREATE USER PREPROD3 IDENTIFIED BY password;
CREATE USER PREPROD4 IDENTIFIED BY password;
CREATE USER PREPROD5 IDENTIFIED BY password;
CREATE USER TEST1 IDENTIFIED BY password;
CREATE USER TEST2 IDENTIFIED BY password;
CREATE USER TEST3 IDENTIFIED BY password;
CREATE USER TEST4 IDENTIFIED BY password;
CREATE USER TEST5 IDENTIFIED BY password;  

GRANT CREATE SESSION TO PROD1;
GRANT CREATE SESSION TO PROD2;
GRANT CREATE SESSION TO PROD3;
GRANT CREATE SESSION TO PROD4;
GRANT CREATE SESSION TO PROD5;
GRANT CREATE SESSION TO PREPROD1;
GRANT CREATE SESSION TO PREPROD2;
GRANT CREATE SESSION TO PREPROD3;
GRANT CREATE SESSION TO PREPROD4;
GRANT CREATE SESSION TO PREPROD5;
GRANT CREATE SESSION TO TEST1;
GRANT CREATE SESSION TO TEST2;
GRANT CREATE SESSION TO TEST3;
GRANT CREATE SESSION TO TEST4;
GRANT CREATE SESSION TO TEST5;

GRANT all privileges TO PROD1;
GRANT all privileges TO PROD2;
GRANT all privileges TO PROD3;
GRANT all privileges TO PROD4;
GRANT all privileges TO PROD5;
GRANT all privileges TO PREPROD1;
GRANT all privileges TO PREPROD2;
GRANT all privileges TO PREPROD3;
GRANT all privileges TO PREPROD4;
GRANT all privileges TO PREPROD5;
GRANT all privileges TO TEST1;
GRANT all privileges TO TEST2;
GRANT all privileges TO TEST3;
GRANT all privileges TO TEST4;
GRANT all privileges TO TEST5;

SELECT DIRECTORY_NAME , DIRECTORY_PATH FROM DBA_DIRECTORIES;
GRANT ALL ON DIRECTORY LOGS TO TEST1;
GRANT EXECUTE ON UTL_FILE to TEST1;
SELECT * FROM all_tab_privs WHERE table_name = 'UTL_FILE';

```



