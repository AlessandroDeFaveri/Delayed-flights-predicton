# Delayed-flights-predicton
The project was developed as part of the Digital Transformation Management course at the University of Bologna.

It aims to predict the occurrence of arrival delays of at least 15 minutes relative to the scheduled time, after a flight’s departure.

## Open the Notebook in Google Colab

Click the button below to launch the project directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/15sdMnCyhp5Wtc3iotAnjhRJSBmI7QjF_?usp=sharing)


## Required Dataset

The project uses the [Flight Delay and Cancellation Dataset (2019–2023)](https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023).  

For performance reasons, the **sample file** `flights_sample_3m.csv` (~3M records) is used instead of the full dataset.  

### How to use it in Colab (via Google Drive)

1. Download `flights_sample_3m.csv` once from Kaggle.  
2. Upload the file into your **Google Drive** (recommended path: `MyDrive/Colab Notebooks/data/`).  
3. Mount Google Drive in Colab and set the dataset path as follows:

   ```python
   from google.colab import drive
   drive.mount('/content/drive')
    ```


    
   

