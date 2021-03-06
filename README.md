# Musical Rudiments
A music rudiments testing application developed for the University of Victoria

## Tools used
- HTML, CSS, Javascript + JQuery is used for front end, PHP/AJAX for back end (generating test reports and storing them on the server end)
- Visualization of the musical notation using Vexflow and Vextab by 0xfe (I have made some small changes to the original library to incorporate changing of colors and hiding key signature when necessary).
- Bootstrap is used for cosmetics.

## Some cool things
- The testing is NOT pulled from a bank of questions. The application has a means of interpretting music theory concepts and building random questions on the fly, given set limitations. Every time a new test begins, all questions are random. 

## Setup
To make the app work all external library links need to be fixed to CDNs. 
Server just needs to have php processing cabapilities. Placing the contents on a WAMP or similar setup will work out of the box if links are fixed.

## Further development / todo

This is a work in progress. I have built this for my department as I was relearing web development with Java and PHP this past year. I am currently considering ideas to expand this program into a more universal testing / learning application for both music and other disciplines.

- As I've been discovering newer tools, frameworks etc, I would like to convert some portions of the application to use Express / Knockout or possibly AngularJS for handling MVC stuff (right now it is all handled using JS / JQuery, and routing is through php headers)
- Make the application more mobile friendly (currently displays properly on all of the devices I tested, but not very pleasent to use on small screens. I'd like to make single question views with larger text for mobile devices).
- Some cleanup of the theory module is necessary, in particular removal of redundant and deprecated structures.
- Redesign of interface to allow more types of questions.
- Incorporate login for students and instructors.
- incorporate saving progress for authenticated users.
- Create an admin screen for tweaking the number of questions and limitations of each question (currently just maintained by me remotely).


