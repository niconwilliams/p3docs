# GeneralDocumentation

General Documentation User Forum


You are responsible for detailing the README.md with general application information, prerequisites/additional software needed to get started, Environment Variables needed to be set, etc



———————————————————_______________________________

Prerequisites/additional Software:


Spring Boot and use Junit for testing (built in testing)(backend).

Angular with sonarLint code quality running (FrontEnd)

…………………………………………………………


POST CONTROLLER









GET

/post/{id}

Retrieve posts by id


PUT

/post/{id}

Update post by id


DELETE

/post/{id}

Delete post by id


POST

/post/add

Add new post


GET

/post

Retrieves all posts


GET

/post/comments/{id}

Retrieves all comments on post by id

Comment Controller









GET

/comments/{id}

Retrieve comment by Id


PUT

/comments/{id}

Update comment by Id


DELETE

/comments/{id}

Delete comment by Id


POST

/comments/add

Add new comment


GET

/comments

Retrieves all comment


The controllers of the backend offer these features and lastly the backend is tested with Junit for errors.


The front end offers the ability for an users to post an comments;using this functionality one care read, update, and respond to comments. SonarLint helps with coding problems and analyzing the code quality.


