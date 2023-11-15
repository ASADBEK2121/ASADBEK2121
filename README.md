import java.util.*

fun main() {
    val input = Scanner(System.`in`)
    println("kartada qancha puliz bor")
    val umumiysuma = input.nextInt()
    println("1 pul yechish : 2 telfonga tolov: 3 gazga tolov ; 4  internetga tolov: ")
    val suma = input.nextInt()
    while (true)
        if (suma == 1){
        println(" PUL YECHISH BOLIMIGA HUSH KELIBSZ!! \n Summani kriting")
    val namber = input.nextInt()
    val ayirma = (umumiysuma-namber)-namber/100
        val qolgasumma = umumiysuma-(ayirma+namber)
        println("amalyot bajarilidi")
        println("qolgan summadan 1% ushlab qolindi = $qolgasumma so'm \n umumiy qolgan balans $ayirma so'm \n" +
                " AMALYOT MUVAFIQIYATLIBAJARILDI")
        println("            \n              ")
        }else if(suma ==2){
        println("telfonga tolov bo'limiga hush kelibsz!!  ")
        print("telfon raqamni kiriting +998  ")
         val telraqam = input.nextInt()
        println("summani kiriting")
        val pul = input.nextInt()
        val yechish =(umumiysuma-pul)-pul/100
   val balans = umumiysuma-(yechish+pul)
        println("qolgan summadan 1% ushlab qolindi =  $balans so'm  \n  umumiy karta balans = $yechish so'm \n" +
                " AMALYOT MUVAFIQIYATLIBAJARILDI")
        println("            \n              ")


    }else if (suma==3){
        println("GAZga tolov bo'limiga hush kelibsz!! ")
        print("gaz raqmini kiriting = ")
        val gazraqam = input.nextInt()
        println("tolov summani kiriting = ")
        val pul1 =input.nextInt()
         val hammasi = (umumiysuma -pul1)-pul1/100
        val balans2= umumiysuma-(pul1 + hammasi)
        println("qolgan summadan 1% ushlab qolindi = $balans2 so'm \n karta balans =  $hammasi so'm \n AMALYOT MUVAFIQIYATLIBAJARILDI")
        println("            \n              ")
    }else if (suma==4){
        println(" intenetga tolov bolimiga hush kelibsz!!")
        print("raqamni kriiting =  ")
        val pasword = input.nextInt()
        println("summani kriting")
        val summa= input.nextInt()
        val hammasi2 = (umumiysuma -summa)-summa/100
        val balans3= umumiysuma-(summa + hammasi2)
        val cashbak = summa *2/100
        println("qolgan summadan 1% ushlab qolindi = $balans3 som  \n karta balns = $hammasi2 som \n sizga  cashback  = $cashbak som berildi  " )
       println("cashback kartaga =  $cashbak som otkazildi \n hozirda sizning  cashback balansinggiz = $cashbak")
        println("amalyot muvafiqiyatli bahjarildi")
        println("            \n              ")
    }
else{
    println("amalyot bajrilmadi qaytadan urinib koring \n yoki bolimlari tog'ri tanlang")
}

}
