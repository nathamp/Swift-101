# Swift-101
Playing around in Playground. Nothing fancy to see here...





// Playground - noun: a place where people can play


import UIKit




// import Cocoa

/*
*
*
*

// import Cocoa

When you use the 'import Cocoa' command, what you're actually doing is loading up a library that has other properties for you to manipulate within this structure. Other libraries can be imported.

let base = 2
let power = 12
var answer = 2

for _ in 1...power{
    answer += base
}

answer

if answer > 20 {
    println("Yes it is!")
}else{
    
if answer < 20{
    println("No it's not!")

}



var BString = 12.23_429_303_934_439



answer

switch answer {
case answer > 15:
    println("More than 15!!")
    
case answer < 15:
    println("Less than 15!")
    
case answer = 26:
    println("On the mulah")
    
default:
    println("Yup")
    
}
*
*              /* */
*
*/







/*

var str = "Hello World!"
str

var strVar:String = "Something"

var someMessage:String = "String"

someMessage = "Hello"

*/

/*
import Cocoa

let formatter = NSDateFormatter()                   // 👈 notice that formatter is a constant
formatter.locale = NSLocale.currentLocale()
formatter.dateFormat = "MM/DD/YYYY"

var newFormatter = NSDateFormatter()

formatter = newFormatter

// Won't work because above, formatter is a constant.

*/



/*
"h"
for index in 0...60{
    println(index)
}

*/

"h"

var number = 6

// var tagniShopping = ["]


var numberTwo = 8
var wordTwo = "word"
// var SecondWord


6 == 3

number == 6



// (var word = hello) doesn't work because without the quotation marks on the hello, it thinks that the word hello is a variable. Since the variable hello does not exist, this will compile an error: use of unresolved identifier ‘hello’

// Adding quotes to the hello tells the compiler that this is a type: String

var word = "Hello"

word + " " + "World!"  // you can add a variable and a type String (notice the quotation marks) on World
                       // also concactenated the space in between the words

var newWord = word + " " + "World!"         // notice what was added together here!


let pi = 3.141

newWord
number.advancedBy(9)   // type in any number to advance by.,



                       // By using the (number.), the '.' allows you to go into the "box" for number and grab some properties/tools. Since number is an type Int, it will only grab properties for that implied type.




number                 // notice that number == number still equal to 6! -- 'number.advancedBy(9)' applies to only statement above line


number == number

                    // by adding in '//', it turns the text green to let the compiler know that this is a comment and that it should be ignore when compiling the code




newWord.isEmpty     // so far, this method only works for type: String values. This is a bool 👉



var newNumber = number.advancedBy(21)       // Different ways to achieve the same result
                                            // '.advanceBy' is a function. i just used a FUNCTION!!!!!!
                                            // Functions are DO-ers. They make thing happen. The parenthesies set things into motion
                                            // Functions == Methods (true). They are synonymous but different. Functions so far are used with variables and constants




// http://goo.gl/b6B42o - Difference between function and methods

// Functions are self-contained chunks of code that perform a specific task. You give a function a name that identifies what it does, and this name is used to “call” the function to perform its task when needed.

// Methods are functions that are associated with a particular type. Classes, structures, and enumerations can all define instance methods, which encapsulate specific tasks and functionality for working with an instance of a given type.




newWord
newNumber


let newPie87 = pi + 3
pi                                          // Since pi is a type: Double, it provides me with the functions as such
                // pi.                      // check out the different functions that it provides



countElements(newWord)                      // counted the number of characters in newWord
newWord
// countElements(newPie87)                  // notice this doesn't work with Type: doubles


var distance = 0

func run() {
 distance = distance + distance.advancedBy(5)
    
// could have also been written as such

// distance += distance.advancedBy(5)                               // '+=' means distance + the distance advanced by 5
}                                                                   // create a function named run


distance

run()
run()
run()

distance        // 👆 notice the change in distance's value after i ran the function 3 times


5 + 5
5 - 5
5 / 5
5 * 5
10 % 3            // The remainder operator (a % b) works out how many multiples of b will fit inside a and returns the value that is left over (known as the remainder).”

10 % 2.1

                                                            // a library is a library of prewritten functions that you can get




// sqrt(5.0)                           // i believe i first had to import the Cocoa library in order for this to take place

// var sqrtFive = sqrt(5.0)

// sqrtFive != 5


// sqrtFive += 5   adds 5 to the value of the variable then returns the final output

// sqrtFive -= 5   subtracts 5 from the value of the variable then returns the final output

// sqrtFive == 5   boolean that will return true or false if the condition holds

// sqrtFive != 5   boolean that will return true or false if the condition holds..







// #####################################=================================================###################################
// #####################################=================================================###################################
// #####################################=================================================###################################







var simpleArray = ["Ace Spade", "Ace Club", "Ace Diamonds", "Ace Hearts"]
var simplerArray = ["SpAce Spade", "SpAce Club", "SpAce Diamonds", "SpAce Hearts"]

simpleArray[0]
// simpleArray += "Change"                     // Changed this 8/25/2014. As of xCode 6.5, this no longer works
simpleArray += ["Change"]
// simpleArray.append("Change")                 Use the method in this line or on line above
simpleArray


// 👆 this will compile an error because Swift was changed so that adding to an array no longer works in this manor. Now, you must either use the .append 'method' or add square brackets to "change" in order for it to work. If there's an array to the left of the +=, there must also be an array to the right of it in order for it to compile.



simpleArray[0] = "Lucky Card"

simplerArray.append("Change 2")                                     // adds value to the end of the array


simplerArray[4] = "Change 4"

// simpleArray

// simpleArray.insert("Miami 2015", atIndex: 5)                        // gives you option to input a new element anywhere in the array

simpleArray



for Word in simpleArray {
    println(Word)
}

// simpleArray.removeAtIndex(5)                                // gives you option to remove a value anywhere in the array
// simpleArray.removeAtIndex(4)
simpleArray

simpleArray[1..<4]                                             // lists items in the array either inclusively or exclusively
simpleArray.getMirror()

simpleArray.append("New Sh!t")

simpleArray.removeLast()                                        // removes element from the last slot


simpleArray + simplerArray                             // Arrays can be added together. Elements will be combined in order

                                        // 1..<5   this will count 1-4, exclusive range because it excludes 5
                                        // 1...5   this will count 1-5, inclusive range because it includes 5




                                            // What is an array? An array is a way to store multiple values/elements. So far, seems as if values must be of the same type.




var byFiveArray = [5,10,15,20]
byFiveArray = []                        // empties the array
byFiveArray



var newDouble = [Double](count:3, repeatedValue:6)
var newTriple   = [String] (count:15, repeatedValue: "Hello")
var newDouble2 = [Double] (count:5, repeatedValue:3)        // What is the difference when the explicit type is taken out

newDouble
newDouble2              // Notice how this changes when the explicit Type: Double is removed above...
newTriple

newTriple [0] = "why"
newTriple
newTriple [2...14] = []         // emptied part of the array
newTriple





// #####################################=================================================###################################
// #####################################=================================================###################################
// #####################################=================================================###################################







// What is a dictionary? A dictionary is a container that stores multiple values of the same type. Sounds just like an array. 

// What's the difference between a dictionary and an array?  Items in a dictionary don't have a specified order

// Why would you use a dictionary instead of an Array!? You use a dictionary when you want to look up items in that container based on their unique identifiers.



   var newDict:Dictionary<String, String> = ["Hey" : "Howdie"]          // notice the : between the two values in the dictionary

// var impDict = ["Hey": "Howdie"]                                  Same way to write line above without having to make it explicit




var statesToWork:Dictionary = [0: "Texas", 1:"California", 2:"Remotely"]
var impDict2 = [0: "Ou", 1:"Est", 2:"Tu"]       // per above line, no need to make the dictionary explicit





statesToWork[3] = "Cameroon"                                // Adds new value to the statesToWork dictionary

statesToWork



statesToWork.updateValue("Cameroun", forKey: 3)     // this 'method' works backwards. Type in new value first, then the Key


