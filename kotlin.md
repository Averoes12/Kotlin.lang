# kita bisa memasukkan class java ke kotlin

Pertama kita buat class java dulu

public class Tes {

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    private String name;

}

lalu kita buat file kotlin dan objek 


	import Learn.Tes

	fun main(args:Array<String>){

    var tes = Tes()//buat objek di kotlin tidak sesulit di java

    tes.name = "Daff"

    print(tes.name)

}

# Instance Objek dari class lain


	fun main(args:Array<String>){

    val kelas = Tes()//Instamce objek ke dalam file main

    kelas.name = "Bolt" //.name sama dengan setName pada java

    println("Your Head is ${kelas.name}")//kita perlu menggunakan {} untuk memasukkan sebuah object ke dalam print


# Memanggil fungsi dari kelas lain


    var ulang  = Repeat()

    ulang.looping()//memanggil fungsi dari class lain


}

# Lambda

Lambda adalah sebuah fungsi yang tidak dideklarasikan,lambda sangat berfungsi untuk memudahkan dalam menulis kode

cara penggunaan lambda

	val message = { println("Happy to learn Kotlin!") }

Pada contoh diatas kita telah membuat sebuah fungsi dan kita bisa memanggilnya dengan `message()`

	 val message = { params: String -> println(params) }

Kita juga bisa memberikan parameter,pada contoh diatas parameter nya bertipe string tanda panah pada contoh diatas digunakan untuk memisahkan antara parameter dan body kita bisa memanggil fungsi tersebut dengan `message("Kotlin is very simple")`


	val hitungLuas = { a: Int, b: Int -> a * b}

kita juga bisa memasukkan dua parameter,kita bisa me