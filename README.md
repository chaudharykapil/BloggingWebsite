# BloggingWebsite
# Requirement
> Python 3.x<br>
> flask module<br>
> SQLAlchemy module<br>
> MySQL<br>
# Steps to follow:
## You need to follow the step (1-7) only once. If you allready done that you can go to step 8 directly
## Step 1: 
Extractr the rar file
## step 2: 
Open the "final_blog" folder
## step 3: 
Inside "final_blog" folder open init.py file
## step 4: 
In line no. 9 and 10 change<br> DATABASE_NAME = your mysql root name and DATABASE_PASS = your mysql password
## step 5: 
Inside same folder open mysql command line and create database named "final_blog" by 
executing command in mysql command line: "create database final_blog;" and close the command line
## step: 6: 
Inside same folder open cmd and type "python" in cmd
## step 7: 
Inside cmd type: <br>
import init (enter)<br>
init.db.create_all() (enter)<br>
exit()<br>
and close the command line
## step 8: 
Reopen cmd in same folder and type "python init.py" (Don't clode the cmd your website is running)
## step 9: 
Open chrome and type "http://127.0.0.1:5000/"
### Congratulation your website is running
