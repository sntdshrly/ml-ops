# Machine Learning Operations
This repository is created for learning machine learning operations.

## Tahap Persiapan
1. Buka Anaconda Prompt
2. Pilih folder yang akan digunakan
   ```
   cd C:\Users\SHERLY SANTIADI\Documents\GitHub\ml-ops
   ```
4. Clone repository
   ```
   git clone https://github.com/dicodingacademy/a443-MLOps-ML-Pipeline.git
   ```
5. Buat virtual environment untuk menghindari kesalahan dependency library dengan nama `mlops-tfx`
   ```
   conda create --name mlops-tfx python==3.9.15
   ```
6. Aktivasi virtual environment
   ```
   conda activate mlops-tfx
   ```
8. Install library
   ```
   pip install jupyter scikit-learn tensorflow tfx==1.11.0 flask joblib
   ```
9. Upgrade pip (jika terjadi error)
   ```
   python -m pip install --upgrade pip
   ```
