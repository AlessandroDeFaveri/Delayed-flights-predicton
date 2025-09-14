# Delayed-flights-predicton
The project was developed as part of the Digital Transformation Management course at the University of Bologna.
It aims to predict the occurrence of arrival delays of at least 15 minutes relative to the scheduled time, after a flight’s departure

## Open the Notebook in Google Colab

Click the button below to launch the project directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/15sdMnCyhp5Wtc3iotAnjhRJSBmI7QjF_?usp=sharing)

## Required Dataset

The project uses the [Flight Delay and Cancellation Dataset (2019–2023)](https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023).  

### How to use it in Colab:

1. Make sure you have the Kaggle API installed:  
   ```bash
   !pip install kaggle
   ```

2. Upload your Kaggle API key (kaggle.json) to Colab:
    ```python
    from google.colab import files
    files.upload()  # upload kaggle.json
    ```
  
3. Place the key in the correct folder:
    ```bash
    !mkdir -p ~/.kaggle
    !cp kaggle.json ~/.kaggle/
    !chmod 600 ~/.kaggle/kaggle.json
    ```

4. Download and unzip the dataset:
    ```bash
    !kaggle datasets download -d patrickzel/flight-delay-and-cancellation-dataset-2019-2023 -p ./data --unzip
    ```


    
   

