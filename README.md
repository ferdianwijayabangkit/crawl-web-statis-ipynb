# 🕸️ Web Scraping: Ekstraksi Statis
### **Implementasi Scraping Halaman Statis dengan Python**

![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)
![Requests](https://img.shields.io/badge/requests-library-brightgreen.svg)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-library-blueviolet.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Affiliation](https://img.shields.io/badge/Affiliation-UNTIRTA-orange.svg)

Repositori ini menyajikan modul pembelajaran yang memandu Anda melalui alur kerja dasar **Web Scraping**. Proyek ini mendemonstrasikan implementasi di **Python** untuk metode **ekstraksi data statis** menggunakan pustaka `requests` dan `BeautifulSoup`.

---

## ✨ Fitur Utama

- **Implementasi Python**: Fokus pada implementasi *scraping* menggunakan ekosistem Python.
- **Materi Pembelajaran**: Menyajikan definisi, contoh, dan alur kerja untuk *scraping* halaman statis, menjadikannya sumber daya yang ideal untuk pemula.
- **Metode Scraping Statis**: Menerapkan strategi *scraping* klasik pada **[quotes.toscrape.com](http://quotes.toscrape.com/)**:
    - **`requests`**: Mengunduh konten halaman web (file HTML mentah).
    - **`BeautifulSoup`**: Mem-parsing HTML mentah menjadi struktur data yang dapat dinavigasi.
    - **`.find_all()`**: Mengekstrak semua data kutipan (`text`) dan penulis (`author`) dari halaman.
- **Laporan Reproducibel**: Menyediakan file Jupyter Notebook (`.ipynb`) yang mendokumentasikan setiap langkah, dari *request* hingga ekstraksi data.

---

## 📂 Struktur Proyek

- `ekstraksi statis.ipynb`: Notebook Python untuk implementasi *scraping* halaman statis.
- `README.md`: File ini.

*(Catatan: Proyek ini tidak memerlukan file data eksternal karena data diambil langsung dari web.)*

---

## 🔧 Tumpukan Teknologi (Tech Stack)

- **Bahasa**: `Python 3.7+`
- **Pustaka Python**: `requests`, `beautifulsoup4`
- **Lingkungan**: `Jupyter Notebook / Lab`

---

## 🚀 Cara Memulai

### Prasyarat

- Instalasi Python 3.x.
- Pustaka yang diperlukan (lihat instalasi di bawah).
- Jupyter Notebook/Lab.

### Instalasi & Penggunaan

1.  **Unduh Repositori**: *Clone* atau unduh proyek ini ke komputer Anda.
2.  **Instal Pustaka**: Buka terminal atau *command prompt* Anda dan jalankan:
    ```bash
    pip install requests beautifulsoup4
    ```
3.  **Jalankan Notebook**:
    - Jalankan Jupyter Lab/Notebook.
    - Buka file `ekstraksi statis.ipynb` dan jalankan sel kode di dalamnya.

---

## 📊 Ringkasan Hasil Utama

| Masalah | Metode Utama | Hasil Utama |
|---|---|---|
| **Ekstraksi Data Web Statis** (`quotes.toscrape.com`) | Static Scraping (`requests` + `BeautifulSoup`) | Berhasil mengunduh halaman dan mem-parsing 10 kutipan beserta penulisnya dari struktur HTML. |

---

## ⚖️ Lisensi & Ketentuan Penggunaan

- **Hak Cipta**: © 2025 Ferdian Bangkit Wijaya - Seluruh Hak Dilindungi.
- **Penggunaan Akademik**: Diizinkan secara bebas untuk keperluan penelitian dan pendidikan non-komersial dengan atribusi.
- **Penggunaan Komersial**: Memerlukan izin tertulis dari pengembang.

---

## 👨‍💻 Author

- **Ferdian Bangkit Wijaya**
- Universitas Sultan Ageng Tirtirta (UNTIRTA)
- Banten, Indonesia 🇮🇩

---

> Proyek ini berfungsi sebagai panduan praktis untuk web scraping, menunjukkan bagaimana `requests` dan `BeautifulSoup` dapat digunakan secara efektif untuk mengumpulkan data dari halaman web statis.
