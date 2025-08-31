# Major-Project

 Designing an Odia to English Translator for Classical Texts using Neural Machine Translation (NMT) while Retaining Poetic Essence

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
