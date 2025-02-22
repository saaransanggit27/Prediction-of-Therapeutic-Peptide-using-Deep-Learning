# Prediction of Therapeutic Peptides using Deep Learning & DAA

## 📌 Project Overview
This project focuses on the **prediction of therapeutic peptides** using **deep learning** while optimizing runtime with **Design and Analysis of Algorithms (DAA)**. It integrates **computational biology** with **efficient algorithmic techniques** to develop a novel methodology for therapeutic peptide prediction.

The system allows users to **input peptide sequences** and **select disease targets**, generating **3D structures** and **predicting therapeutic properties** using a **hybrid deep learning model (CNN-LSTM)**.

## 🏗️ Project Workflow (WCBD)
- **W**: **Workflow Setup** – Collect therapeutic and disease peptide datasets.
- **C**: **Computational Analysis** – Extract physicochemical features, embeddings (ProtBERT), and apply data augmentation.
- **B**: **Bioinformatics Validation** – Compare peptide-target interactions using molecular docking and simulations.
- **D**: **Deep Learning & DAA Optimization** – Train the CNN-LSTM model with optimized runtime techniques.

## 🏆 Key Features
✅ **Dual-Input Model (CNN-LSTM)** – Processes therapeutic peptides and target proteins separately, merges embeddings for interaction prediction.  
✅ **Hybrid Embedding Approach** – Uses **ProtBERT embeddings + physicochemical features** for protein representation.  
✅ **Efficient DAA Techniques** – Reduces computational runtime while maintaining bioinformatics accuracy.  
✅ **3D Structure Generation** – Integrates **AlphaFold & I-TASSER** for peptide modeling.  
✅ **Simulation & Validation** – Includes **molecular docking & dynamics simulations** for real-world accuracy.  

## 🗃️ Dataset
- **Therapeutic Peptides**: Human-derived antimicrobial and antiviral peptide sequences.
- **Disease Peptides**: FASTA sequences of disease-related target proteins (e.g., Cancer, Viral, Microbial, Inflammatory, etc.).

## 📊 Model Training
- Uses CNN-LSTM architecture.
- Input: Therapeutic peptide sequence + target protein sequence.
- Output: Predicted therapeutic interaction score.
- Optimized using DAA techniques for faster runtime.
  
## 🚀 Future Enhancements
- Integrate reinforcement learning for adaptive sequence optimization.
- Improve 3D structure validation using advanced simulations.
- Expand dataset to include more disease target proteins.

