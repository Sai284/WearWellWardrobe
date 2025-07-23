# WearWellWardrobe

Main Program built for JH03 Joint Honours project.

## Stack

Backend (Django):

 - Python
 - Html
 - CSS
 - JavaScript

Frontend (React):

 - JSX 
 - CSS 
 - API 

## Participants

- [Alvaro Martinez Gutierrez](mailto:2775841M@student.gla.ac.uk) - 2775841M
- [Andrew King](mailto:2768771K@student.gla.ac.uk) - 2768771K
- [Layla Clark](mailto:2746942C@student.gla.ac.uk) - 2746942C
- [Madison Horvath](mailto:2620460H@student.gla.ac.uk) - 2620460H
- [Matthew Cole](mailto:2753620C@student.gla.ac.uk) - 2753620C
- [Sai Polukonda](mailto:2788662P@student.gla.ac.uk) - 2788662P


## Coach

- [Raaed Sattar](mailto:2794041S@student.gla.ac.uk) - 2794041S



# Setup
To run locally, you must first set up the database backend, then run the react side. To run on the PythonAnywhere site, you only need to setup the frontend, as this will fetch data from the database automatically.

## Backend Setup (Django)
To get the Django backend running locally, follow these steps:

#### Step 1 - Create and activate a virtual environment
Open your terminal (Windows Command Center or PowerShell) and create and run a virtual enviornment. Ensure that it is running  python 3.7
Once your Virual enviroment is working and you are inside the project folder, run:

pip install -r requirments.txt

to install all the required dependencies 


#### Step 2 - Navigate to ProjectSite
Run the following commands to set up your database:

python manage.py makemigrations  
python manage.py migrate
python populate.py
python manage.py runserver


## Frontend Setup (React)

#### Step 1 - Navigate to ReactSide
Navigate to the directory where your React app is located, probably ReactSide.

#### Step 2 - Install Vite
Run the command:
npm install vite --save-dev

#### Step 3 - Run development server
Run the command:
npm run dev

# User Guide

## Django Website
The purpose of the Django site is to allow for modification of the app content. To login, you must have a pre-made account. Logged in users can create new accounts for other admins to be added to the site. This can be done in the help section, found at the top right of the page.

This website shows all the pages that exist within the app. For each page, it shows the page category, title and content. These can be edited by clicking the paintbrush icon on the right hand side, which will take you to an editing page. Any changes made here will update dynamically in the app.

Some pages are deletable and will be removed from the app if the bin icon next to the page is clicked.

The names of the categories can be edited by clicking on the category in the top bar. To add a new page to the app, the 'add page' button will take you to a creation page where you must specify the category, title and content of the new page. The notes for the page will not display on the app, this is for you to keep track of pages and make comments.


## React App
To navigate the app from the home screen, you can click on each section to visit the associated page. This allows you to read about the information you are looking for on sustainable clothing and follow further links to important sites. To navigate back to the homepage, you can click on the man icon at the top of the screen. You can also visit the main category pages through the burger icon at the top left.

To view the flowchart feature of the app, which exists for disposal and access, you can click on the unsure subpage of these categories. This will take you through a series of questions and will then link you to a sub-page that suits your needs.

# Releases

The repository uses the main branch for our current working version of the app. Local branches are merged into dev-branch then main.


# License

Copyright 2025 JH03 - Alvaro Martinez Gutierrez, Andrew King, Layla Clark, Madison Horvath, Matthew Cole, Sai Polukonda

Licensed under the MIT License (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

       https://opensource.org/licenses/MIT

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
