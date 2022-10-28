3. buah_yang_tersedia = ['jeruk', 'mangga', 'melon' , 'durian' , 'apel' , 'alpukat', 'nanas'] 
   buah_yang_dicari = input('Masukkan nama buah dalam huruf kecil: ')

   if (buah_yang_dicari in buah_yang_tersedia): 
      print('Buah yang anda cari tersedia!') 
   else: print('Buah yang anda cari tidak tersedia!')


   umur = int(input('masukan umur'))

   if umur >= 65:
       print('usia pensiun')
   elif umur >= 25:
       print('usia produktif')
   elif umur >= 15:
       print('usia remaja')
   elif umur >= 1:
       print('usia anak-anak')
   else:
       print('kondisi salah')
       
       
4. listKota = [ 'Jakarta', 'Surabaya', 'Depok', 'Bekasi', 'Solo', 'Jogjakarta', 'Semarang', 'Makassar' ]

   for i, kota in enumerate(listKota): print(i, kota)

   a = int(input('Masukkan bilangan ganjil lebih dari 50: '))

   while a % 2 != 1 or a <= 50: a = int(input('Salah, masukkan lagi: '))

   print('Benar')
