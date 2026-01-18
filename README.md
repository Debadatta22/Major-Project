# Major-Project

# 📜 Designing an Odia to English Translator for Classical Texts  
## 🧠 Neural Machine Translation (NMT) with Poetic Essence Preservation

<p align="center">
  <b>A data-centric, feature-aware Neural Machine Translation system designed to preserve meaning, rhythm, emotion, and poetic structure while translating classical Odia texts into English.</b>
</p>

<p align="center">
  <a href="https://drive.google.com/file/d/17nxboVJQRhAtbR9QvciEB3htwmaDjMDY/view?usp=drive_link">
    <img src="https://img.shields.io/badge/📘_View_Thesis-Click_Here-blue?style=for-the-badge">
  </a>
  <a href="https://drive.google.com/file/d/1p2Bk8U7JxKnqQWP6YuhacBeaHSzNGlwq/view?usp=sharing">
    <img src="https://img.shields.io/badge/🎥_Demo_Video-Watch_Now-red?style=for-the-badge">
  </a>
  <a href="https://drive.google.com/file/d/1WZucphoAUBrfLmAMHdvbgMfCwGRfvEk9/view?usp=sharing">
    <img src="https://img.shields.io/badge/📄_Research_Paper-Read_PDF-green?style=for-the-badge">
  </a>
</p>


----------------
## DataSets

<a href="https://www.kaggle.com/datasets/debdattarut/english-poetry-rhyme-scheme-dataset">
  <img src="https://img.shields.io/badge/Dataset-Rhyme%20Scheme-blue?style=for-the-badge&logo=kaggle" />
</a>

<a href="https://www.kaggle.com/datasets/debdattarut/odia-english-poetic-expanded">
  <img src="https://img.shields.io/badge/Dataset-Odia--English%20Poetry-success?style=for-the-badge&logo=kaggle" />
</a>

<a href="https://www.kaggle.com/datasets/debdattarut/odia-vocabulary-dataset">
  <img src="https://img.shields.io/badge/Dataset-Vocabulary%20Corpus-orange?style=for-the-badge&logo=kaggle" />
</a>


---

## 📌 Project Overview

Classical Odia poetry is rich in **rhythm, metaphor, emotion, and cultural depth**. Conventional machine translation systems often focus only on literal meaning, resulting in translations that lose poetic charm.

This project proposes a **dual-objective Neural Machine Translation (NMT) framework** that not only translates Odia text into English accurately, but also **retains poetic essence** such as:

- Rhyme scheme  
- Emotional tone  
- Line structure and rhythm  
- Stylistic flow  

The system combines **modern Transformer-based NMT models** with **custom poetic feature engineering**, creating a hybrid translation pipeline suitable for literary and creative texts.

---

## 🎯 Objectives

- Translate classical Odia poetry into English with high semantic accuracy  
- Preserve poetic characteristics (rhyme, rhythm, emotion)  
- Address low-resource challenges for Odia language  
- Create reusable poetic datasets and evaluation frameworks  
- Bridge AI, linguistics, and digital humanities  

---

## 🧩 Core Idea & Logic

### Why Traditional NMT Fails for Poetry
- Optimized for news/conversational text
- Ignores rhyme, meter, cultural symbolism
- Produces flat, literal translations

### Our Solution
We decompose the problem into **two complementary stages**:

1. **Literal Translation (Semantic Fidelity)**  
   Uses Transformer-based NMT models (T5, mBART, MarianMT)

2. **Poetic Preservation (Stylistic Fidelity)**  
   Applies rhyme detection, emotion analysis, and poetic synthesis to refine outputs

This layered design allows **control over artistic elements** without sacrificing meaning.

---

## 🏗️ System Architecture (High Level)
Block Diagram:

<img width="827" height="302" alt="MP_Block_Diagram__1_-removebg-preview" src="https://github.com/user-attachments/assets/c2d7f645-79f9-41a7-90e3-5d2fe0f20162" />


---

## 📚 Custom Datasets Created

### 1️⃣ English Rhyme Scheme Corpus
- 2,800+ records
- Classical English poems + synthetic rhyme patterns
- Used for rhyme detection and generation

### 2️⃣ Odia–English Parallel Poetic Corpus
- 3,500+ aligned pairs
- Authentic poetry, vocabulary, phrases, synthetic augmentation
- Includes metadata: emotion_tone, line_complexity, alliteration

### 3️⃣ Poetic Elements Lexicon
- Odia poetic terms mapped to English meanings
- Cultural symbols, months, punctuation semantics
- 500+ poetic concepts

---

## 🧠 Models & Techniques Used

### NMT Models
- T5 (Text-to-Text Transformer)
- mBART (Multilingual Translation)
- MarianMT
- AutoModelForSeq2SeqLM

### Poetic Analysis
- Rhyme detection using phonetic analysis
- Emotion analysis using NLTK VADER
- Structural and complexity metrics
- Rule-based poetic constraints

### Training Enhancements
- Synthetic data augmentation
- Feature-aware fine-tuning
- Beam search with constrained decoding

---

## 📊 Evaluation Strategy

### Automatic Metrics
- BLEU
- ROUGE-L
- chrF
- Perplexity

### Poetic Metrics (Custom)
- Rhyme Accuracy
- Emotion Similarity
- Line Structure Retention

