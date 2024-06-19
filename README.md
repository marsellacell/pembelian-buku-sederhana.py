# pembelian-buku-sederhana.py
ini merupakan sebuah program pembelian buku di toko buku sederhana menggunakan python

import os
import sys


print("Selamat datang di STOREBOOK")
print("1. Novel")
print("2. Komik")
print("3. Biografi")
print("4. Search")

pilihmenu = input("Masukkan jenis Buku yang anda butuhkan: ")

judul =["Hello,Cello","Malioboro at Midnight","Kota Para Pecundang","Rumah untuk Alie","Kata Sandi", 
        "Death Note Short Stories","Akasha Record of Ragnarok 06","One Piece 98","Blue Lock 01","Tokyo Revengers 01",
        "Biografi Politik Habibie","Soekarno: Biografi Singkat 1901-1970","Tan Malaka: Biografi Singkat 1897-1949","History Of Madura","Carok Budaya & Hukum",]
pengarang=["Nadia Ristivani","Skysphire","Itakrn","Lenn Liu","Dian Yutyaningsih",
           "Tsugumi Ohba","Shinaya Umemura dan Takumi Fukui","Eiichiro Oda", "Muneyuki Kaneshiro dan Yusuke Nomura","PKen Wakui",
           "Raden Toto Sugiarto","Taufik Adi Susilo","Taufik Adi Susilo","Drs.H.Muhammad Syamsudin","DR.Wahju Prijo Sjatmiko, SH",]
harga=["Rp. 89.100","Rp. 91.000","Rp. 88.000","Rp. 99.000","Rp. 99.000",
       "Rp. 48.000","Rp. 45.000","Rp. 115.000","Rp. 36.000","Rp. 40.000",
       "Rp. 95.000","Rp. 70.000","Rp. 67.500","Rp. 63.000","Rp. 148.000",]
            
if pilihmenu == '1':
    print("Buku Novel yang tersedia :")
    print(f"1. {judul[0]}")
    print(f"2. {judul[1]}")
    print(f"3. {judul[2]}")
    print(f"4. {judul[3]}")
    print(f"5. {judul[4]}")
    
    pilihbuku = input("Masukkan judul Novel yang anda cari: ")
        
    if pilihbuku == '1':
        buku = '0'
        print(f"Buku        : {judul[0]}")
        print(f"Pengarang   : {pengarang[0]}")
        print(f"Harga       : Rp {harga[0]}")

        belibuku = input("Input Y (beli) dan N (kembali): ")
            
    elif pilihbuku =="2":
        buku = '1'
        print(f"Buku        : {judul[1]}")
        print(f"Pengarang   : {pengarang[1]}")
        print(f"Harga       : Rp {harga[1]}")

        belibuku = input("Input Y (beli) dan N (kembali): ")
        
    elif pilihbuku =="3":
        buku = '2'
        print(f"Buku        : {judul[2]}")
        print(f"Pengarang   : {pengarang[2]}")
        print(f"Harga       : Rp {harga[2]}")

        belibuku = input("Input Y (beli) dan N (kembali): ")
        
    elif pilihbuku =="4":
        buku = '3'
        print(f"Buku        : {judul[3]}")
        print(f"Pengarang   : {pengarang[3]}")
        print(f"Harga       : Rp {harga[3]}")

        belibuku = input("Input Y (beli) dan N (kembali): ")
        
    elif pilihbuku =="5":
        buku = '4'
        print(f"Buku        : {judul[4]}")
        print(f"Pengarang   : {pengarang[4]}")
        print(f"Harga       : Rp {harga[4]}")

        belibuku = input("Input Y (beli) dan N (kembali): ")
            
    else:
        sys.exit("Masukkan judul Novel dengan benar!!!")

