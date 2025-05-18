# 🎤 Natural Language Voice Assistant – UAS Praktikum Pemrosesan Bahasa Alami

Proyek ini adalah tugas Ujian Akhir Semester untuk mata kuliah **Pemrosesan Bahasa Alami** pada program studi **Informatika Universitas Syiah Kuala**.

Aplikasi ini memungkinkan pengguna berinteraksi menggunakan suara, yang kemudian ditranskripsi, diproses oleh model bahasa, dan dikembalikan sebagai suara balasan.

## 🧠 Teknologi yang Digunakan

- **Whisper.cpp** – untuk Speech-to-Text (STT)
- **Gemini API** – sebagai Large Language Model (LLM)
- **Coqui TTS** – untuk Text-to-Speech (TTS)
- **FastAPI** – backend untuk mengatur alur komunikasi
- **Gradio** – antarmuka pengguna berbasis web

## 🔁 Alur Kerja Aplikasi

1. **Input Suara**  
   Pengguna merekam suara melalui antarmuka Gradio.

2. **Speech-to-Text (STT)**  
   Suara dikonversi menjadi teks menggunakan Whisper.cpp.

3. **Pemrosesan LLM**  
   Teks dikirim ke Gemini API untuk mendapatkan respons.

4. **Text-to-Speech (TTS)**  
   Respons teks dikonversi kembali menjadi suara dengan Coqui TTS.

5. **Output Suara**  
   Suara hasil balasan ditampilkan kembali ke pengguna.

## 🎬 Demo

Silakan lihat video demo [disini]([url](https://youtu.be/jrdLVYYRrik?si=2I7H_RmQ4VCXcl3Y)) yang menunjukkan alur singkat mulai dari input suara hingga output suara.

## 📚 Lisensi

Proyek ini hanya digunakan untuk keperluan akademik.

---

Created by: Firjatullah Afny Abus 
Universitas Syiah Kuala – Informatika  
UAS Praktikum Pemrosesan Bahasa Alami
