a. Bahasa pemrograman yang saya gunakan adalah Python karena Python adalah High Level Language untuk mempermudah saya membuat projek ini  
b. Alur program:
    Pertama, Program meminta user untuk menentukan jenis operasi matematika yang ingin di jalankan.
    Kedua, Program menentukan kalimat yang akan digunakan.
    Ketiga, Program akan meminta 2 input yang akan digunakan dalam operasi matematika.
    Keempat, Program akan melakukan operasi matematika sesuai dengan jenis pilihan dan 2 input
    Kelima, Program akan menanyakan apakah ingin melanjutkan operasi
            Jika iya, program kembali ke line pertama dengan hasil sebagai input pertama
            Jika tidak, program akan menanyakan apakah user ingin menggunakan kalkulator lagi
                        Jika iya, program akan kembali ke line pertama
                        Jika tidak, program selesai
                        
<img width="328" height="629" alt="Screenshot 2025-09-17 002748" src="https://github.com/user-attachments/assets/ae915692-65c4-4e36-b91d-ade02190e875" />

c. Kode utama:
    # Meminta input user
        if simpan_angka:
            print(f"Angka yang akan {sifat_angka1} adalah {angka1}")
        else:
            angka1 = float(input(f"Masukan angka yang ingin {sifat_angka1}: "))
        angka2 = float(
            input(f"Masukan angka yang akan menjadi {sifat_angka2}: "))
        # Pemilihan perhitungan
        if pilihan == "1":
            hasil = angka1 + angka2
        elif pilihan == "2":
            hasil = angka1 - angka2
        elif pilihan == "3":
            hasil = angka1 * angka2
        elif pilihan == "4":
            hasil = angka1 / angka2
        elif pilihan == "5":
            hasil = angka1 ** angka2
        elif pilihan == "6":
            hasil = pow(angka1, 1/angka2)
        elif pilihan == "7":
            hasil = angka1 % angka2
        # Pembentukan kata untuk menampilkan hasil dan menanyakan apakah user ingin melanjutkan perhitungan
        konfirmasi = input(
            f"Hasil {sisa} dari {angka1} {sifat_angka1} {angka2} adalah {hasil:.3f} \nApakah anda ingin melanjutkan operasi? (Y/N): ")
        sisa = ""
<img width="1015" height="494" alt="Screenshot 2025-09-17 003118" src="https://github.com/user-attachments/assets/949777a5-4368-44c4-ad5c-df27f7a819b8" />

d. Jika input = 1,4,5 maka output 9
<img width="442" height="225" alt="Screenshot 2025-09-17 003414" src="https://github.com/user-attachments/assets/44355255-87f4-4cc7-8310-a71097486846" />
