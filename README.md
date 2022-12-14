# Pertemuan9--Praktikum5

**Repository ini dibuat unutk memenuhi tugas Pertemuan ke 9 - Bahasa Pemograman (Module Praktikum 4)**


Nama    :  Ghamma Pramana Putra Setyadin

NIM     :  312210247

Kelas   :  TI.22.B1

Dosen   :  Agung Nugroho, M.Kom

Matkul  :  Bahasa Pemograman

**Pada halaman ini (Tugas Pertemuan-9-Module Praktikum 4) Dosen memberi tugas sebagai berikut :**

**Ada dua bahan praktik dimodule 4 kali ini yaitu :**

- Soal latihan pada module praktikum 4

  ![image](https://user-images.githubusercontent.com/115474950/202421372-ff35dfbd-b6fd-4f65-b059-11896a7bcb75.png)

- Berikut ini saya menuliskan syntax sekaligus menuliskan langkah-langkahnya sebagai berikut

```python
# membuat list
print("Buat sebuah list sebanyak 5 elemen dengan nilai bebas")
list = [6, 7, 8, 9, 10]
print(list)

# mengakses list
print("Menampilkan elemen 3")
print(list[2])

print("ambil nilai elemen 2 sampai ke 4")
print(list[1:4])

print("ambil elemen terakhir")
print(list[-1])

# mengubah elemen list
print("ubah elemen 4 dengan nilai lainnya")
list[4]=10
print(list[3])

print("ubah elemen 4 sampai dengan elemen terakhir")
list[4:5]=[20,11]
print(list)

# Tambah elemen list
print("Ambil 2 bagian dari list pertama(A) dan jadikan list ke 2(B)")
list_pertama=list[3:5]
print(list_pertama)

print("tambah list B dengan nilai string")
list_pertama.append("guest")
print(list_pertama)

print("Tambah list B dengan 3 nilai")
list_pertama.append(["guest",7,8])
print(list_pertama)

print("Menggabungkan list B dengan list A")
gabung=list_pertama+list
print(gabung)
```

  ![Screenshot (97)](https://user-images.githubusercontent.com/115474950/202427821-f99cd8a1-67d3-4810-bfd6-1457b1565887.png)

  ![Screenshot (98)](https://user-images.githubusercontent.com/115474950/202427861-92fb38cb-8144-4c82-9857-381338599076.png)


- Berikut hasil run syntax untuk memenuhi latihan module 4 diatas :
  
  ![Screenshot (97)](https://user-images.githubusercontent.com/115474950/202426072-a92a4441-c2c3-46b8-bad0-028cbcba0f81.png)
  
- Soal Tugas Praktikum Module 4
  
  ![image](https://user-images.githubusercontent.com/115474950/202428577-1f0e5020-97d2-4f57-bba4-95b071b8f542.png)

- Pada soal tugas ini saya akan menjelaskan syntax yang saya buat sebagai berikut

```python
print("===================================================================")
print("Nama         :   Ghamma Pramana Putra Setyadin")
print("NIM          :   312210247")
print("Kelas        :   TI.22.B1")
print("Mata Kuliah  :   Bahasa Pemrograman")
print("===================================================================")
print("Tugas Praktikum module 4")

# Buat program sederhana untuk menambahkan data kedalam sebuah list dengan rincian sebagai berikut: ??? Progam meminta
# memasukkan data sebanyak-banyaknya (gunakan perulangan) ??? Tampilkan pertanyaan untuk menambah data (y/t?),
# apabila jawaban t (Tidak), maka program akan menampilkan daftar datanya. ??? Nilai Akhir diambil dari perhitungan 3
# komponen nilai (tugas: 30%, uts: 35%, uas: 35%) ??? Buat flowchart dan penjelasan programnya pada README.md. ??? Commit
# dan push repository ke github.

from prettytable import PrettyTable

baris = []
stop = False

# masukan nilai
while (not stop):
    nama = input("Masukan Nama : ")
    nim = input("Masukan NIM : ")
    tugas = input("Masukan Nilai Tugas : ")
    uts = input("Masukan Nilai UTS : ")
    uas = input("Masukan Nilai UAS : ")
    nilai_akhir = 0.3 * float(tugas) + 0.35 * float(uts) + 0.35 * float(uas)
    baris.append([nama, nim, tugas, uts, uas, nilai_akhir])

    tanya = input("Tambah data? (y/n) : ")
    if (tanya == "n"):
        stop = True

# cetak nilai
print("===================================================================")

x = PrettyTable()
no = 0

for isi in baris:
    no += 1
    x.field_names = ["No", "Nama", "Nim", "Tugas", "UTS", "UAS", "Nilai Akhir"]
    x.add_row([no, isi[0], isi[1], isi[2], isi[3], isi[4], isi[5]])
print(x)
```

![Screenshot (101)](https://user-images.githubusercontent.com/115474950/202728109-4f27434d-d147-48e5-aa8b-77017d9092e1.png)

![Screenshot (102)](https://user-images.githubusercontent.com/115474950/202728139-c5714570-b3ce-421d-8a15-b459eb6b0753.png)

- Berikut hasil run syntax yang saya buat untuk memenuhi praktikum module 4 :
  
  ![Screenshot (100)](https://user-images.githubusercontent.com/115474950/202728674-700302dd-1192-4f98-903d-e4286fbd9749.png)

- Flowchart program diatas adalah sebagai berikut :
  
  ![image](https://user-images.githubusercontent.com/115474950/202729421-4cbc92f8-2f77-4fb7-ac0d-13bca462849c.png)

# Berikut langkah-langkah "Tugas Pertemuan 9 Module 4" yang bisa saya jelaskan/jabarkan

# Sekian Terima Kasih

# Ghamma Pramana Putra Setyadin


