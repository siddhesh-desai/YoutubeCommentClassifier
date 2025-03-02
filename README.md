<a name="readme-top"></a>

<div align="center">

  <h3 align="center"><b>Youtube Comment Classifier</b></h3>




  <p align="center">
    Youtube Comment Classifier is a platform designed to classify youtube comments based on the user's need.
    <br />
    <br>
    <a href="https://github.com/siddhesh-desai/YoutubeCommentClassifier"><strong>Explore the docs »</strong></a>
    <br />
    <a href="https://drive.google.com/file/d/1Jdsm__ofXirzdk_5m5DDQ2T1fb1vaTTl/view">View Demo</a>
    ·
    <a href="https://github.com/siddhesh-desai/YoutubeCommentClassifier/issues">Report Bug</a>
    ·
    <a href="https://github.com/siddhesh-desai/YoutubeCommentClassifier/issues">Request Feature</a>
  </p>
</div>

<!-- ABOUT THE PROJECT -->
<br>

https://github.com/user-attachments/assets/699c7908-86cd-487e-9734-92af3d8979aa

## ♾️ About The Project

YouTube comment classifier project is aimed to analyze and categorize comments on YouTube videos, using a combination of sentiment analysis and a Multinomial Naive Bayes Classifier. This project was developed using Flask, a Python web framework, and integrated with the Google YouTube API to fetch comments from YouTube videos. The primary objective of this project was to efficiently filter and categorize comments into five main categories: spam, relevant, appreciation, grievance and all comments.

Integrated with user authentication, the user has to first register with his/her username and password, and then login to the application. While on the application, the user can logout anytime. Visualisation of the comparison between tyoe of comments - (relevant vs spam) and (appreciation vs grievance) as piecharts is provided on the dashboard in order to make the application more insightful and engaging.

The first component of the project involved sentiment analysis, which was used to determine the emotional tone of the comments. This analysis helped identify whether a comment was appreciative or critical, providing valuable insights into the overall sentiment of the viewers. Sentiment analysis used natural language processing techniques to assign a sentiment score to each comment.

The second part of the project utilized a Multinomial Naive Bayes Classifier to distinguish between relevant and spam comments. This classifier was designed to filter out comments that were unrelated or irrelevant to the video's content, ensuring that only meaningful and contextually appropriate comments were displayed.

By combining these two models, the project provided a comprehensive solution for YouTube content creators and viewers to better manage and engage with comments on their videos. The Flask-based web application allowed users to easily input a YouTube video URL and receive categorized comments, helping them quickly identify appreciative or critical feedback and separate relevant comments from spam. This project has the potential to improve user experience and engagement on YouTube, making it a valuable tool for content creators and viewers alike.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⚙️ Built With

The technologies and tools used are:

- Flask
- HTML
- CSS
- Python
- Google Charts
- Postgres
- Google Colab

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 🧑‍💻 Getting Started

Follow the below steps to set up the project locally:

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/siddhesh-desai/YoutubeCommentClassifier.git
   ```

2. Change the directory:

   ```sh
   cd YoutubeCommentClassifier
   ```

3. Install all requirements:

   ```sh
   pip install -r requirements.txt
   ```

4. Setup .env file:

   ```python
   DEVELOPER_KEY="ENTER_DEVELOPER_KEY_HERE"
   DATABASE_URL="sqlite:///your_database.db"
   ```

   You need to create your developer key from your GCP console.

5. Run wsgi.py file:

   ```sh
   python wsgi.py
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💡 Features

<br>

- Relevant and Spam Comments Detection
- Appreciation and Resentful Comments Detection

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->

## 🛣️ Roadmap

- [x] Enter the Youtube video ID
- [x] Choose your required button
- [x] View Comments

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 👣 Contributing

Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

Project Link: [https://github.com/siddhesh-desai/YoutubeCommentClassifier](https://github.com/siddhesh-desai/YoutubeCommentClassifier)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
