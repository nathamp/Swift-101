# Swift-101
Playing around in Playground. Nothing fancy to see here...


JUST TESTING TO SEE IF THIS CHANGE WILL BE ADDED!!!! HOPEFULLY IT DOES!!
ADDITIONALLY, I CAN ADD LINES OF CODE FROM THE WEBSITE AS WELL! NOW TO TEST TO SEE HOW GITHUB ON MAC WILL DISPLAY EVERYTHING IN ONE WINDOW

UPDATE DONE FROM ATOM!!! NICE TEXT EDITOR. I THINK I WILL HOWEVER MAYBE SWITCH THE THEME UP



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
