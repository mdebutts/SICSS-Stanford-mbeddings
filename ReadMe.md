# Word Embeddings Tutorial - SICSS Stanford 2025

This repository contains materials for a hands-on lecture on word embeddings presented at the [Summer Institute in Computational Social Science (SICSS) at Stanford University](https://sicss.io/2025/stanford/), August 4-15, 2025.

## Overview

This tutorial introduces participants to the foundational concepts of word embeddings through an interactive, hands-on approach. Rather than diving straight into complex neural networks, we build understanding from the ground up using co-occurrence matrices and distributional semantics.

### Learning Objectives

By the end of this tutorial, participants will:
- Understand the core principle of distributional semantics: "You shall know a word by the company it keeps"
- Build co-occurrence matrices from scratch using real text data
- Grasp how high-dimensional word representations capture semantic relationships
- See how dimensionality reduction creates practical word embeddings
- Practice the mathematical intuitions behind modern embedding techniques

## Tutorial Structure

### 1. Introduction: The Semantle Game
We begin with [Semantle](https://semantle.com/), an engaging word-guessing game that demonstrates how semantic similarity can be computationally measured.

### 2. Distributional Semantics Foundation
- Core concept: words are defined by their contexts
- Interactive examples with sentence completion
- The "company you keep" principle

### 3. Building Co-occurrence Matrices
- Hands-on construction of word-context matrices
- Processing real sentences containing target words
- Understanding how frequency patterns encode meaning

### 4. From Raw Counts to Embeddings
- Normalization and dimensionality challenges
- Consolidating similar contexts (e.g., "decide," "rule," "command")
- Creating lower-dimensional representations

### 5. Mathematical Foundations
- Vector operations and semantic arithmetic
- Distance metrics and similarity calculations
- The famous "king - man + woman = queen" example

## Files in This Repository

- `Embeddings_Lecture.ipynb` - Main tutorial notebook with interactive exercises
- `Sample_Sentences.csv` - Dataset of sentences containing target words for analysis
- `requirements.txt` - Python dependencies needed to run the tutorial
- `README.md` - This file

## Getting Started

### Prerequisites
- Basic Python programming knowledge
- Familiarity with Jupyter notebooks
- Understanding of basic linear algebra concepts (helpful but not required)

### Installation

1. Clone this repository:
```bash
git clone https://github.com/mdebutts/SICSS-Stanford-mbeddings.git
cd SICSS-Stanford-mbeddings
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Download required NLTK data:
```python
import nltk
nltk.download('punkt')
nltk.download('wordnet')
```

5. Launch Jupyter notebook:
```bash
jupyter notebook Embeddings_Lecture.ipynb
```

## Tutorial Flow

The notebook is designed for interactive participation:

1. **Warm-up**: Play Semantle to experience semantic similarity
2. **Concept Building**: Work through distributional semantics examples
3. **Hands-on Construction**: Build your own co-occurrence matrices
4. **Data Processing**: Analyze real text data with 500+ sentences
5. **Synthesis**: See how individual concepts combine into modern embeddings

## Key Concepts Covered

- **Distributional Semantics**: How context defines meaning
- **Co-occurrence Matrices**: Capturing word relationships through frequency
- **Dimensionality Reduction**: From high-dimensional counts to practical embeddings
- **Semantic Similarity**: Mathematical measures of word relationships
- **Vector Arithmetic**: Operations that reveal semantic structures

## Educational Philosophy

This tutorial prioritizes conceptual understanding over technical implementation. By building embeddings from first principles, participants develop intuitions that help them:
- Choose appropriate embedding models for their research
- Understand the limitations and biases in pre-trained embeddings
- Design custom embeddings for domain-specific applications
- Critically evaluate embedding-based analyses in computational social science

## About SICSS Stanford 2025

The Summer Institute in Computational Social Science at Stanford University runs from August 4 to August 15, 2025, bringing together graduate students, postdoctoral researchers, faculty, and others interested in computational social science. The program focuses on studying online information systems and emerging technologies through lectures, group activities, guest speakers, and participant-led research projects.

## Target Audience

This material is designed for SICSS participants with varying levels of computational experience, including:
- Social scientists new to computational methods
- Data scientists interested in text analysis applications
- Researchers working with digital trace data
- Anyone curious about how language models understand meaning

## Contributing

If you find errors or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## License

This educational material is released under the MIT License, consistent with SICSS's commitment to open and reproducible research.

## Acknowledgments

- The SICSS community for promoting open computational social science education
- Stanford's Cyber Policy Center and Social Media Lab for hosting SICSS-Stanford 2025
- The creators of Semantle for inspiring the tutorial's opening
- The broader computational linguistics community for developing the theoretical foundations

## Contact

For questions about this tutorial or SICSS Stanford 2025, please refer to the [official SICSS Stanford website](https://sicss.io/2025/stanford/).

---

*"You shall know a word by the company it keeps." - J.R. Firth, 1957*