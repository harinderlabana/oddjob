# oddJob

## What is oddJob?

OddJob is an app that finds local business or individual people just like yourself who may be looking to hire someone for any work or assistance that may be need for that oddJob. This can be anywhere from business employing a job seeker for only 8 hours, or you yourself need a hand around your property.

## Stack

\*\*sort out the front end, back end and database catagories

- NodeJS
- Express
- EJS
- jQuerry
- PostgreSQL
- Git

## Minimum Viable Product:

- Visitors should be able to see the oddJob's on the map and be able to search cities to search for more oddJob's.
- Logged in users or will be able to see a list of cities with oddJob's available for faster navigation.
- Logged in Job Seekers will be able to accept an oddJob posting.
- Logged in Employers wil be able to create an oddJob listing and have its pin show up on the map for Job Seekers to accept.

## User Stories

As a vistor, I can see the map and available oddJob's pinned. I can also search for a city to see available oddJob's in that area.

Each pin on the map has the business name, the date for the oddJob, the pay rate and time required.

As a logged in job seeker, I can see a list of cities with available oddJob's for faster navigation.

As a logged in job seeker, I can favourite certain maps for even faster navigation

As a logged in employer you can create a new entry into the map list if your city does not exsist.

As a logged in employer you can modify maps (add, edit, remove oddJob's)

As a logged in employer amd job seeker, I have a profile showing maps I've created and maps that i've favourited.

## Data

- Job Seekers
- Employers
- oddJob's
- Maps

## Routes

- **_C_** - POST /jobseekers
- **_R_** - GET /jobseekers/:id
- **_U_** - POST /jobseekers/:id
- **_D_** - DELETE /jobseekers/:id

#

- **_C_** - POST /employers
- **_R_** - GET /employers/:id
- **_U_** - POST /employers/:id
- **_D_** - DELETE /employers/:id

#

- **_C_** - POST /oddjobs
- **_R_** - GET /oddjobs/:id
- **_U_** - POST /oddjobs/:id
- **_D_** - DELETE /oddjobs/:id

#

- **_C_** - POST /maps
- **_R_** - GET /maps/:id
- **_U_** - POST /maps/:id
- **_D_** - DELETE /maps/:id

## Wireframe

\*\*Collaborate on design.

- nav bar with logo
- nav bar menue, log in, sign up, favourites(job seekers), post a job(employers)
- map main screen
- single page (think tweeter with hiding post form)
