# Heart Disease Prediction

## Overview

This project implements a heart disease prediction model using machine learning. It includes a Flask web application for user input and real-time predictions.

## Technical Details

- **Machine Learning Model:**
  - Utilizes scikit-learn for heart disease prediction.
  - Model trained and saved using the best practices.
 
  To dive more details of the technical stuffs , please check this document [Download PDF](Group-10-HeartDiseasePrediction.pdf)


- **Web Application:**
  - Built with Flask for a simple and interactive user interface.
  - User input via sliders and dropdowns for feature values.
  - Real-time prediction with the click of a button.

## Project Structure

```plaintext
project/
|-- app/
|   |-- templates/
|   |   |-- index.html
| 
|-- requirements.txt
|-- app.py
```

### Dependency
- Install Dependencies
  ```
  pip install -r requirements.txt
  ```
### Run the Application
```
python3 app.py
```
Open the web application at http://127.0.0.1:5000/ in your browser.
### Demo
We deployed in AWS EC2 Instance.
![](screenshots/before-predict-operation.png)

![](screenshots/no-heart-disease-operation.png)

![](screenshots/have-heart-disease.png)


### Contributors
- [Md Shafi Ud Doula](https://github.com/shaficse)
  
- [Tanzil Al Sabah](https://github.com/tanziltonmoy)

