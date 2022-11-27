---
title: "Library Management REST API"
layout: post
# date: 2016-01-23 22:10
tag: jekyll
image: https://sergiokopplin.github.io/indigo/assets/images/jekyll-logo-light-solid.png
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
description: "REST API for library management system built with Express and MongoDB."
category: project
author: kalpitborkar
externalLink: false
---

# Library Management System
REST API for library management system built with Express and MongoDB.\
Check the github repository here: [Library Management REST API](https://github.com/kalpitborkar/Library-Management-REST-API)

## Organization

### The main entities/resources served by the API are
- Books
- Authors
- Book Instances
- Genres

### Each resource structured in 4 modules
- Router
- Model
- Controller
- View

## Accessing the API 
### Book routes
| Methods | Endpoints                          | Access  | Description                              |
| ------- | ---------------------------------- | ------- | ---------------------------------------- |
| GET     | /                                  | Public  | View home page                           |
| GET     | /book/:id/create                   | Public  | Get HTML form to add a book              |
| POST    | /book/:id/create                   | Public  | Add a book                               |
| GET     | /book/:id/delete                   | Public  | Get HTML form to delete a book           |
| POST    | /book/:id/delete                   | Public  | Delete a book                            |
| GET     | /book/:id/update                   | Public  | Get HTML form to update a book           |
| POST    | /book/:id/update                   | Public  | Update a book                            |
| GET     | /book/:id                          | Public  | View a book                              |
| GET     | /books                             | Public  | View list of all books                   |

### Author routes
| Methods | Endpoints                          | Access  | Description                              |
| ------- | ---------------------------------- | ------- | ---------------------------------------- |
| GET     | /author/:id/create                 | Public  | Get HTML form to add an author           |
| POST    | /author/:id/create                 | Public  | Add an author                            |
| GET     | /author/:id/delete                 | Public  | Get HTML form to delete an author        |
| POST    | /author/:id/delete                 | Public  | Delete an author                         |
| GET     | /author/:id/update                 | Public  | Get HTML form to update an author        |
| POST    | /author/:id/update                 | Public  | Update details of an author              |
| GET     | /author/:id                        | Public  | View details of an author                |
| GET     | /authors                           | Public  | View list of all authors                 |

### Genre routes
| Methods | Endpoints                          | Access  | Description                              |
| ------- | ---------------------------------- | ------- | ---------------------------------------- |
| GET     | /genre/:id/create                  | Public  | Get HTML form to add a genre             |
| POST    | /genre/:id/create                  | Public  | Add a genre                              |
| GET     | /genre/:id/delete                  | Public  | Get HTML form to delete a genre          |
| POST    | /genre/:id/delete                  | Public  | Delete a genre                           |
| GET     | /genre/:id/update                  | Public  | Get HTML form to update a genre          |
| POST    | /genre/:id/update                  | Public  | Update a genre                           |
| GET     | /genre/:id                         | Public  | View all books of the genre              |
| GET     | /genres                            | Public  | View list of all genres                  |

### Book Instance routes
| Methods | Endpoints                          | Access  | Description                              |
| ------- | ---------------------------------- | ------- | ---------------------------------------- |
| GET     | /bookinstance/:id/create           | Public  | Get HTML form to add a book instance     |
| POST    | /bookinstance/:id/create           | Public  | Add a book instance                      |
| GET     | /bookinstance/:id/delete           | Public  | Get HTML form to delete a book instance  |
| POST    | /bookinstance/:id/delete           | Public  | Delete a book instance                   |
| GET     | /bookinstance/:id/update           | Public  | Get HTML form to update a book instance  |
| POST    | /bookinstance/:id/update           | Public  | Update a book instance                   |
| GET     | /bookinstance/:id                  | Public  | View details of a book instance          |
| GET     | /bookinstances                     | Public  | View all book instances                  |

## Built with
- [Nodejs](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [MongoDB Atlas](https://www.mongodb.com/atlas/database)
- [Mongoose](https://mongoosejs.com/)
- [Pug](https://pugjs.org/api/getting-started.html)

## License
Distributed under the MIT License. See `LICENSE.md` for more information.
