## Face Identifier

Program Python ini adalah sistem pengenalan wajah dasar yang dibangun menggunakan pustaka OpenCV. Sistem ini memungkinkan Anda mengumpulkan data wajah baru, melatih model pengenalan, dan menjalankan deteksi serta pengenalan wajah secara **real-time** melalui webcam.


Program ini menggunakan algoritma **Local Binary Pattern Histograms (LBPH)** untuk pelatihan model dan **Haar Cascade Classifier** untuk deteksi awal wajah.

## Fitur Utama

*   **Pengumpulan Data:** Mengambil 100 sampel wajah dari webcam untuk pengguna baru.
*   **Pelatihan Model:** Melatih model LBPH menggunakan semua data wajah yang tersedia di folder `./faces/`.
*   **Pengenalan Real-Time:** Mendeteksi wajah secara langsung melalui webcam dan menampilkan nama pengguna yang diidentifikasi beserta tingkat kepercayaan diri (*confidence level*).

## Dependensi

Pastikan Anda telah menginstal dependensi Python berikut:

* opencv-python (cv2)
* numpy
* opencv-contrib-python` (diperlukan untuk modul `cv2.face`)

File external yang perlu di download:
* https://github.com/rchavezj/OpenCV_Projects/blob/master/Haarcascades/haarcascade_frontalface_default.xml

## Usage

1.  **Clone** repositori dari GitHub:
    ```bash
    git clone <URL_REPO>
    ```

2.  Masuk ke direktori proyek yang baru di-*clone*:
    ```bash
    cd ./src
    ```

3.  Instal library Python yang diperlukan menggunakan `pip`:
    ```bash
    pip install opencv-python numpy opencv-contrib-python
    ```

4.  Jalankan aplikasi utama :
    ```bash
    python projek.py
    ```

## Credits and References
* LTI Team
* https://github.com/rchavezj/OpenCV_Projects/blob/master/Sec07_Simple_Machine_Learning/03_Face_Recognition_%C3%B1_Unlock_Your_Computer_With_Your_Face/%2003_Face_Recognition_%C3%B1_Unlock_Your_Computer_With_Your_Face.ipynb
* https://github.com/rchavezj/OpenCV_Projects/blob/master/Haarcascades/haarcascade_frontalface_default.xml
