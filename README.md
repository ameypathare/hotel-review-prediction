## hotel-review-prediction

$${Overview \space Of \space Code:}$$
<br>
  - **Environment & Tools:**
    - Local environment with PyTorch, HuggingFace Transformers and scikit-learn.
    - GPU acceleration for DistilBERT fine-tuning.
  - **Dataset Source:**  
    - Kaggle: "Datafiniti_Hotel_Reviews_Jun19.csv" (10,000 reviews).  


---

${Data \space Preparation}$  
- Data Loading
- Sentiment Mapping

---

${Data \space Cleaning}$   
- Text Sanitization
- Handling Missing Values
- Duplicate Removal


---

${Data \space Preprocessing}$   

- Tokenization
- Embedding Generation.

---

${EDA}$   

- Sentiment Distribution
- Review Length Analysis
- Punctuation Patterns

---

${Visualization}$    

- Bar Chart – Visualized class distribution.  

---

${Modelling}$   

### **Hybrid Framewor**  
- Feature Engineering
- Model Architecture: DistilBERT Base: DistilBertForSequenceClassification(num_labels=3)


### *Model Training*  

- Fine-Tuning DistilBERT
- Class Balancing
- Hyperparameters


### *Performance Evaluation*  

- Confusion Matrix


### *Testing & Predictions*  

- Predicted sentiments on the test set using the best-performing model.
- Compared predicted labels with true labels.
- Displayed example reviews with predicted sentiment and confidence scores.


### *Model Evaluation*  

- **Confusion Matrix** – Analyzed classification performance.  
- **Identified misclassified images** to assess model weaknesses.  


### *Final Outcome*  

- Successfully classified hotel reviews into positive, neutral, and negative sentiments.
- Combined transformer-based embeddings with traditional ML models for improved accuracy.
- Built a scalable sentiment analysis system to help hotels monitor guest feedback efficiently.
