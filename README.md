This project was made in a python virtualenv so that all dependencies would hopefully be contained in this directy when it is uploaded to github. The steps included in the documentation are as if you were goign to install everything from the ground up.

I will include a simple documentation setup here in this read me presuming you just pulled this repo from git these will be the instructions to get the server up and running and to connect to the site to confirm outside sources can connect and see the random#


presuming pip and git are installed. 

we will cloen the repo cd into the directory

run the command source env/bin/activate

for some reason its not auto installing the requirments like it initially was for me when I cloned the repo and went activated the virualenvironment but since we have pip installed we will run the command sudo pip install flask

once flask is installed that should be all.

now run the command sudo python server.py you should see something like this 

* Serving Flask app "server" (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: off
 * Running on http://0.0.0.0:80/ (Press CTRL+C to quit)
 
 without doing anything more in the commandline go to a web browser and use HTTP not HTTPS to connect to the external IP of the VM
 example http://34.69.126.180 is what i type in to get to the site. I will leave that server running that site so that link should work to demonstrate our site is working.
 
 you should connect to the site if you set everything up correctly 
