# YoutubeEngagementAnalytic

  Youtube, the largest online video-sharing platform today, has provided a place for content creators to share information and earn extra income. Anticipating whether a video will be engaged by viewers or not is an essential factor in helping video creators improve video content and quality before publishing. To facilitate this task, we build an annotated dataset of 4961 videos collected from 20 Youtube channels in Vietnam. We evaluate a number of metrics for measuring video engagement to propose a novel measure which determines the engagement of a video via its likeness and popularity: Q score (i.e., showing likeness) and the number of users in liked comments (i.e., showing popularity). Using our proposed measure, we annotate videos with three levels of engagement including high, medium, and low. From the supervised dataset, we constructed a multi-channel model to infer the degree of engagement based on  the content of a Youtube video such as title, audio, thumbnail, frame, and transcript. We believe our dataset and metric to be useful for engagement analysis as well as studies on social media content.

# Table of Contents
1. [Meta data](#Metadata)
2. [Missing rate](#MissingRate)
3. [Notebook](#Notebook)
4. [Data](#Data)


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
| duration | Duration of video (minutes)|
| day_upload | Day uploading of video|
| month_upload | Month uploading of video|
| year_upload | Year uploading of video|
| title | Title of video|
| title_length | Length of title (number of words)|
| transcript | Transcript of video|
| transcript_length | Length of transcript (number of words)|
| channel\_id | Id of channel |
| level\_channel | Level subscriptions of channel|
| category\_channel | Category of channel |
| label | Level engagment of video|

## MissingRate

| Column     | Missing rate |
| -------    | -----------  |
| video\_id  | 0 %     |
| view\_count |  0 % |
| like\_count |  0 %   |
| dislike\_count |  0 % |
| comment\_count |  0 % |
| like\_rate     |  0 % |
| comment\_rate     |  0 % |
| q\_score     |  0 % |
| num\_unique_users     |  0 % |
| duration |  0 %|
| day_upload |  0 % |
| month_upload |  0 %|
| year_upload |  0 %|
| title |  0 % |
| title_length |  0 %|
| transcript | 70.04 %|
| transcript_length | 70.04 %|
| channel\_id | 0 %|
| level\_channel | 0 % |
| category\_channel | 0 % |
| label | 0 % |


## Notebook

In the notebook has visualized the data for everyone to analyze and verify the data.

## Data

* metadata.csv : medata of videos
* train.csv: train set of videos
* test.csv: test set of videos
* train_transcript.csv: train set of video transcipts
* test_transcript.csv: test set of video transcipts