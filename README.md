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


## B. TUGAS
Diperintahkan untuk membuat script untuk melakukan validasi pada sebuah form. saya membuat form tersebut dengan kode seperti berikut :
