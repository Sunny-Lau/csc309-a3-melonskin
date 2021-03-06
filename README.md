<main>

  # Assignment 3
  
  ## Final Project
  
  After all the work you've put forward throughout the term, it is time to work towards the final project: a full-stack web application. Your general requirements:
  
  *   Your application must include a server-side component and a database
  *   Your application must connect to at least one external public-facing API, ideally the same one you've been working with.
  *   Your application should implement session management, allowing a variety of different users to use the application and manage their own data.
  *   Your server must implement a RESTful API that extends/improves the behaviour of any API you've chosen to work with by allowing individual users to perform the 4 basic REST operations.
  *   Your RESTful API must also implement the following 3 endpoints:
      1.  GET /api/messages
      2.  POST /api/messages
      3.  DELETE /api/messages/1234The objective of these endpoints is to allow an external administrator to "push" status messages to all users of the application, making sure each user gets to see any new messages available as quickly as possible if they are logged in. Messages should be shown in a prominent area of your main view, one at a time, but should not block the rest of the content.
  *   You are responsible for making sure your project is deployed and running throughout the one hour when it will be evaluated. Details on available timeframes below.
  *   Aside from delivering the code for your project you are expected to demo a working version of it on the week when it is due. Regardless, using the main features of your project should be intuitive enough that any user with access to your URL should be able to discover all its features.
  *   Include a `Solutions.md` explaining the features of your web application, the end-user and how s/he might use it.
  *   You are expected to work in the same teams as Assignment 2, unless a TA contacted you with a change of teams.
  *   The deadline for this assignment is Dec 4, 2017\. The last commit before 2:00 PM on that date will be used for marking the assignment. If you plan on submitting the assignment late (refer course information for more details), you should include that in your Solutions.md.
  
  If you plan on deviating from these guidelines, talk to the prof or a TA and include an Instructions.md explaining your decision.
  
  The assignment sits here: [https://classroom.github.com/g/NqxhWiJM.](https://classroom.github.com/g/NqxhWiJM)
  
  ### Marking Considerations
  
  *   Your project provides the ability to perform the 4 basic CRUD operations on your chosen collections. For example, if your project uses a Movie API, you will be evaluated on whether you allow each user to query for movies, add, delete or update their own. Even if the original API does not support these operations, you are expected to do so from your own server and relying on your own database.
  *   Your documentation about your own RESTful API is clear and concise, and demonstrates your understanding of proper REST design best practices
  *   Your project manages "messages" as expected and it is responsive in showing those messages prominently and in real-time as they are posted to the server.
  *   Your project is up and running at the time when it is evaluated
  *   Your application allows individual users to manage their own sessions without creating conflicts among themselves
  *   You will be marked on the functionality of your application, its style and usability, its responsiveness, code quality and structure, and how well the application serves your end-user.
  
  </main>