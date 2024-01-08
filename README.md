# Final-Project-Tableau

## Project/Goals
The goal is to pinpoint the factors FIFA emphasizes in determining players' overall ratings. Focusing on the overall rating is crucial for analysis due to its significance to FIFA players, media, and the players themselves. This metric frequently takes the spotlight in FIFA marketing during game releases. Analyzing this metric provides insights into the calculations behind the scenes.

## Process

Step 1: Executed a comprehensive Exploratory Data Analysis (EDA) in Python, utilizing functions such as .describe(), .info(), etc.

Step 2: Conducted data cleaning in Python, eliminating columns like photos, flags, and club logos. Singularly selected the primary preferred position for precision. In Tableau, transformed Nationality into country/region to optimize map features.

Step 3: Developed 5 charts to visualize the overall dataset.

Step 4: Categorized preferred positions into attackers, midfielders, defenders, and goalkeepers.

Step 5: Generated visualizations of regression models tailored for each position.

Step 6: Consolidated findings into dashboards and a Tableau story.

## Results

Analyzed FIFA18 data and created diverse visualizations, such as nationality maps based on overall ratings, histograms illustrating overall rating distribution, clusters depicting wage vs value, scatter plots comparing position-wise overall ratings vs value, and a line graph examining age vs overall between defenders and non-defenders.

Key findings revealed that the top 3 attributes with the highest R-squared for overall ratings vary by position—attackers: Ball Control, Position, and Reactions; defenders: Interceptions, Marking, and Reactions; goalkeepers: Diving, Positioning, and Reflexes.

Notably, overall ratings display a bell curve, indicating FIFA's intentional adherence to this distribution to balance ratings across positions. This strategy ensures a well-distributed range of ratings, preventing an overabundance of either low or high ratings.

## Challenges 

Navigating through the multitude of columns and attributes presented a significant challenge, especially when pinpointing the attributes with the highest R-squared for each position. Determining which columns deserved attention and which ones could be disregarded introduced an additional layer of complexity to the analysis.

## Future Goals

For future analyses, delving into individual positions to identify the most influential attribute for overall ratings could offer valuable insights. Moreover, exploring the correlations between age, value, and wage with overall ratings might provide additional layers of understanding.
