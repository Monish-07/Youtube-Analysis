# Youtube Analysis
The project aims to gather video statistics from YouTube, including video titles, views, likes, and video lengths, for a given list of video IDs. To achieve this, the project uses the YouTube Data API, which allows access to public YouTube data, such as video information and statistics, using Python and the google-api-python-client library.

**The main components of the project include:**

_YouTube Data API Integration:_ The project uses the google-api-python-client library to interact with the YouTube Data API. It makes API requests to retrieve video information based on the provided video IDs.

_get_video_details Function:_ This function takes the youtube API object and a list of video IDs as input. It iterates over the video IDs, retrieves video information using the API, and stores relevant statistics like title, views, likes, and video length in a list of dictionaries.

_Data Processing:_ The function processes the raw data obtained from the YouTube API response. It handles missing or invalid video length information, converting it into a format suitable for analysis.

_DataFrame Creation:_ The collected video statistics are then converted into a pandas DataFrame. The DataFrame provides a tabular structure to store and manipulate video data.

_Visualization:_ The project includes data visualization using seaborn and matplotlib libraries. It creates a scatter plot to compare the number of views and video lengths. The scatter plot visually illustrates any relationship or patterns between video length and views.

_Output:_ The function returns the final DataFrame containing the 'Title', 'Views', 'Length', and 'Link' columns for each video. It provides a clear and organized representation of video statistics, allowing further analysis or export for external use.

Overall, the project facilitates easy access to video statistics from YouTube and provides an informative visualization to analyze how video length may affect the number of views. This project can be useful for content creators, marketers, or analysts who want to gain insights into video performance and audience engagement on YouTube.


![image](https://github.com/Monish-07/Youtube-Analysis/assets/95215581/feb7f056-4c78-4a34-9290-3438d9495994)

![image](https://github.com/Monish-07/Youtube-Analysis/assets/95215581/62633500-1154-4c0b-8df7-03cc4a964457)

![image](https://github.com/Monish-07/Youtube-Analysis/assets/95215581/fade9ebf-a62a-4de1-a4f7-79cc9c755e30)

![image](https://github.com/Monish-07/Youtube-Analysis/assets/95215581/e355857d-6061-4e9c-a319-6b6770439e65)

![image](https://github.com/Monish-07/Youtube-Analysis/assets/95215581/0aac406d-2b1a-4d1a-a2d1-d33ebe2c15e8)