elif pilihmenu == '2':
    print("Komik yang tersedia")
    print(f"1. {judul[5]}")
    print(f"2. {judul[6]}")
    print(f"3. {judul[7]}")
    print(f"4. {judul[8]}")
    print(f"5. {judul[9]}")
    
    pilihbuku = input("Masukkan judul Komik yang anda cari: ")
        
    if pilihbuku == '1':
        buku = '5'
        print(f"Buku        : {judul[5]}")
        print(f"Pengarang   : {pengarang[5]}")
        print(f"Harga       : Rp {harga[5]}")

        belibuku = input("Input Y (beli) dan N (kembali): ")
            
    elif pilihbuku =="2":
        buku = '6'
        print(f"Buku        : {judul[6]}")
        print(f"Pengarang   : {pengarang[6]}")
        print(f"Harga       : Rp {harga[6]}")

        belibuku = input("Input Y (beli) dan N (kembali): ")
        
    elif pilihbuku =="3":
        buku = '7'
        print(f"Buku        : {judul[7]}")
        print(f"Pengarang   : {pengarang[7]}")
        print(f"Harga       : Rp {harga[7]}")

        belibuku = input("Input Y (beli) dan N (kembali): ")
        
    elif pilihbuku =="4":
        buku = '8'
        print(f"Buku        : {judul[8]}")
        print(f"Pengarang   : {pengarang[8]}")
        print(f"Harga       : Rp {harga[8]}")

        belibuku = input("Input Y (beli) dan N (kembali): ")
        
    elif pilihbuku =="5":
        buku = '9'
        print(f"Buku        : {judul[9]}")
        print(f"Pengarang   : {pengarang[9]}")
        print(f"Harga       : Rp {harga[9]}")

        belibuku = input("Input Y (beli) dan N (kembali): ")
            
    else:
        sys.exit("Masukkan judul Komik dengan benar!!!")
elif pilihmenu == '3':
    print("Buku Biografi yang tersedia")
    print(f"1. {judul[10]}")
    print(f"2. {judul[11]}")
    print(f"3. {judul[12]}")
    print(f"4. {judul[13]}")
    print(f"5. {judul[14]}")
    
    pilihbuku = input("Masukkan Judul Biografi yang anda cari: ")
        
    if pilihbuku == '1':
        buku = '10'
        print(f"Buku        : {judul[10]}")
        print(f"Pengarang   : {pengarang[10]}")
        print(f"Harga       : Rp {harga[10]}")

        belibuku = input("Input Y (beli) dan N (kembali): ")
            
    elif pilihbuku =="2":
        buku = '11'
        print(f"Buku        : {judul[11]}")
        print(f"Pengarang   : {pengarang[11]}")
        print(f"Harga       : Rp {harga[11]}")

        belibuku = input("Input Y (beli) dan N (kembali): ")
        
    elif pilihbuku =="3":
        buku = '12'
        print(f"Buku        : {judul[12]}")
        print(f"Pengarang   : {pengarang[12]}")
        print(f"Harga       : Rp {harga[12]}")

        belibuku = input("Input Y (beli) dan N (kembali): ")
        
    elif pilihbuku =="4":
        buku = '13'
        print(f"Buku        : {judul[13]}")
        print(f"Pengarang   : {pengarang[13]}")
        print(f"Harga       : Rp {harga[13]}")

        belibuku = input("Input Y (beli) dan N (kembali): ")
        
    elif pilihbuku =="5":
        buku = '14'
        print(f"Buku        : {judul[14]}")
        print(f"Pengarang   : {pengarang[14]}")
        print(f"Harga       : Rp {harga[14]}")

        belibuku = input("Input Y (beli) dan N (kembali): ")
            
    else:
        sys.exit("Masukkan judul Biografi dengan benar!!!")
