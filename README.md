# **AI Text Detector – Bulk & Single Detection**  

This project detects AI-generated text using a **RoBERTa-based classifier**.  

## **📌 Features**  
✅ **Single-text detection** – Quickly check if a short passage is AI-generated.  
✅ **Bulk detection** – Process large datasets (100+ essays) with CSV input.  
✅ **Optimized for efficiency** – Uses a **progress bar** for bulk processing.  

---

## **📌 Setup**  

1️⃣ **Clone the repository**  
```sh
git clone https://github.com/your-username/ai-text-detector.git
cd ai-text-detector
python main.py
📂 Project Structure
ai_text_detector_project/
│── data/
│   ├── input.csv  # Your dataset with text to analyze
│   ├── processed_results.csv  # Output results after processing
│── src/
│   ├── detector.py  # AI detection logic
│── notebooks/
│   ├── analysis.ipynb  # Jupyter notebook for experiments
│── requirements.txt  # Dependencies
│── README.md  # Project description and usage guide
│── .gitignore  # Ignore large files, cache, etc.
│── main.py  # Script to run detection on a dataset

