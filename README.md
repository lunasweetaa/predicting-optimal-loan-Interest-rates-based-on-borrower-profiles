# **Predicting Optimal Loan Interest Rates Based on Borrower Profiles**

## **Deskripsi Proyek**
Proyek ini bertujuan untuk membangun model prediktif yang dapat memprediksi tingkat bunga pinjaman optimal berdasarkan profil peminjam. Menggunakan data dari peminjam seperti skor kredit (FICO), rasio penggunaan kredit, dan jumlah cicilan bulanan, model ini akan memberikan estimasi bunga pinjaman yang sesuai dengan profil risiko dan kemampuan bayar peminjam.

## **Tujuan Proyek**
- **Memprediksi bunga pinjaman optimal** berdasarkan karakteristik peminjam.
- **Personalisasi penawaran bunga pinjaman**, sehingga lebih sesuai dengan profil risiko peminjam.
- **Meminimalkan risiko pemberian pinjaman** dengan memanfaatkan data historis peminjam untuk menentukan tingkat bunga yang lebih tepat.

## **Fitur Utama**
- Prediksi bunga pinjaman berdasarkan:
  - **Skor Kredit (FICO)**: Menunjukkan tingkat kelayakan kredit peminjam.
  - **Rasio Penggunaan Kredit (RevolUtil)**: Rasio penggunaan kredit peminjam terhadap total kredit yang tersedia.
  - **Jumlah Cicilan Bulanan (Installment)**: Besaran cicilan bulanan yang harus dibayar peminjam.
- Penyesuaian prediksi bunga pinjaman berdasarkan data input dari pengguna.

## **Teknologi yang Digunakan**
- **Python** untuk pengolahan data dan pembuatan model.
- **Pandas** untuk manipulasi data.
- **Scikit-learn** untuk pembuatan model prediksi.
- **Streamlit** untuk antarmuka pengguna (UI) berbasis web.
- **Matplotlib** dan **Seaborn** untuk visualisasi data.

## **Struktur Folder**
/my-streamlit-app |-- final_project_luna.py # File utama aplikasi |-- requirements.txt # Daftar dependencies |-- README.md # Dokumentasi aplikasi |-- /data # Folder untuk data 

## **Penggunaan**
Aplikasi ini memungkinkan pengguna untuk memasukkan data peminjam, seperti skor kredit (FICO), rasio penggunaan kredit (RevolUtil), dan cicilan bulanan (Installment). Berdasarkan input ini, aplikasi akan memprediksi tingkat bunga pinjaman yang optimal.

**Contoh Input:**
- **FICO:** 750
- **RevolUtil:** 0.2
- **Installment:** 300

**Output:**
- **Prediksi bunga pinjaman:** 5.4%

## **Kontak**
Untuk pertanyaan lebih lanjut, hubungi saya di:
- Email: [ifs20042.luna@gmail.com]
- LinkedIn: [Luna Sweeta Anastasya Pangaribuan](https://www.linkedin.com/in/luna-sweeta-anastasya-pangaribuan)