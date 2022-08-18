# Architecture - Functionality - Testing and Reflection

**Introduction:** The Travlr web application provides vacation booking and reviews using RESTful APIs. There were two userbases for the fictional client, Travlr Getaways: administrators and customers. It was expected that the customer side would have a short user duration, a fast initial load time, and a content-focused interface. On the other hand, admins would be better served with a feature-focused system, more user interaction, a responsive UE, and a longer user duration. MEAN technologies and the MVC architectural pattern were used in this project to create a working prototype of a full-stack web application.

**Backend** The web server is based on Node.js and Express. Travlr also uses Mongoose to model object data along with MongoDB.

**Frontend** A templating engine and Express.js generate HTML in the front end. In addition, the administrator's frontend is a SPA delivered with AngularJS.

**Security** A JSON web token is used to authenticate and authorize API endpoints. A JWT is issued to their browser's local storage when the user's credentials are authenticated. Passwords are never stored in plaintext on the backend and are encrypted one way.

**Mean Stack** 

**1.** MongoDB is known for its speed and flexibility compared to SQL relational databases. Because MongoDB code is developed using BSON and JSON, it is a great candidate for MEAN stack applications primarily using JSON and JavaScript.

**2.** Express is a Node.js framework that simplifies the development of Node applications. Combining Express and Handlebars allows HTML pages to be dynamically rendered and templated.

**3.** Frontend frameworks such as Angular allow the use of SPAs. As a result of this type of architecture, the client is sent a lot of JavaScript files with the first request and can then generate all of the webpages without having to request the server again. With Angular SPAs, the server is less stressed, and the user experience is faster and more responsive. This approach has the disadvantage of making it difficult for search engines to crawl the site. SPAs also require a slow initial page load which may negatively impact the user experience.
 
**4**. Many modern web servers are created using Node.js, a software platform. Web applications are built on top of it. Because Node and Express use JavaScript as their primary programming language, learning the MEAN stack is simple since JavaScript is all you need to know.






