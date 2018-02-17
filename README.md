# JSU Psychology Research Web Application

This application keeps track of research participation credits earned by
the Psychology Major and Minor students at JSU.

## **Site**

The website has 3 types of users; Students, teachers and administrators.
Description about the project

1.  A data base associated with the project is available online.

2.  Only approved faculties can view and modify (ie, data entry) the
    entire database.

3.  Each student can view (but not modify) his or her record. But not
    other student’s records.

4.  The student database has the following information.

    -  Student name and email.

    -  Major in psychology or minor in psychology

    -  Studies participated in.

    -  Total research credits earned.

5.  Students can view and register for available studies.

6.  Researchers an post and modify schedules (Available times ) for each
    study (but their own)

## **Project Structure**

1.  Java servlet hosted on a Tomcat server.

2.  Connected to mySql database.

## **Database Structure**

 <img src="media/image1.PNG" width="624" height="287" />

## **Project Flow**

 Login:

- Administrator

- Faculty

- Student

### **Administrator**

1.  Functionalities

    1.  -Sees all users data

    2.  -View particular user

2.  Query for all user data

    <img src="media/image2.PNG" width="531" height="38" />

3.  Query for researchslotid from searched user

<img src="media/image3.PNG" width="624" height="47" />

### Professor 

Functionality

- Sees only students data

- View particular Student

Functionality currently same as Administrator (Except for user viewing)

### Student

1.  Query to view information about the research the student is
    currently enrolled in.

    <img src="media/image4.PNG" width="624" height="57" />

2.  Query to decrement slot openings for the research that the student
    just enrolled.

 <img src="media/image5.PNG" width="624" height="33" />

3.  Query to make new student research record

    <img src="media/image6.PNG" width="624" height="20" />

## **Usage**

### **Development**

Want to contribute? Great!

To fix a bug or enhance an existing module, follow these steps:

-   Fork the repo

-   Create a new branch `git checkout -b improve-feature`

-   Make the appropriate changes in the files

-   Add changes to reflect the changes made

-   Commit your changes `git commit -am 'Improve feature'`

-   Push to the branch `git push origin improve-feature`

-   Create a Pull Request

**Bug / Feature Request**

If you find a bug (the website couldn't handle the query and / or gave
undesired results), kindly email me at <jmathew@stu.jsu.edu> by
including your search query and the expected result.
