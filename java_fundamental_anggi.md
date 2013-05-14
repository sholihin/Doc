# Konsep OOP dan JAVA #

## Pengertian Java ##

Apa itu Java?? Java adalah sebuah bahasa pemrograman pada komputer sama seperti pendahulunya c++ .
Bahasa pemrograman ini dikembangkan oleh `Sun microsystems` yang dikembangkan pada `tahun 1995` .
Awalnya java diciptakan pada `tahun 1991` oleh `Patrick Naughton, Mike Sheridan , James Gosling dan Bill Joy` beserta programer dari `Sun Microsystems` .
Uniknya nama java diambil dari nama pulau `Jawa` ( bahasa inggris dari jawa ) karena `James Gosling` si `"Bapak Java"` menyukai kopi tubruk yang berasal dari pulau `Jawa` .
Jadi kita perlu berbangga menjadi warga negara Indonesia .

Java sendiri merupakan bahasa pemrograman yang berbasis `OOP` atau kepanjangan dari `Object Oriented Programming` yang artinya adalah
sebuah cara pandang ( `paradigma` ) dalam memecahkan masalah di dunia nyata dianalogikan kedalam bentuk `object` dan `struktur data`
yang didalamnya terdapat kumpulan `item data` disebut `variable` dan `method/fungsi` yang saling berinteraksi dalam sebuah struktur program.

Pemrograman Berorientasi Objek (Object Oriented Programming/OOP) merupakan pemrograman yang berorientasikan kepada objek,
dimana semua data dan fungsi dibungkus dalam class-class atau object-object. Setiap object dapat menerima pesan, memproses data, mengirim, menyimpan dan memanipulasi data.
Beberapa object berinteraksi dengan saling memberikan informasi satu terhadap yang lainnya.
Masing-masing object harus berisikan informasi mengenai dirinya sendiri dan dapat dihubungkan dengan Object yang lain.
Jadi, secara mudah OOP dapat disimpulkan sebagai suatu teknik atau metode untuk menangani kompleksitas pembuatan program.
Jika mengikuti aturan-aturan dalam metode tersebut maka program yang dibuat akan lebih mudah dikembangkan.
Sedikit perbandingan tambahan dengan bahasa C dan C++, Java banyak mewarisi konsep orientasi objek dari C++ namun dengan menghilangkan aspek-aspek kerumitan dalam bahasa C++ tanpa mengurangi kekuatannya.
Hal ini mempermudah programer pemula untuk mempelajari Java namun mengurangi keleluasaan programer berpengalaman dalam mengutak-atik sebuah program.
Di balik kemudahan yang ditawarkan Java, luasnya fasilitas library Java sendiri membuat seorang programer membutuhkan waktu yang tidak singkat untuk dapat menguasai penggunaan library-library tersebut.

Java memiliki :
 
- class

```
public class MainClass {
    
}
```
- package dan

```
package latihan.java.fundamental;
```
- objek

```
mahasiswa a = new mahasiswa();
```

### Sebagai contoh : ### 
- class itu ibarat cetakan kue atau loyang
- objek adalah hasil dari loyang tersebut
- Constructor adalah 

# komponen yg ada pada class :
- porperti/variabel        --> private String nama;
- Constructor      --> bisa lebih dari 1 
- method		  --> berikut contohnya

``` java
public String getNpm(){

}
```

ada function dan prosedur

- `void` tidak memberi nilai balik   --> contoh : seperti save, update dan delete di php
- `return` memberikan nilai balik    --> contoh : menyuruh orang mengambilkan sepatu , nanti dia akan membawakan hasil untuk kita
- 

# cara menginstankan suatu class   --> mahasiswa a = new mahasiswa();
# didalam suatu class secara default memiliki suatu Constructor 
# parameter adalah untuk memberi uang ketika minta tolong beli roti
- kalo mau buat Constructor lebih dari 1 harus menyertakan Constructor yang di buat secara default oleh java-nya 
contoh secara default : 

``` java
public Mahasiswa() {

}
```

maksud dari `./titik` pada object.setNama("Dety");

# Contoh : Source Code MainClass.java #

``` java
public class MainClass {

    public static void main(String[] args) {
        String npm = "123";
        String nama = "sholihin";
        String alamat = "Bogor";

        Mahasiswa mahasiswa1 = new Mahasiswa();
        System.out.println("Mahasiswa 1");
        System.out.println("============================");

        mahasiswa1.setNpm("123");
        mahasiswa1.setNama("sholihin");
        mahasiswa1.setAlamat("Bogor");
        System.out.println(mahasiswa1.getNpm());
        System.out.println(mahasiswa1.getNama());
        System.out.println(mahasiswa1.getAlamat());
        
        System.out.println();
        
        Mahasiswa mahasiswa2 = new Mahasiswa(npm, nama, alamat);
        System.out.println("Mahasiswa 2");
        System.out.println("============================");
        
        System.out.println(mahasiswa2.getNpm());
        System.out.println(mahasiswa2.getNama());
        System.out.println(mahasiswa2.getAlamat());
        

    }
}
```
# Contoh : Source Code Mahasiswa.java #

``` java
public class Mahasiswa {
    private String npm;
    private String nama;
    private String alamat;

    // ini construktor yang di buat secara manual, butuh default Constructor : public Mahasiswa() { }
    public Mahasiswa() {
    }
    
    public Mahasiswa(String npm, String nama, String alamat){
        this.npm = npm;
        this.nama = nama;
        this.alamat = alamat;
        
    }
    //end Constructor manual

    public String getAlamat() {
        return alamat;
    }

    public void setAlamat(String alamat) {
        this.alamat = alamat;
    }

    public String getNama() {
        return nama;
    }

    public void setNama(String nama) {
        this.nama = nama;
    }

    public String getNpm() {
        return npm;
    }

    public void setNpm(String npm) {
        this.npm = npm;
    }
    
    
}
```

- extends = merupakan turunan kelas, atau pewarisan class

# Contoh : Siswa.java #

``` java
public class Siswa extends Mahasiswa {
       
}
```

class di atas telah memiliki turunan sifat dari class Mahasiswa

- fungsi @Override
untuk menghilangkan error pada class Siswa jika ada method yang sama.





