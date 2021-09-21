# Menentukan-Bilangan-Terbesar-dan-Terkecil
Menampilkan bilangan terbesar dan terkecil pada Python


    n = int(input("\nMasukan banyak Bilangan = "))
    bil = []
    for x in range(n):
        m=x+1
        a = int(input("masukkan bilangan ke %d = "%m))
        bil.append(a)
    print('Bilangan yang dimasukkan',bil)
    print("Bilangan terbesar dari daftar tersebut adalah %d" %max(bil), "dan bilangan terkecil dari daftar tersebut adalah %d" %min(bil));
