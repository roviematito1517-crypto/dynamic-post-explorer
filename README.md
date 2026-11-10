# dynamic-post-explorer

Description
Dynamic Post Explorer is a simple web application that loads blog posts from the JSONPlaceholder API. It uses JavaScript Fetch API and displays the first five posts without refreshing the page.

Files
`index.html` - contains the page structure.
`style.css` - contains the basic page design.
`script.js` - fetches and displays the posts.
`screenshots/` - contains sample screenshots of the success and error states.

API Used
https://jsonplaceholder.typicode.com/posts

Required Behaviors
Load Button Integration: The Load Posts button starts the request when clicked.
Async/Await: The `loadPosts()` function uses `async` and `await`.
First 5 Posts Limit: `slice(0, 5)` selects only the first five posts.
Safe DOM Rendering: `createElement()` and `textContent` are used to display API data safely.
Loading Indicator: A loading message appears while the request is running.
Error Handling: The `try...catch` block displays an error message if the request fails.
Retry Capability: The button is enabled again after the request, allowing another attempt.
No Page Refresh: JavaScript updates the page directly without reloading it.
Screenshots

The screenshots folder contains visual examples of the success and error states. The error state can be seen if the API request fails, for example when the internet connection is unavailable.
