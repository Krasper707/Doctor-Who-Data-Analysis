# Doctor Who Episode Ratings Dataset

## 📌 Project Overview
This project involves scraping and analyzing IMDb ratings for episodes of *Doctor Who*, one of the longest-running sci-fi TV series. The dataset includes episode details, air dates, IMDb ratings, and fan votes, allowing for in-depth trend analysis and insights into viewer preferences over time.

## 📂 Dataset Information
The dataset contains the following columns:

| Column Name       | Description |
|------------------|-------------|
| `Season`         | The season number of the episode |
| `Episode Number` | The episode number within the season |
| `Episode Name`   | The title of the episode |
| `Air Date`       | The original air date of the episode |
| `IMDb Rating`    | The IMDb rating given by viewers (out of 10) |
| `Votes`          | The number of IMDb votes the episode received |

## Data Scraping Methodology 🕵️‍♂️

The data was scraped using Python and the following libraries:
### Packages Used:

   - ```requests```: To send HTTP requests and fetch HTML content.

   - ```BeautifulSoup```: To parse and extract data from HTML.

   - ```re```: To clean and extract structured data using regular expressions.

   - ```time```: To add delays between requests and prevent getting blocked.

   - ```pandas```: To store and manipulate the scraped data in a structured format.

### Scraping Process:

- Send HTTP requests to the IMDb episode guide page.

- Parse the HTML using BeautifulSoup.

- Extract episode details including name, air date, rating, and votes using CSS selectors and regex.

- Store data in a Pandas DataFrame and clean the extracted fields.

## 📊 Analysis To Be Performed


1. **Trend Analysis**:
   - IMDb ratings over time.
   - Best and worst-rated seasons.
   
2. **Fan Engagement Insights**:
   - Relationship between number of votes and ratings.
   - Most voted episodes.

3. **Statistical & Machine Learning Insights**:
   - Ratings distribution & outlier detection.
   - Predicting future episode ratings using linear regression.


## 🛠️ Future Improvements
- **Sentiment Analysis**: Scraping fan reviews for text-based sentiment analysis.
- **Doctor-Specific Ratings**: Analyzing how different actors playing the Doctor impacted ratings.
- **Comparing Classic vs. Modern Era**: Evaluating how episode reception changed pre/post-2005.

## 📜 License
This project is licensed under the MIT License.

## 📬 Contact
For any questions or contributions, feel free to reach out!

---

*"Question: What's the best show? Answer: Doctor Who"* 🚀

