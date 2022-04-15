# Lab5Web
# A. Javascript dasar

## Seperti biasa langkah awal adalah buka Aplikasi text editor yang biasa kalian pakai, disini saya menggunakan text Editor VsCode.

## 1. Mengenal Java Script

ika sudah dibuka, langsung buat folder bernama lab5_javascript. setelah itu buat file dengan nama "Mengenal Javascript".

lalu ketik code seperti berikut :

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mengenal JavaScript</title>
</head>
<body>
  <h1>Pengenalan JavaScript</h1>
  <h3>Contoh document.write dan console.log</h3>
  <script>
    document.write("Hello World")
    console.log("Hello world")
  </script>
</body>
</html>

![Screenshot (192)](https://user-images.githubusercontent.com/101470912/163547979-bd151647-7073-4c54-821f-31ff2acedda7.png)
Maka hasilnya akan seperti berikut :

![Screenshot (193)](https://user-images.githubusercontent.com/101470912/163548082-065c5af1-a4b2-46d6-b3a1-4db92e802823.png)
Klik tombol f12 pada komputer anda, agar bisa melihat console.log.


## 2. Alert Box
Selanjutnya kita akan menampilkan Alert box dengan Javascript. Masukan Kode seperti di bawah ini :

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Alert Box</title>
  </head>
  <body>
    <script lang="javascript">
      
      window.alert("ini merupakan pesan untuk anda");
      
    </script>
  </body>
</html>
![Screenshot (194)](https://user-images.githubusercontent.com/101470912/163548262-26dc8e2a-9f8d-410e-922e-628163782aac.png)
Maka Hasilnya akan seperti ini :
![Screenshot (195)](https://user-images.githubusercontent.com/101470912/163548331-df54e0c5-0b16-45c8-baa8-4d7e0bafe0bb.png)


## 3. Method dalam objek
Disini kita akan mencoba memakasi javascript sebagai objek. Masukkan kode berikut :

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Script JavaScript</title>
</head>
<body>
  Percobaan memakai javascript: <br>
  <script lang="javascript">
    
    document.write("Selamat Mencoba javascript<br>");
    document.write("Semoga Sukses !");
    
  </script>
</body>
</html>
![Screenshot (196)](https://user-images.githubusercontent.com/101470912/163548456-b5395053-7489-492f-abe5-57702e57dfa2.png)
Lalu buka di web browser, dan lihat hasilnya.
![Screenshot (197)](https://user-images.githubusercontent.com/101470912/163548537-906871a5-14d8-40bd-b6ea-72fad015033e.png)


## 4. Prompt
Prompt digunakan untuk memasukkan data, bentuknya sama seperti alert box. masukkan kode berikut :

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pemasukan Data</title>
</head>
<body>
  <script lang="javascript">
    var nama=prompt("siapa nama Anda?","Masukkan nama anda");
    document.write("hai, "+ nama );
  </script>
</body>
</html>
![Screenshot (198)](https://user-images.githubusercontent.com/101470912/163548633-5596239f-4a70-4f33-b6cc-9dfd518a8a64.png)
Maka hasilnya akan seperti di bawah ini :
![Screenshot (199)](https://user-images.githubusercontent.com/101470912/163548706-af3d345b-7db4-465e-ab40-e779ee431fb9.png)
jika kita ketik sebuah nama, maka akan muncul kalimat 'hai, (nama)'


## 5. On load
sama seperti alert box, masukkan kode berikut :

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Contoh program javascript</title>
    <script lang="javascript">
      function pesan() {
        alert ("memanggil javascript lewat body onload")
      }
    </script>
  </head>
  <body onload="pesan()">
  </body>
</html>
![Screenshot (200)](https://user-images.githubusercontent.com/101470912/163548816-d1a46669-e0e3-4874-861f-e7a7594f1fe5.png)
Maka Hasil akan muncul seperti ini :
![Screenshot (201)](https://user-images.githubusercontent.com/101470912/163548884-34bdb955-5b92-4d25-9fe2-d55445d123ec.png)

## 6. Operasi Aritmatika
Membuat sebuah program aritmatika menggunakan JavaScript. Perhatikan dan ketiklah kode berikut
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contoh Program Javascript</title>
  <script lang="javascript">
    function test (val1,val2)
    {
      document.write("<br>"+"perkalian : val1*val2"+"<br>")
      document.write(val1*val2)
      document.write("<br>"+"pembagian : val1/val2"+"<br>")
      document.write(val1/val2)
      document.write("<br>"+"penjumlahan : val1+val2"+"<br>")
      document.write(val1+val2)
      document.write("<br>"+"pengurangan : val1-val2"+"<br>")
      document.write(val1-val2)
      document.write("<br>"+"modulus : val1%val2"+"<br>")
      document.write(val1%val2)

    }
  </script>
</head>
<body>
  <input type="button" name="button1" value="arithmethic" onclick="test(9,4)">
</body>
</html>
![Screenshot (202)](https://user-images.githubusercontent.com/101470912/163548982-33153d26-8f48-4b0f-9a4d-2a91ad6ab83f.png)
Jika sudah, langsung buka di browser dan lihat hasilnya.

Tampilan awal, kita langsung di perlihatkan tombol dengan nama 'arithmethic',
![Screenshot (203)](https://user-images.githubusercontent.com/101470912/163549066-713d642e-9730-4fb8-8c1f-88deff3fc2e5.png)
Jika kita klik tombol tersebut, maka akan muncul aritmatikanya
![Screenshot (204)](https://user-images.githubusercontent.com/101470912/163549174-b8ad8094-f4cd-49a6-8ed6-e5a20ff9d7ab.png)


## 7. If - Else
Membuat program if else, if else berguna sesuai dengan kondisi yang kita atur. pada Praktikum ini, Program yang dibuat adalah nilai rendah dan tinggi. jika kita masukan nilai diatas 60, maka program akan menampilkan hasil 'lulus', Sebaliknya jika kita masukan nilai di bawah 60 maka program akan menampilkan hasil 'tidak lulus'. berikut kodenya :
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contoh if-else</title>
</head>
<body>
  <script lang="javascript">
    var nilai = prompt("nilai (0-100): ", 0);
    var hasil = "";
    if (nilai >= 60) 
    hasil = "Lulus";
    else
    hasil = "Tidak Lulus";
    document.write("hasil: " + hasil);
  </script>
</body>
</html> 
![Screenshot (205)](https://user-images.githubusercontent.com/101470912/163549275-2811cb78-b27e-417d-9de1-97fad71041aa.png)
Kita lihat Hasilnya di web browser :
![Screenshot (206)](https://user-images.githubusercontent.com/101470912/163549365-08d9bc68-efd7-4abf-8922-581ff841d324.png)


## 8. Operator Switch
Operator Switch akan menampilkan hasil dengan program yang kita perintah, Ketik kode berikut :

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>COntoh program javascript</title>

  <script lang="javascript">
    function test ()
    {
      val1=window.prompt("input nilai (1-5):")
      switch (val1)

      {
        case "1":
          document.write("bilangan satu")
          break
        case "2":
          document.write("bilangan dua")
          break
        case "3":
          document.write("bilangan tiga")
          break
        case "4":
          document.write("bilangan empat")
          break
        case "5":
          document.write("bilangan lima")
          break
        default :
          document.write("bilangan lainnya")
      }
    }
  </script>
</head>
<body>
  <input type="button" name="button1" value="switch" onclick="test()">
</body>
</html>
![Screenshot (208)](https://user-images.githubusercontent.com/101470912/163549417-5fdbc05a-541e-411d-8e03-9c50752893ae.png)
Maka Hasilnya akan menunjukan bilangan yang kita pilih, yaitu angka 0-5. jika yang kita masukan adalah bilangan yang lebih dari 5, maka akan menampikan hasil 'bilangan lainnya'
![Screenshot (209)](https://user-images.githubusercontent.com/101470912/163549476-f383d239-e45d-4272-a8c6-fbad4f48514d.png)


## 9. Form Input
Ketik Kode seperti berikut :

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>form input</title>

  <script lang="javascript">
    function test (){
      var val1=document.kirim.T1.value
      if (val1%2==0)
        document.kirim.T2.value="bilangan genap"
      else 
        document.kirim.T2.value="bilangan ganjil"
    }
  </script>
</head>
<body>
  <form method="post" name="kirim">
    <p>BIL <input type="text" name="T1" size="20"> MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
    <p><input type="button" value="tebak" name="B1" onclick="test()"></p>
  </form>
</body>
</html>
![Screenshot (210)](https://user-images.githubusercontent.com/101470912/163549537-c24f322a-6822-4e4b-8396-1377ce78089e.png)
Maka hasilnya akan menampilkan seperti ini :
![Screenshot (211)](https://user-images.githubusercontent.com/101470912/163549604-ffcf3b0d-e337-4d2e-bf93-db2d0ad57a50.png)


## 10. Form Button
Pada Praktikum ini, akan di tunjukkan bagaimana cara merubah warna background dan warna font hanya dengan mengklik tombol.

ketik kode berikut :

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>objek document</title>
</head>
<body>
  <script lang="javascript">
    function ubahWarnaLB(warna) {
      document.bgColor = warna;
    }
    function ubahWarnaLD(warna) {
      document.fgColor = warna;
    }
  </script>

  <h1>Test</h1>
  <form>
    <input type="button" value="Latar Belakang Hijau" onclick="ubahWarnaLB('green')">
    <input type="button" value="Latar Belakang Putih" onclick="ubahWarnaLB('white')">
    <input type="button" value="teks kuning" onclick="ubahWarnaLD('yellow')">
    <input type="button" value="teks biru" onclick="ubahWarnaLD('blue')">
  </form>
  <script lang="javascript">
    document.write("dimodifikasi terakhir pada " + document.lastModified);
  </script>
</body>
</html>
![Screenshot (212)](https://user-images.githubusercontent.com/101470912/163549706-87471258-5f57-4d78-ab35-2e4dedf0fdbe.png)
Lihat hasilnya di browser :
![Screenshot (213)](https://user-images.githubusercontent.com/101470912/163549830-69074503-e5ca-4eff-a12d-38f155944f15.png)


## 11. HTML DOM
Kali ini kita akan memuat program yang menghasilkan jumlah, masukan kode berikut :

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Daftar menu</title>
  <script>
    function hitung(ele) {
      var total = document.getElementById('total').value;
          total = (total ? parseInt(total) : 0);
      var harga = 0;

      if (ele.checked) {
        harga = ele.value;
        total += parseInt(harga);
      } 
      else {
        harga = ele.value;
        if (total > 0)
            total -= parseInt(harga);
      }
      document.getElementById('total').value = total;
    }
  </script>
</head>
<body>
  <h1>Daftar Menu Makanan</h1>
  <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);" />Ayam Goreng Rp. 5000</label><br>
  <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);" />Tempe Goreng Rp. 500</label><br>
  <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);" />Telur Dadar Rp. 2.500</label><br>
  <strong>Total Bayar: Rp. <input id="total" type="text"/></strong>
</body>
</html>
![Screenshot (215)](https://user-images.githubusercontent.com/101470912/163549945-1a626061-383c-4d29-9166-25acea24d667.png)
hasilnya akan seperti berikut :
![Screenshot (216)](https://user-images.githubusercontent.com/101470912/163550016-4e55c18e-c60e-431e-9b5d-3960dd0c7271.png)


## B. TUGAS
Diperintahkan untuk membuat script untuk melakukan validasi pada sebuah form. saya membuat form tersebut dengan kode seperti berikut :

![Screenshot (220)](https://user-images.githubusercontent.com/101470912/163550108-581cab5d-7eec-4ab5-b276-a37d3df7dce2.png)
Disini agar tampilan form menarik, saya tambahkan juga CSS. Seperti berikut :

![Screenshot (224)](https://user-images.githubusercontent.com/101470912/163551553-758bb23c-2b7c-4eb0-9517-b1501ed4f401.png)

Dan hasilnya seperti berikut
![Screenshot (221)](https://user-images.githubusercontent.com/101470912/163550263-d8925d0f-4079-44d2-9e1e-d12846631ead.png)

Karena Form yang dibikin adalah Form Validasi, jika ada kekurangan pada pengisinan data maka tampilannya akan seperti ini :
![Screenshot (225)](https://user-images.githubusercontent.com/101470912/163552179-c8f9ef92-31b6-4ac4-8a42-12ffeef16f50.png)

# terima kasih
![download](https://user-images.githubusercontent.com/101470912/163552289-62f3af2c-83ad-4068-b26d-4cada1b9c395.jpg)


