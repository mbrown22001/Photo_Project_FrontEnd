# Photo_Project_FrontEnd

## Overview:
Create a website where a photographer can show off their artwork and have users sign up to schedule meeting shoots with said photographer.

## User Stories:
* The user will start on the Home page which has a youtube video and a headshot of the photographer
* The user will be able to choose their destination at the top of the page. Also has the photographers name and socials at the top.
* When the user accesses the About Me page, they will find basic info about the photographer and some images.
* When the user accesses the Portfolio page, view some of the photographers work and a dropdown box will allow what work specfically.
* The state of Contact Me will depend on whether or not the user is logged in.
* If the user is not logged in, they can request a meeting with the photographer but they won't be able to view their meeting through the site.(MVP)
* If the user is logged in, not only can they request a meeting with the photographer but they can also see what they requested.
* Login takes you to a login and signup screen.

## Routes inventory
#### User Routes
|  Method | Path  | Purpose  | 
|---|---|---|
| GET  | /users  | Access user profile  |
| POST | /users  | Signup | 
| POST | /users/login | Login  |  
| PUT | /users/profile | Edit profile  |

#### Schedule Routes
|  Method | Path  | Purpose  | 
|---|---|---|
| GET  | /appointments  | Get all appointments of all users  |
| GET  | /appointment/mine  | Get all appointments of the current user  |
| POST | /appointment  | Create schedule | 