statesToWork




let citiesToWork = statesToWork.updateValue("South Beach", forKey: 4)               // notice how this returns nil!
                                                                                    // this statement returns nil because in the last instance of the dictionary .statesToWork, there wasn't a key value for the keys that were just add.
statesToWork


citiesToWork

                                                                // try to do the next example using the                     citiesToWork and you'll slowly see why that was some bullshit!



if let partyCity = statesToWork.updateValue("Cameroun", forKey: 3){
    println("Found You!")
}else {
    println("Not you..")
}


                                                                // using citiesToWork in the last example doesn't work because cities to work was created with a nil value. the citiesToWork dictionary didn't have the method for .updateValue thus it was impossible for the if statement to work



if (citiesToWork != nil){                                                                        // if --- { } else { }
    println("Found You!!!")
}else{
    println("Not You...")
}

// citiesToWork[3] = nil

// citiesToWork





// statesToWork[3] = nil                                       // use this to remove a combination from the dictionary. All you have to do is is provide it with the key in the square brackets and the value that you'd like to equate it to

// statesToWork.removeValueForKey(3)                               // same function as the above statement

                                                                // Let's have some fun!!!

if let removedValue = statesToWork.removeValueForKey(3){
    println("We got rid of \(removedValue)")
}else{
    println("Forget (removedValue)")
}
 
// ".... \(RemovedValue)" only works once in the above statement
statesToWork



// statesToWork = [:]                        // empties the dictionary
statesToWork

Array(statesToWork.keys)
Array(statesToWork.values)



// for performance reasons, when given the option to use immututable vs mutable, go with the former



var x = 0.0

var a = "Alex", b = "Bill", c = "Charles"

a
b
c

println("I don't like the look of it \(statesToWork)")          // This is called String Interpolation. Swift allows you to use the variable or constant as a placeholder within the string. It will replace the con/variable withing the string with the appropriate values



                    // Look into using nested comments

                    /* This is a comment /* within a comment*/ within a comment... */

                    // Hopefully that made sense... 😊






// #####################################=================================================###################################
// #####################################=================================================###################################
// #####################################=================================================###################################








// “Integers are whole numbers with no fractional component, such as 42 and -23”


let minValue = UInt.min
let minValue2 = Int.max

// UInt8.max = 255
// UInt16.max = 65_535
// UInt32.max = 4_294_967_295

// Int.max = 9_223_372_036_854_775_807

// Moral of the story, ALWAYS USE 'Int'

// UINT32_MAX = another method of getting the max
// uint defaults to 32 bytes


// “An Int8 constant or variable can store numbers between -128 and 127, whereas
//  a UInt8 constant or variable can store numbers between 0 and 255. ”
// minValue.min      The .min would be called a "member" in this scenario. Keep that in mind.




// “Floating-point numbers are numbers with a fractional component, such as 3.14159, 0.1, and -273.15”

        // "Double represents a 64-bit floating-point number. Use it when floating-point values must be very large or particularly precise. Reads up to 15 decimal places

        // Float represents a 32-bit floating-point number. Use it when floating-point values do not require 64-bit precision." Reads up to 6 decimal places





// swift always defaults to double instead of float. ALWAYS USE TYPE DOUBLE


var pieDub:Double = 3.14159265358979323846264338327950            // goes to the 15th decimal place  👉
var pieFlo:Float = 3.14159265358979323846264338327950             // notice the 6th decimal place... 👉
pieDub + Double(pieFlo)                                           // also could have put in a UInt16 or UInt8

// 👆 can't add double to a float so initiated a new pieFlo variable of type Double. Could have done it vice versa as well

// the value that we assigned to pieDub (👆) is called a "literal"




let newPie1 = Int(pieFlo)                             // during conversions, floating pie values are always truncated 👉


var coolestPieName = pieDub



// i don't think type alias are necessary, but keep a lookout to see if it comes up in texts




let chuch = true
let nay = false
println(nay)


if statesToWork.count <= 1 {        // When using the if statement, the value that it's evaluating MUST be type: Bool
    println("\(nay)")
}else{
    println("\(chuch)")
}






// “Tuples group multiple values into a single compound value.”

let http404Error = (404, "Webpage not Found", 40.44544344355, false, "Will this work")          // 👈 This is a tuple

http404Error

http404Error.0                          // use .# to access indivitual elements of http404Error, which is a tuple
http404Error.1
http404Error.2
http404Error.3
http404Error.4


// 👆 notice how to access the value of a tuple, it's .# instead of [#]

    
let (aAt, bAt, cAt, dAt, fAt) = http404Error

aAt



let http200Error = (codeOne: 200, description: "d'accord")              // 👈 in this tuple, i named the indivitual elements while defining the tuple. Which i did not do when defining the very first tuple

// http200Error.                    // because i named the elements during the defining stage, the '.' returns names instead of numbers for each element.  I can use the element names to access the values of those elements.



let possibleNumber = "Hello"
let newPossibilities = possibleNumber.toInt()

// newPossibilities!       // '!' tells compiler, "i know newPossibilities has a value. Use it!" (known as forced unwrapping). Since this value is an optional and has no value though, this will return a runtime error


newPossibilities


http200Error.codeOne

// 👆 values in a tuple can be of any type and don't have match



if let newPossibilities2 = newPossibilities{                        // "if let" could have been written as "if var"
    println("True")
}else{
    println("That's wassup")
}




// 👆 Optional Binding is used to find out whether an optional contains a value, and if so, to make that value available as a temporary constant or variable”






// let surverAnswer:String?         notice how "let" will not work
var serverAnswer:String?            // String? sets this variable to be an optional

// Unlike in Objective-C, nil is not a pointer—it is the absence of a value of a certain type. Optionals of any type can be set to nil, not just object types.

var surveyAnswer:String! = "You good!?"     // String! sets this variable to ALWAYS have a value. Called an "implicitly unwrapped optionals"

var optionalStr:String! = ""
optionalStr

if (optionalStr != nil) {
    println(optionalStr)
}


serverAnswer
surveyAnswer







// #####################################=================================================###################################
// #####################################=================================================###################################
// #####################################=================================================###################################

    // “An assertion is a runtime check that a logical(bool) condition definitely evaluates to true. Literally put, an assertion “asserts” that a condition is true.”

// “trigger an assertion in your code to end code execution and to provide an opportunity to debug the cause of the absent or invalid value.” 

// “You use an assertion to make sure that an essential condition is satisfied before executing any further code. ”        “If the condition evaluates to true, code execution continues as usual; if the condition evaluates to false, code execution ends, and your app is terminated.”


let alexAge = 27

assert(alexAge <= 35, "You're still young!!!")

// #####################################=================================================###################################
// #####################################=================================================###################################
// #####################################=================================================###################################


// OPERATORS - “a special symbol or phrase that you use to check, change, or combine values.” i.e +, -, *, %

// “More complex examples include the logical AND operator && (as in if enteredDoorCode && passedRetinaScan) and the increment operator ++i, which is a shortcut to increase the value of i by 1”



// Operators can be:
    // Unary    -   Operates on a single target (i++)
    // Binary   -   Operates on two targets (i + i)
    // Ternary  -   Operates on three targets (a ? b : c)


5 + 5
5 - 5
5 / 5
5 * 5
10 % 3            // The remainder operator (a % b) works out how many multiples of b will fit inside a and returns the value that is left over (known as the remainder)

10 % 2.1

// increment operator (++) and a
// decrement operator (--)

var aye = 0
var bee = 0
var cee = 0
let ayeBee = ++aye + bee++ + ++cee
ayeBee                          // Notice how ayeBee calculates to 2 instead of 3 (see bee++)

// “If the operator is written before the variable, it increments the variable before returning its value.”
// “If the operator is written after the variable, it increments the variable after returning its value.”

var ayeTwo = ayeBee + -cee

let thin = -3
let thinOne = -thin
let thinTwo = +thin

