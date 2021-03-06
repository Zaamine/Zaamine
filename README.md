# Hello everyone, I'm Amine Zaamoun

## I'm an ex-Data Scientist intern, CTO of my startup company [deuspi.fr](https://deuspi.fr/), and Student!

- I'm a highly motivated, dynamic, and ambitious 4th-year Engineering Master's student in France at the Ecole CENTRALE de Lille (ITEEM department, co-directed by Skema Business School), I am seeking a work-study contract in Data Science for the academic year 2021/2022.
- I also just finished my 8-month Data Scientist internship at Deutsche Telekom.
- My LinkedIn: [https://linkedin.com/in/amine-zaamoun][linkedin]
- The Data Science articles I wrote on Medium, republished on the [Towards Data Science](https://towardsdatascience.com/) platform, a reference in this field: https://amine-zaamoun.medium.com/

<br />

# Projects and publications:

## [Project 1: Movie recommender System in Python](https://github.com/Zaamine/Movie_Recommender_System-Python)
Implemented a Movie Recommender System which simulates an online interaction between a viewer and the platform, allowing him to get a recommendation of 10 movies according to his choices.

* Used the small version of the latest movie dataset created and indexed by MovieLens between 1995 and 2018: 100 836 ratings applied on 9742 movies by 610 users
* Step 1: Calculated the weighted average score between the popularity of a movie (its number of ratings) and the average of its ratings in order to propose to the viewer a choice of the 100 most popular movies of the Cinema
* Step 2: Made a recommendation of 5 "popular" movies using a Machine Learning algorithm: k-Nearest Neighbors (kNN) with Scikit-learn
* Step 3: Made a recommendation of 5 "less known" movies using a second Machine Learning algorithm: Alternating Least Squares (ALS) with PySpark
* Step 3 bis: Alternative for the 5 "less known" movies recommended using a Deep Learning algorithm: Deep Neural Matrix Factorization (DNMF) with Tensorflow and Keras
* Deployed the final system using the pre-computed results from the precedent models on Flask
* Used the collaborative filtering method to predict the ratings made on a 5-star scale related to each possible (userId, movieId) couple of the dataset and obtaining an RMSE of 0.87

The article I wrote about this project: [Transformation of a simple movie dataset into a functional Recommender System](https://towardsdatascience.com/transformation-of-a-simple-movie-dataset-into-a-functional-recommender-system-89c2a5a668c)

![](/images/recommender_system-screenshot_1.PNG)
![](/images/recommender_system-screenshot_2.PNG)

## [Project 2: e-Commerce Chatbot in Rasa and Python](https://github.com/Zaamine/eCommerce_Chatbot-Rasa_Python)
Implemented a Chatbot (Virtual Assistant) which automates the customer service of an e-commerce website.

* Possibility for the user to get from the chatbot:
	* answers to questions about the company and its services
	* additional information about the products sold by the company
	* a change in his account information such as the first name used on the website, phone number and email address
* Possibility for the user to make requests directly through the chatbot, such as:
	* sending a request directly to the company's customer service department so that it can be processed at a later date
	* suggesting a new product the company should sell on the website
	* providing a feedback regarding his chat experience at the end of each conversation
* Designed 22 conversation scenarios based on the writing of 2211 examples of user intents as NLU training data and 768 chatbot responses in English on the Rasa framework
* Used Rasa Open Source for the chatbot architecture
* Used Rasa Action Server to execute "custom actions" allowing the chatbot to validate forms and query a MySQL database
* Integrated the chatbot on a local copy of a PHP e-commerce website as a rest API using the Webchat plugin in JavaScript

<!-- The article I wrote about this project on [Medium](https://amine-zaamoun.medium.com/): [article title](article url) -->

![](/images/rasa_chatbot-screenshot_1.PNG)
![](/images/rasa_chatbot-screenshot_2.PNG)

## [Project 3: Creation of an e-commerce website](https://deuspi.fr/)
Implemented an e-commerce website allowing the students of the campus of my school in France to provide themselves with food delivered in 15 minutes maximum by offering them a convenience store called “DEUSPI”

* Front-end : HTML, CSS (Bootstrap) and JavaScript (jQuery)
* Back-end : PHP, jQuery’s Ajax and SQL (MySQL database)
* Ajax was mainly used to send and load information asynchronously in order to make the user experience as smooth as possible, while never leaving the product catalog page
* Twilio’s API was used to send a confirmation code to the user during registration, as well as to send additional information about his order
* Google maps’ “autocomplete” API was used to limit the scope of delivery and verify the user's address at the time of the order
* Stripe’s API has been used to secure credit card payment directly from our website without having to keep sensitive information about the user

![](/images/deuspi_website-screenshot_1.PNG)
![](/images/deuspi_website-screenshot_2.PNG)

<br />

# Languages and Tools:

[<img alt="Amine Zaamoun | Jupyter Notebooks" width="35px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/1200px-Jupyter_logo.svg.png" />][jupyter]
[<img alt="Amine Zaamoun | Python" width="35px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/768px-Python-logo-notext.svg.png" />][python]
[<img alt="Amine Zaamoun | Numpy" width="37px" src="https://user-images.githubusercontent.com/50221806/86498201-a8bd8680-bd39-11ea-9d08-66b610a8dc01.png" />][numpy]
[<img alt="Amine Zaamoun | Pandas" width="32px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/22/Pandas_mark.svg/1200px-Pandas_mark.svg.png" />][pandas]
[<img alt="Amine Zaamoun | Scikit-learn" width="70px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/1200px-Scikit_learn_logo_small.svg.png" />][scikit-learn]
[<img alt="Amine Zaamoun | PySpark" width="65px" src="https://miro.medium.com/max/400/1*VNdaFCkls0gyJR0ddP1PCQ.png" />][pyspark]
[<img alt="Amine Zaamoun | Tensorflow" width="35px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2d/Tensorflow_logo.svg/1200px-Tensorflow_logo.svg.png" />][tensorflow]
[<img alt="Amine Zaamoun | Keras" width="35px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ae/Keras_logo.svg/1200px-Keras_logo.svg.png" />][keras]
[<img alt="Amine Zaamoun | Flask" width="32px" src="https://cdn.freebiesupply.com/logos/large/2x/flask-logo-png-transparent.png" />][flask]
[<img alt="Amine Zaamoun | SQL" width="35px" src="https://e7.pngegg.com/pngimages/170/924/png-clipart-microsoft-sql-server-microsoft-azure-sql-database-microsoft-text-logo.png" />][sql]
[<img alt="Amine Zaamoun | MySQL" width="45px" src="https://upload.wikimedia.org/wikipedia/fr/thumb/6/62/MySQL.svg/1200px-MySQL.svg.png" />][mysql]
[<img alt="Amine Zaamoun | Rasa" width="35px" src="https://media.glassdoor.com/sqll/1888472/rasa-technologies-squarelogo-1560943912108.png" />][rasa]
[<img alt="Amine Zaamoun | HTML5" width="44px" src="https://www.w3.org/html/logo/downloads/HTML5_1Color_Black.png" />][html]
[<img alt="Amine Zaamoun | CSS3" width="30px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/CSS3_logo_and_wordmark.svg/1200px-CSS3_logo_and_wordmark.svg.png" />][css]
[<img alt="Amine Zaamoun | JavaScript" width="30px" src="https://www.pngfind.com/pngs/m/39-397580_logo-javascript-pattern-copyright-framework-free-download-js.png" />][javascript]
[<img alt="Amine Zaamoun | jQuery" width="70px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/JQuery-Logo.svg/1280px-JQuery-Logo.svg.png" />][jquery]
[<img alt="Amine Zaamoun | PHP" width="50px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/PHP-logo.svg/1280px-PHP-logo.svg.png" />][php]
[<img alt="Amine Zaamoun | Git" width="50px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/1280px-Git-logo.svg.png" />][git]
[<img alt="Amine Zaamoun | GitHub" width="35px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Octicons-mark-github.svg/1200px-Octicons-mark-github.svg.png" />][github]
[<img alt="Amine Zaamoun | Command Line Interface" width="55px" src="https://banner2.cleanpng.com/20180320/jbq/kisspng-computer-icons-command-line-interface-linux-system-command-line-icon-vector-5ab10e747fd445.0902485515215530125236.jpg" />][cli]

---
	
[linkedin]: https://linkedin.com/in/amine-zaamoun

[jupyter]: https://jupyter.readthedocs.io/en/latest/tryjupyter.html
[python]: https://www.python.org/
[numpy]: https://numpy.org/doc/stable/user/quickstart.html
[pandas]: https://pandas.pydata.org/docs/getting_started/index.html#intro-to-pandas
[scikit-learn]: https://scikit-learn.org/stable/
[pyspark]: https://spark.apache.org/docs/latest/api/python/pyspark.html
[tensorflow]: https://www.tensorflow.org/overview
[keras]: https://keras.io/
[flask]: https://flask.palletsprojects.com/en/1.1.x/
[sql]: https://www.w3schools.com/sql/default.asp
[mysql]: https://dev.mysql.com/doc/
[rasa]: https://rasa.com/docs/rasa/
[html]: https://www.w3schools.com/html/default.asp
[css]: https://www.w3schools.com/css/default.asp
[javascript]: https://www.w3schools.com/js/default.asp
[jquery]: https://api.jquery.com/
[php]: https://www.php.net/manual/en/intro-whatis.php
[git]: https://git-scm.com/
[github]: https://github.com/Zaamine
[cli]: https://www.w3schools.com/whatis/whatis_cli.asp
