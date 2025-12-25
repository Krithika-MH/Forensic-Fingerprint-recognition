# Decentralized AI-Driven Forensic Fingerprint Recognition System

A secure, scalable, and high-accuracy forensic fingerprint recognition system that integrates **Artificial Intelligence** with **Blockchain technology** to ensure data integrity, privacy, and tamper resistance.  
This project combines a **Siamese Neural Network (SNN)** for robust fingerprint matching with **IPFS** and **Ethereum smart contracts** for decentralized storage and access control.

---

## 📌 Abstract

Traditional centralized fingerprint recognition systems suffer from security vulnerabilities, single points of failure, and reduced robustness under altered fingerprint conditions.  
This project proposes a **decentralized forensic fingerprint recognition framework** that leverages:

- **Siamese Neural Networks (SNN)** for accurate fingerprint similarity learning  
- **SIFT-based feature extraction** for optimized representation  
- **IPFS** for decentralized, immutable storage  
- **Ethereum smart contracts** for secure and transparent access control  

Evaluated on the **SOCOFing dataset** (unaltered and altered fingerprints), the system achieved an accuracy of **99.3%**, demonstrating strong robustness even under severe distortions.

---

## 🚀 Key Features

- 🔐 **Decentralized Storage** using IPFS (no single point of failure)
- ⛓️ **Blockchain-based Access Control** via Ethereum smart contracts
- 🧠 **AI-powered Fingerprint Matching** using Siamese Neural Networks
- 🧬 **Robust to Alterations** (easy, medium, hard distortions)
- 📊 **High Accuracy & Reliability** for forensic applications
- 📁 **Efficient Feature Storage** using SIFT-encoded `.npy` files

---

## 🏗️ System Architecture

**Workflow Overview:**

1. Fingerprint image acquisition  
2. Preprocessing and augmentation  
3. Feature extraction using **SIFT**  
4. Feature matching using **Siamese Neural Network**  
5. Storage of fingerprint data and results in **IPFS**  
6. Storage of content identifiers (CIDs) and metadata on **Ethereum blockchain**

This hybrid architecture ensures **security, transparency, and scalability** without compromising recognition performance.

---

## 🧠 AI Model Details

### Siamese Neural Network (SNN)

- Uses **shared-weight CNN branches**
- Learns a discriminative embedding space
- Measures similarity using:
  - Euclidean Distance
  - Cosine Similarity
- Trained with **Contrastive Loss**

**Objective:**
- Minimize distance for matching fingerprints
- Maximize distance for non-matching fingerprints

---

## 📊 Dataset

**SOCOFing Dataset**
- Total images: **55,270**
- Unaltered fingerprints: **6,000**
- Altered fingerprints: **49,270**
  - Easy
  - Medium
  - Hard

**Augmentation Techniques:**
- Rotation
- Scaling
- Flipping
- Noise injection
- Elastic distortions

---

## 📈 Performance Metrics

| Dataset Type       | Accuracy |
|--------------------|----------|
| Real (Unaltered)   | 99.3%    |
| Altered – Easy     | ~98%     |
| Altered – Medium   | ~97%     |
| Altered – Hard     | 96.2%    |

- High precision, recall, and F1-score across all datasets
- No observable performance degradation after blockchain integration

---

## 🔗 Blockchain Integration

- **IPFS**: Stores fingerprint images, feature vectors, and matching results
- **Ethereum Smart Contracts**:
  - Role-based access control
  - Immutable audit trail
  - Transparent verification

Only essential references (CIDs) are stored on-chain, ensuring **privacy compliance and scalability**.

---

## 🛠️ Technologies Used

- **Python**
- **TensorFlow / Keras**
- **Siamese Neural Networks**
- **SIFT Feature Extraction**
- **IPFS**
- **Ethereum Smart Contracts**
- **Solidity**
- **NumPy**
- **OpenCV**

---

## 📄 Research Publication

**Title:**  
*Decentralized AI-Driven Forensic Fingerprint Recognition System*

**Authors:**  
- M. Krithika  
- Kannika Mahesh D  
- Thanush J  

---

## 🔮 Future Enhancements

- Improve scalability for large-scale forensic databases
- Optimize blockchain transaction latency
- Integrate advanced cryptographic protections
- Explore alternatives to IPFS and Ethereum
- Real-time deployment for law enforcement systems

---

## 📬 Contact

**M. Krithika**  
Department of CSE (Data Science)  
Bangalore Institute of Technology  
📧 krithikamh13@gmail.com  

---

## 📜 License

This project is intended for **academic and research purposes**.  
For commercial or extended usage, please contact the authors.
