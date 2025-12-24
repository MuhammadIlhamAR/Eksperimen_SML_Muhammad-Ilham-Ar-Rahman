# Eksperimen SML_Rain Prediction in Aotizhongxin

Repository ini berisi tahap awal pengembangan model klasifikasi untuk memprediksi apakah akan terjadi hujan (Yes/No) berdasarkan data meteorologi

## Struktur Repository
- `PRSA_Data_Aotizhongxin_raw/`: Berisi dataset mentah (file .csv).
- `Preprocessing/`: Berisi notebook eksperimen dan script otomasi.
  - `Eksperimen_Muhammad-Ilham.ipynb`: Notebook untuk analisis data (EDA).
  - `automate_Muhammad-Ilham.py`: Script Python untuk menjalankan preprocessing secara otomatis.

- ## Deskripsi Project
Project ini bertujuan untuk membangun model prediksi hujan. 
Dataset: (https://www.kaggle.com/datasets/kurniatilaelimunifah/prsa-data-aotizhongxin)

## Persiapan
Pastikan Python sudah terinstal di sistem Anda, kemudian instal library yang diperlukan secara manual:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
