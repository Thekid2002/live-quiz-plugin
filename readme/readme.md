
This guide requires docker desktop to be installed \
After installation make sure it is open and working \

Go into this directory with a terminal and run the following command:

```bash
docker-compose up
```

After this two containers should be running
<img src="dockerDesktop.28.16.png">

\
\


Then go to link : http://localhost/moodle/index.php \
and you should se the following:
<img src="installation.25.28.png">
Then click next and you should see the following:
<img src="clickNext.30.17.png">
Then click next and you should see the following:
<img src="selectPostgres.30.52.png">
Select postgres and click next and you should see the following:
<img src="databaseValues.32.26.png">
input the following values:
```
Database host: moodle-postgres-db
Database port: 5432
Database name: moodle
Database user: postgres
Database password: mysecretpassword
Tables prefix: mdl_
Unix-Socket: should be empty
```
More setup will follow but will be dependent on need