// The unary minus operator (-) is prepended directly before the value that it is operating on. It turns the value into a negative.
// The unary plus operator (+) simply returns the value it operates on, without any change. It turns the value into a positive, unless the value is a negative, in which case, it will remain a negative. Doesn't really do anything but is used to "add symmetry" when coding


aye             // notice how aye is equal to 1
aye += 3        // This is shorthand for aye = aye + 3


// COMPARISON OPERATORS - return booleans

    // Equal to (a == b)
    // Not equal to (a != b)
    // Greater than (a > b)
    // Less than (a < b)
    // Greater than or equal to (a >= b)
    // Less than or equal to (a <= b)

// IDENTITY OPERATORS - return booleans

    // identical to (===)
    // not identical to (!==)






/*
// Ternary  -   Operates on three targets (a ? b : c) which takes the form "question ? answer1 : answer2” “It is a shortcut for evaluating one of two expressions based on whether question is true or false. If question is true, it evaluates answer1 and returns its value; otherwise, it evaluates answer2 and returns its value.”

Ternary conditional operator is shorthand for the code below:

if question {
    answer1
} else {
    answer2
}

*/


let contentHeader = 40
let hasHeader = false       // notice the difference when this is changed from true to false
let rowHeight = contentHeader + (hasHeader ? 50 : 20)   // if hasHeader = true, add 50. Else, add 20.

// The above can also be written as 👇

/*
let contentHeight = 40
let hasHeader = true
var rowHeight = contentHeight

if hasHeader {
    rowHeight = rowHeight + 50
} else {
    rowHeight = rowHeight + 20
}
*/


// the ternary conditional operator is concise to use, but can lead to hard-to-read code if overused



// Logical NOT (!a) - Logical operators modify or combine the Boolean logic values true and false

// Logical AND (a && b) - The logical AND operator (a && b) creates logical expressions where both values must be true for the overall expression to also be true. If left side is false, right side isn't evaluated.

// Logical OR (a || b) - You use it to create logical expressions in which only one of the two values has to be true for the overall expression to be true. If left side is true, right side isn't evaluated.

        // Look up "short-circuit evaluation" (If the left side of a Logical OR expression is true, the right side is not evaluated, because it cannot change the outcome of the overall expression.)



let hasRoomkey = true
let hasSafekey = false
let safeHasMoney = true

if hasRoomkey && hasSafekey {
    println("Cash Mulah")
}else{
    println("GTFOH")
}


if hasRoomkey || hasSafekey {
    println("Welcome")
}else{
    println("Bye bye")
}

if (hasRoomkey || hasSafekey) && safeHasMoney {     // 👈 Parenthesis don't need to be added. Makes code cleaner to read
    println("Let's get this bread")
}else{
    println("Dang it")
}



let wiseWords = "\"This time next year, i'm gonna be a beast\" - Alex N."     // use "\ to essentially skip a spot and add the extra quote mark


for Character in wiseWords{
    println("There are \(wiseWords) characters in this wise word!")          // Same as below
}

for Character in wiseWords{
    println("There are \(countElements(wiseWords)) characters in this wise word!")      // Same as above - USE THIS ONE!!
}
//  👆 Note also that the character count returned by countElements is not always the same as the length property of an NSString that contains the same characters. The length of an NSString is based on the number of 16-bit code units within the string’s UTF-16 representation and not the number of Unicode characters within the string. To reflect this fact, the length property from NSString is called utf16count when it is accessed on a Swift String value.”

// \(wiseWords) <-- This is called String Interpolation (see above)
// The expressions you write inside parentheses within an interpolated string cannot contain an unescaped double quote (") or backslash (\), and cannot contain a carriage return or line feed.



// Swift provides three ways to compare String values: string equality, prefix equality, and suffix equality.

wiseWords
let wiseWordss = wiseWords                      // 👈 String Equality (bool) baby - “equal if they contain exactly the same                                                             characters in the same order:”

if wiseWords == wiseWordss {
    println("One in the same")
}else{
    println("Two far apart")
}



// Consider the array below...

let codingPath = [ "First, learn how to write and read code",
    "Second, use that skill to build a great app",
    "Third, 0 use skills to gain continuous income",
    "Third, 1 build apps from anywhere in the world",
    "Third, 2 so far, we're on the right path",
    "Fourth, 0 the natural flow of life is always moving forward",
    "Fourth, 1 if you're not moving forward, you're moving backward"
]


var thirdEye = 0

for scene in codingPath {
    if scene.hasPrefix("Third,") {              // use of the .hasPrefix method
        ++thirdEye
    
}
}
println("There are \(thirdEye) parts to your third👀Eye")



var wardWord = 0

for scene in codingPath {
    if scene.hasSuffix("ward"){
        ++wardWord
    }
}
println("there's always more than \(wardWord) ways to get what you want")


// “Swift’s String and Character types are fully Unicode-compliant Unicode is an international standard for encoding and representing text.

// #####################################=================================================###################################
// #####################################=================================================###################################
// #####################################=================================================###################################


// ARRAYS - stores multiple values of the same type in an ordered list


var shoppingList = ["Pizza Dough", "Pasta Sauce", "Cheese", "Sausage", "Pepperoni"]     // 👈 an Array Literal
shoppingList
shoppingList[1]                     // 👈 Retrieve a value from the array by using subscript syntax. Subscript syntax can be used for a multitude of things..

// shoppingList[0...4] = ["one", "two", "three", "four"]       // Notice how many items were taken out 👇





println("Shopping list contains \(shoppingList.count) items")           // Uses the .count property

shoppingList += ["Bananas", "Ice Cream", "Water"]

shoppingList.getMirror()                // First item in the array has an index of [0]. Arrays are alyways '0-indexed'

// shoppingList[15] = "Truth"          // Will not compile because there is no 15th index. Technically 16th place...

shoppingList.count
// shoppingList.insert("oneAgain", atIndex: 1)         // Remember that Arrays are '0-indexed'
// shoppingList.removeAtIndex(1)
// shoppingList.removeLast()
shoppingList

let newShoppingList = shoppingList.removeLast()
shoppingList.count
newShoppingList
// var testVar = shoppingList.getMirror()
// 👆 the last item in the array has just been removed. shoppingList now contains 7 items, and no water. The newShoppintList constant is now equal to the removed "Water" string


var someInt = [Int]()           // create empty arrays of a certain type. Can be any type..
someInt.count
someInt

// as of Jul 15, 2014, let array is completely immutable, and a var array is completely mutable



// 👇 To create an array of values with the same count
var fourArray = Array(count: 3, repeatedValue: 4)
fourArray
var testArray2 = fourArray + fourArray           // new array's type is inferred



// What would be a real life app scenario for using an array?








// #####################################=================================================###################################
// #####################################=================================================###################################
// #####################################=================================================###################################








// DICTIONARY - is a container that stores multiple values of the same type. Each value is associated with a unique key. Unlike Arrays, items in dictionaries do not have a specified order. 

// Keep in mind that a dictionay is not an ordered list. So values in a dictionary can be returned in any order.

var emptDic = ["":""]           // Dictionary [keyType:valueType]   keyType must be hashable—that is, it must provide a way to make itself uniquely representable. Swift’s basic types (such as String, Int, Double, and Bool) are hashable by default
emptDic

var newDic = [0:"Zero", 1:"One", 2:"Two"]           // 👈 a Dictionary Literal. Within the literal is a "key-value pair" - a combination of a key and a value.

println("New Dic has \(newDic.count) values in it")     // check number of values in a dictionary using the read-only count property


newDic [3] = "Three"            // Added a "key-value pair" using subscript syntax
newDic [3] = "Threee"           // changed the value of a key using subscript syntax

newDic.updateValue("Four", forKey: 4)  // updates the value and returns the old value as a Type: String? in case there wasn't a value before. Which in this case there wasn't. If this were to change the '3' key, it wouldn't return nil

// 👆 The .updateValue above is called a method

newDic

if let newDicValue = newDic [3]{                    // returns an optional value type in case key has no value
    println("Value is \(newDicValue)")
}else{
    println("Value not in dictionary")
}

