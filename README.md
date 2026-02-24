🌧️ Rainfall Intensity Prediction using Deep Learning (X-Band Radar)


📌 Overview

This project develops a deep learning rainfall prediction system using X-band radar data for short-term rainfall forecasting and early flood warning.

Three models were implemented and compared:

- LSTM — temporal rainfall prediction

- ConvLSTM — spatiotemporal radar map prediction

- CNN-LSTM — hybrid model combining spatial and temporal learning

The system predicts rainfall intensity 15 minutes ahead.


🧠 Models


LSTM: learns rainfall trends over time

ConvLSTM: captures storm movement from radar images

CNN-LSTM: extracts spatial features using CNN and predicts intensity using LSTM

✅ CNN-LSTM achieved the best performance.


⚙️ Tools

Python • TensorFlow/Keras • NumPy • Pandas • OpenCV • Matplotlib 


📂 Dataset used in this project:

👉 https://drive.google.com/drive/u/0/folders/1URGjR37aCQLxn2qEhe8_ylJeRoPmXvy7


👩‍💻 Authors

- Aida Binti Shahiedun
- Nur Amirotul Izzah Binti Mohamad Faizal

Supervisor: Dr. Nur-Adib Maspo
