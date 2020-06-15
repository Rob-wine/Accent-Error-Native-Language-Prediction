# Accent-Archive-Predicts
Capstone Project- Executive Statement

### Using the Accent Error Archive website, built and maintained by George Mason University in Washington D.C, I want to investigate the ways in which phonetic error type frequencies can be used to predict native languages. The archive consists of recording by speakers from a diverse variety of countries of origin and native languages. In each recording, they speak in English, while they read the same standarized passage. What is being investigated from recording to recording, is the accent that they exhibit while speaking english.The other information contained in the archive is: ###

< **Meta Data**
(**Age**, **Gender**, **Years Speaking English**, **Method of learning Engish**, **English speaking country where they have resided**, **Other Languages** that the speaker speaks, by **name** and **quantity**, **Country of Origin**, including a **Map of Birth, and English Residence Locations** and **Native Language**)
        
**Images** of phoneme translations of there exact errors. **Sound recordings** of the speakers reading the passage. An example of the passage in **Standard English text**. **Precise Error type embedded and highlighted into the standard English text**. The kaggle data does not contain the precise error type and location information or certain components of the meta data, including the lat/long information. I am scraping these elements. >

See first: Native_Language_prediction_by_accent_error.ipynb
See second: lat_long.ipynb

# Hypothesis & Testing

Problem Statement-  How can we Use machine learning to create a  tool for accent recognition and/or acquisition?

Potential Audience-  Players of an accent prediction game. Companies that outsource customer service support to other non-English language speaking countries. Training Students or Actors who want to acquire standard English accents.

Goals-  Scrape all of the available data from the Speech Accent Error website, identify all of the specific error types and locations by creating an indexing system, capturing the text of error and then deriving the frequency of specific error types for  all speakers categorized by native language type. Preform a variety of classification models, with tuned parameters as well as pca and under and oversampling to see to what degree the models can predict native language, without being allowed to cheat by providing them with highly correlated meta data.

Success Metrics-  Parse  and transform scraped data for complex purposes. Build a collection of classification models, find the best performing model and improve  it's accuracy, Create an interactive framework to gather more data  for further modeling.