# Call Center Performance Analysis

This project aims to analyze the activity and performance levels of a call center operated by a large energy provider during the previous winter. The goal is to identify areas of improvement and enhance the customer experience, with a specific focus on reducing the number of callers who hang up. The dataset used for analysis contains information about the call center's peak hours, including caller wait times, abandoned calls, and average handling times.

## Dataset

The dataset used in this analysis consists of data from 504 'peak' hours of operation during the last winter. Each record in the dataset includes the following columns:

1. **Month**: Refers to three 2-month long periods of time.
2. **VHT**: Specifies whether Virtual Hold Technology (VHT) was turned on or off during the hour.
3. **ToD**: Specifies which peak hour the data is from (morning, afternoon, or evening).
4. **Agents**: An indication of the number of agents available to handle calls during the hour (not very accurate).
5. **CallsOffered**: Number of callers calling during the hour.
6. **CallsAbandoned**: Number of calls arriving during the hour that rang off before speaking to an agent.
7. **CallsHandled**: Number of calls arriving during the hour that spoke to an agent.
8. **ASA**: Average speed of answer in minutes, i.e., the average time between the caller first ringing the call center and speaking to an agent.
9. **Avehandletime**: The average time that calls require from an agent, including 'wrap-up' time.

## Objective

The objective of this project is to analyze the provided dataset and derive insights about the call center's performance during the previous winter. The analysis will focus on the following key aspects:

1. **Caller Wait Time**: Determine the average waiting time a caller spent before being connected to an agent.
2. **Abandoned Calls**: Identify the number of calls that were abandoned by callers while waiting for an available agent.
3. **Agent Performance**: Calculate the average time spent by agents in handling a single caller or call offered during the morning and evening hours.

## Analysis Notebook

The analysis has been performed using a Jupyter Notebook, which provides an interactive environment for running Python code. The notebook contains the necessary code and explanations to perform the analysis and generate meaningful insights.

To run the analysis notebook, make sure you have the required dependencies installed. The following libraries are utilized in the notebook:

- pandas: For data manipulation and analysis.
- numpy: For mathematical operations and array manipulation.
- matplotlib: For creating visualizations.

The notebook is structured as follows:

1. **Data Loading**: Loading the dataset into a pandas DataFrame for further analysis.
2. **Data Cleaning and Preparation**: Preparing the dataset by handling missing values, data formatting, and any required transformations.
3. **Exploratory Data Analysis**: Conducting an exploratory analysis to gain insights into the dataset and understand the distribution of various variables.
4. **Performance Metrics Calculation**: Calculating the performance metrics such as average wait time, abandoned calls, and agent performance.
5. **Data Visualization**: Creating visualizations to present the findings and provide a clear understanding of the call center's performance.
6. **Conclusion**: Summarizing the key findings and providing recommendations for improving the call center's performance.

Make sure to execute each cell in the notebook sequentially to obtain accurate results.

## Conclusion

Through this analysis, we aim to provide insights into the call center's performance during the previous winter and suggest potential improvements for the upcoming winter. By focusing on reducing abandoned calls and optimizing caller wait times, the call center can enhance customer satisfaction and efficiency.

Please refer to the attached Jupyter Notebook for detailed code implementation and analysis results.
