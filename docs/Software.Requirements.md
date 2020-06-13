# My Bloggy Bloggard - Software Requirements

## Goals

1. Create a blog to be able to share stories and knowledge with others

## User Stories

As a <User>, I want <Goal> so that <some reason>

  1. As a viewer, I want to see the list of blog posts so that I can choose a blog topic of interest to me
  2. As a viewer, I want to view an individual of blog post so that I can see all of its content
  3. As an admin, I want to add a new blog post to the site with text and optionally an image

## User Flow

  ![Bloggard User Flow](./docs/Bloggard-User_Flow.svg)

## Business Requirements

  * Pages
    o Home Page
    o Individual Blog Post page
    o New Blog Post page

  * Home Page
    o Display user profile image
    o Display list of blogs with Title, Date, Content
    o Limit the blog text to a certain height

  * Individual Blog Post page
    o Show the cover image, title, content, post date
    o Allow the user to go back to the home page

  * New Post Page
    o Allow an admin to fill in a form with title, content, select a cover image
    o Store the date of the post
    o Allow the admin to submit a blog post to the REST API
    o Reditrect to the Home Page


## Technical Requirements

  * Front End using HTML, CSS, and JavaScript
  * Back End using NodeJS
    o REST API
  * Database
    o JSON
    o SQLite3 (future)
  * REST API Endpoints
    o Get list of Blog Posts
      . api/posts
    o Get individual Blog Post
      . api/posts/:post_id
    o Post new Blog Post
      . api/posts
