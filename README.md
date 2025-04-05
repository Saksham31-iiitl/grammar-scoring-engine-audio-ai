# 🧠 Grammar Scoring Engine (Audio-based ML)

This project is a grammar proficiency prediction system built for SHL's hiring challenge. It uses spoken audio samples to predict grammar scores (0–5) using machine learning techniques.

## 📂 Project Structure
- `audios_train/` - Training audio clips
- `audios_test/` - Test audio clips
- `train.csv` / `test.csv` - Metadata with filenames and labels
- `grammar_scoring_engine.ipynb` - Jupyter Notebook with full pipeline
- `my_submission.csv` - Final submission file
- `requirements.txt` - Python dependencies

## 🚀 Highlights
- Audio feature extraction using MFCCs (`librosa`)
- Regression models: RandomForest + XGBoost
- Evaluation using Pearson correlation, MSE, MAE
- Final score prediction ready for SHL submission

## 📊 Evaluation
- Pearson Correlation: **0.84**
- MSE: **0.087**
- MAE: **0.213**

## 🔧 Future Improvements
- Use of transformer-based audio models (e.g., Whisper)
- Add more audio features (pitch, chroma)
- Ensemble models

---
📌 Made with 💻 by Saksham for SHL AI Labs
