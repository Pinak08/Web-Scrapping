# Web-Scrapping

What does this Application do?
This Program takes input as Email ID of the User and names of TV series.
The main aim of this program is to send user an email consisting of information regarding when the next episode of these TV series will be aired or the series is finished.

How to use this Program?
1. Please verify these points before executing the code.
Make sure your system is installed with Mysql and mysqldb python.
SMTPLIB should be installed in your system.
Your Gmail should allow third party apps(Less secure apps) to send mails.
Check this here - Click here to check. If it is off, then unblock it.
You must be connected to the Internate.
2. Download the main.py file
3. Changes need to be made before running this program
In Line no. 133 - Enter the hostname, user and password of mysql database.
(Default values : host="localhost",user="root",passwd="1111").
In Line no. 167 and 168 - Enter Sender's Email address and Password in specified format.
(Default ID-password will work fine : my fake ID-password).
4. Run python3 main.py in the terminal(After going to specific directory)
You have to give the required input in the terminal, such as your email address and TV series you watch.
Then you will receive a mail containing all the information about that TV series(Example Shown below).

DATABASE Info:
DATABASE Name - SERIES_DATABASE_1
Table Name - userdata
Tables columns - {email, tvseries}
