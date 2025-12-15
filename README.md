# ECE 5831 Final Project  
## Detecting Cryptocurrency Pump-and-Dump Manipulation Using Machine Learning

### Course
ECE 5831 2025 – Pattern Recognition and Neural Networks

### Team Members
- Nawaz Ur Rahman Mohammed  
- Snigdha Kotha  
- Manaswitha Kalapuram  

## Project Overview
Cryptocurrency markets are highly volatile and lightly regulated, making them vulnerable to market manipulation such as pump-and-dump schemes. In these schemes, coordinated groups artificially inflate the price of a cryptocurrency and then sell at the peak, causing losses to retail investors.

In this project, we develop an end-to-end machine learning pipeline to automatically detect pump-and-dump manipulation using real trade-level data from the Binance exchange. Pump signals are collected from public Telegram groups and aligned with historical trading activity. Short-term statistical and behavioral features are extracted from rolling time windows and used to train supervised classification models.

We evaluate Random Forest and AdaBoost classifiers across multiple time window sizes and demonstrate that larger windows provide more stable and reliable detection.


## Repository Structure

ece5831-2024-final-project/
│
├── final-project.ipynb   
├── features.py  
├── downloader.py 
├── README.md                 

Large files such as datasets, presentation slides, and the final report are hosted on Google Drive and linked below.


## Datasets
The dataset consists of:
- Pump event signals collected from public Telegram groups
- Trade-level cryptocurrency data collected using the Binance public API

Dataset (Google Drive):  
https://drive.google.com/drive/folders/1ka62rgWZya7huoAZhrWwv1eb41onZM9s?usp=sharing

---

## Presentation
- **Recorded presentation video (~15 minutes)** explaining the project, methodology, results, and conclusions  
- **Presentation slides (PDF/PPT)** used in the video

Presentation Video (YouTube):  
https://youtu.be/WfoZL01okDw

Presentation Slides:  
https://drive.google.com/drive/folders/1ka62rgWZya7huoAZhrWwv1eb41onZM9s?usp=sharing


## Report
The final report is written using the IEEE conference proceedings format and includes:
- Abstract  
- Introduction  
- Related work / literature review  
- Results  
- Discussion and future work  

Final Report (IEEE format):  
https://drive.google.com/drive/folders/1ka62rgWZya7huoAZhrWwv1eb41onZM9s?usp=sharing

## Demo Video
A demo video is provided to visually showcase the project workflow, model outputs, and performance results.

Demo Video (YouTube):  
https://youtu.be/ncXdIQPdsCc


## How to Run the Project
1. Open below link
https://github.com/kmanas-2509/ece5831-2025-final-project/ece5831-2025-final-project

```
2. Open `final-project.ipynb`

> Note: The notebook contains executed cells to demonstrate successful runs and results.

## Results Summary
- AdaBoost achieved the best overall performance
- The 25-second time window provided the most stable detection
- Precision remained consistently high (~96%), indicating very few false positives
- Results confirm that pump-and-dump schemes leave detectable trading signatures

## Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib  
- Binance API  

## References
Key references are included in the final report, covering cryptocurrency manipulation detection, machine learning methods, and ensemble models.


## License
This project is for academic purposes as part of ECE 5831.

```

