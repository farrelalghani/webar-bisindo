# WebAR BISINDO (Bahasa Isyarat Indonesia) — Abjad Jari A s/d Z

Aplikasi Web-based Augmented Reality & Computer Vision modern untuk pembelajaran abjad jari Bahasa Isyarat Indonesia (**BISINDO**) secara real-time langsung melalui web browser, baik di **Desktop** maupun **Mobile**.

---

## 🚀 Fitur Utama & Pembaruan

- **Abjad Lengkap BISINDO (A - Z):** Mendukung pengenalan gestur satu tangan dan dua tangan khas BISINDO (misal: A, B, F, G, M, N, P, S, T, X).
- **Desain Modern & Responsif:** Antarmuka bergaya *Dark-Themed Glassmorphism* dengan aksen *Lime Green* (`#d7ff69`), responsif secara penuh di layar ponsel cerdas (*mobile*), tablet, dan monitor desktop *widescreen*.
- **Real-Time Hand Tracking:** Pelacakan sendi tangan (21 titik koordinat per tangan) berbasis **Google MediaPipe Tasks Vision (Hand Landmarker)** yang diakselerasi GPU via WebAssembly.
- **Interactive 3D Feedback:** Visualisasi huruf 3D interaktif menggunakan **Three.js** yang melayang dan mengikuti pergerakan telapak tangan.
- **Circular Hold-to-Type System:** Indikator lingkaran progres SVG dengan durasi penahanan 2 detik (dapat diatur) untuk mencegah pengetikan yang tidak disengaja.
- **Kamus & Panduan Isyarat A - Z:** Tersedia *carousel drawer* cepat dan modal kamus lengkap dengan petunjuk langkah demi langkah serta filter kategori (Semua, Vokal, 1 Tangan, 2 Tangan).
- **Speech Synthesis (TTS):** Integrasi Web Speech API (`id-ID`) untuk melafalkan setiap huruf dan membaca seluruh kata yang tersusun.
- **Zero Installation & Zero Build:** Berjalan murni di sisi peramban (*client-side*) tanpa perlu `npm build` atau instalasi dependensi.

---

## 🛠️ Tech Stack

- **HTML5 & Modern CSS3 / Tailwind CSS**
- **JavaScript (ES6 Modules)**
- **[Three.js v0.160.0](https://threejs.org/)** (WebGL & 3D Extruded Text)
- **[Google MediaPipe Vision v0.10.0](https://developers.google.com/mediapipe)** (Hand Landmarker Model)
- **Web Speech API** (SpeechSynthesis)
- **Font Awesome 6 & Google Fonts** (DM Sans, Manrope, Fredoka One)

---

## 💻 Cara Menjalankan

1. Buka folder proyek di editor kode (seperti VS Code).
2. Klik kanan pada berkas [index.html](file:///d:/COLLEGE/SMT7/Realitas%20Maya%20dan%20Berimbuh/WEBAR%20BISINDO1/WEBAR%20BISINDO/index.html) lalu pilih **"Open with Live Server"**.
3. Izinkan akses webcam pada peramban peramban Anda.
4. Atau langsung deploy gratis via **GitHub Pages**, **Vercel**, atau **Netlify**.

---

Dikembangkan oleh **Farrel Muhammad Alghani** & **Rifasha Hadiarto**  
Mata Kuliah: *Realitas Maya dan Berimbuh (Semester 7)*
