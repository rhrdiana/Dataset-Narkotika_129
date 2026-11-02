# A Legal Document Dataset of Narcotics and Psychotropic Criminal Court Decisions

Repositori ini merupakan kumpulan dataset dokumen hukum yang dikembangkan untuk memenuhi penugasan mata kuliah **Information Retrieval (IR)**. Dataset berisi dokumen putusan pengadilan tingkat pertama terkait tindak pidana narkotika dan psikotropika yang bersumber dari Pengadilan Negeri Pangkalpinang.
---

## 1. Dataset Overview

Dataset ini berfokus pada dokumen putusan perkara pidana khusus narkotika dan psikotropika yang diputus oleh Pengadilan Negeri Pangkalpinang pada tahun 2025.

Informasi yang disediakan mencakup dokumen putusan resmi dalam format PDF serta metadata terstruktur yang merepresentasikan informasi penting dari setiap putusan.

### Dataset Summary

| Attribute | Description |
|---|---|
| Dataset Name | Dataset-Narkotika_129 |
| Domain | Criminal Law |
| Case Category | Narcotics and Psychotropics |
| Court Level | First-Instance Court |
| Court Institution | Pengadilan Negeri Pangkalpinang |
| Publication Year | 2025 |
| Number of Documents | 5 Court Decisions |
| Document Format | PDF |
| Metadata Format | XLSX |
| Language | Indonesian |

## 2. Data Source

Seluruh dokumen diperoleh dari sumber resmi Direktori Putusan Mahkamah Agung Republik Indonesia.

**Official Source:**
- [Direktori Putusan Mahkamah Agung Republik Indonesia](https://putusan3.mahkamahagung.go.id/direktori.html)

Pengumpulan data dilakukan dengan mempertimbangkan kategori perkara, tingkat peradilan, dan wilayah hukum yang menjadi cakupan penelitian.

## 3. Repository Structure

Struktur direktori repositori disusun untuk memisahkan dokumen putusan dan metadata dataset agar memudahkan proses pengelolaan serta pemanfaatan data.

```text
Dataset-Narkotika_129/
│
├── Dataset/
│   └── Narkotika.zip
├── Overview/
│   └── Overview.xlsx
└── README.md
```

### Directory Description

| Directory / File | Description |
|---|---|
| `Dataset/` | Direktori penyimpanan dokumen putusan pengadilan. |
| `Narkotika.zip` | Arsip berisi 5 dokumen putusan resmi dalam format PDF. |
| `Overview/` | Direktori penyimpanan metadata dataset. |
| `Overview.xlsx` | Spreadsheet yang memuat ringkasan informasi dari setiap dokumen putusan. |
| `README.md` | Dokumentasi dan deskripsi repositori. |

## 4. Metadata Description

File `Overview.xlsx` menyediakan informasi terstruktur yang diekstraksi dari dokumen putusan. Metadata tersebut terdiri atas beberapa atribut utama berikut:

| Attribute | Description |
|---|---|
| Nomor Putusan | Nomor identifikasi resmi dokumen putusan pengadilan. |
| Lembaga Peradilan | Nama pengadilan yang mengeluarkan putusan. |
| Barang Bukti | Deskripsi barang bukti yang tercantum dalam dokumen putusan. |
| Amar Putusan | Ringkasan keputusan atau ketetapan hakim terhadap perkara. |

Metadata disusun dalam format spreadsheet untuk mempermudah identifikasi, pengelompokan, dan pemrosesan informasi dari dokumen hukum.

## 5. Data Processing Specifications

Untuk menjaga konsistensi dan standardisasi metadata, diterapkan beberapa ketentuan dalam penyusunan data:

- **Text Standardization:** Informasi deskriptif pada kolom Barang Bukti dan Amar Putusan disajikan dalam format teks yang konsisten.
- **Delimiter Convention:** Beberapa entri dalam satu atribut dipisahkan menggunakan tanda titik koma (`;`).
- **List Formatting:** Entri tidak menggunakan penomoran atau bullet list di dalam sel spreadsheet.
- **Metadata Consistency:** Setiap metadata disesuaikan dengan informasi yang tercantum dalam dokumen putusan sumber.

Standarisasi tersebut ditujukan untuk mempermudah proses parsing, ekstraksi informasi, dan pemrosesan teks pada sistem Information Retrieval.

## 6. Dataset Utilization

Dataset ini dapat dimanfaatkan sebagai data pendukung untuk berbagai kebutuhan penelitian dan pengembangan sistem, antara lain:

- **Information Retrieval:** Pengembangan dan pengujian sistem pencarian dokumen hukum.
- **Text Mining:** Analisis dan eksplorasi informasi dari dokumen putusan pengadilan.
- **Information Extraction:** Ekstraksi informasi penting seperti nomor putusan, barang bukti, dan amar putusan.
- **Legal Document Analysis:** Analisis konten dan karakteristik dokumen hukum.

## 7. Developers

**Herdiana Dwi Maharani**

Developed for the Information Retrieval (IR) Course.

---

*This repository is intended for academic and research purposes.*
