# JS AMAZONA

1. Create the folder strucure
    1. create the root folder as js-amazona
    2. add frontend and backend folder
    3. create src folder in the frontend folder
    4. create index.html in the src folder with a heading of JS Amazona
    5. run npm init in the frontend folder
    6. npm install live-server as a dev dependency
    7. add start command as live-server src --verbose
    8. run npm start

2. Design the website (create the skeleton)
    1. create styles.css
    2. link styles.css to the index.html
    3. create the main container div
    4. create the header, main and the footer
    5. style the html and the body
    6. style the main container, header, main and the footer

3. Build the static home page
    1. an un-ordered list for the products
    2. li and div for each product
    3. create and add the product image, name, price and brand
    4. style the prducts and the product
    5. add more products (ctrl-c ctrl-v)

4. Dynamic home page
    1. create a data.js file
    2. export an array of 6 products
    3. create js file to handle dynamic products rendering
    4. create screens/HomeScreen.js
    5. export HomeScreen as an object with a render method
    6. implement render() and return products mapped to appropriate html
    7. create app.js
    8. link to index.html as module
    9. set main id to main container
    10. create router() function
    11. set main container innerHTML to HomeScreen.render()
    12. set load event of window to router()

## URL Routing
1. create routes as route: screen object
2. create utils.js
