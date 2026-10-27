# Django-X-Publisher
A Django-based blogging platform that allows users to create and manage blog posts from a web interface, with integration for automatically publishing posts to a connected X account.
]
## Project Overview

Django X Blog Publisher is a web application designed to combine content management with social media publishing.

Instead of creating a blog post on a website and manually copying it to X, the application is being developed to allow users to publish content directly from the Django dashboard and automatically send the post to their connected X account.

## Features

### Blog Management
- Create blog posts
- View all blog posts
- View individual posts
- Upload video content
- Store posts in a database
- Django administration support

### X Integration
- Connect an X account
- OAuth 2.0 authentication
- Secure account authorization
- Publish blog content to X
- Support for video publishing
- Track X publishing status

### User Experience
- Clean and responsive interface
- Simple content publishing workflow
- Dashboard-based management
- Mobile-friendly design

## Technology Stack

- Python
- Django
- SQLite
- HTML5
- Tailwind CSS
- X API
- OAuth 2.0
- Git & GitHub

## Project Architecture

```text
User
  |
  v
Django Web Application
  |
  +------ Blog Management
  |
  +------ Media Upload
  |
  +------ X Authentication
  |
  +------ X API
  |
  v
Connected X Account
```

## How It Work
Create Post
     |
     v
Add Title & Content
     |
     v
Optional Video Upload
     |
     v
Publish Post
     |
     +----------------+
     |                |
     v                v
Django Database      X API
                      |
                      v
                 X Account
