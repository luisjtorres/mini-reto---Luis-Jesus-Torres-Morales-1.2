# mini-reto---Luis-Jesus-Torres-Morales-1.2
mini reto de la segunda semana
//: Playground - noun: a place where people can play

import UIKit
//Luis Jesus Torres Morales
for n in 0 ... 100 {
    
    if (n >= 30 && n <= 40) {
        if (n%2==0){
    if (n % 5 == 0) {
            print (n, "PAR", "BINGO!!!", "VIVA SWIFT!!!")
             } else {print (n, "PAR", "VIVA SWIFT")}

        }else {if (n % 5 == 0) {
            print (n, "IMPAR", "BINGO", "VIVA SWIFT!!!")
        }else {print (n, "IMPAR", "VIVASWIFT")
}
}
}

else if (n%2==0) {
    if (n%5==0){
        print (n, "PAR", "BINGO!!!")
    } else {print (n, "PAR")}
    
    }else{if (n%5==0){
        print (n, "IMPAR", "BINGO")}
    else {
        print (n, "IMPAR")
        }
        }
}
