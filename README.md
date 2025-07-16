#Gene-SNP-Net-Model/
│
├── data/
│   ├── FGN.txt
│   ├── toyfgn.txt
│   ├── positiveNew.txt
│   ├── negNew.txt
│
├── src/
│   ├── model.py                # كود بناء نموذج GCN + SNP
│   ├── train_model.py          # ملف تدريب النموذج (main function)
│   ├── evaluate.py             # تقييم النموذج (AUROC، AUPRC)
│
├── notebooks/
│   └── GeneSNP-Net-Example.ipynb  # مثال عملي Jupyter notebook
│
├── results/
│   └── top_genes.csv           # ناتج التصنيف لأفضل الجينات
│
├── RunCodeSteps.txt            
├── requirements.txt            
├── README.md                   

##requirements
torch==2.1.0
torch-geometric==2.3.1
numpy
pandas
scikit-learn
matplotlib

##README
# 🧠 Gene-SNP-Net-Model

This project provides the implementation of the **Gene-SNP-Net-Model**, a dual-pathway deep learning approach combining SNP data and functional gene networks (FGN) using Graph Convolutional Networks (GCNs) for predicting Alzheimer’s disease-associated genes.

## 📁 Project Structure

- `data/`: SNP and gene network input files
- `src/`: Main training and model files (Python)
- `notebooks/`: Jupyter examples
- `results/`: Output (e.g., ranked genes)
- `RunCodeSteps.txt`: Manual run instructions

## 📦 Setup

```bash
git clone https://github.com/your-username/Gene-SNP-Net-Model.git
cd Gene-SNP-Net-Model
pip install -r requirements.txt