if let newDicValue2 = newDic.updateValue("Test Value", forKey: 3) {     // returns old optional string? value before updating it to new value
    println("Value is \(newDicValue2)")
}else{
    println("Value is not in dictionary")
}


newDic [3] = nil                // removes a value using subscript syntax 
newDic [3] = "Threee"
newDic.removeValueForKey(4)     // method removes the key-value pair if it exists and returns the removed value, or returns nil if no value existed


if let newDicValue3 = newDic.removeValueForKey(4) {     // returns this because key 4 was removed in above line
    println("Value was \(newDicValue3)")
}else{
    println("Value is not in dictionary")
}

newDic


for (newDicValue, newDicValue2) in newDic {
    println("\(newDicValue) : \(newDicValue2)")
}

for newDicValue in newDic.values {
    println("Code \(newDicValue)")
}


// var testCodes = Array[newDic.keys]

// Brush up on the latter sections of Dictionary Literals






/*

// Notes from Youtube video (http://goo.gl/Nd5oz7) on Arrays and Dictionaries.

list.append     .append is a method. Methods allow you to alter or change something about the object 'list' that you're talking about. Essentially like going into "list's box" and grabbing different methods.

Technically, arrays can be mutated if they're created as a constant. There's a way that i'll find out later 😁 

*/












// #####################################=================================================###################################
// #####################################=================================================###################################
// #####################################=================================================###################################






// Control Flows

// use 'for and while' loops to perform a task multiple times
// use 'if and switch' statements to execute different branches of code based on certain conditions
// use statements such as 'break and continue' to transfer the flow of execution to another point in your code


// Swift adds a for-in loop that makes it easy to iterate over arrays, dictionaries, ranges, strings, and other sequences


// Swift’s switch statement is also considerably more powerful than it's C counterpart. Cases can match many different types of pattern, including range matches, tuples, and casts to a specific type.






// A 'for' loop performs a set of statements a certain number of times. Swift provides two kinds of for loop:

    // ◎ - for-in performs a set of statements for each item in a range, sequence, collection, or progression. Such as ranges of numbers, items in an array, or characters in a string.

    // ◎ - for-condition-increment performs a set of statements until a specific condition is met, typically by incrementing a counter each time the loop ends



let numberedArray = [1, 2, 3, 4, 5, 6, 7, 8, 9, 0]
numberedArray.count

for index in numberedArray{
    println("Number \(index) in the Numbered Array container.")
}

for index in 1...5{
    println("This is the number \(index) number in this range.")
}

for index in 1..<5{
    println("\(index) times 5 is \(index * 5).")
}


// in the above lines, index is a constant whose value is automatically set at the start of each iteration of the loop.

// for-in loops work with Arrays, Dictionaries, and Ranges.


let base = 3
let power = 10
var answer = 1
for _ in 1...power {               // notice the use of the underline here. Used since we don't need each value in the range
    answer *= base
}
println("\(base) to the power of \(power) is \(answer)")


    // use line above in case you don't need each individual output from a range. The underscore character _ (used in place of a loop variable) causes the individual values to be ignored and does not provide access to the current value during each iteration of the loop.


numberedArray // a variable array that i created earlier

for names in numberedArray{
    println("Hello \(names)!")
}

for number in numberedArray{
    println("Whattup number \(number)!!! What it do fool!!!")
}


let namesArray = ["Niagara", "Whisper", "Rayllan", "Sperlina"]

for name in namesArray{
    println("Hello \(name). What a wonderful name you have! D'ou est il!?")
}



// You can also iterate over a dictionary to access its key-value pairs. Each item in the dictionary is returned as a (key, value) tuple when the dictionary is iterated, and you can decompose the (key, value) tuple’s members as explicitly named constants for use within in the body of the for-in loop.



let numberOfLegs = ["Spiders" : 08, "Dogs" : 04, "Old-Man" : 03, "Adult" : 02]

for (speciesName,numberOfLegss) in numberOfLegs{           // 👈 i completely came up with the names of the key and variable
    println("Ever come across a \(speciesName)!? They are amazing in the sense that they all have \(numberOfLegss) legs.")
}


// above example is quite comicle if you switch the name variables

// In addition to arrays and dictionaries, you can also use the for-in loop to iterate over the Character values in a string

for character in "Hello"{
println("\(character)")
}







// for initialization; condition; increment {
//    statements
// }

// 👆 The loop is executed as follows 👇:

/* 

//  1) When the loop is first entered, the initialization expression is evaluated once, to set up any constants or variables that are needed for the loop.

//  2) The condition expression is evaluated. If it evaluates to false, the loop ends, and code execution continues after the for loop’s closing brace (}). If the expression evaluates to true, code execution continues by executing the statements inside the braces.

//  3) After all statements are executed, the increment expression is evaluated. It might increase or decrease the value of a counter, or set one of the initialized variables to a new value based on the outcome of the statements. After the increment expression has been evaluated, execution returns to step 2, and the condition expression is evaluated again.

*/

for var index = 0; index < 3; ++index {             // notice that this is zero indexed.
    println("index is \(index)")
}




// Constants and variables declared within the initialization expression (such as var index = 0) are only valid within the scope of the for loop itself. To retrieve the final value of index after the loop ends, you must declare index before the loop’s scope begins:


// A while loop performs a set of statements until a condition becomes false. Swift provides two kinds of while loops:

    // ◎ - 'while' evaluates its condition at the start of each pass through the loop. Checks conditional, then runs code
    // ◎ - 'do-while' evaluates its condition at the end of each pass through the loop. Runs code, then checks conditional


// A while loop starts by evaluating a single condition. If the condition is true, a set of statements is repeated until the condition becomes false.

            // while condition {
            //     statements
            // }



/*
numberedArray.count

while numberedArray.count <= 10 {
    println("We in here!")
};else{
    println("Stop here!")
}
*/



let finalSquare = 25
var board = [Int] (count: finalSquare + 1, repeatedValue:0)
board.count

board[03] = +08
board[06] = +11
board[09] = +09
board[10] = +02
board[14] = -10
board[19] = -11
board[22] = -02
board[24] = -08

board

var square = 0
var diceRoll = 0

while square < finalSquare {
    // roll the dice
    
    if ++diceRoll == 7 { diceRoll + 1 }
    
    // move by the rolled dice amount
    
    square += diceRoll
    
    if square < board.count {
        // if we're still on the board, move up or down for a snake or a ladder
        
        square += board[square]
    }
}

println("Game Over!")


                // 👆the loop is executed until a particular condition is satisfied. In this case, until finalSquare is reached.




// the do-while loop, performs a single pass through the loop block first, before considering the loop’s condition. It then continues to repeat the loop until the condition is false.


            // do {
            // statements
            // } while condition





// Using the same example as above, we'll rewrite it using a do-while loop

let finalSquare2 = 25
var board2 = [Int] (count: finalSquare + 1, repeatedValue:0)
board2.count

board2[03] = +08
board2[06] = +11
board2[09] = +09
board2[10] = +02
board2[14] = -10
board2[19] = -11
board2[22] = -02
board2[24] = -08

board2

var square2 = 0
var diceRoll2 = 0


do {
    // move up or down for a snake or ladder
    square2 += board2[square2]
    // roll the dice
    if ++diceRoll2 == 7 { diceRoll2 = 1 }
    // let diceRoll = Int(arc4random_uniform(7))                    // 👈 be careful with this line, crashed my code
    // move by the rolled amount
    square2 += diceRoll2
} while square2 < finalSquare2
println("Game over!")

// 👆 does the statement while the condition is met



                // - its the number of elements in the array that are immutable




                                        // ****                        ****
                                        // **** CONDITIONAL STATEMENTS ****
                                        // ****                        ****


// in its simplest form, the if statement executes a set of statements only if that condition is true

var temperatureInFahrenheit = 30
if temperatureInFahrenheit <= 32 {
    println("It's very cold. Consider wearing a scarf.")
}else if temperatureInFahrenheit == 30 {
    println("Water freezes here!")
}else if temperatureInFahrenheit >= 50 {
    println ("It may not be that cold outside, consider a sweater!")
}else {
    println("This water is freezing!")
}


