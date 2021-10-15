# Face-Login System 

This is a web based facial log in/ Sign up website which uses Facial recognition for user authentication and this can be integrated with various websites or web applications.

   This Project is based on [**FaceNet**](https://arxiv.org/abs/1503.03832) deep learning model and uses [**Flask**](https://palletsprojects.com/p/flask/) server for running the [**Keras**](https://www.tensorflow.org/api_docs/python/tf/keras) neural network model, and [**MongoDB**](https://www.mongodb.com/) used as database.
   
   
## Setting up Tools and Libraries
  * [Install Python](https://realpython.com/installing-python/)
  * set up  [Mongodb Atlas](https://www.knowi.com/blog/getting-started-with-mongodb-atlas-overview-and-tutorial/) / [Install and configure MongoDB](https://medium.com/@LondonAppBrewery/how-to-download-install-mongodb-on-windows-4ee4b3493514)


#### Clone this repository and open in text editor ( vs code prefered )  
create separate [**Virtual Python Environment**](https://developer.akamai.com/blog/2017/06/21/how-building-virtual-python-environment) for this project and install required ibraries

  
  #### Install Dependencies 
    pip install requirements.txt 
this will install all required packages.

Now open **app.py** file and input your flask **app.secret_key** (random binary string) and  unique  **MongoURI** to connect to database 

then open Command Prompt and run 

    python wsgi.py
or
    
    run 
  
 this will run your project on localhost:5000  
 #### Now go to your browser and load http://localhost:5000/ 
 ##### That’s it, You have successfully run this project on your machine.
   <br>
   <br>
   <br>
 
 
 **------------------------------------------------- Screenshots ----------------------------------------------------------------**
 

 ## Home Page
   <p float="left">
      <img src="https://user-images.githubusercontent.com/58581435/137475340-3b2acb58-769c-4ce7-b7a6-de13c31a99ed.PNG" width="100%" />
   </p>  
   <br>   
   
 ## Sign Up Page
   <p float="left">
      <img src="https://user-images.githubusercontent.com/58581435/137475379-d994faab-101b-41d4-9041-9dd81fe0af1f.PNG" width="45%" />
      <img src="https://user-images.githubusercontent.com/58581435/137475389-441c1c69-1335-4372-a102-5d3e82a798a3.PNG" width="45%" /> 
   </p> 
   <br>   
   
 ## Login Page (face varification)
   <img src="https://user-images.githubusercontent.com/58581435/137475349-1eade5bc-5299-4f05-ac0d-1b9874451339.PNG"/>
   <p float="left">
      <img src="https://user-images.githubusercontent.com/58581435/137475359-a4eb287d-1617-46e8-b73b-cae74a23952d.PNG" width="45%" /> 
      <img src="https://user-images.githubusercontent.com/58581435/137475364-76b1c56e-bb4a-42e3-8a47-ac9ae7c1b569.PNG" width="45%" /> 
   </p>
   <br>   
   
 ## Login-Recog Page (face recognition)
 ![login-recog page-1](https://user-images.githubusercontent.com/58581435/137475372-bb3853df-de5f-460a-a3bb-586dd9b4dcc1.PNG)
   <br> 
 
 ## Dashboard
 ![dashboard page-1](https://user-images.githubusercontent.com/58581435/137475403-4557012f-009b-4b00-89d7-46b6b9e54162.PNG)
   <br> 
 
 ## User Authentication
  <p float="left">
   <img src="https://user-images.githubusercontent.com/58581435/137475416-a175f9fe-edbe-4396-9d0b-6c2ff8600849.PNG" width="45%" />
   <img src="https://user-images.githubusercontent.com/58581435/137475419-62231b36-cf43-4fc8-b3bc-1f8897a6e9ad.PNG" width="45%" /> 
  </p>
  <p float="left">
   <img src="https://user-images.githubusercontent.com/58581435/137475428-a97c6623-d45b-4124-acb6-f25bb4f92c32.PNG" width="45%" />
   <img src="https://user-images.githubusercontent.com/58581435/137475435-1ee1df72-1a0c-4a8a-b201-0534f1a32856.PNG" width="45%" />    
  </p>  
   <br>
