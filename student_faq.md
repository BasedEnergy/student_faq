# Student FAQ

This FAQ is intended to answer many common questions asked by students of this course.

If you think of other potential questions to add, please let us know! We are always looking for more feedback. 

## Table of Contents

[Unit 01 - Excel](#Unit-01:-excel) <br>
[Unit 02 - VBA Scripting](#Unit-02:-vba-scripting) <br>
[Unit 03 - Python](#Unit-03:-python) <br>
[Unit 04 - Pandas](#Unit-02:-pandas) <br>
[Unit 05 - Matplotlib](#Unit-02:-matplotlib) <br>
[Unit 06 - Python APIs](#Unit-02:-python-apis) <br>
[Unit 07 - Project 1](#Unit-07:-project-1) <br>
[Unit 09 - SQL](#Unit-09:-sql) <br>
[Unit 10 - Advanced Data Storage and Retrieval](#Unit-10:-advanced-data-storage-and-retrieval) <br>
[Unit 11 - Web](#Unit-11:-web) <br>
[Unit 12 - Web Scraping and Document Databases](#Unit-12:-web-scraping-and-document-databases) <br>
[Unit 13 - ETL Project](#Unit-13:-etl-project) <br>
[Unit 14 - Intro to Javascript](#Unit-14:-intro-to-javascript) <br>
[Unit 15 - Interactive Visualizations and Dashboards](#Unit-15:-interactive-visualizations-and-dashboards) <br>
[Unit 16 - D3](#Unit-02:-d3) <br> 
[Unit 17 - GeoJSON and Leaflet](#Unit-17:-geojson-and-leaflet) <br>
[Unit 18 - R](#Unit-18:-r) <br>
[Unit 20 - Tableau](#Unit-20:-tableau) <br>
[Unit 21 - Machine Learning](#Unit-02:-machine-learning) <br>
[Unit 22 - Big Data](#Unit-22:-big-data) 

## Unit 01: Excel
#### What's the relevance of Excel?
- Many companies still use Excel in their day to day operations and expect new employees to be comfortable with the software. 
- We want everyone to start off on the same footing, later in class we will be diving even deeper into data software. VBA will be starting next week, and having a good foundation in Excel will make it easier for everyone.
---
## Unit 02: VBA Scripting
#### What's the relevance of VBA?
- This is an introduction into the basics of programming that will be relevant later in the course, and also a great way to automate the data manipulation that we do in excel.
- This software is prevalent in many older companies and in the financial industry. Many companies will want you to be able to manipulate Excel with VBA.
---
## Unit 03: Python
#### What's up with this crazy indentation?
- With Python, indentation is more than just organization and readability. Python's functionality actually depends on proper indentation!
- In this snippet, we're using indentation to tell our code where our for loops begin and end. In Python, indenting creates blocks of code that work together. Similarly, indenting backwards tells the program when to end a loop.
```python
for x in range(10):
    print(x)

for x in range(20, 30):
    print(x)
```
- The code you will write in Python will be seen by someone else. Focusing on organization is important because you want colleagues to be able to read your code. If the code is poorly organized it will be difficult to read later on.

---
## Unit 04: Pandas
#### When should we use Pandas versus just using Python?
- Python is a scripting language, while Pandas is a library that works on top of Python and makes data manipulation easier.
-  Libraries are pre-written chunks of code that make it easier to unlock the capabilities of a programming language. Someone else already did a ton of hard work to create these libraries and make your lives easier and your workflow more efficient.
- It would be a slog to manually go through all of your data with vanilla Python. Pandas makes this process much quicker.
- It's like using Excel vs using VBA with Excel.
---
## Unit 05: Matplotlib
#### I'm having trouble picking up on this new syntax...
- Luckily, there is a library for that! Whenever we work with a library, we are using code that is already pre-written. We always need to reference the documentation when using a new library. Without looking at the instructions, you will never know how to use this piece of technology. 
- We recognize this may be your first time looking at a library that is less semantic, but this will be a constant for the future. You will see a lot of new technology throughout the course, and each time you will need to dive into the documentation. The docs will be different for each new technology.
#### What is the difference between plot() and subplot()
- 
---
## Unit 06: Python APIs
#### How do I differentiate between the client and the server? 
- The web applications we build in class (and all other web apps) will live on a server, which is basically a gigantic computer or network of computers. When a user goes into their browser and types in an address, the server sends information to the user's computer, or the client.
- Basically: Clients request from the server, and the server returns a response. 

#### Where can I find more information on how to use these APIs?
- Each API is a pre-written set of code that helps you interact with somebody elses information. Every API will come with its own set of documentation, and much like with a library, you will have to dive into it! There should be a developer section on each site that will explain the service and any potential limitations.
- Any time we work with an API, it's a good idea to have the documentation ready and refer to it frequently. This is all part of the process when it comes to picking up and familiarizing yourself with new technologies. 

---
## Unit 07: Project 1
#### I'm not feeling confident with Git... What are some resources that could help?
- 
#### Why are we doing this project?
- Each project that we tackle in this class serves multiple purposes, and they will all be highly critical in your development as a data analyst. First, group projects allow you to start developing a collaborative workflow that is very similar to the workflow you would encounter at many jobs in the field. Good teamwork is an essential real-world skill. Working in a group also allows you to accomplish more and create more impressive projects than you would be able to alone! Take advantage of it!
- This project will be your first opportunity to build a data presentation from the ground up. This is something you will do many times as a data scientist, so the more you practice and reinforce these skills, the better off you will be in the field!
- Finally, this project is going to be featured in your resume and portfolio. Having strong examples of your work in your professional materials increases the chances to wow a potential employer and ultimately get hired!
---
## Unit 09: SQL
#### What's the relevance of PostgreSQL?
- PostgreSQL, or Postgres, is a really cool free, open-source object-relational database management system. Databases are going to be crucial in our work as data scientists! 
- Remember how we discussed the relationship between client and server earlier? We can think of our database as the third part of that relationship. Essentially, the client sends a request to the server, the server grabs the associated data from the database, and then the retrieved data is returned to the client by the server. 
#### But what does SQL mean?
- SQL stands for structured query language. Put simply, SQL is the language that we use to interact with our database. SQL is the most widely used database laguage, is incredibly effective at manipulating data, and is one of the easier languages to learn! Learning SQL is also great for employability - There are thousands of jobs that look for candidates with SQL experience!
---
## Unit 10: Advanced Data Storage and Retrieval
#### What is SQLite and why use it?
- SQLite is a dialect for using an SQL database. The syntax is very similary to the PostgreSQL syntax, with the main difference between the two being that SQLite is entirely serverless. SQlite is not comparable with PostgreSQL or any other SQL language, rather it focuses on providing local data storage for individual applications.
#### What does ORM mean?
- ORM stands for Object-Relational-Mapper. Obect-relational-mapping allows us to write SQL queries using the object-oriented paradigm of the language you prefer to work with. In other words, it allows us to interact with our database using our language of choice (which in our case will be Python)
#### How are classes relevant?
- As you already know, Python is an "object-oriented programming (OOP) language", which means that it is highly concerned with organization and resuability. Classes are crucial to OOP in that they allow us to group related things and keep them together.
- A class is essentially a template that wllows us to create objects, which have variables and beheaviours associated with them.
---
## Unit 11: Web
#### What's the relevance of using web technologies like HTML and CSS?
- 
---
## Unit 12: Web Scraping and Document Databases
#### Why are we using Mongo now? I thought SQL was the best??
---
## Unit 13: ETL Project
#### Why are we doing this project?
---
## Unit 14: Intro to Javascript
#### Oh no! More new syntax that I don't understand!?
#### Why do we need to learn Javascript? I thought this was a Python course.
---
## Unit 15: Interactive Visualizations and Dashboards
#### Why would I use Plotly instead of Matplotlib or another library?

---
## Unit 16: D3
#### This seems like a really difficult library, I'm worried that it will never make sense...
---
## Unit 17: GeoJSON and Leaflet
#### Why is it useful to map out data geographically?
---
## Unit 18: R
#### What is the relevance of R?
---
## Unit 20: Tableau
#### How many ways do I need to know how to make a chart?
#### How is this any different than Excel?
#### Why are we using the public version and not student?
#### What is the difference between public and pro?
---
## Unit 21: Machine Learning
#### What is the relevance of machine learning?
---
## Unit 22: Big Data
#### What is the relevance of Big Data?