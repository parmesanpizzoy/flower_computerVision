# flower_computerVision
# 🖼️ Image Processing & Computer Vision Fundamentals (Python & OpenCV)

Repositori ini berisi kumpulan kode praktik dan eksperimen dasar pengolahan citra (*image processing*) menggunakan **Python**, **OpenCV**, **NumPy**, dan **Matplotlib**. Proyek ini mencakup dasar-dasar manipulasi citra digital mulai dari pemuatan gambar, *histogram equalization*, teknik *thresholding*, hingga berbagai metode *filtering dan blurring*.

---

## 🚀 Fitur & Modul Utama

Skrip utama mencakup 5 tahapan esensial dalam pengolahan citra:
1. **Python & NumPy Basic Review**: Pengenalan struktur data dasar Python (`list`, `tuple`) dan manipulasi *array* menggunakan NumPy.
2. **Load & Display Image**: Memuat gambar dari perangkat (mendukung Google Colab) dan menampilkannya menggunakan Matplotlib dalam format RGB.
3. **Histogram Equalization**: Konversi gambar ke *grayscale*, perhitungan frekuensi piksel secara manual (*pixel counting*), dan pemerataan histogram untuk meningkatkan kontras gambar.
4. **Thresholding Techniques**: Penerapan teknik segmentasi biner, meliputi:
   * *Binary Thresholding*
   * *Inverse Binary Thresholding*
   * *Otsu's Thresholding* (otomatis)
5. **Image Filtering & Blurring**: Penerapan filter untuk memperhalus atau mereduksi noise pada gambar, meliputi:
   * *Averaging Blur*
   * *Gaussian Blur*
   * *Median Blur*
   * *Bilateral Filter*

---

## 🛠️ Prasyarat (Prerequisites)

Pastikan kamu sudah menginstal pustaka Python berikut sebelum menjalankan program:

```bash
pip install opencv-python numpy matplotlib
