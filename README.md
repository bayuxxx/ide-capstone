# 🩺 Health Risk Prediction System

Sebuah aplikasi web berbasis Machine Learning yang dapat memprediksi risiko penyakit seperti **diabetes**, **penyakit jantung**, dan **stroke** berdasarkan data pengguna dan gaya hidup mereka. Aplikasi ini bertujuan membantu masyarakat untuk **deteksi dini** dan meningkatkan kesadaran terhadap kondisi kesehatan.

---

## 🚀 Fitur Utama

- 🧾 Form input data kesehatan (tinggi, berat, tekanan darah, dll)
- 📊 Prediksi risiko penyakit berdasarkan data
- 🧠 Machine Learning model (classification)
- 📈 Visualisasi hasil dan rekomendasi gaya hidup sehat
- 🗃 Riwayat dan monitoring prediksi
- 📤 Ekspor hasil ke PDF (opsional)

---

## 🧪 Teknologi yang Digunakan

| Komponen   | Teknologi                     |
|------------|-------------------------------|
| Frontend   | React.js / Vue.js / Flutter Web |
| Backend    | Python Flask / Django / Node.js (Express) |
| Database   | PostgreSQL / Firebase         |
| ML Model   | Python (scikit-learn, XGBoost)|
| Visualisasi| Chart.js / Recharts           |
| Deployment | Render / Railway / Vercel     |

---

## 📂 Struktur Proyek

```
health-risk-predictor/
│
├── backend/
│   ├── app.py (Flask app)
│   ├── model.pkl (Trained ML model)
│   ├── utils/
│   └── requirements.txt
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
│   └── package.json
│
├── dataset/
│   └── health_data.csv
│
└── README.md
```

---

## 🧠 Machine Learning

- Model: Random Forest / Logistic Regression / XGBoost
- Input:
  - Umur, jenis kelamin, tinggi badan, berat badan
  - Tekanan darah, gula darah, kolesterol
  - Gaya hidup (merokok, olahraga, pola makan)
  - Riwayat keluarga
- Output:
  - Skor risiko (0–100%) untuk masing-masing penyakit

---

## ⚙️ Cara Menjalankan

### 1. Clone Repo

```bash
git clone https://github.com/username/health-risk-predictor.git
cd health-risk-predictor
```

### 2. Backend

```bash
cd backend
pip install -r requirements.txt
python app.py
```

### 3. Frontend

```bash
cd frontend
npm install
npm run dev
```

### 4. Akses

Buka di browser: `http://localhost:3000`

---

## 📈 Contoh Dataset

Gunakan dataset dari Kaggle:

- [Heart Disease Dataset](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)
- [Diabetes Dataset](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)
- [Stroke Prediction Dataset](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset)

---

## 📌 Roadmap (Optional)

- [ ] Integrasi wearable device (smartwatch)
- [ ] Upload PDF hasil lab (OCR + ekstraksi data)
- [ ] Edukasi artikel kesehatan berdasarkan hasil
- [ ] Sistem notifikasi dan reminder sehat

---

## 🧑‍💻 Kontributor

- **Nama Kamu** – [@username](https://github.com/username)

---

## 📄 Lisensi

Proyek ini menggunakan lisensi [MIT](LICENSE).

---

> ⚠️ Disclaimer: Aplikasi ini **bukan alat diagnosis medis**, hanya sebagai alat bantu edukasi dan prediksi awal. Konsultasikan hasilnya dengan tenaga medis profesional.
