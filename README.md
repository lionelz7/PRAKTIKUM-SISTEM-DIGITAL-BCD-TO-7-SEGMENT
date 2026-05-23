# Tugas Praktikum Sistem Digital - Rangkaian BCD to 7-Segment

## 👥 Anggota Kelompok
1. Jericho Mahesa Putra - H1H025043
2. Lionel Christian Alexander - H1H025048
3. Romeo Luthfi Wahyudi - H1H025059
4. Muhamad Rafi Arwindo - H1H025064

---

## 🔗 Link Project
* **Link Tinkercad:** https://www.tinkercad.com/things/dnz904E4HX5/editel?returnTo=%2Fdashboard&sharecode=4RcBE4GCC_BwM-Ttut_G6pqX2LJBzFIA5Eop7SnJLPg

---

## 📝 Penjelasan Tugas & Komponen
Tugas ini merangkai dan menguji rangkaian BCD to 7-Segment menggunakan Tinkercad

### 1. Rangkaian BCD to 7-Segment
Rangkaian BCD to 7-Segment adalah rangkaian digital yang berfungsi sebagai penerjemah dari kode biner (bahasa mesin) menjadi angka desimal (bahasa manusia).  
Cara kerjanya dibagi menjadi 3 tahap:
1. Input (Kode BCD): Saklar DIP Switch mengirimkan kombinasi angka biner 4-bit (hanya kombinasi 0000 sampai 1001) yang mewakili angka desimal 0–9.
2. Proses (Decoder IC CD4511): IC ini membaca kode biner tersebut dan menerjemahkannya untuk menentukan lampu segmen mana saja yang harus dinyalakan.  
3. Output (7-Segment Display): Layar display menerima sinyal dari IC dan menyalakan kombinasi batangan LED (segmen A-G) sehingga membentuk karakter angka 0–9 yang bisa dibaca langsung oleh manusia.

### 2. Gambar Rangkaian BCD to 7-Segment
Berikut adalah gambar tata letak komponen, koneksi kabel (wiring), serta visualisasi yang telah dirangkai pada Tinkercad:

<img width="469" height="230" alt="image" src="https://github.com/user-attachments/assets/ef79255f-6382-4ee8-a076-6d4075093aaa" />

### 3. Tabel Kebenaran BCD to 7-Segment
| INPUT (DCBA) | Tampilan Angka Desimal |
| :---: | :---: |
| 0 \ 0 \ 0 \ 0 | **0** |
| 0 \ 0 \ 0 \ 1 | **1** |
| 0 \ 0 \ 1 \ 0 | **2** |
| 0 \ 0 \ 1 \ 1 | **3** |
| 0 \ 1 \ 0 \ 0 | **4** |
| 0 \ 1 \ 0 \ 1 | **5** |
| 0 \ 1 \ 1 \ 0 | **6** |
| 0 \ 1 \ 1 \ 1 | **7** |
| 1 \ 0 \ 0 \ 0 | **8** |
| 1 \ 0 \ 0 \ 1 | **9** |

---

