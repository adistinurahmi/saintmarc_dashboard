# Saint Marc Café — Customer Voice

Dashboard analisis survei pelanggan kafe dengan tampilan Jepang dan Indonesia.

## Jalankan di komputer

```bash
python -m pip install -r requirements.txt
python -m streamlit run app.py
```

## Publikasikan

1. Unggah `app.py`, `requirements.txt`, dan `README.md` ke root repository GitHub.
2. Masuk ke https://share.streamlit.io/ menggunakan akun GitHub.
3. Pilih **Create app**, lalu **Yup, I have an app** jika ditanyakan.
4. Pilih repository tersebut, branch `main`, dan main file path `app.py`.
5. Pada **Advanced settings**, pilih Python 3.12, lalu simpan dan deploy.
6. Periksa seluruh halaman dan filter sebelum membagikan URL aplikasi.

Data dan hasil praproses sudah tertanam dalam `app.py`; Excel dan CSV tambahan tidak diperlukan. Tidak memerlukan API key.

## Catatan analisis

Sumber yang disebut dalam aplikasi: カフェ調査データ_2020.xlsx dan hasil praproses analisis. Tanggal survei dan metode sampling belum dikonfirmasi. Hasil tidak mewakili seluruh pelanggan atau kondisi semua toko saat ini. Ini merupakan proyek akademis, bukan situs resmi Saint Marc Café.

## Pemeriksaan sebelum publikasi

Diuji menggunakan Python 3.12 dan versi pada requirements.txt. Seluruh 11 halaman, pergantian bahasa Jepang–Indonesia, dan filter tanpa responden berhasil dijalankan menggunakan Streamlit AppTest. Pemeriksaan ini tidak menggantikan pengecekan aplikasi setelah deployment.