### Human Evaluation
- Fluency
- Adequacy
- Poeticness  
(Rated by bilingual Odia-English reviewers)

---

## 🧪 Key Results

| Metric | Baseline NMT | Proposed System |
|------|-------------|----------------|
| BLEU | 17.8 | 18.9 |
| Rhyme Accuracy | 22% | 61% |
| Emotion Similarity | 0.57 | 0.72 |
| Human Poeticness | 2.2 / 5 | 4.1 / 5 |

➡️ **Major gain observed in poetic quality with minimal semantic trade-off**

---

## ⚙️ Environment & Tech Stack

- **Language:** Python 3.12  
- **Frameworks:** PyTorch, TensorFlow  
- **Libraries:** Transformers, SentencePiece, NLTK, SacreBLEU  
- **Platform:** Google Colab / Local GPU  
- **Hardware:** GPU recommended (T4 / V100)

---

## 🚧 Limitations

- Limited size of authentic poetic data
- Cultural metaphors require deeper contextual modeling
- Poetic constraints may slightly alter literal meaning
- Higher inference time due to synthesis step

---

## 🚀 Future Enhancements

- Expand corpus with crowdsourced classical poetry
- Integrate Large Language Models (LLMs)
- Add multilingual poetic translation
- Build interactive human-AI poetic editing tool
- Deploy as web/mobile application
- Develop standardized poetic evaluation benchmarks

---

## 🌍 Applications

- Digital preservation of Odia literature
- Cross-lingual literary research
- AI-assisted creative writing
- Educational tools for language learning
- Digital humanities and cultural archives

---

## 👨‍💻 Author

**Debadatta Rout**  
Final-Year Computer Science Engineering Student  
Research Area: Neural Machine Translation, NLP, AI for Literature  

---

## ⭐ Final Note

> *This project demonstrates that AI can translate not only words, but also rhythm, emotion, and cultural soul — when guided by thoughtful data design and poetic awareness.*

If you find this work meaningful, feel free to ⭐ star the repository and explore the thesis, demo, and research paper above.


## Future Plan:
```
┌─────────────────────────────────────────────────────────────────┐
│                    INPUT PROCESSING LAYER                       │
├─────────────────────┬─────────────────────┬─────────────────────┤
│   Text Input        │   Document Upload   │   Image Input       │
│   (Direct Entry)    │   (PDF/TXT/DOC)     │   (OCR Processing)  │
└─────────────────────┴─────────────────────┴─────────────────────┘
                                │
                                ▼
┌─────────────────────────────────────────────────────────────────┐
│              PREPROCESSING & CULTURAL ANALYSIS                  │
├─────────────────────────────────────────────────────────────────┤
│  • Odia Script Normalization    • Cultural Context Detection    │
│  • Tokenization & Segmentation  • Poetic Device Recognition     │
│  • Metadata Extraction          • Style Pattern Analysis        │
└─────────────────────────────────────────────────────────────────┘
                                │
                                ▼
┌─────────────────────────────────────────────────────────────────┐
│                  HYBRID TRANSLATION ENGINE                      │
├─────────────────────────────────────────────────────────────────┤
│  ┌─────────────────────┐    ┌─────────────────────────────────┐ │
│  │   Base NMT Model    │    │     Cultural Preservation       │ │
│  │  (Fine-tuned on     │────│        Component                │ │
│  │   Poetic Corpus)    │    │  • Rule-based Metaphor Mapping  │ │
│  └─────────────────────┘    │  • Cultural Context Integration │ │
│                             └─────────────────────────────────┘ │
│  ┌─────────────────────────────────────────────────────────────┐│
│  │           Style Transfer & Enhancement Module               ││
│  │  • Rhythm Pattern Matching   • Poetic Device Preservation   ││
│  │  • Rhyme Scheme Adaptation   • Aesthetic Quality Enhancement││
│  └─────────────────────────────────────────────────────────────┘│
└─────────────────────────────────────────────────────────────────┘
                                │
                                ▼
┌─────────────────────────────────────────────────────────────────────┐
│                   DUAL OUTPUT GENERATION                            │
├─────────────────────┬─────────────────────┬─────────────────────────┤
│   Literal Translation│  Poetic Translation │  Cultural Annotations  │
│   (Semantic Focus)   │  (Aesthetic Focus)  │  (Context Preservation)│
└─────────────────────┴─────────────────────┴─────────────────────────┘
                                │
                                ▼
┌─────────────────────────────────────────────────────────────────┐
│              COMPREHENSIVE EVALUATION SYSTEM                    │
├─────────────────────────────────────────────────────────────────┤
│  • Automated Metrics (BLEU, BERTScore, METEOR)                  │
│  • Poetic Quality Assessment (Rhythm, Rhyme, Metaphor)          │
│  • Human Expert Evaluation (Literary Scholars)                  │
│  • Cultural Authenticity Validation                             │
└─────────────────────────────────────────────────────────────────┘
                                │
                                ▼
┌─────────────────────────────────────────────────────────────────┐
│            WEB-BASED INTERFACE (NabakalebaraNMT)                │
├─────────────────────────────────────────────────────────────────┤
│  • Multi-input Support       • Real-time Translation            │
│  • Comparative Output Display• Human Feedback Integration       │
│  • Collaborative Editing     • Cultural Context Explanations    │
└─────────────────────────────────────────────────────────────────┘
