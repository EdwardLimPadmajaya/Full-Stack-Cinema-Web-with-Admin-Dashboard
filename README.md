h1>Full Stack Loop Cinema Website with Admin Dashboard</h1>
<h2>React.js, Node.js, Express.js, MySQL, REST API, GraphQL, Sequelize</h2>

## Overview
Loop Cinemas is a long running cinema operator with several cinema locations around Australia. They focus on a premium, unique experience and bringing community into their cinema experiences. In addition to displaying the latest and greatest films, Loop also holds a few community events, art shows and the like at their locations.

Loop Web will help potential customers discover upcoming films, session times and see ratings and reviews from other moviegoers.

An Admin Dashboard is also created to allow Loop Cinemas admin to create, edit, and delete movie information that is displayed on Loop Web.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Features
### Loop Web
1. **Landing Home Page:** display movies and their session times and average ratings.
2. **Sign Up Page:** allow users to sign up for an account.
3. **Sign In Page:** allow users to sign in to their account.
4. **For logged in users:**
    <ol type="a">
        <li><strong>Profile Page</strong></li>
        <ul>
            <li>display user profile: username, email, sign up date, and reserved tickets.</li>
            <li>edit user profile: change username and/or email.</li>
            <li>delete user profile</li>
            <li>view all movie ticket reservations</li>
        </ul>
        <li><strong>Review Page</strong></li>
        <ul>
            <li>allow users to leave reviews (number of stars and formatted written review) for a particular movie</li>
            <li>allow users to delete reviews</li>
            <li>allow users to edit reviews</li>
        </ul>
        <li><strong>Landing Home Page</strong></li>
        <ul>
            <li>allow users to reserve movie tickets for a particular session</li>
        </ul>
    </ol>
