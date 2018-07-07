//I am a cool kid trying to survive in this dark world .... =D

/*Given an array of numbers, 
replace each number with the product of all the numbers in the array except the number itself *without* using division.
*/

var array = [1,2,3,4,5,6,7]
let product = array.reduce(1){$0 * $1}
array = array.map{
    var result = product
    var newItem = 0
    while result != 0 {
        newItem += 1
        result -= $0
    }
    return newItem
}
print(array)

/* didnt work but was my first idea but since item is a copy of an item on the array and not the item itself(ididntknowthat=D)
for item in array {
    var newItem = 0
    while result != 0 {
        newItem += 1
        result -= item
    }
    item = newItem
}
*/
