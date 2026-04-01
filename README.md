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
- **Data Acquisition**: Ensure Kaggle credentials (`kaggle.json`) are configured to download the `mlg-ulb/creditcardfraud` dataset.
- **Requirements**: Install libraries via `pip install pandas numpy scikit-learn matplotlib seaborn`.
- **Execution**: Run the notebook sequentially from *API Configuration* to *Model Evaluation*.

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

## ⚙️ Installation & Usage
- **Data Acquisition**: Pastikan kredensial Kaggle (`kaggle.json`) sudah dikonfigurasi untuk mengunduh dataset `mlg-ulb/creditcardfraud`.
- **Requirements**: Instalasi pustaka melalui `pip install pandas numpy scikit-learn matplotlib seaborn`.
- **Execution**: Jalankan notebook secara berurutan mulai dari sel *API Configuration* hingga *Model Evaluation*
