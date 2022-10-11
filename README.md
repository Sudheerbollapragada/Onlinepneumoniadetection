# Pneumonia Detector

## About

This webapp was developed using Flask Web Framework and was deployed on Heroku server. The models used to predict the diseases were trained on large Datasets. All the links for datasets and the python notebooks used for model creation are mentioned below in this readme. The webapp can predict following Diseases:


- Pneumonia

# Project Home Page
[Screenshot (38)](https://user-images.githubusercontent.com/40494619/194997705-12ecc98d-40ca-40df-a781-4e65d940f7a5.png)


[Screenshot (39)](https://user-images.githubusercontent.com/40494619/194997821-d2d3434d-32cf-4c37-a34a-3eb589cf0ac0.png)

# Preditng developed Model
![Screenshot (40)](https://user-images.githubusercontent.com/40494619/194997922-a0bd86e9-99ed-4f0e-b063-a6119a408f08.png)
![Screenshot (42)](https://user-images.githubusercontent.com/40494619/194997944-6f4ff80a-460d-4e90-a66c-f20e2b1ce149.png)

![Screenshot (44)](https://user-images.githubusercontent.com/40494619/194998016-2195c1f1-6d6c-4aa5-b5dc-f344f00f00b0.png)


![Screenshot (45)](https://user-images.githubusercontent.com/40494619/194998053-19c320cd-e6d5-42de-9e7c-0033fc480b71.png)

# Sample Positive

![Screenshot (46)](https://user-images.githubusercontent.com/40494619/194998089-14d0ce9d-0495-4a62-800c-afe249d51c77.png)

![Screenshot (36)](https://user-images.githubusercontent.com/40494619/194998108-b3db8de3-020e-47c9-a018-e58b946f1e1d.png)
![Screenshot (47)](https://user-images.githubusercontent.com/40494619/194998126-316cf5fb-6735-4c93-b293-8f48a3bea78c.png)

# Model Accuraacy

| Disease        | Type of Model            | Accuracy |
| -------------- | ------------------------ | -------- |
| Pneumonia      | Deep Learning Model(CNN) | 95%      |

## NOTE

==> You can access the website live at: https://pneumoniadetector.azurewebsites.net/ <br>
==> Python version 3.6.15 was used for the whole project.<br>

## Steps to run this application in your system

1. Clone or download the repo.
2. Open command prompt in the downloaded folder.
3. Create a virtual environment

```
mkvirtualenv environment_name
```

4. Install all the dependencies:

```
pip install -r requirements.txt
```

5. Run the application

```
python app.py
```

## Dataset Links

All the datasets were used from kaggle.


- [Pneumonia Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
