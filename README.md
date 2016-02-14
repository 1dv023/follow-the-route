# Follow the route

In this excercise you should train your ability to create routes in express.js and render som simple views.

## The assignment
You should set up an application that follow this rules:

1. The application should listen to port 8000.

2. When the client asks for the root URL a static file (index.html) should be responded to the client.

3. The application should have a main layout defining a templete for all dynamic views.

4. When the client asks for the "/products" URL a view should be render that output a HTML document with the hardcoded text "This is the page where all products should be shown".

5. When the client asks for the "/products/:id" URL a view should be render that output a HTML document with the hardcoded text "This is the page where the product with the id = :id is shown". If the clienten request /products/231 the text should be: "This is the page where the product with the id = 231 is shown".

6. When the client asks for the "/products/create" URL a view should be render with a simple HTML formular should be shown. The form should have a button that posts the form to the URL described in point 7.

7. When the client posts the form above a function should be called that redirects the client to the URL "/products".

8. When the client calls a URL that does is defeined above a nice 404-page should be render.

9. The application should be able to handle errors

## Vagrant
If you need a vagrant with node.js use https://github.com/1dv023/node-mongodb-vagrant.

