# Final-Project-Kelompok-2
Final project DS rakamin bacth 30
# Travel Insurance Prediction Data
## Deskripsi

Dataset ini berisi data tentang responden yang memiliki dan tidak memiliki travel insurance berdasarkan beberapa variabel seperti jenis kelamin, umur, jenis pekerjaan, dan lain-lain. Dataset ini dapat digunakan untuk mengembangkan model prediksi yang dapat membantu perusahaan asuransi dalam mengidentifikasi pelanggan yang berpotensi membeli travel insurance.

## Sumber Data

Dataset ini berasal dari https://www.kaggle.com/tejashvi14/travel-insurance-prediction-data
Isi Dataset
Dataset ini terdiri dari 11 kolom dan 1987 baris, yaitu:

    'Age': Umur responden
    'Employment Type': Jenis pekerjaan responden
    'GraduateOrNot': Status pendidikan responden
    'AnnualIncome': Pendapatan tahunan responden dalam USD
    'FamilyMembers': Jumlah anggota keluarga responden yang berpergian bersama
    'ChronicDisease': Status penyakit kronis responden
    'FrequentFlyer': Status frequent flyer responden
    'EverTravelledAbroad': Status pernah atau tidak pernah pergi ke luar negeri
    'TravelInsurance': Status memiliki atau tidak memiliki travel insurance (target variable)
    'FamilyInsurance': Status memiliki atau tidak memiliki travel insurance untuk anggota keluarga
    'MedicalInsurance': Status memiliki atau tidak memiliki asuransi kesehatan

## Contoh Penggunaan

Dataset ini dapat digunakan untuk mengembangkan model prediksi yang dapat memprediksi kemungkinan seseorang memiliki atau tidak memiliki travel insurance. Selain itu, dataset ini juga dapat digunakan untuk melakukan analisis statistik atau eksplorasi data untuk mendapatkan insight bisnis yang berguna bagi perusahaan asuransi.

## EDA (Exploratory Data Analysis)
 1. Informasi Dataset:
    - Terdapat beberapa variabel numerik, yaitu 'Age', 'AnnualIncome', dan 'FamilyMembers'.
    - Terdapat beberapa variabel kategorik, yaitu 'Employment Type', 'GraduateOrNot', 'ChronicDisease', 'FrequentFlyer', dan 'EverTravelledAbroad'.
    - Terdapat tiga variabel target, yaitu 'TravelInsurance', 'FamilyInsurance', dan 'MedicalInsurance'.
 2. Statistik Deskriptif Dataset:
    - Rata-rata umur responden adalah sekitar 29 tahun dengan rentang usia antara 18 hingga 84 tahun.
    - Rata-rata pendapatan tahunan responden adalah sekitar 93000 USD.
    - Jumlah anggota keluarga yang berpergian bersama memiliki rentang antara 0 hingga 9 anggota.
    - Sekitar 26% responden memiliki status penyakit kronis.
    - Sekitar 23% responden merupakan frequent flyer.
    - Sekitar 75% responden pernah bepergian ke luar negeri.
    - Sekitar 39% responden memiliki travel insurance, 14% responden memiliki family insurance, dan 7% responden memiliki medical insurance.
 3. Hubungan Antara Variabel:
    - Terdapat korelasi positif antara variabel 'EverTravelledAbroad' dan 'TravelInsurance', yang menunjukkan bahwa responden yang pernah bepergian ke luar negeri cenderung memiliki travel insurance.
    - Terdapat korelasi positif antara variabel 'Employment Type' dan 'TravelInsurance', yang menunjukkan bahwa responden dengan jenis pekerjaan tertentu memiliki kecenderungan untuk memiliki travel insurance.
    - Terdapat korelasi negatif antara variabel 'Age' dan 'TravelInsurance', yang menunjukkan bahwa semakin tua usia responden, semakin rendah kemungkinannya untuk memiliki travel insurance.
 4. Distribusi Variabel:
    - Variabel 'Age' memiliki distribusi yang mirip dengan distribusi normal, dengan beberapa outlier pada rentang usia yang lebih tinggi.
    - Variabel 'AnnualIncome' memiliki distribusi yang cenderung tidak normal, dengan beberapa nilai yang jauh lebih tinggi dari nilai lainnya.
    - Variabel 'FamilyMembers' memiliki distribusi yang cenderung meruncing ke kanan, dengan sebagian besar responden memiliki 0 hingga 3 anggota keluarga yang berpergian bersama.
    - Variabel 'ChronicDisease' dan 'FrequentFlyer' memiliki distribusi yang sangat tidak seimbang, dengan mayoritas responden memiliki status negatif.
    - Variabel 'EverTravelledAbroad' dan variabel target 'TravelInsurance', 'FamilyInsurance', dan 'MedicalInsurance' memiliki distribusi yang tidak seimbang, dengan mayoritas responden memiliki status negatif.
