# ResuMate: AI Resume Analysis & Career Recommendation (FYP)
1. Pasang Python 3.11+, MySQL dan Tesseract OCR.
2. `python -m venv venv && venv\Scripts\activate && pip install -r requirements.txt`
3. Import `schema.sql` ke MySQL. Salin `.env.example` ke `.env` dan isi nilai.
4. `flask --app app create-admin` (cipta akaun admin)
5. `python app.py` dan buka http://127.0.0.1:5000
