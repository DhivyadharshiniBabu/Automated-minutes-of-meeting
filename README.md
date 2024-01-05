# Automated minutes of meeting
  The Goal of Automated minutes of meeting is to keep track of key decisions and agreements that were made during a meeting. This project aims at providing minutes for the recorded meeting or the meeting transcripts by transforming an audio file into text and summarizing into condensed minutes.

## Processing from Audio to text :
* The Audio file is preprocessed using **Open AI-Whisper** to convert into text format
* The obtained text was summarized using **Extractive and Abstractive methods** of text summarization
* In Extractive method,**Sentence scoring** technique was used for obtaining the summary.
* Whereas, in Abstractive method the summary is obtained through the **T5 Transformer model**.
<p align="left">
  <img width="1=200" height="200" src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.fr.freelancer.com%2Fu%2Farunaddagatla%2Fportfolio%2Fabstractive-text-summarization-10585568&psig=AOvVaw2HwiFyf-dYtIvdRTtyAxKD&ust=1704521746833000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCLj-5LzMxYMDFQAAAAAdAAAAABAR">
</p>

## Dataset used :
* The **XSum Dataset** has been used in the training phase of the T5 model.
* In testing phase, we used the **sample audio collected from our colleagues** and generated the summary.

## Evaluation Metrics used :
  **ROUGE Score** for validating the T5 model in Abstractive text Summarization.
