import UIKit

func fizzBuzz() {
    for i in 1...100 {
        if i % 3 == 0 {
            print("fizz")
        }else if i % 5 == 0{
            print("buzz")
        }else if i % 3 == 0 && i % 5 == 0 {
            print("fizzBuzz")
        }else {
            print(i)
        }
    }
}
fizzBuzz()

