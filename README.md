
# Netflix Movies and TV Shows Analysis


This project involves analyzing and cleaning a dataset of Netflix movies and TV shows. The steps include column profiling, dealing with missing values, encoding nulls, working with dates, and extracting additional data.

## Column Profiling
The dataset contains the following columns:

**show_id**: Unique identifier for each show.

**type**: Indicates if the show is a Movie or a TV Show.

**title**: Title of the show.

**director**: Director of the show.

**cast**: Main cast members of the show.

**country**: Country where the show was produced.

**date_added**: Date when the show was added to Netflix.

**release_year**: Year the show was released.

**rating**: Age rating of the show.

**duration**: Duration of the show (in minutes for movies, in seasons for TV shows).

**listed_in**: Genres/categories the show belongs to.

**description**: A brief description of the show.

## Steps for Data Cleaning and Analysis
### Step 1: Dealing with Missing Values
We identified that several columns have missing values:

**director**: 2634 missing

**cast**: 825 missing

**country**: 831 missing

**date_added**: 10 missing

**rating**: 4 missing

**duration**: 3 missing

### Step 2: Encoding Nulls/Missing Values
For categorical columns like country, we will encode missing values with the most frequent value.

### Step 3: Working with Dates
Convert the date_added column to a datetime format and handle any inconsistencies.

### Step 4: Adding New Columns of Data, Splitting / Extracting Data
We will split the listed_in column into several categories by creating a new table including show_id and listed_in.

1. Duplicate the dataset

2. Remove other columns, only keep show_id and listed_in.

3. Split the listed_in column by the delimiter

4. Choose the advanced option "Split into Rows".


# Key Findings
**Distribution of Movies vs. TV Shows:**

_Movies constitute 69.62% of the dataset, while TV shows make up 30.38%._

![image](https://github.com/Thuhien23/Netflix-Movies-And-TV-Shows/assets/96719464/59a542be-e322-468a-8a9b-3e83feeaff73)

**Content Rating Distribution:**

_The most common ratings are TV-MA and TV-14._ 

_Movies and TV shows with higher age ratings (TV-MA, R) are predominant._ 

![image](https://github.com/Thuhien23/Netflix-Movies-And-TV-Shows/assets/96719464/5c968221-be26-496a-b617-47e0f2ea69ff)


**Top Genres:**

_International Movies, Dramas, and Comedies are the most prevalent genres_.

_International TV Shows and Documentaries are also significant categories_.

![image](https://github.com/Thuhien23/Netflix-Movies-And-TV-Shows/assets/96719464/2c415678-939e-43ca-bd90-ae163578bb63)

**Release Year Trends:**

_There has been an increasing trend in the number of releases over the years, with a notable rise from 2010 onwards_.

![image](https://github.com/Thuhien23/Netflix-Movies-And-TV-Shows/assets/96719464/e6b8d3ce-8dfc-4b2c-aaf0-5032b6e675a8)

**Top Producing Countries:**

_The United States leads in content production, followed by India, the United Kingdom, Japan, and South Korea_.

![image](https://github.com/Thuhien23/Netflix-Movies-And-TV-Shows/assets/96719464/7f46c7b8-59a1-4533-83c7-aa71d990b02c)

**TV Shows by Number of Seasons:**

_Most TV shows have only 1 season, with a sharp decline in the number of shows with more than 2 seasons_.

![image](https://github.com/Thuhien23/Netflix-Movies-And-TV-Shows/assets/96719464/2e1fc1f8-c6ce-4708-88f5-47acc70ff8d6)

# Recommendations

**Content Strategy:**

1. **Focus on Popular Ratings**: Since TV-MA and TV-14 ratings dominate, consider acquiring more content that falls within these ratings to attract a larger audience.

2. **Expand International Content**: International Movies and TV Shows are highly popular. Invest in diverse international content to cater to a global audience.

3. **Genre Diversification**:

**Enhance Popular Genres**: Continue investing in genres like International Movies, Dramas, and Comedies.

**Explore Emerging Genres**: Look into underrepresented genres that may have growing interest to identify new opportunities.

**Trend Analysis:**

1. **Release Year Insights:** Analyze trends over the years to understand what type of content has been successful and why. This can guide future content acquisitions and production.

**Historical Content:** Consider adding more classic content from the 1990s and early 2000s if there is a demand for nostalgic content.

2. **Country-Specific Content:**

**Localization:** Tailor content for top-producing countries like the United States, India, and the United Kingdom. This might include localized marketing and dubbing/subtitling.

**Cross-Cultural Appeal:** Identify content that can cross cultural boundaries and appeal to a broader audience.

3. **TV Show Seasons:**

**Short Series Focus:** Since most TV shows have only 1 season, there may be a preference for shorter series or limited series formats.

**Continuation and Sequels:** For shows with good viewership, consider investing in additional seasons to maintain audience interest.

4. **User Engagement and Personalization:**

**Personalized Recommendations:** Use the data on popular genres and ratings to enhance personalized recommendation systems.

**User Feedback:** Collect and analyze user feedback to understand preferences and improve content offerings.
