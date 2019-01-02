# Looping 

1. For

   for (user in 0..2) {

        var Switch: Int = readLine()!!.toInt()

        when (Switch) {

            0 -> println("Switch On")

            1 -> println("Switch Off")

            else -> println("Error")

        }

    }

Hasil output

	0
	Switch On
	0
	Switch On
	0
	Switch On

2. while
		var makan = 1

	    while(makan in 1..3){


        println("hari udah makan $makan Kali")

        makan++
    }

}

Hasil output

	hari udah makan 1 Kali
	hari udah makan 2 Kali
	hari udah makan 3 Kali