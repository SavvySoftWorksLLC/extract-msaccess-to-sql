### Extract MSAccess to SQL
MSACCESS to SQL for OSX/macOS :)

##### Finally its easy and works for OSX
In my line of work I often have to use archaic MSAccess databases. So here is my toolchain to make that easy

##### Setup
- Make sure you have python
- Install mdbtools $`brew install mdbtools`

##### For MYSQL
- Extract MSAccess DB $`MDB_JET3_CHARSET="cp1255" python access_dump.py database.mdb kern > database.sql`
- Import sql $`mysql -uroot -proot database < database.sql`


`#yourWelcome`
