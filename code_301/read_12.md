# C.R.U.D

## Which HTTP Status Code to Use for Every CRUD App

* In your own words, describe what each group of status codes represents:
  * 100’s = informational status code. Returns information about the header and if the page is likely to load.
  * 200’s = success codes mostly. Tells the client-side if their req is accepted.
  * 300’s = codes focused on redirection. What you are looking for is not where you think it is.
  * 400’s = error codes associated with the client-side.  when something goes wrong these codes should be able to help.
  * 500’s = errors on the server-side. Any server issues should be in this group.
* What is status code 202?
  * Accepted - used in async processing. Tells you that the code is valid.
* What is status code 308?
  * Permanent Redirect - tells the client this is the new address and location. redirecting the clients.
* What code would you use if an update didn’t return data to a client?
  * 204 No Content
* What code would you use if a resource used to exist but no longer does?
  * 410 Gone
* What is the ‘Forbidden’ status code?
  * 403 - the client client does not have permission to access.

## Build A REST API With Node.js, Express, & MongoDB - Quick

* Why do we need to pull our MongoDB database string out of our server and put it into our .env?
  * so the information is protected and not shared.
* What is middleware?
  * code that runs after a server gets a request but before it hits the routes.
* What does app.use(express.json()) do?
  * lets you read JSON files.
* What does the /: id mean in a route?
  * lets you identify a specific route if you only wanted to select one.
* What is the difference between PUT and PATCH?
  * patch only updates the information that was given and leaves all other fields alone. where PUT updates all fields.
* How do you make a default value in a schema?
  * set this up in a model
* What does a 500 error status code mean?
  * error on the server. No issue on the client-side.
* What is the difference between a status 200 and a status 201?
  * 201 is more specific that you created something and it was successful.

## Things I want to know more about

Ploesser, Kay "Which HTTP Status Code to Use for Every CRUD App" Moesif, 15 Apr 2021, <https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/>

"Build A REST API With Node.js, Express, & MongoDB - Quick" YouTube, uploaded by Web Dev Simplified, 14 May 2019, <https://www.youtube.com/watch?v=fgTGADljAeg>.

All definitions and information came from the above-listed publication(s).

[<===Back>](README.md)
