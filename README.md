# CS210TermProject - Spotify Data Analysis

This repository includes all required files related to my CS210 term project about my Spotify data. I have downloaded my spotify data between November of 2022 and November of 2023 from the services that Spotify provide for their users so, no web scraping has been done.

## Getting Started

*THE DATA SOURCE*

Spotify

*DATA ANALYSIS TECHNIQUES*

EDA(Exploratory Data Analysis), visualizations and machine learning models are implemented for the data.


*MOTIVATION & AIM*

This project was initiated with the goal of gaining insights into personal music listening habits and preferences. As a music enthusiast, I was curious about understanding patterns related to the times of day, artists, and tracks that dominate my listening history.

The primary aims of this project include:

Exploratory Data Analysis (EDA): Conduct a comprehensive exploration of the dataset, uncovering trends, patterns, and interesting observations related to music listening habits.

Feature Engineering: Enhance the dataset by creating new meaningful features that can provide additional context and insights.

Machine Learning Modeling: Apply machine learning techniques to predict and classify various aspects of the music listening experience, such as the time of day or the likelihood of listening to a specific artist.

Visualizations: Utilize visualizations to effectively communicate findings and make the exploration process more engaging and accessible.

GitHub Repository: Create a well-structured and professional GitHub repository to share the project, code, and results with the community.

Chatbot Integration: Explore the use of a chatbot to enhance user interaction and provide a seamless experience in navigating and understanding the project's insights.

*CONTENT OF DATA*

The original dataset includes a 2248 rows × 4 columns matrix. The first column indicates when I listened to that music, the second column contains the artist's name, the third column contains the track name, and the fourth one includes the milliseconds listened to that song. I have made some changes to the dataframe, which are outlined in the Cs210SpotiDataProject.ipynb file itself, to further investigate my dataframe.

## Requirements
This project requires Python 3.x and the following dependencies:
- pandas==1.3.3
- json==2.0.9
- matplotlib==3.4.3
- seaborn==0.11.2
- scikit-learn==0.24.2

To install all the dependencies, use the following command in a clean virtual environment:
```bash
pip install -r requirements.txt
```

### Installing

* Copy over the repository and work in there.

### Executing program

* Run the program by running `Cs210SpotiDataProject.ipynb`. After some time (Total run time: 22.580676317214966 seconds) a user can inspect the file with their inputs on the bottom of each code segment.
* User can inspect the original .json file located in the repository named StreamingHistorySezerKocaekiz.json file
* More detailed explanations are present in Cs210SpotiDataProject.ipynb files code blocks and text blocks.

## TO-DO

* Machine learning model in the code can be improved by some tweaking in the hyperparameters tuning.
  
## Authors

Sezer Kocaekiz
