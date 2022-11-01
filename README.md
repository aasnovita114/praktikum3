# Cara Installasi Pycharm
Anda harus install Pycharm di https://www.jetbrains.com/pycharm/download/#section=windows  , Dan anda pilih yang Community

![2022-10-31 (2)](https://user-images.githubusercontent.com/115775237/198932831-83182560-3117-4469-8e45-924b8cd7887d.png)

next saja semua perintahnya 

![2022-10-31 (3)](https://user-images.githubusercontent.com/115775237/198933464-45381f87-f77d-4ace-bc48-0bef2d8e66a0.png)

tunggu hingga selesai

![2022-10-31 (4)](https://user-images.githubusercontent.com/115775237/198933506-e6659704-6c9f-48ea-bdc9-5b44ceadc8a3.png)

Jika sudah selesai maka program siap di gunakan

# Cara Menjalankan Pycharm 
# Latihan 1

Pertama-tama anda harus Klik New project lalu kasih nama project anda(sesuai yang anda mau), Dan anda harus pilih yang Previously Configurred interperter lalu klik yang add interperter dan pilih yang System interperter dan anda klik yang versi Python anda seperti gambar di bawah ini

![Capturepycharm2](https://user-images.githubusercontent.com/116045324/199134451-5985a548-aa07-44a6-9bb5-33113b0f8540.PNG)
![Capturepycharm3](https://user-images.githubusercontent.com/116045324/199134493-6cf96269-e28a-4b37-9c29-a2b816a1404f.PNG)

Selanjutnya anda membuat file Python baru di project anda tadi dan anda kasih nama file sesuai yang anda inginkan

![2022-10-31 (8)](https://user-images.githubusercontent.com/115775237/198934387-0fe36386-208d-4ef2-a31d-075c791a91f7.png)

masukan code dari latihan1 anda lalu Run

	# penggunaan end

	print('A', end='')
	print('B', end='')
	print('C', end='')
	print()
	print('X')
	print('Y')
	print('Z')

	# penggunaan separator
	w, x, y, z = 10, 15, 20, 25
	print(w, x, y, z)
	print(w, x, y, z, sep=',')
	print(w, x, y, z, sep='')
	print(w, x, y, z, sep=':')
	print(w, x, y, z, sep='-----')

	# string format
	print(0, 10 ** 0)
	print(1, 10 ** 1)
	print(2, 10 ** 2)
	print(3, 10 ** 3)
	print(4, 10 ** 4)
	print(5, 10 ** 5)
	print(6, 10 ** 6)
	print(7, 10 ** 7)
	print(8, 10 ** 8)
	print(9, 10 ** 9)
	print(10, 10 ** 10)

	# string format
	print('{0:>3} {1:>16}'.format(0, 10 ** 0))
	print('{0:>3} {1:>16}'.format(1, 10 ** 1))
	print('{0:>3} {1:>16}'.format(2, 10 ** 2))
	print('{0:>3} {1:>16}'.format(3, 10 ** 3))
	print('{0:>3} {1:>16}'.format(4, 10 ** 4))
	print('{0:>3} {1:>16}'.format(5, 10 ** 5))
	print('{0:>3} {1:>16}'.format(6, 10 ** 6))
	print('{0:>3} {1:>16}'.format(7, 10 ** 7))
	print('{0:>3} {1:>16}'.format(8, 10 ** 8))
	print('{0:>3} {1:>16}'.format(9, 10 ** 9))
	print('{0:>3} {1:>16}'.format(10, 10 ** 10))

![Capturepychram5](https://user-images.githubusercontent.com/116045324/199134611-c2a40c34-c3a8-4461-8d9f-d0f5c729acdf.PNG)
![Capturepychram6](https://user-images.githubusercontent.com/116045324/199134640-46f00ee3-f437-4a8c-b80d-4f15073a5363.PNG)

lalu hasil run nya
![Capturepychram7](https://user-images.githubusercontent.com/116045324/199134684-63a848c2-eb3a-4291-8898-ba8e9e665df8.PNG)

# Latihan 2 
buat latihan baru "latihan2"

lalu masukkan code program

	a=input("masukkan nilai a:")
	b=input("masukkan nilai b:")
	print("variabel a=",a)
	print("variabel b=",b)
	print("hasil penggabungan {1}&{0}=%s".format(a,b) %(a+b))

	#konversi nilai variabel
	a=int(a)
	b=int(b)
	print("hasil penjumlahan {1}+{0}=%s".format(a,b) %(a+b))
	print("hasil penjumlahan {1}/{0}=%s".format(a,b) %(a/b))

![Capturepychram8](https://user-images.githubusercontent.com/116045324/199134731-fcc1bd24-089d-4647-8067-17dd35c94cec.PNG)

lalu hasil run nya menjadi
![Capturepychram9](https://user-images.githubusercontent.com/116045324/199134824-2fae603b-2eff-4878-b6fb-f5cff52da432.PNG)

# Latihan 3
buat file baru "latihan3"

![2022-10-31 (16)](https://user-images.githubusercontent.com/115775237/198935852-a75da9bf-dfb4-495d-a952-10d7fe51b41d.png)

masukkan code programnya

	string = ""

	x = int(input("Masukkan angka :"))
	bar = x
	# Looping Baris
	while bar >= 0:
	# Looping Kolom Spasi Kosong
	kol = bar
	while kol > 0:
		string = string + "   "
		kol = kol - 1
	# Looping Kolom Bintang Sisi Kiri
	kiri = 1
	while kiri < (x - (bar-1)):
		string = string + " * "
		kiri = kiri + 1
	# Looping Kolom Bintang Sisi Kanan
	kanan = 1
	while kanan < kiri -1:
		string = string + " * "
		kanan = kanan + 1

	string = string + "\n\n"
	bar = bar - 1

	bar = 1
	# Looping Baris
	while bar <= x:
	kol = bar+1
	# Looping Kolom Spasi Kosong
	while kol > 1:
		string = string + "   "
		kol = kol - 1
	# Looping Kolom Bintang Sisi Kiri
	kiri = 0
	while kiri < (x - bar):
		string = string + " * "
		kiri = kiri + 1
	# Looping Kolom Bintang Sisi Kanan
	kanan = kiri
	while kanan > 1:
		string = string + " * "
		kanan = kanan - 1

	string = string + "\n\n"
	bar = bar + 1
	print (string)

![Capturepychram10](https://user-images.githubusercontent.com/116045324/199135017-abb1b15c-0681-44e9-9f30-c58d6caa694b.PNG)
![Capturepychram11](https://user-images.githubusercontent.com/116045324/199135043-81d10de8-214f-46b7-a7fd-e9aa6e7c4668.PNG)

*Hasil Run*
![Capturepychram12](https://user-images.githubusercontent.com/116045324/199135079-a74b321a-0e25-4fa7-ad61-df1fb306f05e.PNG)

# Menghitung Luas Dan Keliling Lingkaran
buat file baru "praktikum3"

	print('menghitung luas dan keliling lingkarang')
	print('________________________________________')

	r=float(input('masukkan nilai jari - jari :'))

	phi=3.14
	diameter=2*r

	print('\nluasnya =', str("%.2f" % luas))
	print('kelilingnya =', str("%.2f" % keliling))

![Capturepychram13](https://user-images.githubusercontent.com/116045324/199135196-edac84bf-ed8f-4e62-a74b-160639d4cadc.PNG)

*Hasil Run*

![Capturepychramluaslingkaran](https://user-images.githubusercontent.com/116045324/199135240-51fff539-9671-4ad5-ab1d-eae3405952fa.PNG)

# Flowchart Menghitung luas dan keliling lingkaran
![image](https://user-images.githubusercontent.com/116045324/199135408-81c19741-d2b3-4bca-8c32-5e6ea49b4f77.png)
Terimakasih

