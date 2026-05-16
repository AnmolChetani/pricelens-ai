# PriceLens AI

A production-grade multimodal machine learning system for intelligent product price prediction using **Natural Language Processing (NLP)** and **Computer Vision (CV)**.

PriceLens AI predicts product prices by learning from:

- Product descriptions (`catalog_content`)
- Product images (`image_link`)

The system combines textual and visual understanding through **multimodal learning architectures** to improve price estimation accuracy.

---

## Project Overview

Traditional pricing systems often rely on structured metadata or historical pricing.

PriceLens AI leverages:

- **NLP** to understand product descriptions
- **Computer Vision** to extract visual patterns
- **Multimodal Fusion** to combine text and image understanding

This project is designed to simulate a **real-world production ML system**.

---

## Problem Statement

Predict product prices using:

### Inputs
- Product catalog description
- Product image

### Output
- Predicted product price

This is a **supervised regression problem**.

---

## Tech Stack

### Machine Learning
- Python
- Scikit-learn
- XGBoost
- LightGBM
- PyTorch

### NLP
- TF-IDF
- Sentence Transformers
- BERT

### Computer Vision
- ResNet50
- EfficientNet
- Transfer Learning

### Deployment
- FastAPI
- Docker
- Render / AWS

---

## Project Architecture

```text
                Product Description
                          │
                          ▼
                    NLP Embeddings
                          │
                          ▼
                    Text Features
                          │
                          ├──────────┐
                          │          │
                          ▼          │
                     Fusion Layer    │
                          ▲          │
                          │          │
                    Image Features   │
                          ▲          │
                          │          │
                    CNN Embeddings   │
                          ▲
                          │
                    Product Image
                          │
                          ▼
                   Predicted Price
```

---

## Project Structure

```text
pricelens-ai/
│
├── notebooks/
├── src/
├── saved_models/
├── app/
├── requirements.txt
└── README.md
```

---

## Development Roadmap

### Phase 1 — Exploratory Data Analysis
- Data inspection
- Missing values
- Price distribution
- Text analysis
- Image inspection

### Phase 2 — Baseline Model
- TF-IDF
- Regression Models
- Benchmark score

### Phase 3 — Advanced NLP
- Sentence Transformers
- BERT Embeddings

### Phase 4 — Image Modeling
- ResNet50
- EfficientNet
- Transfer Learning

### Phase 5 — Multimodal Fusion
- Text + Image fusion
- Deep regression model

### Phase 6 — Production Deployment
- FastAPI API
- Dockerization
- Cloud deployment

---

## Results

| Model | Features | Status |
|--------|----------|--------|
| Baseline | Text | Pending |
| Transformer | Text | Pending |
| CNN | Image | Pending |
| Multimodal | Text + Image | Pending |

---

## Future Improvements

- Advanced multimodal architectures
- Ensemble learning
- Hyperparameter tuning
- Experiment tracking
- Real-time inference optimization

---

## Author

Machine Learning Engineering Project focused on multimodal AI systems and production-grade ML workflows.
