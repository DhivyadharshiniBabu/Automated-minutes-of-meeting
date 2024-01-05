# Automated minutes of meeting
  The Goal of Automated minutes of meeting is to keep track of key decisions and agreements that were made during a meeting. This project aims at providing minutes for the recorded meeting or the meeting transcripts by transforming an audio file into text and summarizing into condensed minutes.

## Processing from Audio to text :
* The Audio file is preprocessed using **Open AI-Whisper** to convert into text format
* The obtained text was summarized using **Extractive and Abstractive methods** of text summarization
* In Extractive method,**Sentence scoring** technique was used for obtaining the summary.
* Whereas, in Abstractive method the summary is obtained through the **T5 Transformer model**.
![](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.abstractivehealth.com%2Fextractive-vs-abstractive-summarization-in-healthcare&psig=AOvVaw2OS0rbd4iW6UBlI1PG0s6j&ust=1704521571772000&source=images&cd=vfe&opi=89978449&ved=0CBMQjRxqFwoTCKDb-ZjOxYMDFQAAAAAdAAAAABAD)

## Dataset used :
* The **XSum Dataset** has been used in the training phase of the T5 model.
* In testing phase, we used the **sample audio collected from our colleagues** and generated the summary.

## Evaluation Metrics used :
  **ROUGE Score** for validating the T5 model in Abstractive text Summarization.
