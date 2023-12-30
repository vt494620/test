# testimport kotlin.coroutines.*

fun <T> runBlocking(t: T): Any {

}

fun main() = runBlocking{
val a =async{
    println("I'computing part of the answer")
    6
}
    val b =async{
        println("I'computing part of the answer")
        7
    }
    println("the answer is ${a.await ()* b.await()}")


}

private fun Any.await(): Any {

}

fun async(function: () -> Int): Any {

}
