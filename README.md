# UAS-Kapita-selekta
# 📈 Analisis Sentimen & Kesenjangan Narasi Rupiah (Media vs Publik)

Repository ini berisi skrip Python untuk melakukan penarikan data (*scraping*) berita ekonomi dari Kompas dan komentar dari Instagram, menganalisis sentimennya menggunakan model berbasis IndoBERT, serta memvisualisasikan jaringan kata (*text network analysis*) dan perbandingan sentimen antara media mainstream dan publik.

---

Fitur Utama

* **Web Scraping Berita:** Otomatis mengambil dan mengesktrak konten artikel dari URL Kompas terkait isu ekonomi.
* **Instagram Automation:** Otomatis melakukan login dan mengekstrak komentar pada postingan Instagram tertentu secara dinamis menggunakan Selenium.
* **Analisis Sentimen IndoBERT:** Mengklasifikasikan teks berita dan komentar publik menjadi sentimen `positive` atau `negative` menggunakan model NLP `crypter70/IndoBERT-Sentiment-Analysis`.
* **Analisis Jaringan Kata (Text Network):** Membangun graf koneksi antar kata menggunakan `NetworkX` berdasarkan struktur teks artikel berita.
* **Visualisasi Komparatif:** Menghasilkan grafik perbandingan (*bar chart*) untuk melihat kesenjangan narasi antara media vs opini publik.

---

Sebelum menjalankan skrip ini, pastikan kamu sudah menginstal **Python (v3.8 ke atas)** dan **Google Chrome** di komputermu.
