This project was made in a python virtualenv so that all dependencies would hopefully be contained in this directy when it is uploaded to github. The steps included in the GROUPS documentation file is as if you were goign to install everything from the ground up.

THIS FILE will include a simple documentation setup presuming you just pulled this repo from git 

these instructions will be the instructions to get the server up and running and to connect to the site to confirm outside sources can connect and see the random#


presuming pip and git are installed on your VM

we will clone the repo  and then cd into the directory

run the command source env/bin/activate to actiavet the virtualenvironment already present in the directory 

for some reason its not auto installing the requirments like it initially was for me when I would clone the repo but since we have pip installed we will run the command sudo pip install flask just to make sure it is infact installed otherwise the file will say flask doesnt exist.

once flask is installed that should be all.

run the command sudo python server.py you should see something like this 


* Serving Flask app "server" (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: off
 * Running on http://0.0.0.0:80/ (Press CTRL+C to quit)
 
 
 
 without doing anything else in the command line go to a web browser and use HTTP not HTTPS to connect to the external IP of the GCP VM
 example http://34.69.126.180 is what i type in to get to the site that is being ran by my VM. I will leave that server running so that link should work to demonstrate our site is working just incase there are some sort of errors in the instructions to prove we infact did the project correctly.
 
 you should be able to connect to the site you just started with the last command if you set everything up correctly.
