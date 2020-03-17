"C:\Program Files\Android\Android Studio\jre\bin\java.exe" -Dkotlin.repl.ideMode=true -Dfile.encoding=UTF-8 -classpath "C:\Program Files\Android\Android Studio\lib\idea_rt.jar;C:\Users\cscharff\AppData\Local\Temp\classpath1642461106.jar" com.intellij.rt.execution.CommandLineWrapper C:\Users\cscharff\AppData\Local\Temp\classpath1642461106.jar org.jetbrains.kotlin.cli.jvm.K2JVMCompiler

You’re running the REPL with outdated classes: Build module 'app' and restart

Welcome to Kotlin version 1.3.70 (JRE 1.8.0_212-release-1586-b04)
Type :help for help, :quit for quit

fun printHello(){
    println("Hello World!")
}

printHello()
Hello World!

1+1
res1: kotlin.Int = 2

50/3
res2: kotlin.Int = 16

3.5*2
res3: kotlin.Double = 7.0

50.3/3.0
res4: kotlin.Double = 16.766666666666666

1.0/3.0
res5: kotlin.Double = 0.3333333333333333

2.times(3)
res6: kotlin.Int = 6

val x = 6

val y:Int = 6

println(x)
6

println(y)
6

x=5
error: val cannot be reassigned
x=5
^

var z = 10
z = 20

println(z)
20

x.toString()
res14: kotlin.String = 6

var s = x.toString()
println(s)
6

println(6 is String)
error: incompatible types: String and Int
println(6 is String)
             ^

println("6" is String)
true

val s1:String = "hhh"

val d:Double = 5
error: the integer literal does not conform to the expected type Double
val d:Double = 5
               ^

val d:Double = 5.0

val d1:Double = 5.toDouble()

val i = 5

println("J'ai $i paires de chaussettes ")
J'ai 5 paires de chaussettes 

val j = 10
println("J'ai ${i+j} paires de chaussettes")
J'ai 15 paires de chaussettes

sqrt(d1)
error: unresolved reference: sqrt
sqrt(d1)
^

import kotlin.math
sqrt(d1)
error: packages cannot be imported
import kotlin.math
              ^
error: unresolved reference: sqrt
sqrt(d1)
^

import kotlin.math.sqrt

sqrt(5.0)
res27: kotlin.Double = 2.23606797749979

kotlin.math.PI
res28: kotlin.Double = 3.141592653589793

val nb1 = 50
val nb2 = 60
if (nb1 > nb2){
    println("Tres bien")
} else {
    println("passable")
}
passable

