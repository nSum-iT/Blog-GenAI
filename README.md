# BlogGen AI: AI Blog Generator

## Overview

Blog GenAI is an AI-powered blog generator built with Django. It generates blog posts from YouTube links provided by users. The application utilizes natural language processing (NLP) techniques, including the AssemblyAI API and OpenAI API, to extract key information from YouTube videos and automatically generate informative blog posts.

## Features

- Generate blog posts from YouTube links.
- Utilize the AssemblyAI API for natural language processing and content extraction.
- Extract key information such as video title and description.

## Installation

1. Clone this repository to your local machine using `git clone`.
2. Navigate to the project directory.
3. Install dependencies by running `pip install -r requirements.txt`.
4. Ensure you have the required API keys for AssemblyAI and OpenAI. Update the settings accordingly.

## Usage

1. Start the Django server by running `python manage.py runserver`.
2. Open your web browser and navigate to `http://localhost:8000` to access Blog GenAI.
3. Provide a YouTube link in the input field to generate a blog post.

## API Keys

- AssemblyAI: Get your API key from [AssemblyAI](https://www.assemblyai.com/).
- OpenAI: Get your API key from [OpenAI](https://openai.com/).

## Endpoints

- `/`: Landing page, requires user authentication.
- `/generate_blog`: Endpoint for generating a blog post from a YouTube link.
- `/blog_list`: Display all blog articles created by the user.
- `/blog_details/<pk>`: Display details of a specific blog article.
- `/login`: User login page.
- `/signup`: User signup page.
- `/logout`: Logout functionality.

## Dependencies

- Django
- pytube
- assemblyai
- openai


