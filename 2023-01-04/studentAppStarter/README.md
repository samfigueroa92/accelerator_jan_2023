# Codealong Notes

Example URL: localhost:9000/students/5?name=Sam&age=30

1. What info what these properties have?

- request.method: The request method (aka "verb"). Ex: GET, POST, etc.

- request.path: The URL pathname from the request URL string of the current request (req). Note that this is the part of the URL after and including the leading slash (e.g. /foo/bar), but without the query string (e.g. ?name=foo) or fragment (e.g. #foobar.)

- request.params: An object containing parameter values parsed from the URL path.
For example if you have the route /user/:name, then the "name" from the URL path wil be available as req.params.name. This object defaults to {}.

- request.query: A dictionary containing the parsed query-string, defaulting to {}.

- request.body: An object containing text parameters from the parsed request body, defaulting to {}.

## Questions I have

- Why do we need Express.js?
- What does an API server do exactly?

## Things I think I learned