// the temeratureInFahrenheit can be changed so that it is neither too cold nor too warm to trigger the if or else if conditions. If so, no message is printed. 





// A switch statement considers a value and compares it against several possible matching patterns. It then executes an appropriate block of code, based on the first pattern that matches successfully. A switch statement provides an alternative to the if statement for responding to multiple potential states.


// The switch statement determines which branch should be selected. This is known as switching on the value that is being considered.


/*
switch some value to consider {
    case value 1:
    respond to value 1

    case value 2,                                   // 👈 notice comma
    value 3:
    respond to value 2 or 3

    default:
    otherwise, do something else
}
*/


// switch statements must be exhaustive, thus default statement must always be included




let unoCharacter: Character = "p"


switch unoCharacter {
    case "a", "e", "i", "o", "u", "y":
    println("This character: \(unoCharacter) is a vowel")       // no function or method to make letter uppercase
    case "b", "c", "d", "f",
    "g", "h", "j", "k", "l", "m", "n", "p",
    "q", "r", "s", "t", "v", "w", "x", "y", "z":            // notice how a single switch case can be written across multiple lines and seperated by commas
    println("This character: \(unoCharacter) is a constanant!")
    default:
    println("Entered character: '\(unoCharacter)' is not a valid character!")
}

// example above defaults to a void character because we only really care about case a and case b. Switches must be exhaustive.


// switch statements in Swift do not fallthrough the bottom of each case and into the next one by default. First come, first served.

// The body of each case must contain at least one executable statement.




let dosCharacter: Character = "a"

switch dosCharacter {
    case "a":
        println("This is the lower case letter 'a'")      // Get an error message if this line is removed because each case must contain at least one executable statement. This approach avoids accidental fallthrough from one case to another, and makes for safer code that is clearer in its intent.
        
    case "A":
    println("This is the upper case letter 'A'")
default:
    println("Nothing to see here folks...")
}



                // ****                ****
                // **** RANGE MATCHING ****
                // ****                ****


let count = 3_000_000_000_000
let countedStars = "stars in the Milky Way"
var naturalCount:String = "No counted stars yet..."

//  Command + '/' to add // in front of selected lines of code 😁 Accidentally landed on this!!!!!

switch count {
case 0:
    naturalCount = "no"
    
case 1...3:
    naturalCount = "a few"
    
case 4...9:
    naturalCount = "several"                // in this scenario, we're setting the output depending on the case matched
    
case 10...99:
    naturalCount = "tens of"
    
case 100-999:
    naturalCount = "hundreds of"
    
case 1000-999_999:
    naturalCount = "thousands of"
    
default:
    naturalCount = "millions and milliions of"
}

println("There are \(naturalCount) \(countedStars)")










// ****         ****
// **** TUPLES  ****
// ****         ****



let somePoint = (0,0)
switch somePoint{
case (0,0):
    println("(0,0) is at the origin")
    
case (_,0):
    println("(\(somePoint.0)) is on the X-Axis")
    
case (0,_):
    println("(\(somePoint.1)) is on the Y-Axis")
    
case (-2...2, -2...2):
    println("(\(somePoint.0),\(somePoint.1)) is inside the box")
    
default:
 println("(\(somePoint.0),\(somePoint.1)) is outside of the box")
    
}



// ****                 ****
// **** VALUE BINDINGS  ****
// ****                 ****


// A switch case can bind the value or values it matches to temporary constants or variables, for use in the body of the case. Known as value-binding, values are bound to temporary constant or variable within the case's body.

let anotherPoint = (2,3)                // 👈when matching, first matching case below is selected
switch anotherPoint {
case (let x, 0):                // this could also be a var
    println("on the x-axis with an x value of: \(x)")
    
case (0, let y):
    println("on the y-axis with a y value of: \(y)")
    
case let (x,y):
    println("somewhere else at \(x), \(y)")

                    // 👈 notice that there is no default case. The last case matches every possible value thus none is needed
    
// 👆 Once the temporary constants are declared, they can be used within the case’s code block. Here, they are used as shorthand for printing the values with the println function.
    
}


// if multiple matches are possible, the first matching case is always used







// ****        ****
// **** WHERE  ****
// ****        ****

// A switch case can use a where clause to check for additional conditions.



let yetAnotherPoint = (5,23)
switch yetAnotherPoint {
    
case let (x,y) where x == y:
    println ("(\(x),\(y) is on the line x == y")
    
case let (x,y) where x == -y:
    println("(\(x),\(y) is on the line x == -y")
    
case let (x,y):                 // can this be changed to default case!? No
    println("(\(x),\(y) is just some arbitrary point")
    
}

// 👆 checks to see if the values entered are on a line that goes diagonal on a graph. Notice again how there's no default case. When calling a default case, colon goes right after the default thus you're not able to value bind.





//var testDogNameed = Array(yetAnotherPoint)   // find out later why this line doesn't work



var bullShit = [""]     // 9/10/2014 After updating to Gold Master, testing how to create an empty array



var testString = String()
var testDouble = Double()
//var testCharacter = Character:()
var testInt = Int()
var testArray = [String]()
var testArray3:Array = [""]     // 9/10/2014 After updating to Gold MAster, had to add quote marks in order for the line to compile
var testDict = Dictionary<String,Int>()
var testDict2 = ["":""]         // 9/10/2014 After updating to Gold MAster, had to add quote marks in order for the line to compile





// ****                              ****
// **** CONTROL TRANSFER STATEMENTS  ****
// ****                              ****



// Control transfer statements change the order in which your code is executed, by transferring control from one piece of code to another. Swift has four control transfer statements:

    // ◎ - 'continue'
    // ◎ - 'break'
    // ◎ - 'fallthrough'
    // ◎ - 'return'



// The continue statement tells a loop to stop what it is doing and start again at the beginning of the next iteration through the loop. It says “I am done with the current loop iteration” without leaving the loop altogether.






//
//
//let puzzleInput = "great minds think alike"
//var puzzleOutput = ""
//for character in puzzleInput {
//    switch character {
//    case "a", "e", "i", "o", "u", " ":
//        continue
//    default:
//        puzzleOutput += character                 // 👈
//    }
//}
//println(puzzleOutput)



// 👆 above it example from the book. Notice how puzzleOutput += no longer works. This is because this action only works with Arrays now. There must be an array on both sides of the +=


let puzzleInput = "great minds think alike"
var puzzleOutput = ""

for character in puzzleInput {
    switch character {
    case "a", "e", "i", "o", "u": // " "
        continue
    default:
        puzzleOutput.append(character)              // this is the same as 'puzzleOutput += character'
    }
}

println(puzzleOutput)

// 👆 for puzzleInput, if it matches the first case, it will continue onto the second one!? Else, it will default and append the character to puzzleOutput which leaves us with the final println(puzzleOutput). I removed the spaces to that they're not concactenated.









// The break statement ends execution of an entire control flow statement immediately. It can be used inside a switch statement or loop statement when you want to terminate the execution of the switch or loop statement earlier than would otherwise be the case.


// ◎ - BREAK IN A LOOP STATEMENT
    // When used inside a loop statement, break ends the loop’s execution immediately, and transfers control to the first line of code after the loop’s closing brace (}). No further code from the iteration of the loop is executed.

//BREAK IN A SWITCH STATEMENT

    // When used inside a switch statement, break causes the switch statement to end its execution immediately, and to transfer control to the first line of code after the switch statement’s closing brace (}). You can write a case as "break" and if the case is matched, the break statement inside the case will end the switch statement immediately.


let numberSymbol: Character = "三" // simplified chinese for the number 3
var possibleIntergerNumber: Int?
switch numberSymbol {
case "1", "١", "一", "๑":
possibleIntergerNumber = 1

case "2", "٢", "二", "๒":
possibleIntergerNumber = 2

case "3", "٣", "三", "๓":
    possibleIntergerNumber = 3
    
case "4", "٤", "四", "๔":
    possibleIntergerNumber = 4
    
default:
    break                // when i try to use continue, get error message that 'continue' is only allowed inside a loop
}