elif pilihmenu == '4':
    print('')
    print("Pencarian Buku")
    cari_buku = input("Masukkan judul atau pengarang Buku yang ingin dicari: ")
    
    hasil_pencarian = []
    for i in range(len(judul)):
        if cari_buku.lower() in judul[i].lower() or cari_buku.lower() in pengarang[i].lower():
            hasil_pencarian.append(i)
    
    if len(hasil_pencarian) > 0:
        print("Hasil Pencarian:")
        for i in hasil_pencarian:
            print(f"Judul      : {judul[i]}")
            print(f"Pengarang  : {pengarang[i]}")
            print(f"Harga      : {harga[i]}")
            if i < 5:
                print("Buku ada di list Novel\n")
                os.system('python "c:/Users/LEGION/OneDrive - ypt.or.id/sem2/pemrog1/coba/lisbuku.py"')
                sys.exit()
            elif 4<i<10:
                print("Buku ada di list Komik\n")
                os.system('python "c:/Users/LEGION/OneDrive - ypt.or.id/sem2/pemrog1/coba/lisbuku.py"')
                sys.exit()
            elif 9<i<15:
                print("Buku ada di menu Biografi\n")
                os.system('python "c:/Users/LEGION/OneDrive - ypt.or.id/sem2/pemrog1/coba/lisbuku.py"')
                sys.exit()
            else:
                sys.exit("buku tidak ada di list")
    else:
        print("Buku tidak ditemukan\n")
        os.system('python "c:/Users/LEGION/OneDrive - ypt.or.id/sem2/pemrog1/coba/lisbuku.py"')
        sys.exit()



pembelian = []
if pilihmenu in ['1', '2', '3', '4']:
    if 'pilihbuku' in locals():
        if belibuku.lower() == 'y':
           pembelian.append({f"Judul": judul[int(buku)], "Pengarang": pengarang[int(buku)], "Harga": harga[int(buku)]})
        elif belibuku.lower() == 'n':
            sys.exit()
        else:
            sys.exit("hanya masukan y/n")
else:
    sys.exit("Masukkan pilihan 1-4")


try:
    jumlah_barang = int(input("Masukkan jumlah barang yang dibeli: "))
    print("")
    print("")
    print("")
    print("==============================")
    print("          STOREBOOK           ")
    print("==============================")
    print("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~")
    print("        Struk Pembelian       ")
    print("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ ")


                
                
    print("Rincian Pembelian:")
    total_harga = 0
    for index, item in enumerate(pembelian):
        print(f"Judul      : {item['Judul']}")
        print(f"Pengarang  : {item['Pengarang']}")
        total_harga += int(item['Harga'].replace("Rp. ", "").replace(".", ""))
        print(f"Harga      : {total_harga}")
        print("")
        print(f"Jumlah barang: {jumlah_barang}")
except ValueError:
    print("Inputkan jumlah barang dengan benar!!!")
    sys.exit()

        
def transaksi_tunai():

    totalHarga = jumlah_barang * total_harga
    print(f"Total Harga: Rp {totalHarga:.2f}")
    try:
        uang_diberikan = int(input("Jumlah uang yang diberikan: "))
    except ValueError:
        print("Masukkan jumlah uang dengan benar!!!")
        sys.exit()
    
    if uang_diberikan < totalHarga:
        print("Uang yang diberikan tidak cukup.")
        sys.exit()
    elif uang_diberikan == totalHarga:
        print("Uang yang diberikan pas.")
        print("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ ")
        print("Terima kasih sudah Berbelanja \n")
        sys.exit()
    else:
        kembalian = uang_diberikan - totalHarga
        

    print(f"Uang Kembalian: {kembalian:.2f}          ")
    print("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ ")
    print("Terima kasih sudah Berbelanja \n")
    sys.exit()

def transaksi_cashless():
    totalHarga = jumlah_barang * total_harga
    
    print(f"Total Harga: Rp {totalHarga}                \n")
    print("Mohon Transfer ke nomor rekening berikut     ")
    print("BCA-12345678 a/n Marsella Dwi Julianti           \n")
    print("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ ")
    print("Terima kasih sudah Berbelanja \n")
    sys.exit()

def bayar():
    tunai = input("Pembayaran: ")
    if tunai.lower() == "tunai":
        transaksi_tunai()
    elif tunai.lower == "non-tunai":
        transaksi_cashless()
    else:
        print("Hanya ketik Tunai atau Non-Tunai")

bayar()
