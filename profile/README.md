# 📊 SmartLead Banking System

### Predictive Lead Scoring & Sales Prioritization for Term Deposit Campaign

---

## 🏦 Deskripsi Sistem

**SmartLead Banking System** adalah sistem pendukung keputusan berbasis _Machine Learning_ yang dirancang untuk meningkatkan efektivitas kampanye pemasaran **deposito berjangka (term deposit)** di sektor perbankan.

Sistem ini memanfaatkan data historis nasabah untuk memprediksi **probabilitas ketertarikan nasabah** terhadap produk deposito berjangka. Hasil prediksi tersebut digunakan untuk:

- memprioritaskan daftar nasabah yang akan dihubungi (call list),
- membantu tim sales fokus pada prospek dengan potensi konversi tertinggi,
- mengurangi inefisiensi waktu dan biaya operasional akibat penargetan yang tidak tepat.

Sistem dikembangkan sebagai **Minimum Viable Product (MVP)** yang mengintegrasikan model Machine Learning dengan antarmuka web interaktif sebagai alat bantu pengambilan keputusan bagi tim sales.

---

## ⚙️ Fitur Utama

- 📈 Prediksi probabilitas nasabah berlangganan deposito berjangka
- 🧮 Model Machine Learning (LightGBM)
- 📋 Prioritized call list berbasis skor probabilitas
- 👤 Informasi kunci nasabah (usia, pekerjaan, status pinjaman, dll.)
- 🖥️ Dashboard/portal interaktif untuk tim sales
- 🎯 Optimasi threshold precision–recall untuk data imbalance

---

## 🧠 Dataset

- **Bank Marketing Dataset (UCI Machine Learning Repository)**
- Sumber: Kampanye pemasaran bank di Eropa
- Target: _Subscription of term deposit (yes/no)_

---

## 👥 Contributors

| Nama                           | Peran                                      | ID Cohort   |
| ------------------------------ | ------------------------------------------ | ----------- |
| Komang Krisna Jaya Nova Antara | Machine Learning Engineer / Data Scientist | COHORT-XXXX |
| _(Nama anggota lain)_          | Backend Developer                          | COHORT-XXXX |
| _(Nama anggota lain)_          | Frontend Developer / UI Designer           | COHORT-XXXX |

> _Catatan: Silakan sesuaikan nama, peran, dan ID cohort sesuai tim._

---

## 🖼️ Screenshot / Mockup Sistem

### 🔹 Halaman Dashboard

![Dashboard](docs/screenshots/dashboard.png)

### 🔹 Halaman Prediksi & Prioritas Nasabah

![Prediction Page](docs/screenshots/prediction.png)

### 🔹 Detail Informasi Nasabah

![Customer Detail](docs/screenshots/customer_detail.png)

> _Screenshot dapat berupa mockup desain atau tampilan sistem hasil implementasi._

---

## 🚀 Teknologi yang Digunakan

- **Python**
- **Scikit-learn**
- **LightGBM**
- **Pandas & NumPy**
- **Matplotlib / Seaborn**
- **Web Framework** (Flask / FastAPI / lainnya)
- **HTML / CSS / JavaScript**

---

## 🎯 Tujuan Pengembangan

- Mengatasi inefisiensi penargetan nasabah dalam kampanye outbound call
- Mendukung pengambilan keputusan tim sales berbasis data
- Meningkatkan tingkat konversi dan efisiensi operasional pemasaran perbankan

---

## 📌 Catatan

Proyek ini dikembangkan sebagai bagian dari **proyek akademik / capstone / studi independen**, dan merepresentasikan implementasi **MVP sistem predictive lead scoring** yang telah banyak diterapkan secara nyata di industri perbankan modern.
