# proyek1-eda-kelompok-10
GCP Cloud Spending Analysis

1. Hanina Marchia Putri (5027261012)
2. Marchelio Fahrul Rahmansyah (5027261027)
3. Muhammad Affan Arsyad (5027261081)

Topik Yang dipih: Cloud Computing                                                                                    
Sumber data: https://www.kaggle.com/datasets/sairamn19/gcp-cloud-billing-data/data                                 
Lisensi: https://cdla.io/sharing-1-0/

3 Temuan Utama
1. Jumlah catatan per region tidak selalu sejalan dengan rata-rata biayanya. asia-east1 memiliki catatan terbanyak (103), tetapi rata-rata biaya per catatannya paling rendah (144.325,72 INR). Rata-rata tertinggi ada di us-east1, sebesar 218.248,50 INR dari 82 catatan.
2. Utilisasi rendah bisa muncul bersama biaya tinggi. Dari 26 catatan dengan CPU dan memori di bawah 20%, ada 8 catatan dengan biaya minimal 270.372,50 INR. Salah satu contohnya adalah Cloud Data Fusion dengan utilisasi CPU 7,96%, utilisasi memori 10,82%, dan biaya 721.519 INR. Data ini belum menjelaskan penyebab biayanya.
3. Modus dari CPU Utilization (%) dan Usage Quantity bersifat multimodal, yang artinya variabel tersebut memiliki beberapa data dengan frekuensi yang sama. CPU Utilization memiliki modus hingga 47 dengan frekuensi 2 kali, sedangkan Usage Quantity memiliki 2 modus dengan frekuensi 2 kali. Pada tabel variabel numerik, modus yang ditampilkan adalah modus pertama atau yang paling kecil.
