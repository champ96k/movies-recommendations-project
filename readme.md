
   In this project we will be using a 
   - Python based web framework called web2py for building APIs  
   - VueJS for building reactive HTML front-end.


#### Demo link: [Click Here](https://demo.rapidquest.in/movie_recommendation/static/index.html)


### web2py
web2py is a free open source full-stack framework for rapid development of fast, scalable, secure and portable database-driven web-based applications.

It is written and programmable in Python. LGPLv3 License 

Learn more at [http://web2py.com](https://en.wikipedia.org/wiki/Web2py)


### Installation Instructions

To start web2py there is NO NEED to install it. Just unzip and do:

      python web2py.py
      
That's it!!!

 ### Start server
 
  - web2py.py: We can start our web server by running this script:
    
            - cd Downloads/web2py_src
            - python web2py.py


### web2py directory structure

      project/
          README
          LICENSE
          VERSION                    > this web2py version
          web2py.py                  > the startup script
          anyserver.py               > to run with third party servers
          wsgihandler.py             > handler to connect to WSGI
          ...                        > other handlers and example files
          gluon/                     > the core libraries
              contrib/               > third party libraries
              tests/                 > unittests
          applications/              > are the apps
          admin/                 > web based IDE
                  ...
              examples/              > examples, docs, links
                  ...
              welcome/               > the scaffolding app (they all copy it)
                  ABOUT
                  LICENSE
                  models/
                  views/
                  controllers/
                  sessions/
                  errors/
                  cache/
                  static/
                  uploads/
                  modules/
                  cron/
                  tests/
              ...                    > your own apps
          scripts/                   > utility and installation scripts
          site-packages/             > additional optional modules



#### Web2py inherently supports MVC (Model View Controller) architecture.

   - Models: define database schema and validations
   - Views: hosts your HTML code
   - Controllers: Python code where you will write business logic and manages interactions between front-end and the database.


#### VueJS

Vue.js is an open-source model–view–viewmodel front end JavaScript framework for building user interfaces and single-page applications. It was created by Evan You, and is maintained by him and the rest of the active core team members[More info](https://vuejs.org/v2/guide/)


#### Posters 

Posters.zip contains posters for each movie in the MovieLens dataset, filename corresponds to the ‘movieId’. It is open-sourced at: https://github.com/babu-thomas/movielens-posters

     movies.json & movies_small.json contain list of dictionaries, containing ‘movieId’, ‘title’, ‘genres’.
     
     
#### Reference

  - [How to Turn Your Machine Learning Scripts into Projects You Can Demo?](https://medium.com/code-heroku/how-to-turn-your-machine-learning-scripts-into-projects-you-can-demo-cbc5611ca442)
  - [Part 2 — How to Turn Your Machine Learning Scripts into Projects You Can Demo?](https://medium.com/code-heroku/part-2-how-to-turn-your-machine-learning-scripts-into-projects-you-can-demo-467b3acff041)
 