if let integerValue = possibleIntergerNumber {
    println("The integer value of \(numberSymbol) is \(integerValue)") // the optional binding will succeed only if possibleIntegerValue was set to an actual value by one of the switch statement’s first four cases.

} else {
    println("An integer value could not be found for \(numberSymbol)")  // figure out how to add tick marks around the numberSymbol
}


// 👆 This example checks numberSymbol to determine whether it is a Latin, Arabic, Chinese, or Thai symbol for the numbers 1 to 4. When the default case matches, the break statement inside the case ends the switch statement’s execution immediately.









// Switch statements in Swift do not fall through the bottom of each case and into the next one. Instead, the entire switch statement completes its execution as soon as the first matching case is completed. If you really need C-style fallthrough behavior, you can opt in to this behavior on a case-by-case basis with the fallthrough keyword.


let integerToDescribe = 5
var description = "The number \(integerToDescribe) is"

switch integerToDescribe {
    case 2, 3, 5, 7, 11, 13, 17, 19:
        description += " a prime number and also"
        fallthrough     // allows the case statement above to "fall into" and append the statement below to the above statement. The fallthrough keyword doesn't check the case condition that it falls into, it simply causes code execution to move directly to the statements inside the next case (or default case👇) block
        
    default:
        description += " an integer"

}

println(description)





// LABELED STATEMENTS

// Loops and switch statements can both use the break statement to end their execution prematurely. You can mark a loop statement or switch statement with a statement label, and use this label with the break statement or continue statement to end or continue the execution of the labeled statement.


//  label name: while condition {
//      statements
//  }



let finalSquare3 = 25
var board3 = [Int](count:finalSquare3 + 1, repeatedValue:0)
board3[03] = +08
board3[06] = +11
board3[09] = +09
board3[10] = +02
board3[14] = -10
board3[19] = -11
board3[22] = -02
board3[24] = -08
var diceRoll3 = 0
var square3 = 0

gameLoop: while square3 != finalSquare3 {
    if ++diceRoll3 == 7 {diceRoll3 = 1}
    switch square3 + diceRoll3 {
    case finalSquare3:                   // diceRoll will move us to the final square, so the game is over
            break gameLoop
        
    case let newSquare where newSquare > finalSquare3:      // diceRoll will move us beyond the final square, so roll again
        continue gameLoop
        
    default:        // this is a valid move, so find out its effect
        square3 += diceRoll3
        square3 += board3[square3]              // not sure exactly what this line means
    }
}
println("Game Over!")

println("Hello World")





// ****            ****
// **** FUNCTIONS  ****
// ****            ****



// Functions are self-contained chunks of code that perform a specific task. You give a function a name that identifies what it does and you can call that name whenever you need for that function to be performed.

    // Every function in Swift has a type consisting of the function's Parameter Type and its Return Type. You can use this type like any other type in Swift.

    //  Functions can be nested into other functions to encapsulate useful functionality.


// When you define a function, optionally, you can define one or more named, typed values, called Parameters (aka "input"), that the function takes as input, AND/OR a type of value that the function will pass back as an output (called its Return Type) once it's done.

// TO USE A FUNCTION, YOU "CALL" THAT FUNCTION. A FUNCTION HAS 3 PARTS:
    //  What the function does
    //  What it expects to receive
    //  What it returns when it is done

// Every function has a function name. Choose a name which describes the task that the function performs. "Call" a function, using its name, in order to use it and and pass it input values (known as Arguments) that match the types of the function’s parameters.
        // A function’s 'arguments' must always be provided in the same order as the function’s parameter list.



func sayHello(personName: String, personAge: Int) -> String {     // indicate the function's return using the -> followed by the return type
    let greeting = "Hello, " + personName + "!"
    let ageQuestion = "Are you really " + String(personAge) + " years old!?"
    return greeting + " " + ageQuestion
    // return greeting
}

println(sayHello("Alex", 27))




// 👆 all of the information is rolled up in the function's "definition". The definition describes what the function does (sayHello), what it expects to receive (personName: String), and what it returns (-> String) when it is done. The definition is prefixed with the func keyword.

println(sayHello ("Mary", 21))      // 👈 I just used my very first function!!!!! "Mary" is an argument. It is a string argument value in parentheses that's passed into the functions.
println(sayHello ("John", 23))      // 👈 sayHello can be wrapped in the println() function because it returns a string value. Technically, this is a function within a function.

// 👆 not sure why the lines above stopped working. Need to look this up later. Didn't work because i had added personAge: INT to the function's definition. Need to find out how to add this in later so that the code is able to compile. 
// update to the direct line above, i was able to resolve the issue by converting the personAge (Int type) to a string so that i could concactonate that with the string constant.



func sayHelloAgain(personName2: String) ->String {
    return "Hello again, " + personName2 + "!"
}

println(sayHelloAgain("Brian"))     // 👈"Brian" is an example of me passing this function a string argument.
println(sayHelloAgain("Jasoné"))    // because the function returns a string, we can use it w/ println to see the output


func dogInfo(dogsName: String, dogsAge: Int) -> String {            // 👈 This is a function with multiple parameters
    return "The dog named \(dogsName) is actually \(dogsAge) years old"
}

dogInfo("Fido", 1)
dogInfo("Sean", 3)
dogInfo("Face", 5)

println((dogInfo("Snow", 3)))




func halfOpenRangeLength (start: Int, end: Int) -> Int{     // 👈 function w/ multiple input parameters (as already done above). Parameters are however, not required.
    return end - start
}

halfOpenRangeLength(0, 25)




func sayHelloWorld() -> String {        // 👈 function w/o any parameters. Just a return.
    return "Hello World!"
}

sayHelloWorld()
println(sayHelloWorld())




func waveGoodbye(byePersonName: String) {       // 👈 function w/o return value
    println("Goodbye \(byePersonName). See you soon!")      // this doesn't HAVE to be 'return"
}

waveGoodbye("Lulu")         // technically, this does return a type Void value which is simply an empty tuple ()
waveGoodbye("Jose")


// 👇 the retuen value of a function can be ignored when it's called

func printAndCount(stringToPrint: String) -> Int {
    println(stringToPrint)
    return countElements(stringToPrint)
}
func printWithoutCounting(stringToPrint:String) {
    printAndCount(stringToPrint)
}

printAndCount("How about lunch? Where would you like to go!?")
printWithoutCounting("How about lunch? Where would you like to go!?")  // notice how for printWithoutCounting, the first function printAndCount, which is set to return an Int value, was called, yet the return value was ignored in the second function because in the definition of the second function, we configured it without a return. 

// Return values can be ignored, but a function that says it will return a value MUST always do so. Doing otherwise will result in a compile-time error.




// FUNCTIONS WITH MULTIPLE RETURN VALUES

// You can use a tuple type as the return type for a function to return multiple values as part of one compound return value.


func count(string: String) -> (vowels: Int, consonants: Int, others:Int) { // 👈 notice the tuple for multiple return types
    var vowels = 0, consonants = 0, others = 0
    for character in string{
        switch String(count)/*.lowercaseString*/ {
        case "a", "e", "i", "o", "u":
            ++vowels
            
        case "b", "c", "d", "f", "g", "h", "j", "k", "l", "m", "n", "p", "q", "r", "s", "t", "v", "w", "x", "y", "z":
            ++consonants
            
        default:
            ++others
            
        }
    }
    return (vowels, consonants, others)
}

count("Hey There")

let total = count("some arbitrary string!")
println("\(total.vowels) vowels and \(total.consonants) consonants")






// FUNCTIONS WITH NO RETURN VALUE


func someFunction (parameterName: Int) {
    // function body goes here, and can use parameterName   // Parameters in here are known as 'local parameter names'
    // to refer to the argument value for that parameter    // because they're only available for use within the function's
                                                            // body.

}


