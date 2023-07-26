# QuizGen

This is a smart Quiz Generator that generates a dynamic quiz from any uploaded text/PDF document using NLP . This can be used for self-analysis, question paper generation, and evaluation, thus reducing human effort.


## Features

- implements automatic question generation _(AQG) techniques_
  > **Automatic question generation (AQG)** is concerned with the construction of algorithms for producing questions from knowledge sources, which can be either structured (e.g. knowledge bases (KBs) or unstructured (e.g. text))
- helps in **resource saving**(time, money and human effort)
- enables the **enrichment of the teaching** process, adapt learning to student knowledge and needs, as well as drill and practice exercises
- presents an _automatic mechanism_ to assemble exams or to adaptively select questions from a question bank

## WorkFlow
![workflow](https://user-images.githubusercontent.com/42115530/95686207-1111e300-0c1a-11eb-993a-766967b91c92.png)

## Landing Page
![P1](https://github.com/cassanisha/QuizGenerator01/assets/112388219/8472dc7f-f423-4183-b3f1-de367139b2b7)

## Quiz Page
![P2](https://github.com/cassanisha/QuizGenerator01/assets/112388219/df28ecea-29ca-4197-b072-313b4c604563)

## Results Page
![P3](https://github.com/cassanisha/QuizGenerator01/assets/112388219/9d1acd92-01ee-4f82-9585-f6b5dda8225d)

## Technology Stack:


<img src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/> <img src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/flask%20-%23000.svg?&style=for-the-badge&logo=flask&logoColor=white"/> <img src="https://img.shields.io/badge/bootstrap%20-%23563D7C.svg?&style=for-the-badge&logo=bootstrap&logoColor=white"/> <img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/> <img src ="https://img.shields.io/badge/sqlite-%2307405e.svg?&style=for-the-badge&logo=sqlite&logoColor=white"/>

- **Frontend**: HTML, CSS, Vanilla JS
- **Backend**: Flask
- **IDE**: VS Code
- **Design**: Canva
- **Version Control**: Git and GitHub
- **Database**: Sqllite3

## How to Get Started?

[![Requirements Up To Date](https://img.shields.io/badge/requirements-up%20to%20date-brightgreen)](QuizGen/requirements.txt)
[![Python](https://img.shields.io/badge/python-v3.7-blue)](https://www.python.org/)

### GitHub Repository Structure

| S.No. | Branch   | Purpose                            |
| ----- | -------- | ---------------------------------- |
| 1.    | [master] | contains the main code             |
| 2.    | [nlp]    | contains all machine learning code |
| 3.    | [webapp] | contains all frontend/backend code |

### Setup

- Fork and Clone the repo using

```
$ git clone https://github.com/cassanisha/QuizGen.git
$ cd Fantastic-Falcons-1.0
```

- Change Branch to `webapp` using

```
$ git checkout webapp
```

- Setup Virtual environment

```
$ python3 -m venv env
```

- Activate the virtual environment

```
$ source env/bin/activate
```

- Install dependencies using

```
$ pip install -r requirements.txt
```


## Browser Support

- **Firefox**: version 4 and up
- **Chrome**: any version
- **Safari**: version 5.2 and up
- **Internet Explorer/Edge**: version 8 and up
- **Opera**: version 9 and up
  > **Note**: Support for modern mobile browsers is experimental. The website is not responsive in mobile devices until now.




---

- Run Flask server using

```
$ python app.py
```
