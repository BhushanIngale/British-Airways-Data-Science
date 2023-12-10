
# British Airways : Data-Science

Uncovering company insights and predicting customer buying behaviours.


## Project Overview
This project is part of the Virtual Experience Programme at British Airways offered by Forage.

### Problem Statement:

- Task 1: Web scraping to gain company insights

        1. Scrape and collect customer feedback by analysing third-party data
        2. Present your insights in using PowerPoint

- Task 2: Predicting customer buying behaviour

        1. Prepare a dataset
        2. Train a machine learning model
        3. Evaluate and present your findings


### Approach:

Web Scraping for collecting the data and Sentiment Analysis using NLP and Transfer Learning for uncovering customer insights.

## Installation & Setup

### Resources Used

- Editor/IDE: Jupyter Notebook
- Environment/Backend: Conda
- Python Version: 3.9

### Python Packages Used

- General Purpose: warnings
- Data Wrangling: numpy, pandas, pycountry_convert
- Web Scraping: requests, bs4
- Data Visualization: matplotlib, seaborn
- NLP: nltk, re, wordcloud, transformers, torch
- Machine Learning: scipy, sklearn, imblearn

## Data
British Airways Customer Reviews are taken from:
`https://www.airlinequality.com`

## Code Structure
```
├── certificate
│   └── British Airways Certificate.pdf
├── reports
│   ├── Presentation_Task_1.pdf
│   ├── Presentation_Task_1.pptx
│   ├── Presentation_Task_2.pdf
│   └── Presentation_Task_2.pptx
├── src
│   ├── data
│   │   ├── BA_Reviews.csv
│   │   ├── BA_Reviews_Cleaned.csv
│   │   └── customer_booking.csv
│   ├── British_Airways_Task_1.ipynb
│   ├── British_Airways_Task_2.ipynb
│   └── Getting Started.ipynb
├── .gitignore
└── README.md
```
## Results & Evaluation

### Conclusion/Insights

- From the Feature Importance Plot, we see that `Length of Stay` and `Purchase Lead` are the 2 most important features.
- We need to add more flights on Weekends.
- More Flights can be added to these routes: AKLKUL, DMKKIX, PENTPE, ICNSIN, MELSGN

## Future Work
This projects performance can further be enhanced by increasing the number of reviews taken for the data preparation as well as using newer pre-trained models from HuggingFace.

## License

[MIT](https://choosealicense.com/licenses/mit/)


