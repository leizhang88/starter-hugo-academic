---
title: YelpCamp for Camping Site Sharing
summary: A full-stack web application for camping site sharing, powered by Node.js and express
tags:
  - Node.js
  - Express
  - MongoDB
date: '2022-08-02T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Home page
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Repo
    url: https://github.com/leizhang88/yelpcamp-su22-nodejs-express
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
##slides: example
---

A full-stack web application for sharing camping site, powered by `Node.js`, specifically `express` for the server side.

Visit [here](https://yelpcamp-su22-nodejs-express.herokuapp.com/)

### Features

- Styled with `Bootstrap`
- RESTful conventions
- MongoDB connection by `mongoose`
- Schema validation by `joi`
- Authentication and authorization based on data relationship
- Session and cookie enabled by `express-session`
- Map API by `mapbox`
- Deployed on `Heroku`


### Screenshots

- User register
  ![register](yelpcamp-register.png)
- Map display
  ![map-display](yelpcamp-map-display.png)
- Authorization based on data ownership
  ![owner](yelpcamp-owner.png)
  ![visitor](yelpcamp-visitor.png)
