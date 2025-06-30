# Hello everyone, I'm Amine Zaamoun

### President of the [Data Oriented Thinking society](https://www.linkedin.com/company/dot-essec-centrale/mycompany) (DOT) of ESSEC & CentraleSupélec in the Master of Data Sciences & Business Analytics | Centrale Lille accredited Engineer

- I'm a highly motivated, dynamic, and ambitious accredited Engineer from Centrale Lille and postgraduate Data Science & Business Analytics student at CentraleSupélec and ESSEC with more than 1.5 years of experience in internship and apprenticeship as a Data Scientist (Deutsche Telekom and Crédit Agricole Consumer Finance). I am currently a Business Intelligence Engineer intern at Amazon in the Paris office.
- My LinkedIn: [https://linkedin.com/in/amine-zaamoun][linkedin]
- The Data Science society at CentraleSupélec and ESSEC I chair this year: https://www.linkedin.com/company/dot-essec-centrale/mycompany
- The Data Science articles I wrote on Medium, republished on the [Towards Data Science](https://towardsdatascience.com/)'s platform, a reference in this field: https://amine-zaamoun.medium.com/
- The article I wrote on DataScientest.com (in French), giving an overwiew of the top 10 important mathematical notions to get started in Data Science: https://datascientest.com/top-10-des-pre-requis-mathematiques-importants-en-data-science

<br />

# Projects and publications:
## [Project 1: Movie Recommender System in Python](https://github.com/Zaamine/Movie_Recommender_System-Python)
Implemented a Movie Recommender System in Python which simulates an online interaction between a viewer and a platform, allowing him to get a recommendation of 10 movies according to his choices.

* Used the small version of the latest movie dataset created and indexed by MovieLens between 1995 and 2018: 100 836 ratings applied on 9742 movies by 610 users
* Step 1: Calculated the weighted average score between the popularity of a movie (its number of ratings) and the average of its ratings in order to propose to the viewer a choice of the 100 most popular movies of the Cinema
* Step 2: Made a recommendation of 5 "popular" movies using a Machine Learning algorithm: k-Nearest Neighbors (kNN) with Scikit-learn
* Step 3: Made a recommendation of 5 "less known" movies using a second Machine Learning algorithm: Alternating Least Squares (ALS) with PySpark
* Step 3 bis: Alternative for the 5 "less known" movies recommended using a Deep Learning algorithm: Deep Neural Matrix Factorization (DNMF) with Tensorflow and Keras
* Deployed the final system using the pre-computed results from the precedent models on Flask
* Used the collaborative filtering method to predict the ratings made on a 5-star scale related to each possible (userId, movieId) couple of the dataset and obtaining an RMSE of 0.87 (less than 1 star of error)

The article I wrote about this project: [Transformation of a simple movie dataset into a functional Recommender System](https://towardsdatascience.com/transformation-of-a-simple-movie-dataset-into-a-functional-recommender-system-89c2a5a668c)

![](/images/recommender_system-screenshot_1.PNG)
![](/images/recommender_system-screenshot_2.PNG)

## [Project 2: e-Commerce Chatbot in Rasa and Python](https://github.com/Zaamine/eCommerce_Chatbot-Rasa_Python)
Implemented a Chatbot (Virtual Assistant) in Python which automates the customer service of an e-commerce website.

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

## Project 3: Creation of an e-commerce website
Implemented an e-commerce website allowing the students of the campus of my school in France to provide themselves with food delivered in 15 minutes maximum by offering them a convenience store called “DEUSPI”.

* Front-end : HTML, CSS (Bootstrap) and JavaScript (jQuery)
* Back-end : PHP, jQuery’s Ajax and SQL (MySQL database)
* Ajax was mainly used to send and load information asynchronously in order to make the user experience as smooth as possible, while never leaving the product catalog page
* Twilio’s API was used to send a confirmation code to the user during registration, as well as to send additional information about his order
* Google maps’ “autocomplete” API was used to limit the scope of delivery and verify the user's address at the time of the order
* Stripe’s API has been used to secure credit card payment directly from our website without having to keep sensitive information about the user

![](/images/deuspi_website-screenshot_1.PNG)
![](/images/deuspi_website-screenshot_2.PNG)

## [Project 4: Management of the training division of Centrale AI](https://github.com/Zaamine/Centrale_AI)
Former Training Manager of the “Centrale AI” association (“Centrale IA” in French) constituted in accordance with the French law of 1901 concerning non-profit organizations, allowing students of the Ecole Centrale de Lille to discover the Artificial Intelligence and Data Science's world:

- Established, supervised and presented complete trainings in Data Science, using the Python programming language
- Organized face-to-face or online meetings with Data Scientists of key accounts and startup companies, allowing students to extend their knowledge and professional network
- Organized events in connection with Data Science and prepared with my team a Hackathon gathering students from all schools of the “Groupe Centrale” in order to let them collaborate and challenge themselves

Video of the training on the Python library Numpy: [youtube.com/watch?v=LBIimDl2QHk](https://www.youtube.com/watch?v=LBIimDl2QHk&ab_channel=CentraleIA) \
Video of the training on the Python library Pandas: [youtube.com/watch?v=kTL-CetEbfA](https://www.youtube.com/watch?v=kTL-CetEbfA&ab_channel=CentraleIA) \
Events: [centraleia.fr/evenements](https://centraleia.fr/evenements/) and [centraleia.fr/conference](https://centraleia.fr/conference/)

<p float="left">
	<a href="https://github.com/Zaamine/Centrale_AI/blob/main/1.Les_bases_1-Numpy/Numpy-librairie_calcul_optimise.ipynb" rel="formation numéro 1 Centrale IA Amine Zaamoun"><img alt="Affiche formation numéro 1 Centrale IA Amine Zaamoun" width="499px" src="/images/affiche_formation_1.png" /></a>
	<a href="https://github.com/Zaamine/Centrale_AI/blob/main/2.Les_bases_2-Pandas/Pandas_librairie_analyse_donnees.ipynb" rel="formation numéro 2 Centrale IA Amine Zaamoun"><img alt="Affiche formation numéro 2 Centrale IA Amine Zaamoun" width="499px" src="/images/affiche_formation_2.jpg" /></a>
	<a href="https://github.com/Zaamine/Centrale_AI/blob/main/5.Interpretabilite_et_ML/Interpretabilite_des_modeles_de_ML.ipynb" rel="formation numéro 5 Centrale IA Amine Zaamoun"><img alt="Affiche formation numéro 5 Centrale IA Amine Zaamoun" width="499px" src="/images/affiche_formation_5.png" /></a>
</p>

## [Project 5: Presidency of the Data Oriented Thinking society (DOT)](https://www.linkedin.com/company/dot-essec-centrale/mycompany)
The objective of DOT is to democratize Data Science by allowing students from all backgrounds at ESSEC and Centrale-Supélec to gain a thorough understanding of the domain and its different applications. As our world revolves increasingly around data collection, mining, predictions, and interpretations, it is essential for leaders of tomorrow to fully grasp data-oriented thinking. Indeed, outside the context of specific teachings such as the Master in Data Sciences & Business Analytics program in both schools, we have seen that this theme is often viewed as a distant subject and reserved for certain fields of study.

We, therefore, want to democratize the "hard" and "soft" skills that define this discipline to any interested student. This association wants to focus on this mix of know-how in order to apply it to problems that companies, institutions, or non-governmental organizations may encounter.
Students will learn from diverse sources of information: student-led workshops, masterclasses organized by companies, conferences from institutions, and much more. Through DOT, we wish to provide not only the basics to advanced theoretical knowledge on data science and analytics but also show the numerous practical uses of their realm (business, environmental, societal, health...). We also wish to formulate the forthcoming problematics of a data-driven world (biases, fake news, energy consumption, health crisis impact...).

- Managed a team of 13 other students to achieve DOT's goals
- Managed to negotiate several partnerships with key players in the world of Data Science: [Artefact](https://www.artefact.com/), [DataScientest](https://datascientest.com/), [Sia Partners](https://www.sia-partners.com/) and [Ekimetrics](https://ekimetrics.com/)
- Supervised the organization of several events throughout the year (coaching sessions with consultants, hackathons, masterclasses and networking events)
- Supervised the organization of in-house workshops in Data Science and its business applications in different industries
- Supervised writing of in-house articles in Data Science and its business applications in different industries

<p float="left">
	<a href="https://www.linkedin.com/feed/update/urn:li:activity:6997199790107193344" rel="DOT members"><img alt="DOT members image" width="499px" src="/images/DOT_members.jfif" /></a>
	<a href="https://www.linkedin.com/posts/artefact-global_data-ia-datascience-activity-7019723395445477378-Zo8p" rel="DOT partnership with Artefact"><img alt="DOT partnership with Artefact image" width="499px" src="/images/DOT_partnership_with_Artefact.jfif" /></a>
	<a href="https://www.linkedin.com/pulse/unlocking-power-data-science-how-gaming-companies-transforming-/?trackingId=eiQMjRfFonZVk9K%2BC1rSAg%3D%3D" rel="DOT gaming in Data Science article"><img alt="DOT gaming in Data Science image" width="499px" src="/images/DOT_gaming_in_data_science_article.png" /></a>
</p>

## [Project 6: Analyzing Arsenal 2003-2004 Invincibles run using Network Science](https://github.com/Zaamine/Analyzing_Arsenal_2003_2004_Invincibles_run_using_Network_Science/blob/main/MLNS_Project-Arsenal_Invincibles_run-ZAAMOUN-CORNELUS_JOUAIDI_ELBIARI.pdf)

Analyzed Arsenal FC’s unbeaten Premier League season using advanced graph-based techniques to extract tactical and structural insights from match data.

* Built passing networks for each match with players as nodes and passes as weighted edges using StatsBomb’s event data API
* Computed key graph metrics (degree, betweenness, closeness, eigenvector centrality, PageRank, etc.) to identify key players and their tactical roles
* Used xG (Expected Goals) modeling and passing flow analysis to highlight game momentum and performance peaks across key matches
* Trained a Graph Convolutional Network (GCN) to classify match outcomes based on passing network structure, achieving 75% accuracy despite a small dataset
* Quantified continuity of the starting XI throughout the season using Graph Edit Distance and Node2Vec embeddings with cosine similarity

📄 Paper: *Analyzing Arsenal 2003–2004 Invincibles run using Network Science*  
🗂 Status: Internal academic project — available in [this](https://github.com/Zaamine/Analyzing_Arsenal_2003_2004_Invincibles_run_using_Network_Science/blob/main/MLNS_Project-Arsenal_Invincibles_run-ZAAMOUN-CORNELUS_JOUAIDI_ELBIARI.pdf) link

![](/images/Arsenal_Invincibles_season-Figure_1_Average_passes_network.jpeg)
![](/images/Arsenal_Invincibles_season-Figure_3_Henry_heatmap_against_Leeds.jpeg)
![](/images/Arsenal_Invincibles_season-Figure_4_Participation_of_Pires_in_progressive_passes_against_Liverpool.jpeg)
![](/images/Arsenal_Invincibles_season-Figure_5_xG_flow_chart_against_Man_City.jpeg)

## [Project 7: Building a BI Decision-Support Dashboard for FC Barcelona’s Post-Messi Era](https://github.com/Zaamine/FC_Barcelona_Business_Intelligence_Dashboard/blob/main/BI%20final%20project%20presentation.pdf)

Created a comprehensive and interactive Tableau dashboard using real-life match statistics and FIFA<sup>TM</sup> video game attributes to support FC Barcelona's team management following Messi’s departure.

* Combined five seasons of match event data (StatsBomb) with FIFA<sup>TM</sup> in-game player statistics to analyze player evolution, form, and suitability for future roles
* Built data pipelines in Python for extraction, cleaning, merging, and enhancement of datasets, transforming raw stats into actionable features
* Modeled the data using both a conceptual ER schema and a logical snowflake schema, enabling dynamic linking of player, club, season, and match statistics
* Designed visualizations for performance tracking, radar-based skill comparison, and strategic planning: player renewal/sale decisions, match strategy, and talent identification
* Delivered four key insights through a dashboard story format in Tableau, including Messi’s impact, aging squad concerns, renewal/sale decisions, and internal youth talent recommendations

📊 Tools used: Python, pandas, Tableau, StatsBomb API, FIFA<sup>TM</sup> video game datasets
📁 Project presentation available in [this](https://github.com/Zaamine/FC_Barcelona_Business_Intelligence_Dashboard/blob/main/BI%20final%20project%20presentation.pdf) link -  dashboard available upon request

![](/images/FC_Barcelona_Business_Intelligence_Dashboard-screenshot_1.png)
![](/images/FC_Barcelona_Business_Intelligence_Dashboard-screenshot_2.png)

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
