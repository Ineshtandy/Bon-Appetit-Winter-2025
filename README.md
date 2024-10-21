# Bon-Appetit-Winter-2025

## Overview
New York City, known as the culture capital of the world, is the brewing pot for a fresh shot of rich diverse cultural experiences from all across the globe. This makes New York to be a great place for an enriching cullinary exploration. From a quick hot dog on the run, or a satisfying pizza after a long work day, or a comforting bowl of ramen on a snowy morning, New York has everything one's taste buds can ever dream of. However, the hunt for healthy food can hinder an individual's experience of New York. Therefore, this data analysis project aims to create a resourceful tool that helps food enthusiasts find restaurants free of health violations. This project leverages the health inspection data as provided by the city of NY itself (availale at NYC Open Data) and cross references with the wealth of information from Google Maps API to filter the best establishments catering to the needs of every individual.

## Conclusion
This project is for anyone who loves food and is planning to visit New York in the Winter of 2025. The results of this project can be an addition to your cullinary adventure on the streets of NY or maybe the motivation you need to finally make the trip to The Big Apple. This is your stop for a healthy, tasty, pocket friendly random list of 25 establishments to visit during your 5 day trip, ensuring you are both healthy and happy while making sure there's never a dull moment in your trip!

### Base Dataset: [Link to NYC Open Data](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j/about_data)

### Google Cloud:
The APIs used for supporting the development of this project are as follows:
1. **Places API (New)**
2. **Geocoding API**
3. **Geolocation API**
4. **Maps JavaScript API**
5. **Places API**
6. **Google Cloud APIs**
7. **Google Cloud Storage JSON API**
8. **Maps Static API**

**Demo Map with all data points**
<img width="1216" alt="Demo" src="https://github.com/user-attachments/assets/46790b2f-6d2e-4a42-8239-a48ca60d2dde">


### Final Interactive Map Image:
<img width="1212" alt="Final Result" src="https://github.com/user-attachments/assets/ef7c5984-39d7-434f-90be-c22351fc9083">


### Reflections and Takeaways
- **Data Analysis Skills**: Gained hands-on experience in analyzing and interpreting health inspection data, honing my ability to derive actionable insights from complex datasets.

- **Proficiency in Data Cleaning and Preparation**: Developed expertise in cleaning and preparing large datasets, ensuring data accuracy and integrity.

- **API Integration Experience**: Successfully integrated multiple Google Cloud APIs, including the Places API and Geocoding API, enhancing my technical proficiency in utilizing external data sources to enrich project outcomes.

- **Culinary Trends and Consumer Insights**: Explored the intersection of food culture and health trends, gaining a unique perspective on consumer behavior that can inform data-driven marketing and product development strategies.

- **Problem-Solving and Critical Thinking**: Encountered and resolved various dependability, erroneous/garbage/unknown(non context) data challenges during project development, strengthening my problem-solving abilities and enhancing my capacity for critical thinking.

- **Project Management**: Learned to manage the entire project lifecycle, from conceptualization to execution, which has equipped me with strong organizational skills and the ability to work independently or collaboratively in a team setting.

- **Health and Safety Compliance Understanding**: Developed a nuanced understanding of health and safety regulations in the food industry, providing valuable context that can be applied in roles related to public health data analysis.

- **User-Centric Design**: Focused on creating a tool that caters to the needs of food enthusiasts, emphasizing the importance of user experience in data product development.

- **Passion for Data-Driven Decision Making**: This project reinforced my commitment to leveraging data for making informed decisions and helped me build my overall skillset in the field of Data Science.


### Future Works
- Implementation of logistic regression to predict price ranges based on user ratings, a custom-calculated popularity score, total user reviews, and geographic location.
- ***popularity score = rating * log(user_ratings_total)***

- **Task:** To find a linearly separable realtionship between the attributes currently present in the data.

- The following graphs represent the relationship between price range and the (present, non modified) features currently present.
  1. Graph of Rating and Total User Ratings
     ![ratingvstotal](https://github.com/user-attachments/assets/aee8dfdd-b2a8-4c6a-8f3e-fe7ff22433ae)
  2. Graph of Total User Ratings and Popularity
     ![totalvspopularity](https://github.com/user-attachments/assets/5c74d050-b2a0-4d8c-b89f-cf4ce542c1f9)
  3. Graph of Popularity and Total User Ratings
     ![popularityvsrating](https://github.com/user-attachments/assets/c9d6bae9-fccf-4fc2-aede-598631601176)

- Leverage predictive modeling to accurately represent pricing trends within the diverse culinary landscape of New York City.
