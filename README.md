# Death Classification
This project is a part of the ADS-502 Applied Data Mining course in the Applied Data Science Program at the University of San Diego.

**Project Status: [Completed]**

## Installation
    To use this project, clone the repository on your device using the command below:
        
        git clone git@github.com:clairebentzen/death-classification.git

    Download 2015_data.csv from https://www.kaggle.com/datasets/cdc/mortality
## Project Objective
Death caused by injury in the United States falls into one of five categories: unintentional, suicide, homicide, undetermined, or legal intervention. Undetermined deaths leave the families of victims with unanswered questions and a lack of closure as well as leaves investigators with potentially unsolved cases. In an attempt to provide answers, this project aimed to classify the manner of death for those that were undetermined. A successful model will classify an undetermined manner of death into either homicide or not  homicide based on statistical relationships found between the independent and dependent variables. The implications of the results of this death classification model can assist investigators in cold cases and making conclusions in undetermined deaths. A death that is ruled a homicide by this model can give investigators an indication that the case should be reopened and/or further investigated.

### Project Contributors
Claire Bentzen - https://github.com/clairebentzen

Katie Mears - https://github.com/KatieMears628

Marvin Moran - https://github.com/mmoran90

### Methods Used
- Data Mining
- Classification Modeling
- Data Manipulation
- Data Visualization
- Programming

### Technologies
- Python

## Project Description
The dataset that is used for this project was the mortality data from the Centers for Disease Control and Prevention, obtained from Kaggle. It consists of over two million mortality records and 77 variables for 2015. Using Python as the programming language, the team performed exploratory data analysis, data preprocessing, and evaluated several different models. All of the models used variations of artificial neural network algorithms including hidden layers, no hidden layers, reduced hidden layers, and regularization. The models were first assessed by analyzing test loss and accuracy, then were further evaluated using recall, precision, and F1 scores to determine the best performing model to accurately classify undetermined deaths. The optimal method was selected with the intentions of using it in the deployment stage to classify undetermined deaths.

## License
MIT License

Copyright (c) 2023 Claire Bentzen

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Acknowledgments 
- Dr. Ebrahim Tarshizi