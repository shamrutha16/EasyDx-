
# EasyDX 



A simple chatbot that can help users check their symptoms and provide relevant information. This chatbot uses natural language processing (NLP) techniques and a recurrent neural network (RNN) model to understand user queries and respond accordingly.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Training](#training)
- [Dependencies](#dependencies)


## Introduction

This repository contains code for a EasyDx (symptom checker chatbot). The chatbot can engage in conversations with users, gather information about their symptoms, and provide information about potential conditions or nearby medical centers. It uses a pre-trained RNN model for natural language understanding.

## Getting Started

To get started with the EasyDx, follow these steps:

1. Clone the repository to your local machine:

  

2. Install the required dependencies:



3. Download the necessary data files and place them in the appropriate directories:
   - `intents.json`: Contains predefined intents for the chatbot.
   - `data_rnn.pth`: Pre-trained RNN model for natural language understanding.
   - `medical_centers.json`: Data file containing information about medical centers.

## Usage

To use the EasyDx , run the `app.py` file:

```
python app.py
```

This will start a Flask web application that you can interact with. 

## Training

If you want to retrain the RNN model or modify the chatbot's behavior, follow these steps:

1. Modify the intents and patterns in `intents.json` to customize the chatbot's responses.

2. Run the training script to retrain the RNN model:

   ```
   python train.py
   ```

3. Save the trained model with a new filename and update the `FILE` variable in `chat.py` with the new filename.

## Dependencies

The Symptom Checker Chatbot relies on the following dependencies:

- Python 3.x
- PyTorch
- Flask
- NLTK
- geocoder


You can install these dependencies using the provided `requirements.txt` file.



---

---
