# Wechat Message Analysis and Prediction
## Introduction 
This project was created to practice my skills in data analysis and prediction. The project includes visualizing Wechat message patterns and predicting future interactions. 
## Data Collection
The data can be collected with [this project by LCO44](https://github.com/LC044/WeChatMsg). The expected data format is a `.csv` file, while `.docx` and `.txt` files are also supported.
## Data Analysis (In Progress)
Currently the only analysis is a visualization of the number of messages sent per day.
## Prediction 
The prediction task is to predict the number of messages sent in the next day. Techniques including weighted sum, linear regression, time series analysis, categorical encoding, and ensemble learning are used.
## Future Work
- NLP analysis of message content
- Include NLP features in prediction
- Include user profile features in prediction
- Neural network prediction
## Work with Your Own Data
To work with your own data, simply put the data in the `data` folder and change the path form the second cell in the notebook (the default name is `msg.csv` so if you use that name, there's no need to make any change). If you use any other format than `.csv`, you will need to change the `read_csv` function to the appropriate function for your data format.   
The required packages are listed in the `requirements.txt` file and can be installed with `pip install -r requirements.txt`.