# MuhammadAlghifarie-PBO2-Latihan1
Berikut adalah file README untuk aplikasi **Latihan1** yang menggunakan Java Swing untuk menjumlahkan dua angka:

### README File (Latihan1)

```markdown
# Aplikasi Latihan1 - Penjumlahan Dua Angka

## Deskripsi
Aplikasi ini dibuat menggunakan Java Swing yang memungkinkan pengguna untuk memasukkan dua angka pada dua kolom input, kemudian menambahkan angka-angka tersebut dengan menekan tombol **Tambah**. Hasil penjumlahan akan ditampilkan pada kolom **Hasil**.

## Fitur
- **Input Angka Pertama**: Pengguna dapat memasukkan angka pertama pada kolom input.
- **Input Angka Kedua**: Pengguna dapat memasukkan angka kedua pada kolom input.
- **Tombol Tambah**: Tombol ini akan menjumlahkan angka pertama dan angka kedua, dan menampilkan hasilnya di kolom hasil.
- **Tombol Hapus**: Tombol ini belum berfungsi, tetapi dapat digunakan untuk pengembangan lebih lanjut.
- **Tombol Keluar**: Tombol ini akan menutup aplikasi.

## Persyaratan
- **Java Development Kit (JDK)** versi 8 atau lebih tinggi.
- IDE seperti **NetBeans** atau **IntelliJ IDEA** untuk pengembangan.

## Instalasi dan Penggunaan
1. **Clone atau Unduh Proyek**: 
   - Download atau clone proyek ini ke komputer Anda.
   
2. **Buka Proyek di IDE**:
   - Buka proyek ini di IDE favorit Anda, seperti NetBeans atau IntelliJ IDEA.

3. **Jalankan Program**:
   - Jalankan aplikasi dengan menekan tombol "Run" di IDE Anda.

4. **Masukkan Angka**:
   - Masukkan angka pertama dan angka kedua pada kolom yang tersedia.

5. **Klik Tombol Tambah**:
   - Tekan tombol **Tambah** untuk melihat hasil penjumlahan di kolom **Hasil**.

6. **Tombol Keluar**:
   - Klik tombol **Keluar** untuk menutup aplikasi.

## Struktur Kode
- **Latihan1.java**: Kelas utama yang berisi logika aplikasi dan GUI.
- **GUI Elements**:
  - `JTextField` untuk input angka dan menampilkan hasil.
  - `JButton` untuk tombol aksi: Tambah, Hapus, Keluar.
  - `JLabel` untuk teks penjelasan di GUI.

## Cara Menambahkan Fitur Lain
1. **Tombol Hapus**: Anda dapat menambahkan aksi pada tombol **Hapus** untuk menghapus input dan hasil.
   ```java
   jButton2.addActionListener(new java.awt.event.ActionListener() {
       public void actionPerformed(java.awt.event.ActionEvent evt) {
           jTextField1.setText("");
           jTextField2.setText("");
           jTextField3.setText("");
       }
   });
   ```

