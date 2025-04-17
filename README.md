
# 📦 NLP_Customers_Reviews_Fine_tuning

**Fine-Tuning a Language Model on Customer Reviews**  
This project focuses on enhancing a language model using real-world customer review data to improve sentiment understanding, review summarization, and overall NLP capabilities.

---

## 🧠 Project Overview

The project involves fine-tuning a transformer-based model using datasets containing customer reviews. It includes sentiment classification, clustering, summarization, and deployment for user interaction.

---

## 📁 Project Structure

```
NLP_Customers_Reviews_Fine_tuning/
├── classification/       # Review sentiment classification code
├── claster/              # Clustering and analysis of product reviews
├── dploy/                # Deployment using Streamlit or other frameworks
├── summary/              # Text summarization logic and scripts
├── done.csv              # Cleaned dataset of customer reviews
├── requirements.txt      # Required Python libraries
└── README.md             # This file
```

---

## ⚙️ Requirements

Install all required libraries using pip:

```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

1. **Classification**:

```bash
cd classification
python classify_reviews.py
```

2. **Clustering**:

```bash
cd claster
python cluster_analysis.py
```

3. **Summarization**:

```bash
cd summary
python summarize_reviews.py
```

4. **Deployment**:

```bash
cd dploy
streamlit run app.py
```

---

## 📊 Dataset

The project uses a cleaned dataset named `done.csv` containing real customer reviews. Make sure the file is present and properly formatted.

---

## 🤝 Contribution

Contributions are welcome! Feel free to fork the repository, make changes, and open a pull request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
