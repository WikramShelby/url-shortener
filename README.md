# url-shortener

# Scalable URL Shortener

A backend system that converts long URLs into short and shareable links. The service handles efficient redirection, unique link generation, and tracks click analytics.

## Features

* Generate short URLs from long links
* Efficient redirection to original URLs
* Unique ID generation to avoid collisions
* REST APIs for URL creation and retrieval
* Click tracking and basic analytics

## Tech Stack

Backend

* Node.js
* Express.js

Database

* MongoDB

Tools

* Git
* GitHub
* Postman

## API Endpoints

Create Short URL

POST /api/url

Retrieve Original URL

GET /:shortId

Get Analytics

GET /api/url/stats/:shortId

## Future Improvements

* Custom short URLs
* Rate limiting
* Redis caching
* URL expiration

🚧 **Project Status: Under Progress**
