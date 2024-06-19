def menu():
    print("Pilihan Operasi Matematika:")
    print("1. Tambah")
    print("2. Kurang")
    print("3. Kali")
    print("4. Bagi")
    print("5. Keluar")
    pilihan = int(input("Masukkan pilihan Anda: "))
    return pilihan

def tambah():
    a = float(input("Masukkan angka pertama: "))
    b = float(input("Masukkan angka kedua: "))
    print("Hasil penjumlahan:", a + b)

def kurang():
    a = float(input("Masukkan angka pertama: "))
    b = float(input("Masukkan angka kedua: "))
    print("Hasil pengurangan:", a - b)

def kali():
    a = float(input("Masukkan angka pertama: "))
    b = float(input("Masukkan angka kedua: "))
    print("Hasil perkalian:", a * b)

def bagi():
    a = float(input("Masukkan angka pertama: "))
    b = float(input("Masukkan angka kedua: "))
    if b != 0:
        print("Hasil pembagian:", a / b)
    else:
        print("Pembagian oleh nol tidak diperbolehkan.")

def main():
    while True:
        pilihan = menu()
        if pilihan == 1:
            tambah()
        elif pilihan == 2:
            kurang()
        elif pilihan == 3:
            kali()
        elif pilihan == 4:
            bagi()
        elif pilihan == 5:
            print("Terima kasih!")
            break
        else:
            print("Pilihan tidak valid.")

if __name__ == "__main__":
    main()
