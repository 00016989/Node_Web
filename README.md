Before everything run codes:
    npm install -y
    npm i express express-validator pug body-parser nodemon


The Event CRUD website embodies the essence of efficiency and organization in managing events effortlessly. With its intuitive CRUD functionalities, users are empowered to seamlessly create, read, update, and delete events with utmost convenience. At its core, this application serves as a digital assistant for event organizers, providing them with a centralized platform to coordinate and maintain event-related information.

One of the key features of this website is its ability to capture essential event details, including location, description, and time. By offering a structured input mechanism, users can ensure that all pertinent information is accurately recorded and readily accessible. Whether it's a small gathering or a large-scale conference, the website accommodates events of various scales and complexities.

Moreover, the user interface of the Event CRUD website is designed with simplicity and functionality in mind. Navigating through the application is a breeze, allowing users to focus on the task at hand without unnecessary complexities. Additionally, the website's responsiveness ensures seamless access across different devices, enabling users to manage events on the go.

In essence, the Event CRUD website revolutionizes event management by harnessing the power of technology to streamline processes and enhance productivity. By providing a robust platform for creating and managing events, this application empowers organizers to execute memorable and successful events with ease.

Github repo: https://github.com/00016989/Node_Web/tree/master

I could not sign up to Amazon because of billing issues, they kept ask it as verify you credit card and having issues.



Structured files of Website

the folder containing controller logic which shows which services (web services, etc) will be used in order to handle routed actions
    /controllers
        /api
            /event
                index.js
        /web                    
            /home
                index.js
    
Data of website   
    /data
        mock_db.json

public folder is for keeping files essential for building user-interface (client-side)
    /public
        /css
            styles.css
        j/s
            scripts.js

    
route files will keep controllers/handlers for specific route groups. indicated route names are examples and a student must name his/her own route files depending on the context.    
    /routes
        /api
            /event
                index.js
            index.js
        /web
            /home
                index.js
            index.js

The folder containing service layer logic   
    /services
        /event
            index.js        

    /validators
        /event
            index.js

name for the ‘templates’ folder is expected but not required. This can be changed but requires specific steps.    
    /views
        /home
            index.pug 
            add_update.pug
        head.pug

    app.js  the name of the file
    package.json project configuration file. usually initiated with
    package-lock.json
    .gitignore
    README.md
