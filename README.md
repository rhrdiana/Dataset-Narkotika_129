# Indonesian Narcotics and Psychotropic Criminal Court Decisions Dataset

Repositori ini dikembangkan untuk memenuhi penugasan mata kuliah **Information Retrieval (IR)**. Repositori ini berisi kumpulan dokumen putusan pengadilan tingkat pertama terkait tindak pidana khusus dengan klasifikasi narkotika dan psikotropika yang bersumber dari Direktori Putusan Mahkamah Agung Republik Indonesia.


---

## 1. Dataset Overview

Dataset ini mencakup **5 dokumen putusan pengadilan** dengan ruang lingkup perkara pidana khusus narkotika dan psikotropika.

Pengumpulan dokumen dilakukan berdasarkan kriteria klasifikasi perkara, lembaga peradilan, rentang tahun putusan, dan status hukum dokumen sesuai dengan ketentuan penugasan.

### Dataset Summary

| Attribute | Description |
|---|---|
| Dataset Name | Dataset-Narkotika_129 |
| Domain | Criminal Law |
| Case Classification | Narkotika dan Psikotropika |
| Case Category | Pidana Khusus |
| Court Level | First-Instance Court |
| Court Institution | Pengadilan Negeri Pangkalpinang |
| Publication Period | 2023–2025 |
| Number of Documents | 5 Court Decisions |
| Document Format | PDF |
| Metadata Format | XLSX |
| Language | Indonesian |

## 2. Data Source

Seluruh dokumen putusan diperoleh dari sumber resmi:

- [Direktori Putusan Mahkamah Agung Republik Indonesia](https://putusan3.mahkamahagung.go.id/direktori.html)

Pengumpulan data dilakukan melalui direktori putusan dengan memilih kategori **Pidana Khusus** dan klasifikasi **Narkotika dan Psikotropika**.

### Document Selection Criteria

Kriteria pemilihan dokumen dalam dataset meliputi:

1. **Case Category:** Dokumen termasuk dalam kategori perkara Pidana Khusus.
2. **Case Classification:** Dokumen memiliki klasifikasi Narkotika dan Psikotropika.
3. **Court Institution:** Seluruh dokumen berasal dari satu lembaga peradilan, yaitu Pengadilan Negeri Pangkalpinang.
4. **Decision Year:** Tahun putusan berada dalam rentang 2023–2025.
5. **Legal Status:** Tidak menggunakan dokumen putusan dengan status Berkekuatan Hukum Tetap (BHT).
6. **Document Quantity:** Dataset terdiri atas 5 dokumen putusan pengadilan.

## 3. Repository Structure

```text
Dataset-Narkotika_129/
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
| `Narkotika.zip` | Arsip terkompresi yang berisi 5 dokumen putusan resmi dalam format PDF. |
| `Overview/` | Direktori penyimpanan metadata dataset. |
| `Overview.xlsx` |  Berisi ringkasan informasi dari setiap dokumen putusan. |
| `README.md` | Dokumentasi dan deskripsi repositori. |

## 4. Metadata Description

File `Overview.xlsx` menyediakan metadata terstruktur yang merepresentasikan informasi penting dari setiap dokumen putusan.

Atribut metadata yang digunakan meliputi:

| Attribute | Description |
|---|---|
| Nomor Putusan | Nomor identifikasi resmi dokumen putusan pengadilan. |
| Lembaga Peradilan | Nama pengadilan yang mengeluarkan putusan. |
| Barang Bukti | Deskripsi barang bukti yang tercantum dalam dokumen putusan. |
| Amar Putusan | Informasi mengenai keputusan atau ketetapan hakim terhadap perkara. |

## 5. Dataset Utilization

Dataset ini dapat dimanfaatkan untuk berbagai kebutuhan penelitian dan pengembangan sistem, antara lain:

- **Information Retrieval:** Pengembangan dan pengujian sistem pencarian dokumen hukum.
- **Text Mining:** Analisis dan eksplorasi informasi dari dokumen putusan pengadilan.
- **Information Extraction:** Ekstraksi informasi penting seperti nomor putusan, barang bukti, dan amar putusan.
- **Legal Document Analysis:** Analisis konten dan karakteristik dokumen hukum.

## 6. Developers

**Herdiana Dwi Maharani**

*Developed for the Information Retrieval (IR) *

---

**Repository Purpose:** Academic and Research Purposes.