//range
if(nb1 in 1.100){
    println(nb1)
}
error: unresolved reference. None of the following candidates is applicable because of receiver type mismatch: 
public inline operator fun <T : Any, R : Iterable<Int>> ???.contains(element: Int?): Boolean where R : ClosedRange<Int> defined in kotlin.ranges
public operator fun <T> Array<out Int>.contains(element: Int): Boolean defined in kotlin.collections
public operator fun BooleanArray.contains(element: Boolean): Boolean defined in kotlin.collections
public operator fun ByteArray.contains(element: Byte): Boolean defined in kotlin.collections
public operator fun CharArray.contains(element: Char): Boolean defined in kotlin.collections
public operator fun CharSequence.contains(char: Char, ignoreCase: Boolean = ...): Boolean defined in kotlin.text
public operator fun CharSequence.contains(other: CharSequence, ignoreCase: Boolean = ...): Boolean defined in kotlin.text
public inline operator fun CharSequence.contains(regex: Regex): Boolean defined in kotlin.text
public operator fun DoubleArray.contains(element: Double): Boolean defined in kotlin.collections
public operator fun FloatArray.contains(element: Float): Boolean defined in kotlin.collections
public operator fun IntArray.contains(element: Int): Boolean defined in kotlin.collections
public operator fun LongArray.contains(element: Long): Boolean defined in kotlin.collections
public operator fun ShortArray.contains(element: Short): Boolean defined in kotlin.collections
public operator fun <T> Iterable<Int>.contains(element: Int): Boolean defined in kotlin.collections
public inline operator fun <K, V> Map<out Int, ???>.contains(key: Int): Boolean defined in kotlin.collections
public inline operator fun CharRange.contains(element: Char?): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Byte>.contains(value: Double): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Byte>.contains(value: Float): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Byte>.contains(value: Int): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Byte>.contains(value: Long): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Byte>.contains(value: Short): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Double>.contains(value: Byte): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Double>.contains(value: Float): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Double>.contains(value: Int): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Double>.contains(value: Long): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Double>.contains(value: Short): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Float>.contains(value: Byte): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Float>.contains(value: Double): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Float>.contains(value: Int): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Float>.contains(value: Long): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Float>.contains(value: Short): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Int>.contains(value: Byte): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Int>.contains(value: Double): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Int>.contains(value: Float): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Int>.contains(value: Long): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Int>.contains(value: Short): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Long>.contains(value: Byte): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Long>.contains(value: Double): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Long>.contains(value: Float): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Long>.contains(value: Int): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Long>.contains(value: Short): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Short>.contains(value: Byte): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Short>.contains(value: Double): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Short>.contains(value: Float): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Short>.contains(value: Int): Boolean defined in kotlin.ranges
public operator fun ClosedRange<Short>.contains(value: Long): Boolean defined in kotlin.ranges
public inline operator fun IntRange.contains(element: Int?): Boolean defined in kotlin.ranges
public inline operator fun LongRange.contains(element: Long?): Boolean defined in kotlin.ranges
public operator fun UIntRange.contains(value: UByte): Boolean defined in kotlin.ranges
public inline operator fun UIntRange.contains(element: UInt?): Boolean defined in kotlin.ranges
public operator fun UIntRange.contains(value: ULong): Boolean defined in kotlin.ranges
public operator fun UIntRange.contains(value: UShort): Boolean defined in kotlin.ranges
public operator fun ULongRange.contains(value: UByte): Boolean defined in kotlin.ranges
public operator fun ULongRange.contains(value: UInt): Boolean defined in kotlin.ranges
public inline operator fun ULongRange.contains(element: ULong?): Boolean defined in kotlin.ranges
public operator fun ULongRange.contains(value: UShort): Boolean defined in kotlin.ranges
public operator fun <T> Sequence<Int>.contains(element: Int): Boolean defined in kotlin.sequences
if(nb1 in 1.100){
       ^

if(nb1 in 1..100){
    println(nb1)
}
50

if(nb1 in 1..100){
    println("nb1 est entre 1 et 100")
}
nb1 est entre 1 et 100

when(nb1){
    0 -> println("Zero")
    in 1..100 -> println("Entre 1 et 100")
    else -> println("Superieur a 101 (strictement)")
}
Entre 1 et 100

when(nb1){
    0 -> println("Zero")
    in 1..100 -> println("Entre 1 et 100")
    else -> println("Pas dans l'intervalle considere")
}
Entre 1 et 100

var e:Int = null
error: null can not be a value of a non-null type Int
var e:Int = null
            ^

var e:Int? = null

if (e!=null){
    println("e n est pas null")
} else {
    println("e est null")
}
e est null

e.toString()
res38: kotlin.String = null

if(e != null){
    printl("e.method() est ok")
}
error: unresolved reference: printl
    printl("e.method() est ok")
    ^

if(e != null){
    println("e.method() est ok")
}

var h = 10
h?.dec()
res41: kotlin.Int = 9

//array
//list

var school = listOf("Thies","Bambey","Dakar")
println(school)
[Thies, Bambey, Dakar]

var schoolm = mutableListOf("Ziguinchor","St Louis")
println(schoolm)
[Ziguinchor, St Louis]

schoolm.remove("Ziguinchor")
println(schoolm)
[St Louis]

school.remove("Thies")
error: unresolved reference. None of the following candidates is applicable because of receiver type mismatch: 
public inline fun <T> MutableCollection<out String>.remove(element: String): Boolean defined in kotlin.collections
public inline fun <T> MutableList<???>.remove(index: Int): ??? defined in kotlin.collections
public inline fun <K, V> MutableMap<out String, ???>.remove(key: String): ??? defined in kotlin.collections
school.remove("Thies")
       ^

for(element in school){
    println(element)
}
ThiesBambeyDakar

for(element in school){
    println(element+" ")
}
Thies Bambey Dakar 

var newschool = arrayOf("ISM", 1, "SupDeco")
println(newschool)
[Ljava.lang.Object;@5904c3dc

println(newschool[0])
ISM

for(elt in newschool){
    println(elt + " ")
}
error: unresolved reference. None of the following candidates is applicable because of receiver type mismatch: 
public inline operator fun BigDecimal.plus(other: BigDecimal): BigDecimal defined in kotlin
public inline operator fun BigInteger.plus(other: BigInteger): BigInteger defined in kotlin
public operator fun <T> Array<???>.plus(elements: Array<out ???>): Array<???> defined in kotlin.collections
public operator fun <T> Array<???>.plus(elements: Collection<???>): Array<???> defined in kotlin.collections
public operator fun <T> Array<String>.plus(element: String): Array<String> defined in kotlin.collections
public operator fun BooleanArray.plus(element: Boolean): BooleanArray defined in kotlin.collections
public operator fun BooleanArray.plus(elements: BooleanArray): BooleanArray defined in kotlin.collections
public operator fun BooleanArray.plus(elements: Collection<Boolean>): BooleanArray defined in kotlin.collections
public operator fun ByteArray.plus(element: Byte): ByteArray defined in kotlin.collections
public operator fun ByteArray.plus(elements: ByteArray): ByteArray defined in kotlin.collections
public operator fun ByteArray.plus(elements: Collection<Byte>): ByteArray defined in kotlin.collections
public inline operator fun Char.plus(other: String): String defined in kotlin.text
public operator fun CharArray.plus(element: Char): CharArray defined in kotlin.collections
public operator fun CharArray.plus(elements: CharArray): CharArray defined in kotlin.collections
public operator fun CharArray.plus(elements: Collection<Char>): CharArray defined in kotlin.collections
public operator fun DoubleArray.plus(element: Double): DoubleArray defined in kotlin.collections
public operator fun DoubleArray.plus(elements: DoubleArray): DoubleArray defined in kotlin.collections
public operator fun DoubleArray.plus(elements: Collection<Double>): DoubleArray defined in kotlin.collections
public operator fun FloatArray.plus(element: Float): FloatArray defined in kotlin.collections
public operator fun FloatArray.plus(elements: FloatArray): FloatArray defined in kotlin.collections
public operator fun FloatArray.plus(elements: Collection<Float>): FloatArray defined in kotlin.collections
public operator fun IntArray.plus(element: Int): IntArray defined in kotlin.collections
public operator fun IntArray.plus(elements: IntArray): IntArray defined in kotlin.collections
public operator fun IntArray.plus(elements: Collection<Int>): IntArray defined in kotlin.collections
public operator fun LongArray.plus(element: Long): LongArray defined in kotlin.collections
public operator fun LongArray.plus(elements: LongArray): LongArray defined in kotlin.collections
public operator fun LongArray.plus(elements: Collection<Long>): LongArray defined in kotlin.collections
public operator fun ShortArray.plus(element: Short): ShortArray defined in kotlin.collections
public operator fun ShortArray.plus(elements: ShortArray): ShortArray defined in kotlin.collections
public operator fun ShortArray.plus(elements: Collection<Short>): ShortArray defined in kotlin.collections
public operator fun String?.plus(other: Any?): String defined in kotlin
public operator fun String?.plus(other: Any?): String defined in kotlin
public inline operator fun UByteArray.plus(element: UByte): UByteArray defined in kotlin.collections
public inline operator fun UByteArray.plus(elements: UByteArray): UByteArray defined in kotlin.collections
public operator fun UByteArray.plus(elements: Collection<UByte>): UByteArray defined in kotlin.collections
public inline operator fun UIntArray.plus(element: UInt): UIntArray defined in kotlin.collections
public inline operator fun UIntArray.plus(elements: UIntArray): UIntArray defined in kotlin.collections
public operator fun UIntArray.plus(elements: Collection<UInt>): UIntArray defined in kotlin.collections
public inline operator fun ULongArray.plus(element: ULong): ULongArray defined in kotlin.collections
public inline operator fun ULongArray.plus(elements: ULongArray): ULongArray defined in kotlin.collections
public operator fun ULongArray.plus(elements: Collection<ULong>): ULongArray defined in kotlin.collections
public inline operator fun UShortArray.plus(element: UShort): UShortArray defined in kotlin.collections
public inline operator fun UShortArray.plus(elements: UShortArray): UShortArray defined in kotlin.collections
public operator fun UShortArray.plus(elements: Collection<UShort>): UShortArray defined in kotlin.collections
public operator fun <T> Collection<???>.plus(elements: Array<out ???>): List<???> defined in kotlin.collections
public operator fun <T> Collection<???>.plus(elements: Iterable<???>): List<???> defined in kotlin.collections
public operator fun <T> Collection<???>.plus(elements: Sequence<???>): List<???> defined in kotlin.collections
public operator fun <T> Collection<String>.plus(element: String): List<String> defined in kotlin.collections
public operator fun <T> Iterable<???>.plus(elements: Array<out ???>): List<???> defined in kotlin.collections
public operator fun <T> Iterable<???>.plus(elements: Iterable<???>): List<???> defined in kotlin.collections
public operator fun <T> Iterable<???>.plus(elements: Sequence<???>): List<???> defined in kotlin.collections
public operator fun <T> Iterable<String>.plus(element: String): List<String> defined in kotlin.collections
public operator fun <K, V> Map<out ???, ???>.plus(pairs: Array<out Pair<???, ???>>): Map<???, ???> defined in kotlin.collections
public operator fun <K, V> Map<out ???, ???>.plus(pair: Pair<???, ???>): Map<???, ???> defined in kotlin.collections
public operator fun <K, V> Map<out ???, ???>.plus(pairs: Iterable<Pair<???, ???>>): Map<???, ???> defined in kotlin.collections
public operator fun <K, V> Map<out ???, ???>.plus(map: Map<out ???, ???>): Map<???, ???> defined in kotlin.collections
public operator fun <K, V> Map<out ???, ???>.plus(pairs: Sequence<Pair<???, ???>>): Map<???, ???> defined in kotlin.collections
public operator fun <T> Set<???>.plus(elements: Array<out ???>): Set<???> defined in kotlin.collections
public operator fun <T> Set<???>.plus(elements: Iterable<???>): Set<???> defined in kotlin.collections
public operator fun <T> Set<???>.plus(elements: Sequence<???>): Set<???> defined in kotlin.collections
public operator fun <T> Set<String>.plus(element: String): Set<String> defined in kotlin.collections
public operator fun <T> Sequence<???>.plus(elements: Array<out ???>): Sequence<???> defined in kotlin.sequences
public operator fun <T> Sequence<???>.plus(elements: Iterable<???>): Sequence<???> defined in kotlin.sequences
public operator fun <T> Sequence<???>.plus(elements: Sequence<???>): Sequence<???> defined in kotlin.sequences
public operator fun <T> Sequence<String>.plus(element: String): Sequence<String> defined in kotlin.sequences
    println(elt + " ")
                ^

var newschool = arrayof("A", "B")
for(elt in newschool){
    println(elt + " ")
}
error: unresolved reference: arrayof
var newschool = arrayof("A", "B")
                ^

var newschool = arrayOf("A", "B")
for(elt in newschool){
    println(elt + " ")
}
A B 

println(java.util.Arrays.newschool)
error: unresolved reference: newschool
println(java.util.Arrays.newschool)
                         ^

println(java.util.Arrays.toString(newschool))
[A, B]

var myA = Array(5){it*2}

println(myA)
[Ljava.lang.Integer;@1d70dc00

println(java.util.Arrays.toString(myA))
[0, 2, 4, 6, 8]

fun printHello(){
    println("Hello World!")
}

fun main(args:Array<String>){
    printHello()
}

main()
error: no value passed for parameter 'args'
main()
     ^

main(arrayOf("1"))
Hello World!

fun main(args:Array<String>){
    printHello()
    println(args[0])
}
main(arrayOf("1"))
Hello World!1

fun f(x:String):String {
    return "une chaine de caracteres"
}

f("a")
res63: kotlin.String = une chaine de caracteres

fun g(x:String, y:Int):Int {
    return 5
}
g("a",10)
res64: kotlin.Int = 5

fun h(x:String, y:Int){
    return y+1
}
h("jj")
error: type mismatch: inferred type is Int but Unit was expected
    return y+1
           ^
error: no value passed for parameter 'y'
h("jj")
      ^

fun h(x:String, y:Int){
    return y+1
}
error: type mismatch: inferred type is Int but Unit was expected
    return y+1
           ^

fun h(x:String, y:Int):Int{
    return y+1
}

h("jj")
error: no value passed for parameter 'y'
h("jj")
      ^

h("jj",10)
res69: kotlin.Int = 11

fun fish(day:String):String{
    return when(day){
        "Monday" -> "Capitaine"
        else -> "Yaboy"
    }
}

fish("Tuesday")
res71: kotlin.String = Yaboy

fun eatFish(day:String, holiday:String, regime:String){
    return when{
        day == "Friday" -> true
        holiday == "Eastern" -> true
        regime == "Vegetarian" -> true
        else -> false
    }
}
eatFish(day="Monday","","")
error: the boolean literal does not conform to the expected type Unit
        day == "Friday" -> true
                           ^
error: the boolean literal does not conform to the expected type Unit
        holiday == "Eastern" -> true
                                ^
error: the boolean literal does not conform to the expected type Unit
        regime == "Vegetarian" -> true
                                  ^
error: the boolean literal does not conform to the expected type Unit
        else -> false
                ^
error: mixing named and positioned arguments is not allowed
eatFish(day="Monday","","")
                     ^
error: mixing named and positioned arguments is not allowed
eatFish(day="Monday","","")
                        ^
error: no value passed for parameter 'holiday'
eatFish(day="Monday","","")
                          ^
error: no value passed for parameter 'regime'
eatFish(day="Monday","","")
                          ^

fun eatFish(day:String, holiday:String, regime:String):Boolean{
    return when{
        day == "Friday" -> true
        holiday == "Eastern" -> true
        regime == "Vegetarian" -> true
        else -> false
    }
}
eatFish(day="Monday","","")
error: mixing named and positioned arguments is not allowed
eatFish(day="Monday","","")
                     ^
error: mixing named and positioned arguments is not allowed
eatFish(day="Monday","","")
                        ^
error: no value passed for parameter 'holiday'
eatFish(day="Monday","","")
                          ^
error: no value passed for parameter 'regime'
eatFish(day="Monday","","")
                          ^

eatFish("Monday","","")
error: unresolved reference: eatFish
eatFish("Monday","","")
^

fun eatFish(day:String, holiday:String, regime:String):Boolean{
    return when{
        day == "Friday" -> true
        holiday == "Eastern" -> true
        regime == "Vegetarian" -> true
        else -> false
    }
}

println(eatFish("M","",""))
false

println(eatFish("Friday","",""))
true

fun eatFish(day:String, holiday:String ="", regime:String=""):Boolean{
    return when{
        day == "Friday" -> true
        holiday == "Eastern" -> true
        regime == "Vegetarian" -> true
        else -> false
    }
}
eatFish("Friday")
res78: kotlin.Boolean = true

fun isHot(temp:Int):Boolean{
    if (temp > 25){
        return true
    } else {
        false
    }
}
error: a 'return' expression required in a function with a block body ('{...}')
}
^

fun isHot(temp:Int):Boolean{
    if (temp > 25){
        return true
    } else {
        return false
    }
}

fun isHot(temp:Int):Boolean{return temp>25}

fun isHot(temp:Int):Unit{
    println("Il fait chaud")
}

val waterFilter = {dirty:Int -> dirty/2}
println(waterFilter(15))
7

fun isHot(temp:Int){
    println("Il fait chaud")
}

//higher order function
fun updateDirty(dirty:Int, operation:Int->Int):Int{
    return operation(dirty)
}

fun ff(x:Int):Int{
    return 10
}

fun gg(x:Int):Int{
    return x+1
}

updateDirty(10, ff)
updateDirty(10,gg)
error: expecting comma or ')'
fun updateDirty(dirty:Int, operation:Int->Int):Int{
                                        ^
error: expecting ')'
fun updateDirty(dirty:Int, operation:Int->Int):Int{
                                        ^
error: expecting an element
fun updateDirty(dirty:Int, operation:Int->Int):Int{
                                             ^
error: expecting an element
fun updateDirty(dirty:Int, operation:Int->Int):Int{
                                              ^

fun updateDirty(dirty:Int, operation:Int->Int):Int{
    return operation(dirty)
}
error: expecting comma or ')'
fun updateDirty(dirty:Int, operation:Int->Int):Int{
                                        ^
error: expecting ')'
fun updateDirty(dirty:Int, operation:Int->Int):Int{
                                        ^
error: expecting an element
fun updateDirty(dirty:Int, operation:Int->Int):Int{
                                             ^
error: expecting an element
fun updateDirty(dirty:Int, operation:Int->Int):Int{
                                              ^

fun updateDirty(dirty:Int, operation:(Int)->Int):Int{
    return operation(dirty)
}

//higher order function


fun ff(x:Int):Int{
    return 10
}

fun gg(x:Int):Int{
    return x+1
}

updateDirty(10, ff)
error: function invocation 'ff(...)' expected
updateDirty(10, ff)
                ^
error: no value passed for parameter 'x'
updateDirty(10, ff)
                ^
error: type mismatch: inferred type is Int but (Int) -> Int was expected
updateDirty(10, ff)
                ^

updateDirty(10,ff(10))
error: unresolved reference: ff
updateDirty(10,ff(10))
               ^

fun updateDirty(dirty:Int, operation:(Int)->Int):Int{
    return operation(dirty)
}

fun gg(x:Int):Int{
    return x+1
}

gg(5)
res92: kotlin.Int = 6