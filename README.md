# The Atomic Blog

A React blog app for writing, searching and clearing posts. Thirty sample posts are generated on load, and the whole component tree shares state through the Context API.

**Live demo:** [creat-your-custom-blogs-web-app.netlify.app](https://creat-your-custom-blogs-web-app.netlify.app/)

![The Atomic Blog](https://raw.githubusercontent.com/pokurumohanendra/My-Portfolio/main/public/projects/the-atomic-blog.jpg)

## Features

- Add a post with a title and body
- Live search across post titles and bodies, with a result count
- Clear all posts
- Archive list with a show and hide toggle
- Light and dark mode toggle
- Sample content generated with Faker

## Tech stack

React, Context API (`PostContext`), `memo`, `useMemo`, Faker, Create React App.

## Getting started

You need Node.js (LTS).

```bash
npm install
npm start
```

| Script | What it does |
|--------|--------------|
| `npm start` | Run the development server |
| `npm run build` | Create a production build |
| `npm test` | Run the tests |

## Project structure

```
src/
├── App.js          layout and components (header, search, posts, form, archive)
├── PostContext.js  shared state through the Context API
├── App-v1.js       earlier iteration of the app
└── App-memo.js     earlier iteration that uses memoization
```

## About

Built as a learning project to practise component composition, sharing state with Context, and avoiding unnecessary re-renders with `memo` and `useMemo`.

## Author

[Pokuru Mohanendra](https://github.com/pokurumohanendra) · [LinkedIn](https://www.linkedin.com/in/pokuru-mohanendra/)
