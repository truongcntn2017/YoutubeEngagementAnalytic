# YoutubeEngagementAnalytic

  Youtube, the largest online video-sharing platform today, has provided a place for content creators to share information and earn extra income. Anticipating whether a video will be engaged by viewers or not is an important factor in helping video creators improve video content and quality before uploading. The dataset includes 4961 videos collected from 20 Youtube channels in Vietnam. The paper explores a number of measures to measure video engagement that have been proposed previously. From there, we proposed a new measure to determine the engagement of a video based on two metrics: Q score (showing likeness) and the number of users in liked comments (showing popularity). Using our proposed measure, we separated videos into three levels of engagement including high, medium, and low. From the labeled dataset, we constructed a multi-channel to predict engagement based on the components of a Youtube video including title, audio, thumbnail, frames, and transcript. We hope our dataset and measure can be reused for other studies with different problems.

# Table of Contents
1. [Meta data](#Metadata)
2. [Notebook](#Notebook)
3. [Data](#Data)


## Metadata


| Column     | Description  |
| -------    | -----------  |
| video\_id  | Id of video       |
| view\_count | Views of video   |
| like\_count | Likes of video   |
| dislike\_count | Dislikes of video   |
| comment\_count | Comments of video   |
| like\_rate     | Metric of video engagement |
| comment\_rate     | Metric of video engagement |
| q\_score     | Metric of video engagement |
| num\_unique_users     | Metric of video engagement |
| channel\_id | Id of channel |
| level\_channel | Level subscriptions of channel|
| category\_channel | Category of channel |
| label | Level engagment of video|
| day_upload | Day uploading of video|
| month_upload | Month uploading of video|
| year_upload | Year uploading of video|




## Notebook

In the notebook has visualized the data for everyone to analyze and verify the data.

## Data

* metadata.csv : medata of videos
* train.csv: train set of videos
* test.csv: test set of videos
* train_transcript.csv: train set of video transcipts
* test_transcript.csv: test set of video transcipts