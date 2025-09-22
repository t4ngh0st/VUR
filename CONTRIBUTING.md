# Panduan Kontribusi

Terima kasih ingin berkontribusi di VUR 🎉

## Struktur
- Semua paket ditempatkan sesuai kategori (`core`, `extra`, `utils`, dll.).
- Setiap paket minimal memiliki:
  - `template`
  - `packages.json`
  - `README.md`
  - opsional `patches/`

## Alur Kontribusi
1. Fork repo ini
2. Tambahkan paket baru atau update template
3. Jalankan lint:
   ```bash
   ./scripts/lint-template.sh

