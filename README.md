# NoSQL
This project demonstrates the creation of a data platform using MongoDB as the NoSQL database for an e-commerce company that will store the catalog data from a JSON file and further export it to a CSV file.

The project is viewable via code snippets and screenshots in the images folder, and I will explain each image and what is going on below.

In this project I created a database in MongoDB titled 'catalog' where I can store JSON files with information about the company's available catalog. I have taken a JSON file with 400+ rows of electronics and imported it into a collection in the database (respectfully titled 'electronics'). The file can be found in the data folder and the image "mongoimport.jpg" shows the CLI command for the creation of the database and the importing of the file. 

In the images "mongo-query{1,2,3}.jpg", I ran a few queries on the collection to understand some aspects of the data, and finally in "mongoexport.jpg" I exported some base features of the rows of data, such as 'type' and 'model', into a CSV file for use in a relational database if needed. 