// if you want users of the function to define parameter names when they call your function, define an 'external parameter name' for each parameter IN ADDITION to the local parameter name. Write the external parameter name in front of the local parameter name, seperated by a space.











// FUNCTIONS WITH EXTERNAL PARAMETER NAME AND SHORTHAND EXTERNAL PARAMETER NAME

func someFunction2 (externalParamaterName localParameterName: Int) {        // ALWAYS use external name to call function
  
    // function body goes here, and can use localParameterName
    // to refer to the argument value for that parameter
    
}



// If you provide an External Parameter name for a parameter, that external name must ALWAYS be used when calling the function.





func dogNameAndAge2 (/*insertDoggieName*/ #doggieName: String, /*insertDoggieAge*/ #doggieAge: Int, var /*insertDoggieSex*/ #doggieSex:String) -> String { // notice '#' sign
    switch doggieSex {          // 👈 notice that the local name is still being used here
        
    case "he", "male", "Male":
    doggieSex = "he"
        
    case "she", "female", "Female":
    /*var*/ doggieSex = "she"       // the 'var' keyword wasn't even needed for this to compile
        
        
    default:
    doggieSex = "it"
        
    }
return "This dog's named \(doggieName) and \(doggieSex) is \(doggieAge) years old!"
}

dogNameAndAge2(doggieName: "Paul", doggieAge: 5, doggieSex: "male")



func join (s1:String, s2:String, joiners:String) -> String {
    return s1 + joiners + s2
}

join("Hello", "World", ", ")


// to make the join function above clearer when calling the function, we'll add some external parameter names to it. I'll recreate it as joiner

func joiner (joinThisString s1:String, toThisString s2:String, withThisJoiner join:String) -> String{
    return s1 + join + s2
}

joiner(joinThisString: "Hello", toThisString: "World!", withThisJoiner: ", ")
joiner(joinThisString: "How is ", toThisString: " doing!?", withThisJoiner: "she")


// 👆the shorthand way to write the extenal parameter name would have been to simply add a # sign to the local parameter name. If that local parameter name is already unambiguous, you can just add the # sign. This tells Swift to use that name as both the local parameter name and the external parameter name.
















// FUNCTIONS WITH SHORTHAND EXTERNAL PARAMETER NAME





func containsCharacter (#string: String, #characterToFind:Character) -> Bool{
    for character in string {
        if character == characterToFind {
            return true
        }
    }
 return false
}

containsCharacter(string: "Howdie", characterToFind: "y")

containsCharacter(string: "Sure", characterToFind: "s") // 👈 interesting how it returns false even though this is an s



let containsAvee = containsCharacter(string: "aardvark", characterToFind: "v")
// line above will return true because there's a lowercase v in the string.

containsAvee












// FUNCTIONS WITH DEFAULT PARAMETER VALUES - place parameters with default values at the end of the function's definiton

func newJoiner(#joinThisString: String, #withThisNewString:String, /*#*/usingThisDefaultJoiner: String = " ") -> String {
    return joinThisString + usingThisDefaultJoiner + withThisNewString
}


// 👆 adding the shorthand external name to the 'usingThisDefaultJoiner' returns an extraneous error message. Notice how the i've set usingThisDefaultJoiner to be explicit. I could have easily made it implicit.


newJoiner(joinThisString: "Hello", withThisNewString: "World!")
newJoiner(joinThisString: "Hello", withThisNewString: "World!", usingThisDefaultJoiner: " - ")

// 👆 in the two lines above, on the first line, i used the default value to concactonate the the two strings. In the second line, i actually set the value for the 'usingThisDefaultJoiner' line. If i'm not going to use the default value, then i have to erase it altogether. 



// 👇 just some quick fun 😁


func gameResults (
    
    #washingtonWizards: String,
    #miamiHeat: String,
    #inThisCity:String,
    var optionalFinalWizardScoreWas: Int = 0,   // You can avoid defining a new variable yourself within the function by specifying one or more parameters as variable parameters instead. See below...
    
    var optionalFinalMiamiScoreWas: Int = 0,
    var optionalThisTeamWon:String = "This team won!",
    var optionalThisTeamLost:String = "",
    var optionalExcitingGame:Bool = true,
    var optionalBriefDescription:String = ""
    
                )

    -> String {
        
        // i'm good enough to but in a simple number comparison string up here. Input the scores
        
        switch optionalThisTeamWon{
        case "miami Heat", "Miami Heat", "the Heat", "#SuckABron", "the miami Heat", "the Miami Heat":
            let optionalThisTeamWon = "The Miami Heat"
            
        case "washington Wizards", "the Wizards", "Washington Wizards", "the washington Wizards", "the Washington Wizards":
            let optionalThisTeamWon = "The Washington Wizards"
            
        default:
            let optionalThisTeamWon = "We'll have an update for you as soon as this game is over."
        }
        
        if optionalThisTeamWon == "The Miami Heat"{
            let optionalThisTeamWon = true
        }
        
        // maybe i need to call a new variable for the example that i'm trying to pull off below. Call that new variable, and see if it matches the optionalThisTeamWon above...
    
//        switch optionalBriefDescription{
//            
//            case optionalThisTeamWon.
//                optionalBriefDescription = "In today's thriller match, the Miami Heat fired things up as they sizzled all over the court in what we can only describe as Lebron Jame's best gave ever!. We'll put in a description here later to let you know how this game went!"
//                    
//            case optionalThisTeamWon = "":
//                optionalBriefDescription = "-"
//            
//            
//            {
        
        return "In today's exciting game, \(optionalThisTeamWon) beat \(optionalThisTeamLost). The final score was \(optionalFinalMiamiScoreWas) to \(optionalFinalWizardScoreWas)! Stay tuned for the game highlights!"
        
        }


// 👆 recognize in the above line that parameters with default values are not required to have External Parameter Names assigned. The External Parameter Names are assigned to parameters with default values by default.
















// VARIADIC PARAMETERS - A Variadic Parameter accepts zero or more values of a specified type. You write a Variadic Parameter by inserting an elipsis (...) after a parameter's type name. 

    // The values passed to a Variadic Parameter are made available in the body of the function as an array of the appropriate type.


func arithmeticMean (numbers:Double...) -> Double{
    var total:Double = 0
    for number in numbers {
        total += number
    }
    return total/Double(numbers.count)
}

arithmeticMean(3,4,5,3,9,5,6,2,3)
arithmeticMean(3,8,19)

            // 👆 “A function may have AT MOST one variadic parameter, and it must ALWAYS appear last in the parameter list, to avoid ambiguity when calling the function with multiple parameters.”

            // “If your function has one or more parameters with a default value, and ALSO has a variadic parameter, place the variadic parameter after all the defaulted parameters at the very end of the list.”












//CONSTANT AND VARIABLE PARAMETERS

    // You can avoid defining a new variable yourself within the function by specifying one or more parameters as variable parameters instead.


func alignRight (var string:String, count:Int, pad:Character) -> String {
    let amountToPad = count - countElements(string)
    for _ in 1...amountToPad {
        string = String(pad) + string
    }
    return string

}


let originalString = "Hello"
let paddedString = alignRight(originalString, 10, "-")


paddedString
originalString


        // “The changes you make to a variable parameter do not persist beyond the end of each call to the function, and are not visible outside the function’s body. The variable parameter only exists for the lifetime of that function call.”











//IN AND OUT PARAMETERS

        // If you want a function to modify a parameter’s value, and you want those changes to persist after the function call has ended, define that parameter as an in-out parameter instead.

// Write an in-out parameter by placing the inout keyword at the start of its parameter definition.

// An in-out paramater has a value that's passed into the function, is modified by the function, and is passed back out of the function TO REPLACE THE ORIGINAL VALUE.

        // an in-out parameter cannot have default values
        // variadic values cannot be marked as in-out
        // if you mark a value as inout, it cannot also be marked as var or let
        // you can't pass in a string literal into an in-out parameter
        // YOU CAN ONLY PASS VARIABLES INTO IN-OUT PARAMETERS



