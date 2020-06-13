# My Bloggy Bloggard - Software Requirements

## Goals

1. Create a blog to be able to share stories and knowledge with others

## User Stories

As a <User>, I want <Goal> so that <some reason>

  1. As a viewer, I want to see the list of blog posts so that I can choose a blog topic of interest to me
  2. As a viewer, I want to view an individual of blog post so that I can see all of its content
  3. As an admin, I want to add a new blog post to the site with text and optionally an image

## User Flow

  ![Bloggard User Flow](https://raw.github.com/Leif-W/bloggard/master/docs/Bloggard-User_Flow.svg)

## Business Requirements

  * Pages
    * Home Page
    * Individual Blog Post page
    * New Blog Post page

  * Home Page
    * Display user profile image
    * Display list of blogs with Title, Date, Content
    * Limit the blog text to a certain height

  * Individual Blog Post page
    * Show the cover image, title, content, post date
    * Allow the user to go back to the home page

  * New Post Page
    * Allow an admin to fill in a form with title, content, select a cover image
    * Store the date of the post
    * Allow the admin to submit a blog post to the REST API
    * Reditrect to the Home Page


## Technical Requirements

  * Front End using HTML, CSS, and JavaScript
  * Back End using NodeJS
    * REST API
  * Database
    * JSON
    * SQLite3 (future)
  * REST API Endpoints
    * Get list of Blog Posts
      * api/posts
    * Get individual Blog Post
      * api/posts/:post_id
    * Post new Blog Post
      * api/posts
