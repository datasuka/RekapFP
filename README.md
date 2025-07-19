# Rekap Faktur Pajak ke Excel 📄➡️📊

Aplikasi Streamlit untuk membaca file PDF Faktur Pajak dan mengubahnya menjadi Excel sesuai format yang telah ditentukan.

## 🚀 Cara Jalankan

```bash
pip install -r requirements.txt
streamlit run app.py
```

## 📥 Input

- File PDF Faktur Pajak (e-Faktur)

## 📤 Output

- File Excel berisi rekap:
  - Kode dan Nomor Seri Faktur
  - Nama PKP & Pembeli
  - NPWP, Alamat, Email, NIK, dll
  - Nilai DPP, PPN, PPnBM
  - Kota dan Tanggal Faktur
  - Penandatangan

## 🛠️ Dependensi

- Streamlit
- PyMuPDF (`pymupdf`)
- Pandas
- Openpyxl