# Prediksi Harga Mobil Bekas di Saudi Arabia

## **Project Overview**

Proyek ini bertujuan untuk mengembangkan **model Machine Learning** yang dapat memprediksi harga pasar wajar untuk mobil bekas di Arab Saudi. Tujuannya adalah membantu penjual, pembeli, dan platform marketplace otomotif dalam menentukan harga yang tepat berdasarkan data historis dan karakteristik mobil.

Model ini menganalisis fitur-fitur penting seperti **Umur Mobil (Car Age), Ukuran Mesin (Engine Size), Merek Mobil (Make), Tipe Mobil (Type), Jarak Tempuh (Mileage), Opsi (Options), Tipe Gear (Gear Type), Wilayah (Region),** dan **Asal Mobil (Origin)** untuk memprediksi harga yang diharapkan. Dengan pipeline preprocessing otomatis dan algoritma regresi, sistem ini memberikan prediksi harga yang akurat dan mencerminkan tren pasar.

### **Fitur Utama**

* **Pipeline Preprocessing:** Menangani fitur kategori menggunakan OneHot dan Binary encoding, serta menormalisasi fitur numerik dengan RobustScaler.
* **Benchmark Model:** Mengevaluasi beberapa model regresi (Ridge, Random Forest, XGBoost, LightGBM, CatBoost) menggunakan metrik RMSE.
* **Hyperparameter Tuning:** Mengoptimalkan model terbaik (CatBoost) dengan RandomizedSearchCV untuk performa lebih baik.
* **Evaluasi Model:** Menampilkan RMSE, MAE, dan R² pada data test.
* **Analisis Feature Importance:** Menunjukkan faktor-faktor yang paling berpengaruh terhadap harga, dengan **Umur Mobil, Ukuran Mesin, dan Merek** sebagai kontributor utama.
* **Visualisasi:** Scatter plot prediksi vs aktual dan bar plot pentingnya fitur untuk interpretasi hasil model.

### **Manfaat / Use Case**

* **Penjual:** Memberikan rekomendasi harga jual yang kompetitif.
* **Pembeli:** Menilai harga pasar wajar.
* **Marketplace:** Meningkatkan transparansi harga dan kepercayaan pengguna.

### **Teknologi yang Digunakan**

* Python (pandas, numpy, seaborn, matplotlib)
* Scikit-learn, Category Encoders, XGBoost, LightGBM, CatBoost


Proyek ini menunjukkan bagaimana **pricing berbasis data** dapat meningkatkan efisiensi dan transparansi di pasar mobil bekas, sekaligus menjadi dasar untuk pengembangan fitur lebih lanjut seperti ensemble model, integrasi marketplace, dan rekomendasi harga otomatis.

