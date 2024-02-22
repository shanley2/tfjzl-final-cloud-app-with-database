
**General Notes**

An `onlinecourse` app has already been provided in this repo upon which you will be adding a new assesement feature.

- If you want to develop the final project on Theia hosted by [IBM Developer Skills Network](https://labs.cognitiveclass.ai/), you will need to create the same project structure on Theia workspace and save it everytime you close the browser
- Or you could develop the final project locally by setting up your own Python runtime and IDE
- Hints for the final project are left on source code files
- You may choose any cloud platform for deployment (default is IBM Cloud Foundry)
- Depends on your deployment, you may choose any SQL database Django supported such as SQLite3, PostgreSQL, and MySQL (default is SQLite3)

**ER Diagram**
For your reference, we have prepared the ER diagram design for the new assesement feature.

![Onlinecourse ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)



To run:

Clone to local machine

Set up the virtual environment to contain necessary packages:

- pip install --upgrade distro-info
- pip3 install --upgrade pip==23.2.1
- pip install virtualenv
- virtualenv djangoenv
- source djangoenv/bin/activate

Set up Python runtime and test the template project
- pip install -U -r requirements.txt

Set up migrations
- python3 manage.py makemigrations
- python3 manage.py migrate
Set up migrations
- python3 manage.py makemigrations
- python3 manage.py migrate

Set up migrations
- python3 manage.py makemigrations onlinecourse
- python3 manage.py migrate
