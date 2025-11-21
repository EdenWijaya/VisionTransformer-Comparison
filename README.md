# Vision Transformer Comparison (ViT vs Swin Transformer)

Proyek ini bertujuan membandingkan performa dua arsitektur Vision Transformer:
1. **ViT Base Patch16 224**
2. **Swin Transformer Tiny**

Perbandingan dilakukan berdasarkan:
- Akurasi
- Precision, Recall, F1-Score
- Confusion Matrix
- Parameter model & ukuran model
- Waktu inferensi per gambar
- Throughput (FPS)

Proyek ini menggunakan dataset **Indonesian Food** yang disediakan sebelumnya, berisi 5 kelas:
- bakso
- gado_gado
- nasi_goreng
- rendang
- soto_ayam

File label tersimpan dalam `train.csv` dan semua gambar berada pada folder `train/`.

---

## 🔧 Requirements

Install dependencies:

```bash
pip install -r requirements.txt
