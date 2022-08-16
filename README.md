# oddJob

Wiki Map
A web app that allows users to collaboratively create maps which list multiple "points". For example: "Best Places to Eat Around Town" or "Locations of Movie Scenes".

Requirements:

- users can see a list of the available maps
- users can view a map
- a map can contain many points
- each point can have: a title, description, and image
- authenticated users can create maps
- authenticated users can modify maps (add, edit, remove points)
- users can favourite a map
- users have profiles, indicating their favourite - maps and maps they've contributed to
  use http://leafletjs.com/ or https://developers.google.com/maps/

WARREN [ ]

## What is oddJob?

OddJob is an app that finds local businesses or individuals looking to hire someone for any work or assistance that may be need for that oddJob. This can be anywhere from business employing a job seeker for few hours, or you yourself need a hand for that oddJob.

WARREN [ ]

## Stack

Backend

- Nodejs
- Express
- Postgres

Frontend

- HTML
- CSS
- Javascript

WARREN [ ]

## Minimum Viable Product:

- Vistors can interact with the map, search for cities and view oddJobs pinned where available.
- Logged in users can post, edit, delete oddjobs that they've created
- Logged in users can favourite oddJobs to a custome map that is shareable.

WARREN [ ]

## User Stories

- As a non-logged in user, I can interact with the map, see oddJobs pinned and search for other cities because I want look for more oddJobs.

- As a logged in user, I can accept an oddJob, post an oddJob as a business or individual and I can favourite oddJobs to a custome map because I want to share these maps with others or access these oddJobs at a later time.

- As a logged in user I can create, update or delete oddJobs I've created because I may want to change information or remove a posting.

WARREN [ ]

## Data

- users: (id, name, email, password, phone, location, rating, reviews(use oddjob id for title of review))
- odd_jobs: (id, user_id(fk), title, type, pay_rate, start_time, end_time, location, date, active(BOOLEAN), image_url) (\*\*also look into using an eventlistener onclick to hide job button and change colour)
- Maps (id, user_id(fk), odd_id(fk), start_location, information/details) \*\* possibly need to hold information for global oddjob maps with all listings and also user created favourite maps.

WARREN [ ]

## Routes

- **_B(browse)_** - GET /users
- **_R(read)_** - GET /users/:id
- **_E(edit)_** - POST /users/:id
- **_A(add)_** - POST /users
- **_D(delete)_** - POST /users/:id/delete

- **_B(browse)_** - GET /oddjobs
- **_R(read)_** - GET /oddjobs/:id
- **_E(edit)_** - POST /oddjobs/:id
- **_A(add)_** - POST /oddjobs
- **_D(delete)_** - POST /oddjobs/:id/delete

- **_B(browse)_** - GET /maps
- **_R(read)_** - GET /maps/:id
- **_E(edit)_** - POST /maps/:id
- **_A(add)_** - POST /maps
- **_D(delete)_** - POST /maps/:id/delete

WARREN [ ]

## Wireframe

\*\*Collaborate on design.

- nav bar with logo
- nav bar menue, log in, sign up, favourites(job seekers), post a job(employers)
- map main screen
- single page (think tweeter with hiding post form)
