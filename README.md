# Statistical Analysis on Youtube Trending Video
![Project Logo](banner-porto-3.png)

##  Background
The background of the problem is very important to know because it will make it easier to identify the source of the problem and determine the right solution. Background information on the problem can be used as a basis for evaluating data and making wise decisions in dealing with the problem at hand.

## Table of Contents
- [Problem Statements](#problem-statements)
- [Data Understanding](#data-understanding)

## Problem Statements
In the context determined in background previously, it includes:
1. Do trending videos have the same quality and characteristics even though the video attributes vary?
2. Why can increased user accessibility help manage trending videos?
3. How can screening process help determine the suitability of uploaded content so that views and engagement increase?
4. What features can help improve the relationship between creators and content connoisseurs so that new content will be positively received?
5. How and how much is the relationship between various attributes in determining the sustainability of trending videos?

The hypothesis being tested is the anti-thesis of the problem background. Everything about the data has no significant intercorrelation and even if there is it is just coincidence.

## Data Understanding
This dataset is provided as material for working on the topic of Trending Video Statistics on YouTube specifically for the United States region. In the early stages, the information contained will be described in more depth to understand its characteristics. As material for analysis, the datasets used are sourced from following [link](https://drive.google.com/drive/folders/1JFhDSfs4vzWuCdsBFObEp5sVLQMo-dR1), for each row the data contained consists of 16 columns, each of which contains information as follows:

| Column | Description |
| --- | ---  |
| `video_id` | *unique identifier* for each video on **YouTube** |
| `trending_date` | the date when the related video was popular |
| `title` | the title name of the related video that is *mandatory* |
| `channel_title` | the name of the channel where the related video originates or is collected |
| `category_id` | related video categorizations listed are in the form of numbers but are nominal in nature |
| `publish_time` | the date when the associated video was released |
| `tags` | words or phrases used as the context of the associated video |
| `views` | the number of users who played the associated video |
| `likes` | the number of users who gave positive *feedback* by pressing the *likes* button |
| `dislikes` | the number of users who gave negative *feedback* by pressing the *dislikes* button |
| `comment_count` | the number of comments left by users regarding the associated video |
| `thumbnail_link` | image link that represents the related video to entice potential viewers to play the video |
| `comments_disabled` | a feature that can be used by video owners so that viewers cannot comment on related videos |
| `ratings_disabled` | a feature used by video owners so that viewers cannot give any *feedback*, such as *likes* and *dislikes* |
| `video_error_or_removed` | a condition where the related video cannot be played back |
| `description` | a description of specific information from the linked video |



### Bahasa Pemrogaman
Proyek ini dibuat menggunakan bahasa pemrograman Python dan framework Jupyter Notebook, dengan penggunaan library pandas, matplotlib, seaborn, dan plotly untuk analisis data dan visualisasi, serta beberapa library tambahan untuk membantu praproses data. Sebagai tambahan, visualisasi data dan presentasi proyek dapat diunduh pada link berikut: [Dashboard](https://public.tableau.com/app/profile/muhammad.reyhan.arighy/viz/Tableau-USvideos-Capstone2/Dashboard?publish=yes) dan [Presentasi](https://www.youtube.com/watch?v=MDm8X7vweHs&t=18s).

### Metode Analisis
Beberapa teknik analisis statistik yang akan digunakan termasuk uji statistik, analisis faktor, dan analisis korelasi. Selain itu, akan digunakan juga teknik visualisasi data untuk memudahkan pemahaman tentang pola dan tren dalam dataset.

### Cara Penggunaan
Untuk menggunakan proyek ini, dataset dapat diunduh pada [tautan berikut](https://drive.google.com/drive/folders/1uw9ptpZpbd3RHc77j-qeELPbcdwaniS4). Selanjutnya, unduh file '`Explanatory Data.ipynb`' dari repo ini. Tempatkan dataset dan file Jupyter Notebook pada satu folder yang sama dan jalankan file '`Explanatory Data.ipynb`'.

### Lisensi
Proyek ini merupakan tugas Casptone Project Modul 2 - Data Analisis dari Purwadhika Digital Technology School untuk program Job Connector Data Science and Machine Learning.
