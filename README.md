 # Tugas Bahasa Pemrograman
 <p> Nama   :   Viena Dwi Puytri Maulina <p>
 <p> Nim    :   312110469
 <p> Kelas  :   TI.21.C1 <p>

 ## Latihan 1

 ![gambar 1](ss/3.png)
 
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
