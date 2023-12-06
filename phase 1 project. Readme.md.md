# Overview

The project involves Microsoft's exploration into the creation of a new movie studio. The overarching goal is to gain actionable insights from the cinematic landscape, focusing on genres, ratings, financial performance, audience engagement, and other relevant factors. The project comprises data preparation, exploratory data analysis (EDA), and the derivation of strategic recommendations based on the insights gleaned from the analysis. Key datasets include Movie Basics, Movie Ratings, and BOM Movie Gross, which are analyzed individually and then integrated for a comprehensive understanding of the movie industry. The methods employed involve data cleaning, statistical analysis, and visualization techniques to guide Microsoft in making informed decisions for a successful entry into the filmmaking domain.

# Business Understanding:

**Stakeholders**

- **Microsoft Leadership Team:**  Responsible for strategic decision-making and overall success of Microsoft's new venture into the movie industry.

- **Content Creation Team:** Tasked with developing and producing movies that align with audience preferences and financial viability.

- **Marketing Team:** Charged with promoting and distributing the movies effectively to maximize audience reach and revenue.

# Key Business Questions:

- 1.**Genre Strategy**

**Question:** What genres are currently popular, and how should Microsoft strategically position its content creation to maximize audience appeal and market success?

**Objective:** Identify the most promising genres to inform Microsoft's content creation strategy.

- 2. **Audience Engagement**

**Question:** How do audience ratings and engagement (numvotes) correlate with movie attributes, and what strategies can enhance audience interaction with Microsoft's content?

**Objective:** Understand factors influencing audience engagement and identify strategies to boost interaction.

- 3. **Financial Performance**

**Question:** What are the key financial indicators, including correlations between domestic and foreign gross, and how can Microsoft optimize its financial success in the movie industry?

**Objective:** Maximize revenue by understanding financial patterns and market dynamics.

- 4. **Content Duration Optimization**

**Question:** What is the ideal movie runtime that aligns with audience preferences, and how can Microsoft optimize content duration for success?

**Objective:** Determine optimal movie runtime to enhance viewer satisfaction and engagement.

- 5. **Global Market Strategy**

**Question:** How can Microsoft strategically approach the global market, considering variations in financial success and audience preferences?

**Objective:** Develop a market-specific approach for global success.

- 6. **Decision-Making Support**

**Question:** How can data-driven insights guide Microsoft's decision-making in content creation, marketing, and overall business strategy?

**Objective:** Provide actionable recommendations based on comprehensive data analysis.
Competitive Landscape:

**Question:** How does Microsoft's potential entry into the movie industry compare with existing competitors, and what can be learned from industry trends?

**Objective:** Understand the competitive landscape and position Microsoft strategically.

- 7. **Content Portfolio Optimization**

**Question:** What should be the composition of Microsoft's initial content portfolio to balance genre diversity, financial success, and audience satisfaction?

**Objective:** Optimize the content portfolio for a successful market entry.
Addressing these key business questions will equip Microsoft with valuable insights to make informed decisions, enhance competitiveness, and foster success in the dynamic and competitive movie industry.

# Data Understanding and Analysis

# Source of Data

The primary datasets used for this analysis are as follows:

**Movie Basics**

Source: IMDb Datasets (https://www.imdb.com/interfaces/)
Description: Contains fundamental details about movies, including titles, genres, release years, and runtime.

**Movie Ratings**

Source: IMDb Datasets (https://www.imdb.com/interfaces/)
Description: Provides information about movie ratings, including average ratings and the number of votes.

**BOM Movie Gross**

Source: The Numbers (https://www.the-numbers.com/)
Description: Focuses on financial aspects of movies, including domestic and foreign gross, studio information, and release years.

# Description of Data

**Movie Basics**

**Features**
movie_id: Unique identifier for each movie.
primary_title: Title of the movie.
original_title: Original title of the movie.
start_year: Release year of the movie.
runtime_minutes: Duration of the movie in minutes.
genres: Genres associated with the movie.

**Movie Ratings**

**Features**
movie_id: Unique identifier for each movie.
averagerating: Average rating of the movie.
numvotes: Number of votes the movie received.

**BOM Movie Gross**

**Features**
title: Title of the movie.
studio: Studio associated with the movie.
domestic_gross: Domestic box office gross revenue.
foreign_gross: Foreign box office gross revenue.
year: Release year of the movie.

**Integrated Data (Master Dataset)**

Merged information from Movie Basics, Movie Ratings, and BOM Movie Gross.
Integrated features for comprehensive analysis, including financial metrics, audience ratings, and content details.

**Temporal Considerations**

The data spans from 2010 to 2018, capturing a significant period in the cinematic landscape.

**Genre Distribution**

Comedy is identified as the most prevalent genre based on the analysis.
Financial Metrics:

A strong positive correlation (0.82) between domestic and foreign gross suggests consistent financial performance.
Runtime Preferences:

The average movie runtime from 2010 to 2018 falls within the 105 to 115-minute range.
Audience Engagement:

A weak negative correlation (-0.05) between the number of votes (numvotes) and the start year indicates nuanced relationships.
Strategic Implications:

These insights provide valuable guidance for Microsoft's content creation, financial strategies, and global market entry.
In summary, the datasets offer a rich source of information for understanding audience preferences, financial dynamics, and genre trends, allowing for informed decision-making as Microsoft ventures into the movie industry.

# Visualizations

**Genre Distribution Bar Chart**

- ![Genre Distribution](https://github.com/liciemw/README.md/blob/main/download.png)

**Correlation Heatmap**

- ![Correlation Heatmap](https://github.com/liciemw/README.md/blob/main/download%20(3).png)

**Distribution of Movie Runtimes Histogram**

- ![Movie Runtimes](https://github.com/liciemw/README.md/blob/main/download%20(2).png)

# Conclusion

After an in-depth exploration of the cinematic landscape through data analysis, several key findings have emerged, providing valuable insights for Microsoft's venture into the movie industry.

**Genre Preferences**

Comedy stands out as the most frequently produced genre, indicating a strong audience preference for humorous content.
 Microsoft's movie studio can strategically focus on creating and promoting comedy films to align with audience preferences and maximize market appeal.

**Financial Dynamics**

There is a robust positive correlation (0.82) between domestic and foreign gross, signifying consistent financial performance in both markets.
 Microsoft can capitalize on this correlation by formulating global distribution strategies and investing in content that resonates with diverse audiences worldwide.

**Audience Engagement Patterns**

The average number of votes (numvotes) has a weak negative correlation (-0.05) with the start year, suggesting nuanced relationships between audience engagement and the release timeline.
 Microsoft should consider factors influencing audience engagement over time, potentially tailoring marketing strategies based on evolving audience behaviors.

**Strategic Recommendations**

**Strategic Genre Focus:** Prioritize the production of comedy films while diversifying content to meet a range of audience preferences.

**Global Distribution Strategies:** Develop distribution strategies that leverage the strong correlation between domestic and foreign gross, ensuring a global reach for Microsoft-produced films.

**Dynamic Marketing Approaches:** Implement dynamic marketing approaches that account for changing audience engagement patterns, utilizing data-driven insights for targeted promotional campaigns.

**Conclusion Overview**

The cinematic data analysis not only sheds light on current industry trends but also provides actionable recommendations for Microsoft's new movie studio. By aligning content creation strategies with audience preferences and leveraging financial correlations, Microsoft can position itself for success in the competitive movie landscape.
