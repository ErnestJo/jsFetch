# jsFetch
The Fetch API provides a JavaScript interface for accessing and manipulating parts of the HTTP pipeline, such as requests and responses. It also provides a global fetch() method that provides an easy, logical way to fetch resources asynchronously across the network

# A basic fetch request is really simple to set up. Have a look at the following code:
fetch('http://example.com/movies.json')
  .then(response => response.json())
  .then(data => console.log(data));
