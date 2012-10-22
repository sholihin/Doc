# java memiliki OOP (Object Oriented Programming)
# java memilik 
- class
- package
- objek		--> mahasiswa a = new mahasiswa();

contoh : 
- class itu ibarat cetakan kue / loyang
- objek adalah hasil dari cetakan kue tersebut
- contruktor adalah 

# komponen yg ada pada class :
- porperti/variabel        --> private String nama;
- contruktor      --> bisa lebih dari 1 
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
# didalam suatu class secara default memiliki suatu contruktor 
# parameter adalah untuk memberi uang ketika minta tolong beli roti
- kalo mau buat contruktor lebih dari 1 harus menyertakan contruktor yang di buat secara default oleh java-nya 
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

    // ini construktor yang di buat secara manual, butuh default contruktor : public Mahasiswa() { }
    public Mahasiswa() {
    }
    
    public Mahasiswa(String npm, String nama, String alamat){
        this.npm = npm;
        this.nama = nama;
        this.alamat = alamat;
        
    }
    //end contruktor manual

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





