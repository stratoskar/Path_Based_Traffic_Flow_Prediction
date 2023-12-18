# Path Based Traffic Flow and PAth Crossing Time Prediction, using Strict Path Queries.

This repository is an extention of my thesis. You can find analytical information about my thesis in this link: https://github.com/stratoskar/Traffic_Flow_Prediction/

## Repository Overview

- **Objective:** Forecast traffic flow in paths of San Francisco, California, using historical data. Also, using the same data, we are trying to find the future average crossing time per each path.
- **Methodology:** Time series forecasting using machine and deep learning models. We use the Strict Path Queries paper to measure traffic flow in each path accurately. Read more about SPQ methodology [here](Related_Work/Strict_Path_Queries.pdf).
- **Data:** The dataset consists of paths, each comprising consecutive edges representing road segments between intersections.
- **Number of Paths:** 1000 paths are used for making traffic forecasts.
- **Approach:** The problem is transformed into time series forecasting, with one time series for each path in the dataset.

## Dependencies

To run the code in this repository, ensure you have the latest version of Python installed. The required libraries are listed [here](Necessary Python Libraries.txt). You can install them using pip or conda commands.

## About Me
My name is Efstratios Karkanis, and I am a 4th-grade student at the University of Piraeus. If you have any questions or would like to get in touch, feel free to reach out to me at stratoskarkanis2@gmail.com.

Feel free to explore the code and the insights gained from this project. Contributions and feedback are always welcome!
