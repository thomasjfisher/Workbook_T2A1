# T2A1 - Workbook - Thomas Fisher

## 1. Describe the architecture of a typical *Rails* application

Ruby on Rails (Rails) is structured so that developers can use it as effectively as possible. Through the use of the MVC structure (Model, View, Controller). This helps keep the code DRY (Don't Repeat Yourself!) Convention over configuration! What this means is that by using Rails, it is basically one big template so that developers can being creating from a certain point, saving them time and becoming much more productive! It separates an application into the following components:

<u>Model</u>: The model is what interacts with the database to retrieve information and handle interactions between elements of the database. Model also interacts between the controller. Any functionality such as CRUD (create, read, update, delete) are all handled within the Model.

<u>View</u>: View is the interaction between the users and the website. In Rails the view is often in HTML files that have Ruby code. View presents the data to the users in certain formats designed by the developers, which is set in the Controllers.

<u>Controller</u>: The controller is where the flow of the application is handled. Controller communicates with both the Model and the View, in order to send and receive data to pass certain logic. Controller will handle the information from the Model, then forward that to the View, where the user can interact with the site. 

**References:**
https://coderacademy.instructure.com/courses/308/pages/mvc-intro-2?module_item_id=15856
https://coderacademy.instructure.com/courses/308/pages/rails-intro-2?module_item_id=15857



## 2. Identify a database commonly used in web applications (including *Rails*) and discuss the pros and cons of this database

So what is a database, and why is one better than another? Well, a database is where you can store all of the information and data required for your Rails app. There are multiple databases available and they differ in how they structure the data and information.  Most databases use SQL (Structured Query Language) in order to create, read, update and delete. 

The database in which I am currently most familiar, is Postgres. Postgres is one of the more user friendly databases. The structure of Postgres can be seen as a collection of tables. The tables within the database all have titles and the information stored to each of those tables, within the database. So, what are the pros and cons of using Postgres?

**Pros:**

- Easy to use, beginner friendly	
- Free and open source
- Much faster than some other databases
- Supports images, video, audio data

**Cons:**

- Less online documentation and resources available compared to other databases. 
- Somewhat difficult to find out why an error is occurring, unless you know how. 

**References:**
https://coderacademy.instructure.com/courses/308/pages/sql-intro-orm-models-and-migrations-2?module_item_id=15862



## 3. Discuss the implementation of *Agile* project management methodology

So what is Agile Project Management and why use it? When it comes to Agile Project Management, a team will come together and define what they need to do in order to complete the desired goals required of them. When setting out in Agile Project Management, often the manager will focus on setting out to define a road map, a Product Requirements Document (PRD) and a backlog.

A typical site which is used to monitor ta system like this is Trello. By mapping things out like this, it gives an insightful overview to how and what the team must do in order to reach the desired end goal. By having the road map clearly laid out, it provides them with a visual guide of what steps can be take. When it comes to the PRD, it is vital to have a set out list of what is actually required by the client, and important to stick to it. Items that go in to the backlog often consist of features, issues and or bugs that are required to be dealt with. Some are often of minor importance, and can be left until more pressing issues are dealt with. Some issues, however, may be of a higher importance, in which if it is required of the team leader to assign one or more people to that certain issue, so that they can resolve it more productively and move on with the development.  

What Agile Project Management allows a team to do, is get together, and create a shared understanding. This creates the difference between a good product team, and a great product team. Before even getting to the basics of the road map, PRD and backlog, often agile teams will do many activities together to better understand the customer problem and needs. This is commonly known as the discovery phase. This may include customer research, data insights and collection, surveys etc. By doing these activities together, everyone is across what needs to be done, making everyone's job much easier. 

**References:**
https://www.atlassian.com/agile/product-management
https://www.atlassian.com/agile/product-management/roadmaps



## 4. Provide an **overview** and **description** of a standard source control workflow

Workflow is about controlling the sequence of events that transform a piece of work  to ensure every person can use the best tool at the right time. Managing change can be difficult, especially when it comes to software development. It is a complex process where multiple developers are working with many different tools, to build one thing, together. It is imperative that each developer has and knows their role, and that the management of each developer and work load are managed efficiently. A good workflow allows all of the tools, processes and people for optimal productivity. One way to make use of managing this is via GitHub's Branching. By using branches, developers can work on their specific work without affecting other branches of the repository. 
"Use a branch to isolate development work without affecting other branches in the repository. Each repository has one default branch, and can have multiple other branches. You can merge a branch into another branch using a pull request."

**References:**
https://www.atlassian.com/git/tutorials/comparing-workflows
https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches



## 5. Provide an **overview** and **description** of a standard software testing process (e.g. manual testing)

"Manual testing is the process of manually [testing software](https://en.wikipedia.org/wiki/Software_testing) for defects. It requires a tester to play the role of an end user whereby they use most of the application's features to ensure correct behaviour. To guarantee completeness of testing, the tester often follows a written [test plan](https://en.wikipedia.org/wiki/Test_plan) that leads them through a set of important [test cases](https://en.wikipedia.org/wiki/Test_case)." - https://en.wikipedia.org/wiki/Manual_testing

What this means, is that before any software goes live, there will be developers responsible for making sure that the software is fully functional, without any problems occurring. Manual testing is always done prior to any implementation of automated testing. 

An example of manual testing that I have encountered so far, is on my Rails side project, when I created a new menu item, if I did not upload an image, the new menu item would not show on the View page. It would only show on the item page where the information of the menu items was stored. By doing this, I managed to find out that if a image was not assigned to an item, it would not show! I overcame this by setting a default image to be assigned to each new item, therefore, allowing the item to be added to my menu, and the user could change the image later.

**References:**
https://en.wikipedia.org/wiki/Manual_testing
https://www.guru99.com/software-testing.html



## 6. **Discuss** and **analyse** requirements related to information system security and how they relate to the project

When it comes to Information Security, there are three main principals: Confidentiality, Integrity and Availability. This is known as the CIA Triad. When it comes to designing a program, it should be designed to achieve one or more of the principals. In this day and age, it is vital that all necessary precautions are taken when it comes to handling of information and data.

But what exactly do each of these principals do? 

**Confidentiality:** This is where certain measures are taken in order to protect against the unauthorized disclosure of information. When it comes to protecting information, implementing the restriction of access of who can see the information. Anyone else who does not have the correct access, will not be granted access to the information.  

**Integrity:** Integrity is assuring that the information that is being accessed has not been altered by anyone or anything, and is a true representative of what is intended. There are times that information can actually lose integrity through malicious intent, when someone who makes changes to certain information without the correct authorization. 

**Availability:** This is when information can be access and also changed by any persons with authorization, within an allocated time frame. 

By adhering to the CIA Triad, this will make sure that the correct steps and precautions will be taken when completing the project. 

**References:**
https://bus206.pressbooks.com/chapter/chapter-6-information-systems-security/
https://www.lbmc.com/blog/three-tenets-of-information-security/



## 7. **Discuss** common methods of protecting information and data and how you would apply them to the project

There are many ways to ensure the protection of information and data of users and their sessions. 

**Risk Assessment:** What this means is that, based on how important the information is that you are storing, the higher posed risk there is if that information and data is hacked and or leaked. The more important that information, the more attention that is required to guard that information.

**Backups:** Making regular updates and backing up data is a great way to maintain the protection of information and data, so that if something does go wrong and information or data is tarnished, then having the backup of information and data will still be available. It is important to maintain regular backups.

**Access Controls:** Another way of making sure that the protection of all information and data is maintained, is to allow access to certain areas of the app/site to certain people. Quite often a site will have admins. The admins will likely have the most control over the site and can make changes if and when needed. By limiting other users access, this allows for better protection of information and data.

Implementing these few methods will go a long way in protecting user information and data for the project. There are many more methods in which user information and data can be protected, and often the more methods that are in place, the better of you and the users will be when it comes to the protection of information and data.

**References:**
https://guides.rubyonrails.org/security.html
https://gdprinformer.com/gdpr-articles/6-essential-data-protection-methods



## 8. **Research** what your legal obligations are in relation to handling user data and how they can be met for the project

The privacy of users information and data on the internet, it is one of most talked about and most expected things by most when it comes to online privacy. With how easy it is to access web sites online and online shopping, it is possible that almost everyday user's are handing over their personal data and information to web sites. We have a legal obligation to all users and customers, in making sure that their data and personal information is protected by us with no exceptions. It is a vital part of trust and integrity of us, the business.

Here in Australia, we have the federal Privacy Act 1988. This act is designed to promote the protection of an individuals privacy by imposing obligations on those people and or companies that handle the users information, to manage the data with transparency and with responsibility.

Adhering to the laws is what the aim will be for the project, and making sure that there is no breach of trust by any parties. User experience play a major role in whether something is a success or not. Making sure to look after our users is a top priority, because at the ned of the day, without trust, there would be no customers, meaning no business.  

**References:**
https://www.lexology.com/library/detail.aspx?g=6b37a60b-e179-419a-a822-c1fe47cf49e3
https://www.oaic.gov.au/privacy/privacy-for-organisations/small-business/
https://guides.rubyonrails.org/security.html#intranet-and-admin-security



## 9. **Describe** the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure.

So what is a relational database model? In order to know that, we need to know what a relational database is. A relational database is a collection of tables, each having a unique name, all showing a type of database that stores data and allows access to certain data that relates to one another. A relational database model is represented in the tables. 

In each row of the table, there is a record with its own unique key. The columns of the table hold the assigned attributes of the input data. They may have a one to one relations ship, one to many, many to many, depending on the data input.

For example, you might have 3 Tables. Students, teachers and classes. Each of these tables will have a unique key, in this example, names of the students, teachers and the classes. Each of the tables will have a relationship with another. So a student, Tom, will have a relationship with a teacher, Alex, who teaches a class, JavaScript. Each of the entries will have a unique key and its own data, yet can still have relations with many of the other inputs of data. Student Tom might also have a class of Ruby, taught by teacher Nandini. 

It is through the use of relational database models, that you can marry many different types of data from one table to another, as many times as is relevant.

**References:**
https://www.oracle.com/au/database/what-is-a-relational-database/
https://coderacademy.instructure.com/courses/308/pages/database-relations-many-to-many-and-polymorphic?module_item_id=15864
https://coderacademy.instructure.com/courses/308/pages/database-relations-one-to-one-and-one-to-many?module_item_id=15863



## 10. **Describe** the integrity aspects of the relational database model. Your description should include information about the types of data integrity and how they can be enforced in a relational database.

There are many forms of integrity that a relational database model has. 

**Logical Integrity:** The logical integrity is what manages to keep the relevant data constant when it is being used by multiple relations. It also helps to protect against hackers, and of course, human error. 

**Data Integrity:** Data Integrity is having the correct and relevant data stored in your database. Making sure that there is no data values are being repeated, making sure that incorrect values are not being stored, and that they relationships between the tables are not broken and can function.

**Domain Integrity:** This refers to the range of acceptable values that are stored and shown in certain columns within the database, such as integer, text, string, float. Making sure that the entry made for a column should be available in the domain of that specified data type.

**Entity Integrity:** Entity Integrity relies on the primary keys, the unique data values, that there is no empty field, and make sure that the data is not listed more than one time.

**Referential Integrity:** Referential Integrity is the maintenance of the consistency of data between two tables. There are rules created in the structure of the database as to how the foreign key is used to ensure that when any sort of changes are made, the database maintains the integrity of the data. 

**User Defined Integrity:** This is where the user can set certain rules in order to suit certain needs. Often times, User Defined Integrity will be used when it is deemed that any of the previous mentioned do not provide enough data integrity.

**References:**
https://www.talend.com/resources/what-is-data-integrity/#:~:text=Entity%20integrity%20relies%20on%20the,in%20a%20variety%20of%20ways
https://afteracademy.com/blog/what-is-data-integrity



## 11. **Describe** the manipulative aspects of the relational database model. Your description should include information about the ways in which data is manipulated (added, removed, changed, and retrieved) in a relational database.

There are many ways in which the relational database model can be manipulated. What this means, is that there are multiple ways in which the stored data can be used, added to other data and information, and even removed from certain information and data! 

**Projection:** This is the operation of retrieving specific attributes from a relation. It is used on a single relation to produce a new relation that then is shown to include on the attribute that have been requested in the original relation. So you might have a student, Tom, his ID is 105, and he is studying Diploma of IT. If you want to call Tom, and what he is studying, you will not get the student ID, as the data that you actually are after, is just the name and what he is studying.

**Selection:** This is the operation of retrieving certain requested tuples, (an ordered set of data constituting a record) from a relation based on a specified condition. So again, if you had a list of 10 students, and only wanted the students who were studying Ruby, you could call the relevant conditions and then only the students with the relevant data will show.  

**Join:** This is the operation of adding the tuples of two relations based on certain conditions. So for example here, you could call upon the all the students and teachers that are learning and teaching Ruby. So that might show that from students Tom and Ash, and Teachers Alex and Nandini, it has retrieved that Tom is studying Ruby, and Nandini is teaching Ruby.

**References:** 
http://www.se.rit.edu/~swen-220/slides/SWEN-220-DataModels_01_Relational.pdf
http://dsc.du.ac.in/wp-content/uploads/2020/04/is464t08.pdf
https://www.cs.uct.ac.za/mit_notes/database/htmls/chp02.html#data-manipulation-the-relational-algebra



## 12. **Identify** and **explain** the workings of TWO **sorting** algorithms and **discuss** and **compare** their performance/efficiency (i.e. Big O)

So, what is Big O, and what does it do? "Big O is an equation that outlines how much time or space it will take an algorithm to run based on certain inputs." This is subject to change, depending on the size of input.

**Bubble Sort:** Bubble sort, is one of the simplest forms of Big O notation. The algorithm will take a look at each element in the list and compare it to the following input, to check if the two elements need to swap places. It is one of the most simplest types, but also one of the slowest. The reason that I have chosen to compare Bubble Sort with Merge Sort, is so that you can see just how great a difference there is when it comes to sorting algorithms. 

```javascript
const arr = [2, 4, 5, 8, 7, 0, 1, 6, 9, 3];

function bubbleSort(arr) { 
  
  for(let i = 0; i < arr.length; i++) {
    for(let j = 1; j < arr.length; j++) {
      if(arr[j-1] > arr[j]) {
        let oldVal = arr[j-1];
        arr[j-1] = arr[j];
        arr[j] = oldVal;
      }
    }
  }
  
  return arr;
}

// Returns [0, 1, 2, 3, 4, 5, 6, 7, 8, 9] 
```

*JavaScript code source: https://medium.com/@yonislots/4-common-sorting-algorithms-what-to-know-and-the-big-o-63ef76268991*

**Merge Sort: ** Merge Sort is considered one of the fastest and most efficient sorting algorithms. It achieves the expected outcome by splitting the list in two, until there are no more elements left in each list. Then, each element is compared to another. When those two are sorted, it then compares with anoter set of sorted two.

```javascript
const arr = [2, 4, 5, 8, 7, 0, 1, 6, 9, 3];

function mergeTwoAndSort(arr1, arr2) {
  let arr = [];

  while(arr1.length && arr2.length) {
    if(arr1[0] < arr2[0]) {
      arr.push(arr1[0]);
      arr1 = arr1.slice(1);
    }
    else {
      arr.push(arr2[0]);
      arr2 = arr2.slice(1);
    }
  }

  if(arr1.length) arr = arr.concat(arr1);
  else arr = arr.concat(arr2);

  return arr;
}

function mergeSort(array) {  
  if(array.length === 1) {
    return array;
  }

  let half = Math.floor(array.length / 2);
  let firstHalf = mergeSort(array.slice(0, half));
  let secondHalf = mergeSort(array.slice(half));

  return mergeTwoAndSort(firstHalf, secondHalf);
}

// Returns [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
```

*JavaScript code source: https://medium.com/@yonislots/4-common-sorting-algorithms-what-to-know-and-the-big-o-63ef76268991*

Now, when it come to the implementation of either of these algorithms, it is clear to see that Merge Sort is one of the most efficient ways in which to handle sorting, versus Bubble Sort. Where Bubble Sort is required to search through and then compare each element, Merge Sort divides and conquers the elements, arranging them in the fastest way possible. 

**References:**
https://coderacademy.instructure.com/courses/308/pages/cs-fundamentals-bigo?module_item_id=15873https://en.wikipedia.org/wiki/Big_O_notation
https://medium.com/@yonislots/4-common-sorting-algorithms-what-to-know-and-the-big-o-63ef76268991



## 13. **Identify** and **explain** the workings of TWO **search** algorithms and **discuss** and **compare** their performance/efficiency (i.e. Big O)

When it comes to search algorithms, again, seeking out the best and most efficient functioning algorithm is obviously going to be the most desired outcome. Following, I will compare Linear searching to Binary searching.

**Linear Search:** When it comes to linear searching, it is by far one of the simplest algorithms. The reason for choosing this, is to show just how much of a difference in efficiency there will be when compared with Binary Search.

For example, if you are required to find the number 10 in an array of numbers.

```ruby
arr = [1,2,3,4,5,6,7,8,9,10]
```

How Linear Search works is by checking each element of the array. So, it will check if 1 = 10. If not, it will move to the second element in the array and will continue until the element matches the output, in this case, the number 10. It will take 10 steps in order to find the required number, 10.



**Binary Search:** Binary Search is a much more efficient way of searching and finding an element. Lets say we wanted to find the number 7 in the array. 

```ruby
arr = [1,2,3,4,5,6,7,8,9,10]
```

Binary search will search in the middle, until the element that it is searching for remains. So it will go to the half, and find 5. 7>5, so it will discard the left half of the array. We are now left with

```ruby
 arr = [6,7,8,9,10]
```

Again, Binary Search will find the middle. This time it will find 8. Well, 8 > 7, so we go back to the array!

```ruby
arr = [6,7]
```

Again, it will find the middle here and see that the left of the array is 6, and the right is 7, discarding the left of the array and therefore finding the required element of 7! We see that it has only taken 3 steps to find the 7! Much more efficient than the 10 steps that it takes for the Linear Search.

## 14. Conduct **research** into a marketplace website (*app*) and answer the following parts: 

Airbnb is an online platform where people form communities and can list and rent their homes! It is largely used world wide, and is incredibly prevalent in the renters market.

**a. List and describe the software used by the app.** 

**Languages:** Airbnb use the Ruby and JavaScript languages. both of these languages are prominently used by web developers all over the world.

**Framework:**   Airbnb uses the framework Ruby on Rails. Due to the fact of just how easy to use and how much has been set up prior to first starting, this makes Ruby on Rails a great framework to use for business.

**JavaScript Framework:** Airbnb uses react, as it is a flexible and very efficient tool used for building chic user interfaces. 

**Web Server:** Nginx is the powerful web server that is used by Airbnb.

**Cloud Storage:** Amazon S3, EBS are used to store user data.

**Cloud Hosting:** Amazon EC2 is a cloud hosting tool used which manages traffic coming into Airbnb's system, ensuring that the system is running at all times. 

**Cloud Database:** Amazon RDS is the cloud relational database used. 

**Data Tools:** Airbnb uses a range of data tools, from Presto, Druid, Airpal. Due to just how much user data Airbnb holds, they use many different tools in order to store, process, analyse and manage the data.

**b. Describe the hardware used to host the app.** 

As Airbnb is a fully online functioning app and website, the hardware needed in order to host the app is required by the users. Airbnb is fully functional on all devices. From computers, to tablets, even from the palms of our hands on our phones! 

**c. Describe the interaction of technologies within the app** 

In Airbnb, a user can sign up, sign in and then search the data base of listed houses/apartments/rooms. They can also search by price, location and availability. There are ways in which a user can message the hosts in order to speak to them directly, without requiring any sort of personal information to be handed over.

**d.** **Describe the way the data is structured within the app** 

For the Users table, they will have a user id, user name, and a friend id. Each Hosts table, each host will have a host id, host profile page, host since date. Listsings will have a listing id, host id, and a name. Amenities will have a listing id, property type, bed type, room type. Calendars will have one listing is, date and availability.

**e**. **Identify entities which must be tracked by the app** 

Airbnb must keep track users, hosts, listings,  calendar, reviews, amenity. All of these are important to keep track of as Airbnb deals with people relying on receiving the expected product, in this case the room/house etc, to be there and readily available. 

**f.** **Identify the relationships and associations between the entities you have identified in part (e)** 

Each host can have many listings. Each user can have many reviews. Each listing can have one calendar for availability, can have one amenity to show the rooms available, bed, bath, showers etc. Each listing can have many user reviews.

**g.** **Design a schema using an Entity Relationship Diagram (ERD) appropriate for the database of this website (assuming a relational database model)** 

![Airbnb ERD]()







