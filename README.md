# Project2-MIST4610

# Team Name and Members
Primary Keys:
Andrew Rhodes (https://github.com/ajr70185), Cory Abrams (https://github.com/coryabrams), Jack (John) Gallagher (https://github.com/jackgallagher15), Gracie (Virginia) Young (https://github.com/virginiayoung), Logan Miller (https://github.com/lem33453)

# Scenario Description
This iteration of our project evolves Project 1 by introducing new entities and queries to enhance the database's analytical capabilities. The main purpose remains to build a relational database that manages the operations of a movie production and distribution company. At the center of the model is the Movie entity, representing the films produced by the company and distributed across various channels, including theaters and streaming platforms. The database tracks related elements such as actors, directors, revenue, reviews, ratings, and streaming availability, along with expanded analytical capabilities 
These enhancements enable the database to provide a more comprehensive understanding of relationships between entities while solving real-world problems that were beyond the scope of the previous model. With the updated model, companies can address critical operational, financial, and strategic challenges. They can optimize financial performance, refine distribution strategies, gain insights into audience reception, and enhance customer engagement and satisfaction.
For example, the database can identify top-grossing films, determine the most profitable streaming platforms by genre, and analyze the relationship between professional ratings, fan reviews, and overall box office success. It also provides sophisticated insights into consumer engagement, integrating data on viewing patterns, reviews, and ratings to personalize marketing and content recommendations.
By leveraging these capabilities, the database becomes a powerful tool for business analysis and profitability forecasting. It empowers companies to make data-driven decisions in production, marketing, and distribution. Its ability to track performance across key dimensions—such as box office revenue, streaming platform success, and actor collaborations—ensures companies remain competitive while enhancing customer satisfaction and loyalty.



# Data Model
![FINAL FINAL FINAL Data Model](https://github.com/user-attachments/assets/b59a1e7b-d456-4594-9bbd-1b424e997546)
Since we are expanding what we completed in project 1 into project 2, we felt it was important to highlight the differences and changes made. Firstly, using the new information about advanced SQL, we were able to change table and column names with ease that were previously incorrectly labeled and to update existing entities. Our biggest addition is the Many to Many Recursive relationship between the Actor table, as there are many actor collaborations that take place in movies - not necessarily just one star actor. Additionally, we were able to add Modality and Cardinality to the model, showing whether an input should be required from entity to entity.

# Data Dictionary

# Query 1: Create a view that calculates the average rating for each genre
<img width="467" alt="Screenshot 2024-12-02 at 7 31 44 PM" src="https://github.com/user-attachments/assets/be55039e-adfa-4519-a60e-7acfef8d0706">
<img width="267" alt="Screenshot 2024-12-02 at 7 32 21 PM" src="https://github.com/user-attachments/assets/18538ae0-1832-442d-b1c7-fe2808fc724f">

Justification: Calculating the average rating for each genre allows managers to gain insight into audeince preferences and market trends. It can allow the manager to optimize their rating by aligning their movie with market trends and audience preferences. This can allow them to increase their revenue. Movies with higher ratings generally have a higher revenue.

# Query 2: Create a procedure that takes multiple parameters to filter movies by genre and range of release years
<img width="282" alt="Screenshot 2024-12-02 at 7 32 54 PM" src="https://github.com/user-attachments/assets/c81d81f0-cf19-44c4-a16b-cc99dd3b559f">
<img width="286" alt="Screenshot 2024-12-02 at 7 33 10 PM" src="https://github.com/user-attachments/assets/52074616-76c9-4119-81de-dc655b9de324">

Justification: Creating a procedure that filters movie by genre and release date allows managers to analyze trends within a specific genre over time. This allows managers to understand historical data so that they can tailor their movie to keep up with current market trends. This can lead to an increase in revenue for future movies.

# Query 3: Create a procedure that specifies an actor's name to output the total amount of movies that them and all other actors are in
<img width="348" alt="Screenshot 2024-12-02 at 7 33 50 PM" src="https://github.com/user-attachments/assets/05dafe34-3f39-49a5-b2a4-27f4ef0fa64b">
<img width="327" alt="Screenshot 2024-12-02 at 7 34 04 PM" src="https://github.com/user-attachments/assets/64ac0639-3029-41b3-b220-bfcdb2639514">

Justification: Creating a procedure that outputs the total number of movies actors have been in is valueable for understanding collaboration patterns. Actors who often work together can lead to higher audience engagenment, which can also lead to a more successful box office.

# Query 4: Create a procedure that takes in a movie's name as a perameter and returns the streaming platform that you can access the movie on
<img width="631" alt="Screenshot 2024-12-02 at 9 02 46 PM" src="https://github.com/user-attachments/assets/302b758f-b121-4c70-9cc3-ef3b0ce6b58b">
<img width="160" alt="Screenshot 2024-12-02 at 9 03 03 PM" src="https://github.com/user-attachments/assets/b89e6bdd-f8cb-466b-9e81-b5447114b1e4">

Justification: Creating a procedure that takes the movies and returns the streaming platform is important for enhancing customer experience. It allows managers to track where specific movies are available. This can aid them in decisions on which streaming platforms they want to put their movie on. 

# Query 5: Create a procedure that takes in an actor's name as a parameter and returns that actor's mentor
<img width="578" alt="Screenshot 2024-12-02 at 9 03 20 PM" src="https://github.com/user-attachments/assets/9997ec6d-3a5a-4067-ae2b-1a5d0543cf69">
<img width="203" alt="Screenshot 2024-12-02 at 9 03 30 PM" src="https://github.com/user-attachments/assets/fa8661b8-d983-47ac-be4b-f93e951a5956">

Justification: Creating a procedure that takes an actors name as a parameter and returns their mentor is valuable for understanding mentor relationships in the movie industry. It allows managers to track emerging talented actors that they can play roles in their upcoming movies.

# Tableau Dashboard: Provides information about box office revenue based on many different factors
