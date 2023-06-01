# NLP Model Service 🧠 
The NLP Model Service is responsible for processing natural language text data and making predictions using a trained machine learning model. The model architecture used in this service is a combination of Long Short-Term Memory (LSTM) and Convolutional Neural Network (CNN) layers.
## Model Architecture
<div align="center">
    <div style="display: flex; flex-direction: row; justify-content: center; align-items: stretch;">
        <div style="display: flex; flex-direction: column; justify-content: center; align-items: center;">
            <img src="https://drive.google.com/uc?export=§view&id=10v-kx8AZ9Gm8ShsYlnLRK1PlvY8SIhso" style="margin-right: 10px;"/> 
            <p>This architecture describes NLP model.</p>
        </div>
    </div>
</div>

## Installation
To set up the NLP Model Service, follow these steps:
1. Install the required dependency by running the following command:

    `pip install openpyxl`  
  
2. Run the provided Jupyter Notebook (.ipynb) file on Colab or any other suitable environment to train and create your own machine learning model.

3. After running the notebook, you will obtain the output file classify_sentences.h5. This file should be placed under the lstm_and_cnn directory in the NLP Model Service.

4. Finally, run the __init__.py file to start the NLP Model Service.

Please ensure that all necessary dependencies are installed and the model file is correctly placed before running the service.