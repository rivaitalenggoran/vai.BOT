# vai.BOT

vai.BOT adalah chatbot sederhana yang dirancang untuk menjawab pertanyaan seputar Rivai Hayashi Hendrik Talenggoran. Chatbot ini dapat memberikan informasi mengenai nama, tempat tinggal, hobi, makanan favorit, warna kesukaan, sekolah, dan hubungan Rivai. Saat ini, vai.BOT hanya dapat diakses melalui terminal atau shell dan belum di-deploy ke environment yang lebih luas.

## Fitur
- Menjawab pertanyaan tentang identitas Rivai (nama, tempat tinggal, dll.)
- Memberikan informasi mengenai hobi dan preferensi pribadi Rivai
- Menyediakan detail mengenai latar belakang pendidikan dan proyek yang sedang Rivai kerjakan

## Teknologi yang Digunakan
- Python
- Natural Language Processing (NLP)
- Modul `os` dan `sys` untuk mengelola input dan output terminal

## Instalasi

1. **Clone Repository**
    ```bash
    git clone https://github.com/rivaitalenggoran/vai.BOT.git
    cd vai.BOT
    ```

2. **Buat Virtual Environment (Opsional, Tapi Direkomendasikan)**
    ```bash
    python -m venv venv
    source venv/bin/activate  # Linux / MacOS
    .\venv\Scripts\activate   # Windows
    ```

3. **Instal Dependencies**
    Pastikan Anda memiliki `requirements.txt`. Jalankan perintah di bawah untuk menginstal semua dependencies yang diperlukan:
    ```bash
    pip install -r requirements.txt
    ```

## Cara Menggunakan vai.BOT

1. **Jalankan Script**
    Untuk menjalankan vai.BOT di terminal:
    - Buka terminal
    - Ketikkan ```rasa shell ```
    - Berinteraksi dengan chabot di terminal
    

2. **Interaksi**
    Setelah bot berjalan, Anda bisa mulai mengetik pertanyaan di terminal. Beberapa contoh pertanyaan yang dapat Anda ajukan ke vai.BOT:
    - "Siapa nama Rivai?"
    - "Apa hobi Rivai?"
    - "Di mana Rivai tinggal?"
    -  "Status Rivai sekarang"

3. **Terminasi**
    Untuk menghentikan bot, cukup tekan `Ctrl + C` di terminal atau ketik `exit`.

## Catatan
Saat ini vai.BOT hanya dapat diakses melalui terminal, dan pengembangannya masih dalam tahap awal. Fitur deployment ke cloud atau platform lainnya masih dalam tahap rencana. Proyek ini juga memiliki kelemahan dalam hal environment yang belum optimal untuk deployment skala besar.

## Kontribusi
Jika Anda ingin berkontribusi, silakan buat pull request atau ajukan masalah di repository ini. Semua kontribusi sangat dihargai!


