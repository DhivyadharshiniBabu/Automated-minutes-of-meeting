# Automated minutes of meeting
  The Goal of Automated minutes of meeting is to keep track of key decisions and agreements that were made during a meeting. This project aims at providing minutes for the recorded meeting or the meeting transcripts by transforming an audio file into text and summarizing into condensed minutes.

## Processing from Audio to text :
* The Audio file is preprocessed using **Open AI-Whisper** to convert into text format
* The obtained text was summarized using **Extractive and Abstractive methods** of text summarization
* In Extractive method,**Sentence scoring** technique was used for obtaining the summary.
* Whereas, in Abstractive method the summary is obtained through the **T5 Transformer model**.
<img width="842" alt="63bd8a1f20da862484184fdb_blog extractive " src="https://github.com/DhivyadharshiniBabu/Automated-minutes-of-meeting/assets/121101960/7c685a90-dd67-4d54-b949-b1b4f869c44b">
![0_xfXDPjASztwmJlOa](https://github.com/DhivyadharshiniBabu/Automated-minutes-of-meeting/assets/121101960/e5e04dc8-695b-4a5d-9a43-0f633c0e3724)

## Dataset used :
* The **XSum Dataset** has been used in the training phase of the T5 model.
* In testing phase, we used the **sample audio collected from our colleagues** and generated the summary.

## Evaluation Metrics used :
  **ROUGE Score** for validating the T5 model in Abstractive text Summarization.
