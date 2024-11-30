### MS Spam Detector App

### Overview

The SMS Spam Classification Detector is a machine learning application that predicts whether an SMS message is "spam" or "not spam" (ham). It utilizes a pipeline comprising TF-IDF vectorization and Linear Support Vector Classification (SVC) to accurately classify SMS messages.

### Features

-   **Input**: Textbox for entering SMS messages.
    
-   **Output**: Textbox displaying the classification result ("spam" or "not spam").
       
-   **Model**: Pipeline with TF-IDF vectorizer and Linear SVC.

### Usage

-   **Enter** your SMS message in the input textbox.
    
-   **Submit** to get the classification result displayed in the output textbox.
    
-   Use the provided URL to access and share the app.

    ![sms_spam_interface.](sms_spam_interf.png)(http://127.0.0.1:7860

### Notes

-   The model is initially trained with a small sample dataset. For production use, it should be trained with a larger, more comprehensive dataset.
    
-   The app is designed to be easily deployable and shareable through Gradio's interface.