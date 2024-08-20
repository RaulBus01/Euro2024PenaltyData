# Euro2024PenaltyData
Euro2024PenaltyData project is a data mining and analysis initiative focused on understanding and predicting penalty kick performance for players participating in the UEFA Euro 2024 tournament
Data Collection:

    Wikipedia Scraping:
        The project starts by scraping national team squads from Wikipedia, gathering detailed information about each player.

    Player Identification:
        Each player is then matched with their unique identifier (ID) from SofaScore, a comprehensive sports data platform, to enable accurate data retrieval. 

    SofaScore API Scraping ( https://www.sofascore.com ) :
        Using the collected IDs, detailed penalty data for each player is retrieved from the SofaScore API, including metrics like the number of penalties taken, conversion rates, and penalty placement details.

Data Cleaning and Processing:

    The raw data is cleaned and processed to ensure accuracy and consistency, making it ready for comprehensive analysis and modeling.

Data Analysis and Visualization:

    Conversion Rates:
        The project calculates and visualizes the conversion rates of penalties for different players and teams, highlighting top performers.

    Top Nations Analysis:
        An analysis is conducted to identify and visualize the nations with the most penalty attempts, providing insights into teams' reliance on penalties as a scoring strategy.

    Penalty Shot Distribution:
        A goal is represented as a grid divided into 13 zones, each corresponding to an area where a penalty shot could land. This visualization reveals common targeting patterns among players.

Predictive Modeling and Clustering:

    Predictive Models:
        The project incorporates predictive modeling techniques to forecast the outcomes of penalty kicks based on historical data. These models help identify factors that increase the likelihood of a successful penalty.

    K-Means Clustering:
        K-means clustering is applied to group players based on their penalty-taking behaviors and performance metrics. This clustering helps identify distinct profiles of penalty takers, such as precision shooters, power hitters, or mixed-style players.
  
![image](https://github.com/user-attachments/assets/cfffb48c-142f-452a-80cc-fb7c6d4e6504)
![image](https://github.com/user-attachments/assets/ac8e6ea2-36be-4ec8-94a8-ef8813c8b857)
![image](https://github.com/user-attachments/assets/51c58e08-3ba2-4801-8b3d-8ba54c3c1fc7)
![image](https://github.com/user-attachments/assets/67b0780c-4ede-477a-8831-7f98c0892b60)
![image](https://github.com/user-attachments/assets/190c2709-d2b1-4c60-b078-f278416bbd24)
![image](https://github.com/user-attachments/assets/f25125f0-2002-4c97-a4be-5b2f829772c3)
![image](https://github.com/user-attachments/assets/69554e01-3a80-42fa-92ca-f0b931068c22)