func swapTwoInts (inout aaa:Int, inout bbb:Int) {
    let temporaryA = aaa
    aaa = bbb
    bbb = temporaryA
   
}


var someIntt = 3
var anotherIntt = 107
// swapTwoInts(&someInt, &anotherIntt)  // not exactly sure why this line doesn't work. Need to find out.

println("someInt is now \(someIntt), and anotherInt is now \(anotherIntt)")




func testFunction (inout testLetterA: String, inout testLetterB: String) -> String {
    return testLetterA + testLetterB + "equals what!?"
}
// testFunction(&"Two", &"Two")  // this one doesn't work either albeit i get a different error code


        // In-out parameters are not the same as returning a value from a function. A return value may not be defined but the function will still modify the values. In-out values are simply an alternative for a function to have an effect outside of the scope of its function's body.











// FUNCTION TYPES

func addTwoInts (intA:Int, intB:Int) -> Int {       // 👈This function type is (Int,Int) -> Int
    return intA + intB
}
addTwoInts(4, 9)



func multiplyTwoInts (intA:Int, intB:Int) -> Int {  // 👈 This function type is (Int,Int) -> Int
    return intA * intB
}
multiplyTwoInts(4, 9)



func printHelloWorld () {        // 👈 This "function type" is () -> () because it has no parameters and returns Void
    println("hello, world!")
}
printHelloWorld()

// Functions that don’t specify a return value always return Void, which is equivalent to an empty tuple in Swift, shown as ()




// 👇 I'm going to initiate a variable that's a function but i'll initiate it using the function type

var additionFunction: (Int,Int) -> Int = addTwoInts  // 👈 “Set this new variable to refer to the function called addTwoInts.”
additionFunction (9,4)



var newMultiplyFunction: (Int,Int) -> Int = multiplyTwoInts
newMultiplyFunction(9,4)

// 👆 Seems as if first we have to create the function above, then we can use its structure in a new function that mimics the initial function.



var newestMultipleFunction = newMultiplyFunction  // 👈notice that was done here
newestMultipleFunction(9,5) // this is the new function
newMultiplyFunction (9,5)   // notice i can still call this function


newestMultipleFunction = addTwoInts     // 👈switched the multiply function to an addition function
newestMultipleFunction(9,5)


func printMathResult (addTwoInts: (Int,Int) -> Int, a:Int, b:Int) { // a function w/in a function. Notice the function type
    println("Result: \(addTwoInts(a, b))")
}

printMathResult(addTwoInts, 8, 8)       // notice the structure in which i'm calling this function
printMathResult(addTwoInts, 9, 0)
printMathResult(newMultiplyFunction, 8, 9)

// 👆 “The role of printMathResult is to print the result of a call to a math function of an appropriate type.” Notice that, within printMathResult, i can call in whatever function i want as long as it fits the function type defined in printMathResult's definition. All that matters is that the function that i call in is of the correct type.




func stepForward (input:Int) -> Int {
    return input + 1
}

func stepBackward (input:Int) -> Int {
    return input - 1
}

stepBackward(9)
stepForward(9)



func chooseStepFunction (backwards:Bool) -> Int -> Int{ // the first Int is a function type, which will then return an Int
   
    return backwards ? stepBackward : stepForward   // notice question mark and colon between the two functions.
    
    // 👆the above line can also be written as:
        // if backwards {
        // return stepBackward
        // } else {
        // return stepForward
        // }
}


chooseStepFunction(true)(4)
var currentValue = 3

let moveNearerToZero = chooseStepFunction(currentValue > 0)(currentValue /* this can be any number or value*/)

// in the above line, because the boolean returns a true or false, it will determint whether stepBackward or stepForward gets used. As defined in the return structure when chooseStepFunction was created, it'll use stepBackward if it equates to true, and stepForward if false.



//  return backwards ? stepBackward : stepForward

    // essentially, the line above says return backwards based on a boolean which is visible via the question mark. If true, stepBackward will be used, else, stepForward function will be used.




println("Counting to zero....")
while currentValue != 0 {
    println("\(currentValue)...")
    currentValue = chooseStepFunction(currentValue > 0)(currentValue) // used the line instead of moveNearerToZero
 }
println("zero!")
// 👆in the above, when trying to use the moveNearerToZero, it continuously loops. Hopefully will find out why later











// NESTED FUNCTIONS

    // Nested Functions, as apposed to Global Functions, are functions that are defined inside the body of another function.
    // Nested Functions are hidden from the "outside world" by default, but can still be used by their enclosing function.
    // an enlcosing function can also return a nested function to be used in another function

// 👇 we'll rewrite chooseStepFunction to use and return nested functions.



func chooseStepFunction2 (backwards2:Bool) -> Int -> Int {
    func stepForward2 (input:Int) -> Int {
        return input + 1
    }
    func stepBackward2 (input:Int) -> Int{
        return input - 1
    }
    return backwards2 ? stepForward2 : stepBackward2
}

var currentValue2 = -4

// switch currentValue2:
// let moveNearerToZero2 = chooseStepFunction2(true)()

//while currentValue2 != 0 {
//    println("\(currentValue2)...")
//    // currentValue2 = chooseStepFunction2(currentValue2>0)
// }







// When talking about the "Scope" of a function in Swift, it simply means 'where that fuction can be called'. Is it global or nested(local)!?










// ****          ****
// **** CLOSURES ****
// ****          ****
// **** CLOSURES ****
// ****          ****
// **** CLOSURES ****
// ****          ****
// **** CLOSURES ****       
// ****          ****




// “Closures are self-contained blocks of functionality that can be passed around and used in your code.”

    // Closures can capture and store references to any constant & variable from context in which they are defined. This is known as "closing" over those constants and variables, hence the name “closures.
    // Global and Nested Functions are actually special cases of closure


// Closures can take one of 3 forms:
        // Global functions - are closures that have a name and do not capture any values.
        // Nested functions - are closures that have a name and can capture values from their enclosing function.
    // Closure expressions - are unnamed closures written in a lightweight syntax that can capture values from their surrounding context.



var newNames = ["Alex", "Chris", "Jonathan", "Ewa", "Barry", "Daniela"]

func backwards (s1:String, s2: String) -> Bool {
    return s1 > s2
}


// “For characters in strings, “greater than” means “appears later in the alphabet than” : B > A ; Tom > Tim; Z > A
// “For characters in strings, “less than” means “appears earlier in the alphabet than”  : A < C : Sam < Soft; A < Z

// the

var reversed: () = sort(&newNames, backwards)   // Sort mutates (no 'let') the array and returns a brand new array
var newReversed = sorted(newNames, backwards)   // Sorted doesn't modify the array and returns a new sorted array
// 👆 in the above examples, use Sorted instead of Sort as listed in apple's Swift book

println(reversed)
println(newReversed)




func forwards (s1: String, s2: String) -> Bool {
    return s1 < s2
}
var forwardSort = sorted(newNames, forwards)    // sorted is a Closure



// 👆 The above function and sorting would be easier written using 'Closure Expression Syntax'

    // Closure expression syntax can use constant parameters, variable parameters, and inout parameters.
        // Default values cannot be provided.
        // Variadic parameters can be used if you name the variadic parameter and place it last in the parameter list.
        // Tuples can also be used as parameter types and return types.



newReversed = sorted(newNames, {(s1:String, s2: String) ->
    
    Bool in return s2 < s1 })

        //👆 “The start of the closure’s body is introduced by the 'in' keyword. ”

// 👆 “for the inline closure expression, the parameters and return type are written inside the curly braces, not outside of them.”


var newForward = sorted(newNames, {(s1:String, s2: String) ->
    Bool in return s2 > s1 })

































































// MAKE A FUNCTION THAT WILL TAKE IN A STRING VALUE, AND RETURN THE STRING VALUE IN ALL CAPS

//func makeAllCaps (makeThisStringAllCaps:String) {
//    println("\(makeThisStringAllCaps)")
//}
//
//makeAllCaps("Let's make this string all caps!")
//
//var uppCase: () = makeAllCaps("Let's make this string all caps!")
//








