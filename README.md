# CO3: Advanced NLP Using Transformers and Machine Learning

## 📌 Overview

This repository contains practical implementations of advanced Natural Language Processing (NLP) techniques using Python, Machine Learning, and Hugging Face Transformers.

The experiments cover transformer-based text classification, sentence embeddings, text generation, Named Entity Recognition (NER), machine translation, text summarization, chatbot development, automatic document classification, and hybrid sequence modeling for document boundary detection.

**Course Outcome:** CO3

## 🎯 Objectives

- Understand transformer-based NLP models.
- Implement text classification using BERT.
- Generate text using GPT-2.
- Extract named entities using pretrained transformers.
- Perform machine translation and text summarization.
- Develop a conversational chatbot.
- Automate document classification and separation.
- Explore probabilistic and Finite State Machine (FSM)-based sequence modeling.

## 🛠️ Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Hugging Face Transformers
- PyTorch
- Scikit-learn
- Pandas and NumPy
- NLTK / spaCy
- Matplotlib (where required)

## 📚 Experiments List

### Experiment 24: Fine-Tuning BERT for Text Classification Using Hugging Face

**Objective:** Fine-tune a pretrained BERT model to classify text into predefined categories.

**Key Concepts:**
- Tokenization
- BERT model
- Fine-tuning
- Text classification
- Model evaluation

**Libraries:** `transformers`, `datasets`, `torch`, `scikit-learn`

**Notebook:** `24_BERT_Text_Classification.ipynb`

### Experiment 25: Sentence Embeddings Using BERT and GPT-2

**Objective:** Generate vector representations of sentences using pretrained BERT and GPT-2 models.

**Key Concepts:**
- Token embeddings
- Sentence representations
- Mean pooling
- Cosine similarity
- Semantic similarity

**Libraries:** `transformers`, `torch`, `scikit-learn`

**Notebook:** `25_Sentence_Embeddings_BERT_GPT2.ipynb`

### Experiment 26: Text Generation Using GPT-2 on a Custom Dataset

**Objective:** Generate text using GPT-2 and explore its behavior with a custom text dataset.

**Key Concepts:**
- Pretrained GPT-2
- Text preprocessing
- Language modeling
- Text generation
- Sampling strategies

**Libraries:** `transformers`, `torch`

**Notebook:** `26_GPT2_Custom_Text_Generation.ipynb`

### Experiment 27: Named Entity Recognition Using Transformers (BERT)

**Objective:** Identify entities such as persons, organizations, locations, and other named entities in text.

**Key Concepts:**
- Named Entity Recognition (NER)
- Token classification
- BERT
- Entity extraction

**Libraries:** `transformers`, `torch`

**Notebook:** `27_BERT_Named_Entity_Recognition.ipynb`

### Experiment 28: Machine Translation Using MarianMT or T5

**Objective:** Translate text from one language to another using pretrained Hugging Face translation models.

**Key Concepts:**
- Machine translation
- Encoder-decoder architecture
- MarianMT / T5
- Tokenization
- Translation evaluation

**Libraries:** `transformers`, `sentencepiece`, `torch`

**Notebook:** `28_Machine_Translation_MarianMT_T5.ipynb`

### Experiment 29: Text Summarization Using BART or T5

**Objective:** Generate concise summaries of longer documents using pretrained transformer models.

**Key Concepts:**
- Abstractive summarization
- BART / T5
- Input tokenization
- Summary generation
- Text preprocessing

**Libraries:** `transformers`, `torch`

**Notebook:** `29_Text_Summarization_BART_T5.ipynb`

### Experiment 30: Chatbot Development Using a Pretrained Transformer

**Objective:** Develop a conversational chatbot using a pretrained DialoGPT model or another suitable conversational language model.

**Key Concepts:**
- Conversational AI
- Dialogue generation
- Context management
- Transformer-based language models
- Chat history

**Libraries:** `transformers`, `torch`

**Notebook:** `30_Transformer_Chatbot_DialoGPT.ipynb`

### Experiment 31: Automatic Document Classification and Separation Using ML

**Objective:** Automatically classify documents into predefined categories and separate them according to their predicted labels.

**Key Concepts:**
- Text preprocessing
- TF-IDF vectorization
- Machine learning classification
- Model evaluation
- Document sorting and separation

**Libraries:** `pandas`, `scikit-learn`, `os`, `shutil`

**Notebook:** `31_Automatic_Document_Classification.ipynb`

### Experiment 32: Hybrid Probabilistic + FSM-Based Sequence Modeling for Document Boundary Detection

**Objective:** Detect document boundaries by combining probabilistic sequence modeling with a Finite State Machine (FSM).

**Key Concepts:**
- Probabilistic sequence modeling
- Finite State Machine (FSM)
- Sequence transitions
- Boundary detection
- Document segmentation

**Libraries:** `numpy`, `re` and other libraries as required by the implementation.

**Notebook:** `32_Hybrid_Probabilistic_FSM_Boundary_Detection.ipynb`

## ⚙️ Installation

Clone this repository:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

Navigate to the project directory:

```bash
cd YOUR-REPOSITORY
```

Install the required libraries:

```bash
pip install transformers torch datasets scikit-learn pandas numpy sentencepiece nltk
```

For notebook execution, install Jupyter:

```bash
pip install notebook
jupyter notebook
```

Alternatively, open the notebooks in Google Colab.

## ▶️ How to Run

1. Clone or download this repository.
2. Open the required `.ipynb` notebook in Google Colab or Jupyter Notebook.
3. Install the dependencies mentioned in the notebook.
4. Upload or load the required dataset, if applicable.
5. Run the cells sequentially.
6. Review the generated outputs and evaluation results.

**Note:** Some transformer models require an internet connection for their initial download. Large models may also require a GPU or substantial memory.

## 📊 Expected Outcomes

After completing these experiments, learners will be able to:

- Fine-tune transformer models for NLP tasks.
- Generate sentence embeddings and analyze semantic similarity.
- Perform text generation, NER, translation, and summarization.
- Build a basic conversational chatbot.
- Apply machine learning to automatic document classification.
- Combine probabilistic methods and FSMs for sequence boundary detection.

## 📁 Repository Structure

```text
CO3-Advanced-NLP/
│
├── README.md
├── 24_BERT_Text_Classification.ipynb
├── 25_Sentence_Embeddings_BERT_GPT2.ipynb
├── 26_GPT2_Custom_Text_Generation.ipynb
├── 27_BERT_Named_Entity_Recognition.ipynb
├── 28_Machine_Translation_MarianMT_T5.ipynb
├── 29_Text_Summarization_BART_T5.ipynb
├── 30_Transformer_Chatbot_DialoGPT.ipynb
├── 31_Automatic_Document_Classification.ipynb
└── 32_Hybrid_Probabilistic_FSM_Boundary_Detection.ipynb
```

## 👨‍💻 Author

**Ankit Maurya**

B.Tech – Computer Science and Engineering (Artificial Intelligence)

## 📄 License

This repository is intended for educational and academic purposes.

## 🙌 Acknowledgements

- Hugging Face Transformers Documentation
- PyTorch Documentation
- Scikit-learn Documentation
- Google Colab
