db
==

8:58pm, 12/9/2012

this db needs to be imported to mysql


it might be too big to run with the gui tool that xampp provides

so run it in the command line, you can add c:\xampp\mysql\bin to your environment path or just run
the following command in that path:

$ mysql -u root -p -h localhost test_db < test_db.sql

root is the default  username, unless u created a admin username

localhost is used for ur local machine so leave that

and test_db is the db name that you will create

it will prompt u for a password, so the line above is assumming you don't have a password
when u get prompted for the password just press enter and be patient, it takes a little bit


anthony successfully imported the db and has no issues