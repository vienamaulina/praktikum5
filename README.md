 # Tugas Bahasa Pemrograman
 <p> Nama   :   Viena Dwi Putri Maulina <p>
 <p> Nim    :   312110469
 <p> Kelas  :   TI.21.C1 <p>

 ## Latihan 1
<p> berikut soalnya <p>

 ![gambar 1](ss/3.png)

<p> berikut programnya <p>

 ```python
 kontak={'Ari': '081267888', 'Dina': '087677776'}
print("=======================")
print("      DAFTAR KONTAK    ")
print("=======================")    
print("# Nama   |   No Telpon")
print("=======================")
print("# Ari    | ",   kontak['Ari'])
print("# Dina   | ", kontak['Dina'])
print("Menampilkan kontaknya Ari")
print("Ari      | ", kontak['Ari'])  # menampilkan kontak Ari
print("Menambahkan kontak baru")
kontak['Riko']='087654544' # menambah kontak baru
print("=======================")
print("      DAFTAR KONTAK    ")
print("=======================") 
print("# Nama   |   No Telpon")
print("=======================")
print("# Ari    | ",   kontak['Ari'])
print("# Dina   | ", kontak['Dina'])
print("# Riko   | ", kontak['Riko'])
print("Mengubah kontak Dina")
kontak['Dina']= '088999776' # Mengubah kontak Dina
print("Dina     | ", kontak['Dina']) 
print("Menampilkan semua nama")
print(kontak.keys())  # Menampilkan semua nama
print("Menampilkan semua no")
print(kontak.values())  # Menampilkan semua No
print("Menampilkan daftar nama dan nomornya")
print(kontak.items())  # Menampilkan daftar kontak
print("Menghapus kontak Dina")
del kontak['Dina'] # Menghapus kontak Dina
print(kontak.items())

 ```

 <p> kemudian run, hasilnya seperti ini <p>

 ![gambar 2](ss/2.png)

 ## Praktikum 5

 <p> Berikut soalnya <p>

 ![gambar 3](ss/4.png)

 <p>berikut programnya<p>

  ```python
  dataMahasiswa = {}
print("==================================================================")
print("|      PROGRAM INPUT NILAI MAHASISWA MENGGUNAKAN DICTIONARY      |")
print("==================================================================")

while True:
    c = input("\nA)dd, E)dit, S)earch, D)elete L)ist, Q)uit: ")

```
<p> 1. Menu ADD (menambahkan data)<p>
<p> berikut program nya <p>

```python
  ## MENU ADD
    if (c.lower() == 'a'):
        print("\n=========================")
        print("| TAMBAH DATA MAHASISWA |")
        print("=========================")
        nama          = input("Masukkan Nama        : ")
        nim           = input("Masukkan NIM         : ")
        nilaiTugas    = int(input("Masukkan Nilai Tugas : "))
        nilaiUts      = int(input("Masukkan Nilai UTS   : "))
        nilaiUas      = int(input("Masukkan Nilai UAS   : "))
        nilaiAkhir    = (0.30 * nilaiTugas) + (0.35 * nilaiUts) + (0.35 * nilaiUas)
        dataMahasiswa[nama] = nim, nilaiTugas, nilaiUts, nilaiUas, nilaiAkhir
        print("\nData Berhasil Ditambahkan!")

```

