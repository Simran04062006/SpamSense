# 📧 SpamSense

SpamSense is a specialized text analytics platform that uses a **Multinomial Naive Bayes classifier** to identify spam. Unlike simple blacklists, SpamSense calculates the probability of a message being spam based on the frequency and distribution of words within a provided training corpus.

---

## 🚀 Features
- **Probabilistic Classification**  
  Real-time analysis of input text with confidence scoring.

- **Keyword Sensitivity**  
  Visual breakdown (via **Recharts**) showing which words had the highest impact on the decision.

- **Dynamic Training**  
  Users can add their own "Ham" or "Spam" samples to the corpus to improve the model’s accuracy on the fly.

- **AI-Powered Context**  
  Uses **Gemini AI** to explain why the mathematical model reached its conclusion in plain English.

---

## 🛠️ Tech Stack
- **Frontend**: React + Recharts (for visualization)  
- **Backend**: Node.js / Python (for model training
