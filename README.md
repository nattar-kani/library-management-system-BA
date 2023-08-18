# Library Management System for Stanford

## Description

## Current State

## Overview and Summary

Stanford University is a private research university in California. The university was founded in 1885 and as of today, 83 Nobel laureates, 28 Turing Award laureates, and 8 Fields Medalists have been affiliated with Stanford as students, alumni, faculty, or staff. 

For the benefits of the students Stanford started its own library in 1885. The library at Stanford was housed in one large room capable of accommodating 100 readers. As the university grew to enroll more than 20,000+ students in a given year the library grew as well. Today the library boasts of having more than 4 million books in it.

The paper based maintaining, organizing, and handling of countless books became a nightmare. The university wanted a Library Management Software to automate their library’s activities. Using the software one can find books with a click, issue/reissue books quickly, and it will manage all the data efficiently using this system. It also provides immediate and accurate information regarding any type of book, magazine, or research paper, thereby saving a lot of time and efforts.

## Problems with manual library:

- A lot of time is wasted managing the manual library.
- The number of employees needed to manage the library is high.
- Fine calculation is a tedious and time-consuming affair.
- No reports could be generated on books issued due to the manual system.
- It is difficult to manage 4 million books present in the library.
- Students could deposit the books only in the library timings.

## Advantages of Library Management System:

- Reduce overheads and increase productivity of library staff 
- Cost reduction
- Up-to-date records of all books, research papers, magazines, and other materials available in the library
- Improve student engagement in the library
- It will generate dynamic reports for better decision-making

## Environments

We are going to be creating and maintaining the program in Java. We chose Java because it will not change much over time and if we make it well, there will be very little maintenance to be done on the code. 

## Future State

Client has given them the following requirements:
The LMS should keep records of different categories of material available in the library like books, magazines, research papers, journals, and newspapers. 
The books should be classified subject wise in the software.
Each category like books, magazines, research papers, journals, and newspapers will have different issuing periods. For example, a book can be issued for 3 weeks but a magazine only for 1 week. Newspapers cannot be issued for use outside the library and so on.
Every reading material available shall have a RFID tag on it. The record of the same will be stored in the database. For each reading material record information like author, book name, publisher name, book edition, date and year of publication, cost of the book, and date of purchase of the book.
When a student wants a reading material from the library, they will select the material and go to the checkout counter. The library staff will use a RFID reader to capture the details of the book. The student's name is tagged along with the book they borrowed. 
System will record the issue date and return date of the book. 
System shall do an automatic calculation of fines in case of delayed return of books.
Library staff should be able to search for books on the LMS by search criteria like name of the book or author.
Students should be able to access the library system online to know the return date. They should be able to access it via the web or mobile interface.
System shall send automated emails to the students 3 days before the return date to avoid late return of books. 
Access to free e-journals and e-books through the software.
Anti-theft detection: RFID readers are placed at the exit gate of the library and the RFID reader tracks books to a range of 2 meters and would trigger the alarm with a loud sound in case anyone tried to pass through the gate with an unissued book. 
Book drop box stations to be installed outside the library: Students can return books at any time in the RFID enabled book drop box station. Student’s loan is immediately cancelled once the student deposits the book in the drop box.

## Management would like the following reports:
Which books are most rented?
Records of issued and unissued materials in the library (management will decide whether to stock them or not)
Amount of fine collected in a day, week, and month.
Number of lost books
Report on total number of books, journals, etc.
Age of books, that is, which books are more than 20 years old. College generally would prefer not to have very old books since new versions come up every few years.

## System Requirement:
LMS can be used on any Windows and MacOS run computers 

Users will need an active internet connection.

It will be RFID ready (NCIP 2.0 HTTP server available)

Auto scheduled tasks like emails and database maintenance

Data should be stored in cloud

Highly secure, scalable, and reliable

 

Usability:

The screens should be self-explanatory and very user friendly.

 

Project Task: 

Identifying stakeholders – Create a list of stakeholders (as taught in Business Analysis Planning and Monitoring Knowledge Area)

Identify the problem statement in this system

Identify advantages of the new Library Management System

Create as-is and future process map (using flowcharts). You can use any of the popular tools in the market like Microsoft Visio, Lucid Chart, Creately, Pidoco, or Balsamiq

As a Business Analyst working on this project, find out the scope of the Library Management System. To find the scope you can use Use Case diagram (UML) or Context diagram

Write down the main features that need to be developed

Write the in-scope and out-of-scope items for this software

Draw a data flow diagram for the system

Draw an ER diagram of the system

Write out the Business Requirements, both Functional and Nonfunctional Requirements

Draw wireframes or mock screens for any 2 of the features namely book record creation and any other feature as deemed fit by the student. (Use the technique prototyping or wireframing that is taught in the training). You can use any of the wireframing tools like Microsoft PowerPoint, Microsoft Word, Balsamiq, Sketch, Adobe XD, Adobe Illustrator, Figma, UXPin, InVision Studio, InVision Freehand, or Moqups
