# Credit Card Fraud Detection System
A credit card fraud detection system utilizing Machine Learning algorithms optimized for handling highly imbalanced datasets. This project focuses on detection precision to minimize financial loss while maintaining seamless user experience.

*This project was developed as part of a Data Science portfolio to implement advanced preprocessing techniques and evaluate classification models on real-time transaction data.*

## 📝 Project Description
This project performs an in-depth analysis of credit card transaction datasets to identify suspicious patterns. The primary challenge is the data distribution where fraud transactions account for <0.2% of total data, necessitating specific handling techniques to prevent model bias toward normal transactions.

## ✨ Key Features
- **Data Preprocessing & Scaling**: Implementation of RobustScaler to manage outliers in high-variance transaction features.
- **Handling Imbalanced Data**: Utilization of Random Under-Sampling techniques to balance target classes and enhance model sensitivity to fraud.
- **Exploratory Data Analysis (EDA)**: Visualization of V1-V28 feature distributions and correlations to understand anomalous transaction characteristics.
- **Predictive Modeling**: Implementation of Logistic Regression as an efficient baseline model for binary classification on large-scale data.
- **Advanced Evaluation Metrics**: Employment of Precision-Recall Curves, Confusion Matrices, and ROC-AUC to measure performance beyond standard accuracy.

## 🛠️ Tech Stack & Implementation
- **Programming Language**: Python 3.x
- **Data Manipulation**: Pandas & NumPy for efficient array and data frame processing.
- **Machine Learning**: Scikit-Learn for classification models and evaluation metrics.
- **Data Visualization**: Matplotlib & Seaborn for statistical plotting and correlation analysis.
- **Environment**: Google Colab with Kaggle API integration for automated data retrieval.

## 📈 Methodology
- **Sampling Strategy**: Reducing non-fraud transactions to match fraud counts to prevent overfitting on the majority class.
- **Dimensionality Understanding**: Analysis of PCA-transformed features (V1-V28) to identify the most significant indicators of fraudulent behavior.
- **Model Validation**: Dataset partitioning into Training and Testing sets with strict class distribution control.

## ⚙️ Installation & Usage

### 1. Prerequisites (Kaggle API)

This project uses the Kaggle API to download the dataset.

- Obtain your `kaggle.json` from your Kaggle account settings.
- In Google Colab, add your credentials to the **Secrets** tab (KAGLLE\_USERNAME and KAGGLE\_KEY).
- If running locally, place `kaggle.json` in your `~/.kaggle/` folder.

### 2. Setup Environment

```bash
# Clone the repository
git clone https://github.com/Billy1205/fraud-detection-system.git
cd fraud-detection-system

# Install dependencies
pip install -r requirements.txt
```

### 3. Data Acquisition

The notebook is configured to automatically download and extract the dataset:
  - **Dataset**: [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
  - **License**: DbCL-1.0

### 4. Running the Notebook

Execute the cells in `notebooks/fraud-detection-system.ipynb` sequentially.


***

# Credit Card Fraud Detection System
Sistem deteksi penipuan transaksi kartu kredit menggunakan algoritma Machine Learning yang dioptimalkan untuk menangani dataset yang sangat tidak seimbang (*highly imbalanced dataset*). Proyek ini berfokus pada presisi deteksi guna meminimalkan kerugian finansial sekaligus menjaga pengalaman pengguna.

*Proyek ini dikembangkan sebagai bagian dari portofolio Data Science untuk mengimplementasikan teknik preprocessing tingkat lanjut dan evaluasi model klasifikasi pada data transaksi real-time.*

## 📝 Project Description
Proyek ini melakukan analisis mendalam terhadap dataset transaksi kartu kredit untuk mengidentifikasi pola transaksi mencurigakan. Tantangan utama dalam proyek ini adalah distribusi data di mana transaksi penipuan (fraud) hanya mencakup <0.2% dari total data, sehingga memerlukan teknik penanganan khusus agar model tidak bias terhadap transaksi normal.

## ✨ Key Features
- **Data Preprocessing & Scaling**: Implementasi RobustScaler untuk menangani outlier pada fitur transaksi yang memiliki varians tinggi.
- **Handling Imbalanced Data**: Penggunaan teknik Random Under-Sampling untuk menyeimbangkan kelas target guna meningkatkan sensitivitas model terhadap transaksi fraud.
- **Exploratory Data Analysis (EDA)**: Visualisasi distribusi fitur V1-V28 dan korelasi antar variabel untuk memahami karakteristik transaksi anomali.
- **Predictive Modeling**: Implementasi Logistic Regression sebagai baseline model yang efisien untuk klasifikasi biner pada data skala besar.
- **Advanced Evaluation Metrics**: Menggunakan Precision-Recall Curve, Confusion Matrix, dan ROC-AUC untuk mengukur performa model melampaui metrik akurasi standar.

## 🛠️ Tech Stack & Implementation
- **Programming Language**: Python 3.x
- **Data Manipulation**: Pandas & NumPy untuk efisiensi pemrosesan array dan data frame.
- **Machine Learning**: Scikit-Learn untuk implementasi model klasifikasi dan metrik evaluasi.
- **Data Visualization**: Matplotlib & Seaborn untuk pembuatan grafik statistik dan analisis korelasi.
- **Environment**: Google Colab dengan integrasi Kaggle API untuk pengambilan data secara otomatis.

## 📈 Methodology
- **Sampling Strategy**: Mengurangi jumlah transaksi non-fraud agar sejajar dengan jumlah transaksi fraud guna menghindari overfitting pada kelas mayoritas.
- **Dimensionality Understanding**: Analisis fitur hasil transformasi PCA (V1-V28) untuk mengidentifikasi indikator paling berpengaruh terhadap perilaku fraud.
- **Model Validation**: Pembagian dataset menjadi Training dan Testing set dengan kontrol distribusi kelas yang ketat.
Berikut adalah terjemahan Bahasa Indonesia yang telah disesuaikan agar tetap terlihat teknis namun mudah dipahami oleh pengguna lokal. Saya juga memperbaiki instruksi `cd` agar sesuai dengan nama repositori Anda.

## ⚙️ Instalasi & Penggunaan

### 1. Prasyarat (Kaggle API)

Proyek ini menggunakan Kaggle API untuk mengunduh dataset secara otomatis.

- Dapatkan file `kaggle.json` dari pengaturan akun Kaggle Anda.
- **Di Google Colab**: Tambahkan kredensial Anda ke tab **Secrets** (ikon kunci di sidebar kiri) dengan nama `KAGGLE_USERNAME` dan `KAGGLE_KEY`.
- **Di Lokal (PC/Laptop)**: Simpan file `kaggle.json` di dalam folder `~/.kaggle/`.

### 2. Persiapan Lingkungan (Setup)

```bash
# Klon repositori ini
git clone https://github.com/Billy1205/fraud-detection-system.git
cd fraud-detection-system

# Instal pustaka/dependensi yang diperlukan
pip install -r requirements.txt
```

### 3. Akuisisi Data

Notebook ini telah dikonfigurasi untuk mengunduh dan mengekstrak dataset secara otomatis:
- **Dataset**: [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Lisensi**: DbCL-1.0

### 4. Menjalankan Notebook

Jalankan sel kode di dalam `notebooks/fraud-detection-system.ipynb` secara berurutan dari atas ke bawah.
