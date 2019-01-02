# Percabangan di Kotlin

1. if 

contoh kode 


		var switch  = 1 

    	if (switch == 1) {

    	println("Switch On")
	}

2. if else


		var switch  = 0

    	if (switch == 1) 

    	println("Switch On")

    	else 
        
        print("Switch Off")

Hasil Output

	Switch Off

3. else if

		var switch  = 2

    if (switch == 1) 

    println("Switch On")

    else if (switch == 0)
        
        print("Switch Off")

    else 
        
        println("Error")

Hasil Output
		
		Error

4. when

		
    for (user in 0..2) {

        var Switch: Int = readLine()!!.toInt()

        when (Switch) {

            0 -> println("Switch On")

            1 -> println("Switch Off")

            else -> println("Error")

        }

    }

Kita bisa menuliskan if else seperti ini


       val T:Int = readLine()!!.toInt()

        val suhu = if(T < 50) "Temperature is Cold" else if(T >= 51 || T == 100 ) "Temperature is Warm" else "Temperature is Hot"

    println(suhu)
}