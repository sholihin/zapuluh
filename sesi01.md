## Sesi 1 ##

#### Java Basic ####

Pemrograman **Java** dapat didefinisikan sebagai koleksi benda-benda yang berkomunikasi. 
Mari kita secara singkat pelajari **class**, **object**, **methods** dan **instance variables** dibawah ini.

1. **Object** - Object memiliki kondisi dan perilaku. 
	Contoh dalam kehidupan nyata adalah : 
		Seekor kucing memiliki warna, nama dan juga berkembang biak serta memiliki perilaku, mengeong dan makan. 
		Begitu juga dengan Object yang adalah instance dari suatu **Class**.

2. **Class** - Class **A** dapat didefinisikan sebagai template / blue print yang menggambarkan perilaku atau
	menyatakan bahwa sebuah Object adalah dukungan dari Class itu sendiri.

3. **Methods** - Methods pada dasarnya adalah perilaku. Sebuah Class dapat berisi banyak Methods. 
	Pada Methods-lah logika ditulis, data dimanipulasi dan semua tindakan yang dieksekusi.

4. **Instance Variables** - Setiap object memiliki perangkat yang khas atau unik dari Instance Variables. 
	Setiap object dibuat dengan nilai dan itulah tugas dari Instance Variables.


### Memulai Membuat Pemrograman Java ###

Mari kita lihat kode sederhana yang akan mencetak kata `**Hello World**`.

``` java
public class MyFirstJavaProgram {

   / * Ini adalah program java pertama saya.  
    * Ini akan mencetak 'Hello World' sebagai output
    * /

    public static void main(String []args) {
       System.out.println("Hello World"); // mencetak Hello World 
    }
} 
```


Mari kita melihat bagaimana untuk menyimpan file, mengkompilasi dan menjalankan program. 
Silakan ikuti langkah-langkah berikut:

1. Buka notepad dan tambahkan kode seperti di atas.
2. Simpan file dengan nama: **MyFirstJavaProgram.java**.
3. Buka **command prompt** dan masuk ke direktori tempat Anda menyimpan Class tadi. Asumsikan di **C:\belajarJAVA\**.
4. Ketik perintah **javac MyFirstJavaProgram.java** dan tekan **enter** untuk mengkompilasi kode Anda. 
5. Jika tidak ada kesalahan dalam kode anda, maka anda dapat mengketikkan **java MyFirstJavaProgram** untuk menjalankan program Anda.	

Jika tidak terjadi kesalahan maka akan muncul output seperti dibawah ini :

``` cmd
C : > javac MyFirstJavaProgram.java
C : > java MyFirstJavaProgram 
Hello World
```


### Basic Syntax ###

Hal-hal berikut sangat penting untuk diingat dalam pemograman java.

1. **Case Sensitivity** - Java adalah bahasa pemrograman yang memiliki sifat case sensitive yang berarti 
	identifier Hello dan halo akan memiliki arti yang berbeda di Java.
	
2. **Class Names** - Untuk semua nama Class huruf pertama harus di Upper Case. 
	Jika terdapat lebih dari satu kata yang digunakan untuk membuat nama Class maka masing-masing kata dalam huruf pertama harus di Upper Case.
	Contoh : **MyFirstJavaClass Class**.
	
3. **Method Names** - Semua nama Method harus dimulai dengan huruf Lower Case. 
	Jika Method dibuat dengan susunan beberapa kata-kata, maka huruf pertama setiap kata dalam itu harus di Upper Case. 
	Contoh public void myMethodName ().
	
4. 


