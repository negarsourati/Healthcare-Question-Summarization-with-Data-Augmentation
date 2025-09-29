## Project Overview
- **Dataset**: [MEQSUM](https://github.com/abachaa/MeQSum) – medical question summarization dataset with expert-written summaries.
- **Data Augmentation**:  
  - Round-Trip Translation (RTT) across multiple pivot languages (Spanish, German, Italian, Chinese, French).  
  - Selection of high-quality paraphrases using:
    - Frechét Question Distance (FQD)  
    - Precision Recall Question Distance (PRQD)  
    - Question Semantic Volume (QSV).  

- **Summarization Models**:
  - BART
  - T5
  - GPT-based models

- **Evaluation Metrics**:
  - ROUGE-1, ROUGE-2
  - BLEU, METEOR

---

## Steps Implemented
1. Load and preprocess MEQSUM dataset.  
2. Perform RTT-based paraphrase generation.  
3. Apply FQD, PRQD, and QSV to filter diverse and informative questions.  
4. Summarize questions using pre-trained models.  
5. Evaluate generated summaries with standard metrics.  
