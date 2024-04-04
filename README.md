# Netflix-Movies-And-TV-Shows-Clustering-final-Iteration



![Local GIF](venti-views-lI7dlA5VBp8-unsplash.jpg)
Photo by <a href="https://unsplash.com/@ventiviews?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Venti Views</a> on <a href="https://unsplash.com/photos/white-and-black-concrete-building-during-night-time-lI7dlA5VBp8?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
  
  

<h3 align="Left">
  <br>
 <h2>Problem Statement</h1>
<br>
The task at hand revolves around delving into the Netflix dataset to extract insights into the platform's content. This dataset encompasses details about both movies and TV shows, including their attributes and availability across different regions. By merging this dataset with external sources such as IMDB ratings and Rotten Tomatoes, we can unlock further valuable insights.
<ul>
<h2>Project Steps</h1>

<br>
<li>1.EDA(Exploratory Data Analysis:
<br>
Clean the dataset, unpack the Netflix content, address null/missing values, and conduct a comprehensive analysis to unveil trends, patterns, and correlations among various attributes.</li>
<br>
<br>
<li>2.Understanding Content Availability:
<br>
Identify the types of content available across different countries and discern any variations or preferences.</li>
<br>
<br>
<li>3.Analyzing Netflix's Focus:
<br>
Explore whether Netflix has shown a tendency towards prioritizing TV shows over movies in recent times.</li>
<br>
<br>
<li>4.Clustering Similar Content:
<br>
Utilize text-based features to group similar content, paving the way for the development of a content-based recommender system.</li>
<br>
</ul>
<br>
  <br>
 <h2>Project Summary</h1>
<br>
<br>
 <h2>Problem Statement:</h1>
<br>
This project centers on a dataset comprising TV shows and movies available on Netflix as of 2019, sourced from Flixable, a third-party Netflix search engine. Over recent years, Netflix has undergone a notable shift, witnessing a significant rise in TV shows while the number of movies has declined. The aim is to extract meaningful insights from this dataset and explore potential synergies with external datasets such as IMDB ratings and Rotten Tomatoes.

  <br>
 <h2>Project Summary</h1>
<br>
The aim of this project is to analyze a dataset containing TV shows and movies available on Netflix as of 2019, obtained from Flixable, a third-party Netflix search engine. The dataset consists of 7,787 rows and 12 columns, with no duplicate entries. However, several features exhibit missing values. It provides crucial information about content types (TV show or movie), titles, directors, casts, production countries, Netflix addition dates, release dates, durations, ratings, and descriptions.

The project follows a structured approach, outlined below:
<ul>
<li>Addressing Missing Values:
Rectify any null or missing values present in the dataset.</li>

<li>Handling Nested Columns:
Process nested columns like director, cast, listed_in, and country to facilitate clear visualization and analysis.</li>

<li>Rating Categorization:
Categorize ratings into suitable categories such as adult, children's, family-friendly, and unrated content.</li>

<li>Exploratory Data Analysis (EDA):
Conduct thorough EDA on various attributes, unearthing valuable insights to aid in churn prevention.</li>

<li>Cluster Formation:
Form clusters using attributes like director, cast, country, genre, rating, and description. Tokenize, preprocess, and vectorize attribute values using TF-IDF vectorizer.</li>

<li>Dimensionality Reduction:
Reduce dataset dimensionality using Principal Component Analysis (PCA) to enhance performance.</li>

<li>Clustering Algorithms:
Employ K-Means Clustering and Agglomerative Hierarchical Clustering algorithms to construct two distinct cluster types. Determine the optimal number of clusters using techniques like the Elbow method, Silhouette score, and Dendrogram.</li>

<li>Content-Based Recommender System:
Develop a content-based recommender system using the cosine similarity matrix. This system analyzes the user's watched shows and generates personalized recommendations to enrich their experience.</li>
</ul>

EDA Findings
Movies constitute approximately 69.1% of the content, with TV shows comprising around 30.9%.
The content is predominantly aimed at adults and teenagers, with no TV shows rated for general audiences.
Most movies have a duration of 90 to 120 minutes, while TV shows typically consist of a single season.
Netflix witnessed a significant surge in content additions post-2015, peaking in November 2019 for both TV shows and movies.
Content is frequently added on the 1st and 15th of each month.
There's been a consistent uptrend in content releases, particularly post-2008, with notable declines in 2018 and 2020.
International movies and TV shows are the most popular genres, followed by dramas and comedies.
The USA leads in content production, trailed by India and the United Kingdom.
Noteworthy directors include Jan Suter, Raul Campos, Jay Karas, Alastair Fothergill, and Ken Burns.
Renowned cast members include Anupam Kher, Shah Rukh Khan, Naseeruddin Shah, Takahiro Sakurai, Yuki Kaji, and Daisuke Ono.
Most top-producing countries generate adult-oriented content, except India, which leans towards content suitable for teenagers.
Common words in descriptions include family, friend, life, find, two, take, world, woman, live, and love.
Machine Learning Conclusion:
I applied K-Means and Hierarchical Agglomerative clustering techniques to cluster the dataset.
K-Means with 5 clusters was chosen as the final model due to well-defined clusters and a high Silhouette score.
The Silhouette score served as the evaluation metric, indicating the quality of clusters.
Additionally, I developed a recommendation system for personalized content suggestions based on similarity scores.
