# Welcome to Setup Process!

Hi! Welcome to the **setup** of  **Project Development**. If you want to learn about requirements and how to run it in your local machine , you can read me...! If you want to run, use, fork, clone you can stick with me till the last step. With that being said let's get the setup **started**.


# Pre-requisites 

This project works on Django(python) version may differ the following are basic Pre-requisites to be followed for setting-up the project environment:

- Python -  3.0.1 or higher
- Virtualenv for working on development server
- pip: a python package which will help us to install all dependencies and the requirements
- Django - 3.1.5 or higher

## Creating and Activating Virtual Environment:
To create a virtual environment type the following command in a command prompt and give enter

- Step 1: Install the virtualenv(if you don't have installed). In my case already installed so, for you it will be something like collecting the package and it will be insatlled.
	![My_Image](https://i.imgur.com/AnzvsXg.png)

	>pip install virtualenv

- Step 2: Create a virtual environment
	>python -m venv <name_of_environment> .
	>>**Note**: Replace the `<name_of_environment>` with the name you prefer
	>>**Note**: dot (.) is used to install in the same directory.

	![My_Image](https://i.imgur.com/rvsUNdD.png?1)
	
-  Step 3: Now, let's activate the virtual environment. Navigate to the root directory of the project by using the command :
		
		
			- cd <project root directory>

	

To, activate the virtual environment: 
- windows : 
			
		>env\Scripts\activate

 - Mac/Linux: 
		
		 $ source bin/Scripts/activate

	![My_Image](https://i.imgur.com/sLk3aot.png)

 - step 4:
	  Let's, perform the initial migration of our database. As we know that django comes with a database and by default its SQLite3.
	  

	    python manage.py migrate	
	    
	![My_Image](https://i.imgur.com/9IUsKAf.png)	

## Installing the Requirements:

In the root directory there will be a file named **requirements.txt** which has all the requirements.
To, install all the requirements run this command:

    pip -r requirements.txt
    
This, will Install all the requirements including django and all other requirements. 

## Run the server:
To, run the server on localhost run this command which is common for all the OS:

    (project-dev) D:\AAdityAA\Root_project_directory>python manage.py runserver

>**Note:** Make sure  that the virtual environment name is present inside the brackets which indicates that you are inside inside the virtual environment.

![My_image](https://i.imgur.com/9ls6Fak.png)


This, indicates that the installation is done properly and you are good to go.....!!!

Happy Coding...!!!!
