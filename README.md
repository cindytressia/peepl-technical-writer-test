
# 📘 Jawaban Tugas Tekstual – IT Technical Writer Test  

---

## 🔹 Nomor 1 – Algoritma Mengoperasikan Sepeda Ontel/Kayuh  

### Pseudocode
```
Start

  Persiapan:
    - Cek tekanan ban
    - Cek fungsi rem depan & belakang
    - Atur tinggi sadel
    - Pasang helm (opsional)

  Posisi awal:
    - Berdiri di sisi sepeda
    - Posisikan pedal kanan di jam "2" (sekitar 45–60°) sebagai pedal start
    - Tangan pegang setang, pandangan ke depan

  Mulai mengayuh:
    - Naik ke sadel dengan seimbang
    - Dorong pedal start ke bawah untuk memberi dorongan awal
    - Letakkan kaki kiri ke pedal satunya dan mulai kayuh bergantian (kanan–kiri)

  Kendali & keseimbangan:
    - Jaga pandangan jauh ke depan
    - Pegang setang rileks, koreksi arah
    - Jika kecepatan rendah → tambah kayuhan

  Manuver:
    Jika perlu belok:
      - Kurangi kecepatan
      - Condongkan sepeda ke arah belok
      - Arahkan setang halus

  Berhenti:
    Jika ingin berhenti:
      - Kurangi kayuhan
      - Rem belakang dulu, lalu tambah rem depan
      - Turunkan satu kaki ke tanah
      - Turun dari sepeda dengan aman

End
```

### Flowchart
![Flowchart Sepeda](https://github.com/user-attachments/assets/c136241b-9836-4d3b-a9fb-f567878f512a)

---

## 🔹 Nomor 2 – Algoritma Menghitung Luas Kulit Tabung  

### Pseudocode
```
Start
  Deklarasi variabel r, t, luas
  Input nilai jari-jari tabung (r)
  Input nilai tinggi tabung (t)

  luas ← 2 * π * r * (r + t)

  Output "Luas permukaan tabung = ", luas
End
```

### Langkah Algoritma
1. Mulai program.  
2. Siapkan variabel `r` (jari-jari), `t` (tinggi), dan `luas`.  
3. Masukkan nilai jari-jari tabung.  
4. Masukkan nilai tinggi tabung.  
5. Hitung luas permukaan tabung dengan rumus:  

   **luas = 2 * π * r * (r + t)**  

6. Tampilkan hasil perhitungan luas permukaan tabung.  
7. Program selesai.  

---

## 🔹 Nomor 3 – Algoritma Deret Fibonacci  

### Pseudocode
```
Start
  Input n (jumlah suku Fibonacci)

  Output "Deret Fibonacci hingga n adalah:"

  For i = 0 to n-1 do
      If i <= 1 then
          hasil ← i
      Else
          hasil ← suku(i-1) + suku(i-2)
      EndIf

      Output hasil
  EndFor
End
```

### Langkah Algoritma
1. Mulai program.  
2. Masukkan jumlah suku Fibonacci yang ingin ditampilkan (`n`).  
3. Tampilkan teks: *"Deret Fibonacci hingga n adalah:"*.  
4. Lakukan perulangan dari `i = 0` sampai `i < n`:  
   - Jika `i = 0` atau `i = 1` → nilai suku = `i`.  
   - Jika `i > 1` → nilai suku = jumlah dua suku sebelumnya.  
5. Cetak hasil setiap suku.  
6. Ulangi sampai semua suku selesai ditampilkan.  
7. Program selesai.  
