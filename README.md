# praktikum5


# Membuat Program Input Nilai Menggunakan Dictionary

print("PROGRAM INPUT NILAI")print("===================")

while True:print("")c = input("L)ihat, T)ambah, U)bah, H)apus, C)ari, K)eluar: ")if c.lower() == 'l': break

# Masukan L untuk menampilkan: print("Daftar Nilai")
                  print("=============================================================")
                  print("| NO |  NIM  |   NAMA   |  TUGAS  |  UTS  |  UAS  |  AKHIR  |")
                  print("=============================================================")
                  print("|                     TIDAK ADA DATA                         ")
                  print("=============================================================")
# Masukan t untuk menampilkan :
                 print("Tambah Data")
                 nilai = []
                 nim = input("NIM: ")
                 nama = input("Nama: ")
                 nilaiUts = int(input("Nilai UTS: "))
                 nilaiUas = int(input("Nilai UAS: "))
                 nilaiTugas = int(input("Nilai Tugas: "))
                 nilaiAkhir = (nilaiUts * 35/100) + (nilaiUas * 35/100) + (nilaiTugas * 30/100)

                 nilai.append([nama, nim, nilaiTugas, nilaiUts, nilaiUas, int(nilaiAkhir)])

# Masukan L untuk menampilkan :
                               print("\n   Daftar Nilai   ")
                               print("=============================================================")
                               print("| NO |  NIM  |   NAMA   |  TUGAS  |  UTS  |  UAS  |  AKHIR  |")
                               print("=============================================================")

                               print("| {no:2d} | {nama:12s} | {nim:9s} | {nilaiTugas:5d} | {nilaiUTS:5d} | {nilaiUAS:5d} | {nilaiAKHIR:6.2f} |"
                                 .format(no=i, nama=item[0], nim=item[1], nilaiTugas=item[2], nilaiUTS=item[3], nilaiUAS=item[4] nilaiAKHIR=item[5]))
                               print("======================================================================")
