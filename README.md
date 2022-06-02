# Trading Bot using Machine Learning

This project uses Machine Learning techniques to create models that maximize trading performance. We start by using a trading strategy based on Support Vector Machine Algorithm (SVM), using the rolling window data (Simple Moving Averages - SMA) to generate signals (-1 - Sell , 1 - Buy). We start out by using two rolling windows (two SMAs), one short and one long. After adapting our data (scaling and splitting data) we create, fit and predict the model. Given that our first iteration dosen't produce any remarkable results, we keep changing our inputs and using different machine learning libraries to achieve better results.

---

## Technologies

The following technologies were used to build and deploy this application:

* Python - Version 3.9.7
* Anaconda (Which includes Jupyter Lab and Pandas)
* hvPlot
* matplotlib
* DateOffset
* sklearn

---

## Installation and Usage Guide

### 1. Install Python 3.9.7

For installing Python 3.9.7 you can find the Installation Files for both Windows/Mac OS in the following link
 * [Anaconda Installation Files](https://www.anaconda.com/products/individual "Anaconda Installation Files")

If you require assistance installing it, you can follow the following videos for guidance
* [Youtube Video Python Installation Guide - Windows](https://www.youtube.com/watch?v=uSVl7gRXP80 "Python Installation Video - Windows") 
* [Youtube Video Python Installation Guide - Mac](https://www.youtube.com/watch?v=r6bBaj797t8 "Python Installation Video - Mac") 
 
### 2. Install Anaconda and required dependencies

For installing Python 3.9.7 you can find the Installation Files for both Windows/Mac OS in the following link
 * [Python Installation Guide](https://www.python.org/downloads/release/python-397/ "Python Installation Guide")

For installing Anaconda, you can follow the following videos for guidance
* [Youtube Video Anaconda Installation Guide - Windows](https://www.youtube.com/watch?v=g6ln1dAt-RI "Anaconda Installation Video - Windows") 
* [Youtube Video Anaconda Installation Guide - Mac](https://www.youtube.com/watch?v=oWVTO_69U4c "Anaconda Installation Video - Mac")

For installing sklearn, you can follow the following link for guidance
* [sklearn Installation Guide](https://scikit-learn.org/stable/install.html "sklearn Installation Guide")


### 3. Installing the Trading Bot using Machine Learning repository

Navigate to your desired location where you would like to save the documents for this application. You can do this by using the ```cd``` command followed by a space and the file path inside quotations ```" file path "```. In my example I have gone to Desktop.

![image](https://user-images.githubusercontent.com/94983278/149385012-181d1769-0af6-487e-8e04-823a28f2c3ed.png)

Clone this project's repository from GitHub using the following command 

```https://github.com/epocaterrasus/TradingBotUsingMachineLearning.git```

### 4. Opening the file on Jupyter Notebook

Being in the folder created when you downloaded the repository type ```jupyter lab```, this should open a window in your predetermined browser with Jupyter Lab. In the left corner you can see the files inside the repository, open the ```machine_learning_trading_bot.ipynb``` which contains all steps and notes.

---

### Images

Initial Model
![bokeh_plot](https://user-images.githubusercontent.com/94983278/161437456-cf5eb8d4-fa31-4997-858b-91395d9f1769.png)

Model after Adjustments and Tuning
![bokeh_plot2](https://user-images.githubusercontent.com/94983278/161437458-a6a0c0df-d765-47ef-acb9-789ebe081230.png)

---

## Contributors

Maxwell Snyder - mholts1020@gmail.com

---

## License

MIT License

Copyright (c) 2022 mholts1020@gmail.com

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