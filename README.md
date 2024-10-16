# Praktikum 2 OOP
## Pertemuan 4
### Nama : Yusdiansyah Andika Haryo Saputra
### NIM  : 31231650
### Kelas: TI.23.A.6

## Enkapsulasi
  Enkapsulasi adalah salah satu konsep yang sangat penting. Enkapsulasi memungkinkan para pengembang untuk mengatur dan menyembunyikan implementasi internal suatu objek, sementara memungkinkan interaksi dengan objek tersebut melalui antarmuka yang ditentukan dengan baik.

# Belum Selesai!
```java
package pert4oop;

#SEBENTAR!
public class person {
    private String Nama;
    private String JenisKelamin;
    private int Umur;

    public void setNama(String nama){
        this.Nama = nama;
    }

    public void setJenisKelamin(String jeniskelamin){
        this.JenisKelamin = jeniskelamin;
    }

    public void setUmur(int umur){
        this.Umur = umur;
    }

    public String getNama(){
        return this.Nama;
    }

    public String getJenisKelamin(){
        return this.JenisKelamin;
    }
    
    public int getUmur(){
        return this.Umur;
    }
}
```
```java
package pert4oop;

public class Panggil {
    public static void main(String[] args) {
        person Anton = new person();
        person Riko = new person();

        Anton.setNama("Anton");
        Anton.setUmur(19);
        Anton.setJenisKelamin("Laki-laki");

        Riko.setNama("Riko");
        Riko.setUmur(17);
        Riko.setJenisKelamin("Perempuan");

        System.out.println(Anton.getNama()+" adalah anak "+Anton.getJenisKelamin()+" berumur "+Anton.getUmur()+" tahun.");
        System.out.println(Riko.getNama()+" adalah anak "+Riko.getJenisKelamin()+" berumur "+Riko.getUmur()+" tahun.");
    }
}
```
