# Salary-prediction--Amazon-EC2-deployment
Model deployment in to Amazon EC2 interface


1.Created the flask code for our API.
2. Checking the working of the model in our local environment.
3. Login to Amazon cloud account( if new then create and account)
4.Created an EC2 instance (free tier - UBUNTU instance created)
5.Download Putty and the Puttygen can used to generate the Private Key .
6.To transfer our fules from local to Cloud environment we could use "WINSCP" software.
7.The flask code is updated with the port number.
8. Since we are utilizing the free-tier the python and other libraries had to installed manually through putting using the commands 

   sudo apt-get update && sudo apt-get install python3-pip

   pip3 install -r requirements.txt

9. Run the application using the command : python3 app.py
10. get the weburl and verify the prediction model.
