# Backend Setup #

### To set up the backend for this project, follow the steps below: ###

#### Download [PostgreSQL](https://postgresapp.com/downloads.html) from the official website and install it on your local machine. ####


#### Download the [SQL file](https://drive.google.com/file/d/1faVucEwm3QMGFJknN9jKyF3xT5fqoUiK/view) for the Project. ####

#### After downloading the SQL file, navigate to the directory where it was saved using your terminal. ####

#### In the terminal, enter the following command to start PSQL:  `psql` ####

#### Create a new database named `dvproject` by entering the following command: `CREATE DATABASE dvproject;` ####

#### Connect to the newly created database by entering the following command: `\c dvproject;` ####

#### Execute the following command to load the data from the SQL file into the database: `\i database_backup.sql` ####

#### Restart your terminal and enter the following commands to view all the tables in the `dvproject` database: ####
`psql`
`\c dvproject` 
`\dt` 

#### Navigate to the `Backend` folder and then `server` folder. ####
#### Open the `__init__.py` file and modify `line number 30` to match your `PostgreSQL username`. ####

#### Create a `virtual environment` for the project by entering the following commands: ####
`pip3 install virtualenv`
`virtualenv env`
`source env/bin/activate`
#### Download all the prerequisites for Backend by following command:####
`pip install -r requirements.txt`
#### Finally, run the backend server by entering the following command: ####
`python3 __init__.py`

#### Keep this terminal open and open a new terminal to run Frontend ####

# Frontend Setup #

#### To run the front end of this project, make sure that you have [Node.js](https://nodejs.org/en/download) installed on your local machine. ####
#### Navigate to the `Frontend` folder ####
#### Install all the requirements for Frontend by the following command: ####
`npm install`
#### To start the Frontend, write following command: ####
`npm start`