# Phishing URL Detection Using BERT-Based Transformer Models

Topik Riset:
"Deteksi URL Phishing dengan Model Transformer Encoder-Decoder: Studi Kasus Analisis URL"

## Deskripsi
Model Transformer Encoder-Decoder digunakan untuk menganalisis URL atau email yang mencurigakan dalam mendeteksi phishing. Dengan memanfaatkan kemampuan encoder untuk menangkap informasi kontekstual secara mendalam dan decoder untuk menghasilkan representasi yang lebih spesifik, model ini mampu memahami pola-pola karakteristik yang terdapat pada URL atau teks email phishing. Proses analisis ini dilakukan berdasarkan dataset yang telah dikumpulkan melalui crawling. Dengan pendekatan ini, model dapat mengenali ciri-ciri phishing bahkan pada URL yang menyerupai URL sah, menawarkan keunggulan dibandingkan metode tradisional yang sering kali hanya mengandalkan aturan atau analisis permukaan.

## Novelty
Sedang. Meskipun Transformer Encoder-Decoder sudah digunakan di banyak aplikasi NLP, penerapannya dalam klasifikasi URL phishing masih relatif jarang ditemukan. Novelty dapat ditingkatkan dengan menggabungkan analisis struktur URL dan perilaku pengguna untuk menghasilkan prediksi yang lebih akurat dan kontekstual. Selain itu, pendekatan ini dapat dieksplorasi lebih lanjut dalam membandingkan efisiensi dengan arsitektur berbasis BERT atau model lain yang sejenis.

## Dataset: Malicious URL Dataset
Dataset yang digunakan adalah Malicious URL Dataset, yang mencakup jutaan URL berbahaya, termasuk URL phishing. Dengan pendekatan Transformer Encoder-Decoder, model dapat memahami pola dan karakteristik URL secara lebih mendalam. Dataset ini memungkinkan pengembangan sistem pendeteksi phishing yang lebih akurat dan robust terhadap variasi URL berbahaya.
URL: Malicious URL Dataset​ (GitHub)

## Sample Tests
### Data Training Results
![Screenshot 2025-01-03 233823](https://github.com/user-attachments/assets/045545c4-c3b2-4346-b8ef-24af6fdf6faa)


### Data Testing Results
![summary](https://github.com/user-attachments/assets/74e154e1-220c-4243-b0a1-329e613f0964)



## Built With
- Google Colab
- Visual Studio Code
- Torch

## Contributor

  - **Bonifasius Tarigan**
    [bonifasiustrg](https://github.com/PurpleBooth)

