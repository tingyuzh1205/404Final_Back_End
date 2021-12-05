# JSON Server Posts API

To run this project locally:

```
npm install
npm run dev
```

Here are a few GET endpoints:

- Fetching a collection of post resources: http://localhost:4000/api/posts
- Fetching a single post resource: http://localhost:4000/api/posts/0
- Fetching a collection of post resources with related data: http://localhost:4000/api/posts?_embed=comments&_expand=category&_expand=author
- Fetching a collection of post resources sorted by the post title in descending order: http://localhost:4000/api/posts?_sort=title&_order=desc

Check out the [JSON Server README](https://github.com/typicode/json-server#table-of-contents) to see all the ways you can query for data.

JSON Server also provides all of the standard [REST API endpoints (GET, POST, PUT, and DELETE)](https://github.com/typicode/json-server#plural-routes). We used these endpoints in class when we were building [the blog application](https://codesandbox.io/s/week-7-prep-sm3f2?file=/src/App.js).

This project has been deployed to Heroku. Replace http://localhost:4000 in the URLs above with https://json-server-posts-api.herokuapp.com.
