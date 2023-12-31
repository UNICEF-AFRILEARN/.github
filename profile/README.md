# Afrilearn-AI-Learning-Personalisation

<p align="center">
    <a href="https://github.com/UNICEF-AFRILEARN/unicef_afrilearn/blob/main/LICENSE.md">
        <img alt="GitHub" src="https://img.shields.io/github/license/UNICEF-AFRILEARN/unicef_afrilearn?logo=GitHub&style=plastic">
    </a>
    <a href="https://github.com/UNICEF-AFRILEARN/unicef_afrilearn/issues?q=is%3Aopen+is%3Aissue">
        <img alt="open issues" src="https://img.shields.io/github/issues-raw/UNICEF-AFRILEARN/unicef_afrilearn?color=red&logo=GitHub&style=plastic">
    </a>
    <a href="https://github.com/UNICEF-AFRILEARN/unicef_afrilearn/issues?q=is%3Aissue+is%3Aclosed">
        <img alt="closed issues" src="https://img.shields.io/github/issues-closed-raw/UNICEF-AFRILEARN/unicef_afrilearn?color=green&logo=GitHub&style=plastic">
    </a>
    <a href="https://github.com/UNICEF-AFRILEARN/unicef_afrilearn/blob/main/CODE_OF_CONDUCT.md">
        <img alt="code of conduct" src="https://img.shields.io/badge/contributors-code%20of%20conduct-blue">
    </a>
    <a href="https://github.com/UNICEF-AFRILEARN/unicef_afrilearn/blob/main/CONTRIBUTING.md">
    <img alt="contributing guidelines" src="https://img.shields.io/badge/contributing-guidelines-brightgreen">
    </a>
    <a href="https://github.com/UNICEF-AFRILEARN/unicef_afrilearn/graphs/commit-activity">
    <img alt="commits" src="https://img.shields.io/github/commit-activity/w/UNICEF-AFRILEARN/unicef_afrilearn?color=yellow&style=plastic">
    </a>
    <a href="https://twitter.com/afrilearn">
    <img alt="follow on twitter" src="https://img.shields.io/twitter/follow/Afrilearn?style=social">
    </a>
    <a href="https://www.youtube.com/channel/UC_BnnokJom1DWipMl0oSxWA">
    <img alt="follow on YouTube" src="https://img.shields.io/youtube/channel/views/UC_BnnokJom1DWipMl0oSxWA?style=social">
    </a>
</p>

Some children learn best by watching videos, some by reading class notes, some by solving practice problems, and some by social collaboration. Beyond blending storytelling, social learning, and supplementary tech skills content, Afrilearn leverages artificial intelligence to give every child access to personalized learning using the unique method that works best for them. This can be solved using AI recommendation systems. The recommender system provides course recommendations based on user history and similar profiles. A more detailed documentation is available [here](https://github.com/UNICEF-AFRILEARN/question_recommendation/blob/main/docs/Recommender%20System%20Development%20946729cc1a9c43ca80c4251c151d195a.pdf). 

This repo is deployed as a web app and api through Heroku [here](https://unicef-afrilearn-app.herokuapp.com/).


## Installation
Clone this repository. Navigate to the repository and create a python virtual environment through your method of choosing. Activate the environment and install the required libraries through
```
git clone https://github.com/UNICEF-AFRILEARN/question_recommendation.git
cd question_recommendation
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Architecture
<img alt="architecture diagram" src="https://github.com/UNICEF-AFRILEARN/.github/blob/main/architecture.png">

## Dependencies
The backend is developed in python 3.x.x. Other libraries and packages, along with their versions, are included in [requirements.txt]('../../requirements.txt'). In short, you need the following libraries and their dependencies.
- pandas
- numpy
- flask_cors
- flask
- mlxtend
- Pymongo

## Usage
<a href="https://question-reco-377d2cf63eb7.herokuapp.com/">visit web app</a>


## Contributors

<a href="https://github.com/UNICEF-AFRILEARN/unicef_afrilearn/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=UNICEF-AFRILEARN/unicef_afrilearn" />
</a>
