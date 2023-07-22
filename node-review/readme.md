# Node workshop

In this workshop, we'll build up a NodeJS app from the ground up and check our understanding as we go along.

Remember to preview the `README` first.

## Level 300

Welcome to Node Workshop Level 300.

## Questions

Q1) Define an **API**
Answer: API stands for Application Programming Interface. It is a software intermediary that allows two applications to communicate with each other

Q2) What is the purpose of an **API**
Answer: Is to enable communication and interaction between different software applications or components

Q3) Define an **endpoint**
Answer: An endpoint can also refer to a software interface that enables two applications to communicate with each other.
If you're unsure about the questions above, then try starting a discussion with another pair.

## Requirements

We need to set up a **single endpoint**.

For this endpoint, a client application should be able to make a GET request to the "/" endpoint at localhost:9090
and the server should respond with a message "You've successfully reached the server"

Firstly,

Q4) Look inside `app.js`.

On line 12, we need to pass some arguments ( inputs ) to the `server.get` method.
What type of inputs should we pass to the `server.get` method? Use the express documentation to check your answer.

{YOUR_ANSWER_HERE}
We need to pass argument expression and function(request,response)