# employee-manager-System

The purpose of this application is to allow users to dynamically update, and manage their business. It utilizes the power of the mysql node module to use javascript to update our mySQL database and view our insertions using console.table.


# Install

git clone repo 
cd employee-manager-system
npm i

Create a new file called .env that will store your MySQL server information:

touch .env
Format the contents of .env as follows, substituting your MySQL server information where applicable:

DB_HOST=localhost
DB_PORT=3306
DB_USER=username
DB_PASS=password

Import the database schema and optional demo data:

#login to mysql
mysql -u username -p

#import the required schema
source schema.sql

#import the optional demo data
source seeds.sql

# start 

node index.js

# demonstration

![preview](https://user-images.githubusercontent.com/74078719/111413844-3d83cc80-869c-11eb-9577-59f19045178b.gif)

<img width="784" alt="dbschema" src="https://user-images.githubusercontent.com/74078719/111414032-89cf0c80-869c-11eb-850a-4af66224c9ad.png">
