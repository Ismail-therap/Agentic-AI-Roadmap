# Roadmap-To-Learn-Agentic-AI:

# 1. Python Programming Language
#### Python:
![python-logo-master-v3-TM-flattened](https://user-images.githubusercontent.com/20041231/211717885-0b1e049b-f5b3-457d-ba7a-9345ec3aa39c.png)

1. Complete Python Playlist In English: [![YouTube](https://img.shields.io/badge/YouTube-Video-green)](https://www.youtube.com/watch?v=bPrmA1SEN2k&list=PLZoTAELRMXVNUL99R4bDlVYsncUNvwUBB)

2. Complete Python Playlist In Hindi:   [![YouTube](https://img.shields.io/badge/YouTube-Video-green)](https://www.youtube.com/watch?v=MJd9d9Mpxg0&list=PLTDARY42LDV4qqiJd1Z1tShm3mp9-rP4v)

# 2. Basic Machine Learning Natural Language Processing [![YouTube](https://img.shields.io/badge/YouTube-Video-green)](https://www.youtube.com/watch?v=ENLEjGozrio)
# Text Encoding Techniques for Machine Learning

## Introduction
Text encoding is a crucial step in natural language processing (NLP). Several encoding techniques are commonly used to convert text data into numerical form for machine learning models. This document outlines four key encoding techniques: One-Hot Encoding, Bag of Words, TF-IDF, and Word2Vec with examples.

## One-Hot Encoding (OHE)
One-hot encoding represents each word as a binary vector. Each position in the vector corresponds to a word in the vocabulary, and only one position is set to 1 while others are set to 0.

**Example:**  
Suppose the vocabulary consists of the words: `[cat, dog, mouse]`. The one-hot encodings would be:
- `cat → [1, 0, 0]`
- `dog → [0, 1, 0]`
- `mouse → [0, 0, 1]`

## Bag of Words (BoW)
The Bag of Words model represents text data by counting the frequency of words in a given document without considering their order.

**Example:**  
Consider two sentences:
- Sentence 1: `The cat sat on the mat`
- Sentence 2: `The dog barked at the cat`

**Vocabulary:** `[the, cat, sat, on, mat, dog, barked, at]`

- BoW Vector for Sentence 1 = `[2, 1, 1, 1, 1, 0, 0, 0]`  
- BoW Vector for Sentence 2 = `[2, 1, 0, 0, 0, 1, 1, 1]`

## Term Frequency-Inverse Document Frequency (TF-IDF)
TF-IDF is a statistical measure used to evaluate the importance of a word in a document relative to a collection of documents (corpus). It assigns higher values to words that are frequent in a document but rare in the overall corpus.

**TF Formula:**  
TF(t) = (Frequency of term t in document) / (Total terms in document)


**IDF Formula:**  
IDF(t) = log (N / (1 + Number of documents containing term t))


Where:
- **`N`** = Total number of documents
- **`|{ d ∈ D : t ∈ d }|`** = Number of documents containing term `t`

## Word2Vec
Word2Vec is a neural network-based technique that maps words into continuous vector spaces using either the Skip-gram or Continuous Bag of Words (CBOW) model. It captures semantic meaning by placing similar words closer in the vector space.

**Example:** For a given sentence:
> `The cat chased the mouse`

Word2Vec may encode the words as follows:
- `cat → [0.21, -0.12, 0.87, ...]`  
- `mouse → [0.19, -0.14, 0.85, ...]`

## Average Word2Vec (AvgWord2Vec)
This technique computes the average of all Word2Vec vectors for the words in a document. It is useful for representing entire sentences or documents as fixed-size vectors.

**Example:**  
Given sentence: `The cat chased the mouse`
AvgWord2Vec = (1/n) ∑ Word2Vec(w_i)

Where `n` is the number of words in the sentence.





# 3. Complete Deep Learning For NLP [![YouTube](https://img.shields.io/badge/YouTube-Video-green)](https://www.youtube.com/watch?v=w3coRFpyddQ&list=PLZoTAELRMXVNNrHSKv36Lr3_156yCo6Nn)
1. Deep Learning NLP: [![YouTube](https://img.shields.io/badge/YouTube-Video-green)](https://www.youtube.com/watch?v=w3coRFpyddQ&list=PLZoTAELRMXVNNrHSKv36Lr3_156yCo6Nn)
2. Indepth Transformer Explanation: [![YouTube](https://img.shields.io/badge/YouTube-Video-green)](https://www.youtube.com/watch?v=3bPhDUSAUYI)


# 4. Complete Generative AI Tutorials With End To End Projects
<img src="https://github.com/krishnaik06/Roadmap-To-Learn-Generative-AI-In-2024/assets/20041231/ebaa03ec-4370-4ea0-989d-5314370cd2da" alt="Alt Text" width="300" height="200">
<img src="https://github.com/user-attachments/assets/e3070185-ffd2-49f4-a159-825c7c2bda02" alt="Alt Text" width="300" height="200">
<img src="https://github.com/user-attachments/assets/dbbba97d-c4f2-4ffe-8b8d-4b992005f3fc" alt="Alt Text" width="300" height="200">
<img src="https://github.com/user-attachments/assets/9e721c21-bba1-4840-9d9c-4992ba7e376f" alt="Alt Text" width="300" height="200">





1. Generative AI Tutorials With Projects [![YouTube](https://img.shields.io/badge/documentation-link-green)](https://python.langchain.com/docs/get_started/introduction) [![YouTube](https://img.shields.io/badge/YouTube-Video-red)](https://www.youtube.com/watch?v=HEHUpBO8UVc&list=PLA1lVIthbM1D5I6r5uY2K89X1KD2w5LNh&index=2)
2. Agentic AI Playlist With Different Frameworks  [![YouTube](https://img.shields.io/badge/documentation-link-green)](https://python.langchain.com/docs/get_started/introduction) [![YouTube](https://img.shields.io/badge/YouTube-Video-red)](https://www.youtube.com/watch?v=Qs_j5wRbVr8&list=PLZoTAELRMXVMBr14UQ30AFlnlQ7eL5wjl&index=1)
3. MultiModal RAGs [![YouTube](https://img.shields.io/badge/documentation-link-green)](https://python.langchain.com/docs/get_started/introduction) [![YouTube](https://img.shields.io/badge/YouTube-Video-red)](https://www.youtube.com/playlist?list=PLQxDHpeGU14D6dm0rmAXhdLeLYlX2zk7p)

## 5. Best AGENTIC AI Frameworks to Learn

1. Langchain And LangGraph
<img src="https://github.com/user-attachments/assets/b6014d81-ecdd-44b9-94a5-ad78ad2629f0" alt="Alt Text" width="300" height="200">

**Langchain And LangGraph [![YouTube](https://img.shields.io/badge/documentation-link-green)](https://www.langchain.com/langgraph)**

2. Phidata

<img src="https://github.com/user-attachments/assets/18e3515d-5730-4de9-bb9f-3673fcc753e1" alt="Alt Text" width="400" height="100">

**Phidata [![YouTube](https://img.shields.io/badge/documentation-link-green)](https://www.phidata.com/)**

3. CrewAI
<img src="https://github.com/user-attachments/assets/c0430873-fcdd-45b4-a014-5820690ffab2" alt="Alt Text" width="200" height="100">

**CrewAI [![YouTube](https://img.shields.io/badge/documentation-link-green)](https://www.crewai.com/)**

4. Autogen
<img src="https://github.com/user-attachments/assets/4cd2c677-ace6-4b40-8877-ab8c7dbcbc6f" alt="Alt Text" width="200" height="100">

**Autogen [![YouTube](https://img.shields.io/badge/documentation-link-green)](https://microsoft.github.io/autogen/dev/index.html)**

## 6. Generative AI With Cloud AWS And GCP
1. Generative AI With AWS
<img src="https://github.com/user-attachments/assets/2372e74e-54b1-4809-ae3d-2b97f41feabc" alt="Alt Text" width="200" height="200">

**Generative AI With AWS [![YouTube](https://img.shields.io/badge/YouTube-Video-green)](https://www.youtube.com/watch?v=2WOa4_3Bgtw&list=PLZoTAELRMXVP5zpBfH7pab4aB1LbmCM1z)**

2. Generative AI With Azure Complete Tutorials
<img src="https://github.com/user-attachments/assets/119eeeba-b7f4-445c-866c-d5f54c71d4c0" alt="Alt Text" width="200" height="100">

**Generative AI With Azure [![YouTube](https://img.shields.io/badge/YouTube-Video-green)](https://www.youtube.com/watch?v=3SRh2nzN2DM&t)**

## Live Agentic AI And Generative AI With Cloud Bootcamp

<img src="https://github.com/user-attachments/assets/631e9c52-e385-4bab-a629-ab2167a199ee" alt="Alt Text" width="500" height="300">

1. **Admission Link: https://learn.krishnaikacademy.com/l/a981029ab3**
2. **Start Date January 25th, 2025**
3. **Timing:3 PM to 6 PM IST (Saturday and Sunday)**
4. **Duration: 4-5 months**
5. **Mentors: Sourangshu Paul, Mayank Aggarwal, Krish Naik, and Sunny Savitha**
6. **Reach out to Krish Naik's counselling team on 📞 +91-9111533440 in case of any queries we are there to help you out.**









