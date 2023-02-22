# Multilingual News Portal with Authentication

This project is a web application that allows users to view news, access a profile page, and authenticate using fake credentials. The application also features multilingual support for the website menu and uses React, Redux, and TypeScript.

## Features

- Home page with custom content
- News page with the ability to load more posts and delete posts
- Profile page with custom text, accessible only with authentication
- Localization for website menu (English and Ukrainian)
- Form authentication with "fake" credentials
- Uses React, React Router, Redux, @reduxjs/toolkit, and TypeScript
- Material UI for styling

## Getting Started

To get started with this project, you can follow these steps:

1. Clone the repository using the following command:
```bash
git clone https://github.com/BadMonkeyDev/multilingual-news-portal-with-auth.git
```

2. Install the necessary dependencies using `npm`

```bash
npm install
```
3. Run the development server:
```bash
npm start 
```
4. Navigate to `http://localhost:port/` to view the application in your browser.
(link will be listed in console)

## Usage

To use this application, you can follow these steps:

1. Navigate to the home page, news page, or profile page using the links in the website menu.
2. On the news page, click the "Load More" button to load additional posts. Click the "Delete" button on any post to remove it from the page.
3. If you try to access the profile page without authentication, you will be redirected to the home page.
4. To authenticate, click the "Log In" button in the website menu and enter the fake credentials:
```js
username: admin
password: 12345 
```
5. After successful authentication, you will be redirected to the profile page.

## Localization

The website menu supports two languages: English and Ukrainian. To switch the language, click the "EN" or "UK" button in the website menu.
