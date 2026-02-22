# Bike Sharing Dashboard 🚲

Proyek analisis data untuk dashboard bike sharing menggunakan Streamlit.

## Prerequisites

- Python 3.8 atau versi lebih baru
- Virtual environment (venv)

## Instalasi

1. **Clone repository** (jika belum):
   ```
   git clone https://github.com/DescaAR/bike-sharing-analysis.git
   cd bike-sharing-analysis
   ```

2. **Buat virtual environment**:
   ```
   python -m venv .venv
   ```

3. **Aktivasi virtual environment**:
   - Pada Windows: `.venv\Scripts\activate`
   - Pada macOS/Linux: `source .venv/bin/activate`

4. **Install dependencies**:
   ```
   pip install -r requirements.txt.txt
   ```

## Menjalankan Dashboard

1. Pastikan virtual environment sudah diaktifkan.

2. Jalankan dashboard dengan perintah:
   ```
   streamlit run dashboard.py
   ```

3. Buka browser dan akses URL yang ditampilkan (biasanya `http://localhost:8501`).

## Struktur Proyek

- `dashboard.py`: File utama dashboard Streamlit
- `main_data.csv`: Data harian bike sharing
- `main_data_hour.csv`: Data per jam bike sharing
- `main_data_day.csv`: Data harian (duplikat?)
- `proyek_analisis_data.py`: Script analisis data
- `requirements.txt.txt`: Daftar dependencies

## Dependencies

- pandas
- matplotlib
- seaborn
- streamlit

## Catatan

Dashboard ini menggunakan data bike sharing untuk analisis dan visualisasi.
