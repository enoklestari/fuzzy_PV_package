# Estimasi Harga Package PLTS Skala Besar (Utility-Scale) Menggunakan FIS

Proyek ini mengimplementasikan **Sistem Inferensi Fuzzy (FIS)** untuk mengestimasi harga proyek Pembangkit Listrik Tenaga Surya (PLTS) skala besar di Indonesia. Model ini dibangun berdasarkan benchmark data dari **Indonesia Solar Energy Outlook 2025 (IESR)**.

## Latar Belakang
Penentuan biaya investasi (*Capital Expenditure*) PLTS skala MW sangat dipengaruhi oleh variabel non-linear seperti ketersediaan lahan dan target kapasitas daya. Proyek ini menggunakan logika fuzzy untuk menangani ketidakpastian tersebut dan memberikan estimasi harga yang kontinu (variabel).

## Fitur Utama
- **Input Ganda:** Luasan Area ($m^2$) dan Kapasitas Daya (MW).
- **Inference Engine:** Singleton Output dengan 9 aturan (Rule Base) matriks 3x3.
- **Output Dinamis:** Hasil investasi yang fleksibel melalui metode *Weighted Average*.
