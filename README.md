![GitHub Repo stars](https://img.shields.io/github/stars/rppradhan08/resume-segmentation)
![GitHub forks](https://img.shields.io/github/forks/rppradhan08/resume-segmentation?color=green)
![contributors-shield](https://img.shields.io/github/contributors/rppradhan08/resume-segmentation)
[![LinkedIn][linkedin-shield]](https://in.linkedin.com/in/raj-praveen-pradhan-306625101)

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/rppradhan08/resume-segmentation">
    <h1>Resume Segmentation</h1>
  </a>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Steps involved](#steps-involved)
  - [Packages](#packages)
- [Contact](#contact)

<!-- ABOUT THE PROJECT -->

## About The Project

<p align="center">
  <img src="https://raw.githubusercontent.com/rppradhan08/resume-segmentation/master/images/wordcloud.png" height="250px" width="350px">
</p>

In this project we will be using NLP to preprocess the text inside resume and segregate resumes based on domain. As this is a classification task, we will be using word embedding technique to transform raw text into numerical features. Based on these features final predictions will be performed. For detailed walk-through refer **Resume_Segmentation.ipynb**.

### Steps involved

- Reading data from source and preprocessing it to more desirable format.
- Performing EDA and generating Wordcoud.
- Used word embedding technique for transforming text into numerical vectors.
- Trained a KNN model to classifiy unseen resume to its most nearest match.

### Packages

For proper execution of application firstly create an environment, then to install prerequisite libraries execute below command in terminal.

```
pip install sklearn
pip install nltk
pip install wordcloud
pip install pandas
pip install numpy
pip install matplotlib
```

## Contact

Raj Praveen Pradhan - [LinkedIn](https://in.linkedin.com/in/raj-praveen-pradhan-306625101)
