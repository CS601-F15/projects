CS 601 - Fall 2015 - Yap Project
=================================

*This project description is tentative and subject to change.*

The goal of this project is to implement a Yelp-like review site, called Yap! Make sure you are familiar with [Yelp](http://www.yelp.com) before beginning this project.

For this project, you will build your own web site from scratch. You will design and implement a two-tier web application with a Java front end and a SQL backend. 

You *may* reuse pieces of your Lab assignments for this project, but it is not required. In some cases, you may need to modify or redesign your Lab code in order to integrate it into your site.

You do *not* need to seed your database with the Yelp data set. 

80% of your final project grade will be based on the functionality of the features your site provides. 

#Required Features

You *must* complete all of the following required features for a total of 30 points.


| Points   | Feature         | Description |
| :-------: |:-------------:| :-----|
| 5 | User registration | Provide a *Sign Up* button that allows a user to register to use your service. User must be able to enter appropriate account information and user data must be saved appropriately in your system. | 
| 5 | Login and logout | Allow a user to login and logout of your site. Maintain the user session appropriately. |
| 5 | View businesses | Display a list of all businesses with reviews in your system. Show the average rating for each business. |
| 5 | View reviews for a specific business | Allow a user to select a specific business and display reviews for that business. |
| 5 | Relational database - Users | Use a relational database to store *user account* data. |
| 5 | Relational database - Reviews | Use a relational database to store *review* data. |


#Additional Features

You must complete at least 50 points worth of the following additional features. You may receive up to 10 points extra credit for completing more than 50 points worth of features.


| Points   | Feature         | Description |
| :-------: |:-------------:| :-----|
| 10 | Add review | Allow a user to add a new review for a business. Unlike Yelp, allow a user to create a business if it does not already exist. |
| 5 | Modify/delete review | Allow a user to modify or delete a review *that s/he has written*.
| 10 | Voting | Allow users to vote on whether a review is Useful, Funny, or Cool. |
| 5 | View businesses by city or neighborhood | Provide the ability to restrict which businesses are display, for example by city, neighborhood, or type of business (e.g., restaurants, hair salons, etc). |
| 5 | Sort by | Allow a user to dynamically choose how to sort a list of displayed businesses, for example by rating or alphabetically. |
| 5 | Show *n* reviews per page | Provide pagination to allow a user to see some specific number of reviews per page and scroll to the next page. |
| 5 | Javascript | Use Javascript and/or a template library to generate the UI shown in the browser. |
| 10 | Review sorting algorithm | Implement a *proprietary* review sorting algorithm, for example based on the number of views of the review and/or the number of reviews of the user. For credit you will need to implement and demonstrate a sophisticated algorithm. |
| 10 | Images | Integrate images into your site, allow a user to upload images with a review and display when a review is viewed. |
| 10 | Allow login with another service | E.g., login with Google, Facebook, etc. |
| 10 | Maps integration | Integrate a maps service, e.g., embed google maps on your site. |
| 10 | Search | Allow a user to search reviews for particular phrases. |
| 10 | Web service | Provide a *thorough* web service API that allows access to your site. To receive credit, you must have appropriate documentation of your API. |
| 10 | Hosted | Run on Amazon Web Services or another hosting site. |
| 10 | Roll Your Own Server | Use your own HTTP server. Your server must use raw Sockets for communication and must completely support GET and POST requests. |
| up to 10 | Choose your own | Propose your own feature to the instructor during office hours. |

#Requirements

1. **Java** - Unless you have received a special exception from the professor, you are expected to use Java to implement this assignment.
2. **Demos** - You must make an appointment to demonstrate your code for each release. The demonstration must be completed by the deadlines specified below. 
3. **Demo Appointments** - Demonstration times are first come, first served. If you fail to make an appointment you will not receive credit. If you are not ready by your appointment time, you will not receive credit.
4. **Remote Execution** - At each demonstration, your code must be running on your assigned microcloud node, or on AWS or another hosting service.
5. **Servlets** - You are encouraged to use Servlets/Jetty.
6. **3rd Party Libraries** - You may use other frameworks and/or libraries. For any library, however, seek instructor approval.
7. **Code Submission** - At the time your demonstration appointment begins, all code you wish to be considered for the release must be committed to your github `<username>-project` repository.
8. **Github Usage** - You are expected to use Github appropriately.
9. **User Experience** - Your web pages should look professional. You may use Bootstrap, or other frameworks for this purpose. If you do not, that's fine, but make sure your pages have a clean look.
10. **Demo Design** - You must design your demonstration for each release carefully. It is *your responsibility* to show the professor complete working functionality for each feature. If you fail to demonstrate, completely, how a feature works you may not receive credit for that feature. Be prepared with a script of how you will demonstrate your site, and make sure to include demonstration of how your features handle error cases (e.g., login of a user that does not exist).


#Grading

You will be graded on three releases of your project. 

##Release 1 - Due 11/4 

- (25 points) Functionality. You are expected to implement 25 points worth of functionality for Release 1. Features will **not** be granted partial credit---a feature is either implemented completely or it receives 0 points. If you complete more than 25 points worth of functionality you will be granted full credit, but not extra credit. 
- (1 point) Project management including use of github.
- (2 points) System architecture and code design.
- (1 point) Quality of user experience.
- (1 point) Demonstration of appropriate test cases.

##Release 2 - Due 11/25

- (25 points) Functionality. You are expected to implement 25 points worth of functionality for Release 2. Features receiving full credit in Release 1 are not eligible for credit in Release 2.
- (1 point) Project management including use of github.
- (2 points) System architecture and code design.
- (1 point) Quality of user experience.
- (1 point) Demonstration of appropriate test cases.

##Release 3 - Due 12/17

- (30 points) Functionality. You are expected to implement 30 points worth of functionality for Release 3. Features receiving full credit in Release 1 or 2 are not eligible for credit in Release 3. Points will be *deducted* for any features in the Required list that are not complete.
- (2 points) Project management including use of github.
- (4 points) System architecture and code design.
- (2 points) Quality of user experience.
- (2 points) Demonstration of appropriate test cases.
