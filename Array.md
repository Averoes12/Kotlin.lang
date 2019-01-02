# Array 

Dalam kotlin penulisan array 

1. Dengan menggunakan `intArrayOf`

	
    var arr =  intArrayOf(11,33,4)


    for (i in arr){

        println("this is $i")
    }

Hasil Output

	this is 11
	this is 33
	this is 4

Kita juga bisa merubah nya dengan method .set

	    var arr =  intArrayOf(11,33,4)

	    arr.set(1,7)//parameter pertama adalah nomer index dan yang kedua isi dari indesx

    for (i in arr){

        println("this is $i")
    }

Hasil Output

	this is 11
	this is 7
	this is 4

Kita juga bisa mengambil salah satu dari array dengan method .get


    var arr =  intArrayOf(11,33,4)
  
        println(arr.get(index = 2))

Hasil Output

	4

Kita bisa mengambil index yang terakhir dengan method .last 

	    var arr =  intArrayOf(11,33,4)
  
        println(arr.last())

Cara Membuat array yang kedua

	    var arr1 = IntArray(3)

        arr.set(0,3)
        arr.set(1,2)
        arr.set(2,4)


    for(i in arr){

        println("This is index ke $i")//yang kita print adalah variable i bukan arr

        }

   