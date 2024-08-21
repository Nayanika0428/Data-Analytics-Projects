## YouTube Trending Analytics: Exploring the Path to Video and Channel Success
### Project Overview
This project analyzes YouTube trending video data collected using the YouTube API. The goal is to identify key factors that contribute to video virality and channel growth, providing insights that can help content creators optimize their strategies for better engagement and visibility on the platform.

### Project Structure
The project consists of the following key files:

#### Data Collection:

* YT_Api_datacollect.ipynb: This notebook is used for collecting trending video and channel data from the YouTube API.

#### Video Data Analysis:

* YT_DATA_ANALYSIS_with_outliers.ipynb: Analysis of video data, including outliers, to understand the impact of extreme values on trends and correlations.
* YT_video_analysis_without_outliers.ipynb: Analysis of video data with outliers removed, providing a clearer view of the general trends.
  
#### Channel Statistics Analysis:

* Channel_statistics_trending_videos.ipynb: Analysis of channel-specific metrics such as upload rate, subscriber count, and channel age, and their relationship to the number of trending videos.

#### Project Report
* YouTube Trending Analytics.pdf: Describes the project objective, findings/analysis and conclusion

### Python Libraries Used
The following Python libraries were used in this project:

* pandas - For data manipulation and analysis
* numpy - For numerical operations
* matplotlib - For creating static, animated, and interactive visualizations
* seaborn - For statistical data visualization
* scikit-learn - For building and evaluating regression models
* requests - For making HTTP requests to the YouTube API
* json - For parsing JSON responses from the API
* datetime - For handling date and time operations

### Results
The analysis provides insights into factors like video duration, tag usage, and channel activity, and their impact on video success. The findings are documented in the notebooks and can be used to guide content creation strategies on YouTube.
