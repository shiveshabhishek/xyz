This folder contains 2 python scripts:
**add_plan.py** :This script takes arguments (username,password and build number) and reads the file created by `bootstrapper_init` to get the suite ids and with these, it hits TestRail's API and creates a test plan with YYYY-MM-DD-build-BUILD_NO. 
**testrail.py** : Helps in making GET and POST requests to TestRail.
