#### ** watch whole mega project videos again and again until u can make one by yourself **
#### ** make proper readme file in very detail **
#### ** make changes to your project and make it even better visually and function wise **

# MegaBlog

MegaBlog is a React-Js project aimed at creating a powerful blogging platform.

## Installation

- Install dependencies listed in `package.json`:
   ```bash
   npm install @reduxjs/toolkit react-redux react-router-dom appwrite @tinymce/tinymce-react html-react-parser react-hook-form

## Create Test Environment Variables:
  - Create a `.env` file in the project root (12megablog).
  - Use the `.env.sample` file as a template.
  - Add `.env` to `.gitignore` to prevent pushing sensitive information to GitHub.
  - Connect `app.js` to the environment. If using Vite-React or React, refer to their respective documentation for setting environment variables.

## Setup Appwrite

- Create a new project in Appwrite.
- Refer to the provided video tutorial for guidance on setting up Appwrite processes.
- Create a `conf` folder and a `conf.js` file.
  - Implement the required services for your app's authorization. This `auth` file can serve as a base code snippet for authentication purposes in other projects.

## Store
- create store
- create authslice where we track the authentication means we ask store if user is authenticated or not.