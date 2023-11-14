Mengganti IMEI L860-GL

    Copy folder L860-GL_IMEI_Changer ke C:\
    Buka CMD, run as administrator
    Eksekusi CMD:

cd C:\L860-GL_IMEI_Changer

    Siapkan serial port modem & IMEI yang akan digunakan, misal:

Serial port modem : COM1
Target IMEI       : 356938035643809

    Untuk mengganti IMEI, eksekusi CMD berikut:

sec_provision.exe -c COM1 -i1 356938035643809 -k Sprk2048dev.key

    Jika CMD diatas tidak berhasil, gunakan CMD berikut untuk mengganti IMEI (Alternatif):

sec_provision.exe -c COM1 -i1 356938035643809 -k AltSprk2048dev.key

    Selesai, jangan lupa untuk menghapus folder C:\L860-GL_IMEI_Changer
