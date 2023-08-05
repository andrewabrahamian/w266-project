# ECTQA: Expanding Earnings Call Transcript Summarization

- [Paper](https://drive.google.com/file/d/10T5dFbaFxWsjvcKADsinkoHHGSJOua50/view?usp=drive_link)
- [Presentation](https://docs.google.com/presentation/d/1RtnstHrDSqOiAghMz-ZIyZIkulTVMRpADbt76pBLv-A/edit?usp=sharing)
- [Human Evaluation Analysis](https://docs.google.com/spreadsheets/d/1FqbbUi6S3VujwpzZM7Ey0CVCCR_SLGOA0CddqmMiJlw/edit?usp=drive_link)

## Abstract
There has been significant progress in automatic text summarization yet financial document summarization is still an emerging field of study, particularly for public company's earnings calls. Techniques to efficiently and effectively summarize company earnings calls in a comprehensive yet consumable manner are still in their infancy. In this paper, we present **ECTQA**, a novel dataset of the Q&A sections of **earnings call transcripts (ECTs)** hosted by publicly-traded companies and reference summaries generated a salient sentence extractive model. These Q&A sections are typically 90% of any given earnings call and are largely under-analyzed by academic research and financial news organizations. We also present methods to fine-tune the **ECT-BPS** modeling framework that generates both extractive and abstractive paraphrased summaries of the *Prepared Remarks* of ECTs with the intent to apply it to our novel **ECTQA** dataset.

## Data
The **ECTQA** dataset can be found in the `data` folder. 

## Models
The extractive, abstractive, unsupervised, and long document summarization models dan be found in the `models` folder.

## Code
The notebooks can be found in the `code` folder.