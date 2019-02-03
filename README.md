# wouldyourather Project
Udacity React-Redux Evaluation Project

This is my implemnetation of the Would You Rather project as part of the Udacity React Nanodegree Program.

Would You Rather is a web application that allows users to create, vote and view polls as well as their rank in the leaderboard.

# Installation
* install all project dependencies with `npm install`

#Additional Dependencies required to run this project
npm install react-redux --save
npm install react-redux-loading --save
npm install react-router-dom --save
npm install redux --save
npm install redux-thunk --save
npm install semantic-ui-react --save

# Start App
* start the server with `npm start`

# App Functionality
once application start it will  show list of existing users. Once the user select any user from list and log in  it will show home which display unanswered questions and answered questions.

The information about the logged in user appears on the top right of all pages. If someone tries to navigate anywhere by entering the address in the address bar, the user is asked to sign in and then the requested page is shown. The application allows the user to log out and log back in.

Once the user logs in, the user is able to toggle between his/her answered and unanswered polls on the home page, which is located at the root. The polls in both categories are arranged from the most recently created (top) to the least recently created (bottom). The unanswered questions is shown by default.

What would be the point of seeing answered and unanswered polling questions if we couldn’t actually vote or see the results? Each polling question has a "View Poll" link to the details of that poll. The details of each poll are available at questions/:question_id.

When a view poll is clicked on the home page, the following is shown:

Text “Would You Rather”;
Avatar of the user who posted the polling question; and
Two options.
For answered polls, each of the two options contains the following:

Text of the option;
Number of people who voted for that option; and
Percentage of people who voted for that option.

The application shows a 404 page if the user is trying to access a url that does not exist. 

Logged in user can create new question using link New Question, it will give 2 option 

Enter Option1 Text
or
Enter Option2 Text

The user is able to navigate to the leaderboard, it will show the score and also contains answered questions as well as created question by user. it will show also picture as well as name.