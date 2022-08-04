---
title: Online Learning Management System
summary: A full-stack web application of client-server architecture
tags:
  - Node.js
  - React
  - Redux
  - Java
  - MySQL
date: '2022-07-08T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Application architecture
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Client repo
    url: https://github.com/leizhang88/wbdv-sp21-client-react
  - icon: github
    icon_pack: fab
    name: Server repo
    url: https://github.com/leizhang88/wbdv-sp21-server-java
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

A full-stack Online Learning Management application where the front end implemented by `React` communicates with a local `MySQL` database through the `Java` middle tier.

### Functions

- The client built by `React` allows users to toggle with course components and to implement CRUD operations by sending RESTful requests to a remote server using `Redux`
- The local server hosting a `MySQL` database is built specifically to store data of widgets, the smallest unit of component created by users
- The `Java` middle tier handles the tractions between the client and the local database

### Features

- Bootstrap Styled
- React Single Page Application
- RESTful Web Services by Redux and Java Spring Boot

### Screenshots
- Course table
![course table](wbdv-course-table.png)
- Course component toggling
![toggling](wbdv-module-list.png)
