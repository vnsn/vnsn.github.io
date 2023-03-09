# Jen Evenson

I'm a software developer with an MBA on a site reliability team at Adobe.

# Certifications / Education

* Red Hat Certified System Administrator (RHCSA), April 2021
* V School (coding bootcamp) Certificate in Fullstack Web Development, using the MERN stack: MongoDB, Express, React, Node.js
* Master of Business Administration (MBA) from Santa Clara University
* Coursework toward second Bachelors in Computer Science (stopped and got the MBA instead)
* Bachelor of Arts (BA) in Economics from University of California at Santa Cruz

# Bootcamp Projects

## Full-stack application: [Best Advice I Ever Got](https://best-worst-advice.herokuapp.com/)

### Objective
Create a site where visitors can post the best advice they've ever gotten and who gave it to them. Users can also read and comment on entries from other users. The administrator can edit and delete entries and comments.

### Technologies Used
* Front End: HTML, CSS, JavaScript, React, Redux + Thunk, Axios
* Back End: Express, MongoDB, Mongoose
* Hosted at Heroku with the database at MLab

### Challenges / Lessons Learned
* There is one Form component that handles both adding and editing versus having one component for each, as I had been taught.
* I wanted to keep all the data I'd loaded into my local Mongo database, so I spent some time learning how to export and import JSON files into Mongo.

### Ideas for improvements
* User authentication so users can edit / delete their own entries.

## Front-end application: [Movie Game](https://movie-game.netlify.com/)
[View the code on Github](https://github.com/vnsn/assignments/tree/master/projects/d30-01-api-project)

### Objective
Game where users are shown a movie title and the names of 4 actors. They have to guess which actor was NOT in the movie. 

### Technologies Used
* Front End: HTML, CSS, JavaScript, React, Redux + Thunk, Axios
* API used: [The Movie Database](https://www.themoviedb.org/)
* Hosted at Netlify

### Challenges / Lessons Learned

* The biggest thing I learned is that if you are making a trivia game app, either write your own API or use a trivia API with questions already built! Don't GET a bunch of raw data and then build your own questions on the fly inside your app components.

### Ideas for improvements
* Hide the "next question" button until the user chooses an answer and the answer has been evaluated.
* Pull the year out of release date and just display that with the movie name.
* Increase the number of movies from which questions are generated.
* Add user accounts so scores can be saved and "high score" can be shown.

# Contact
You can contact me on [LinkedIn](https://www.linkedin.com/in/jvnsn/)
