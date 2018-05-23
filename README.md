# Q.TwoNumberInputAndOutputPlusTwoNumber


## *두 개의 정수를 입력받아 두 수를 하나로 합친 결과를 출력하는 함수 (1, 5 입력 시 15 반환)*
````
func getAdd(_ num: Int , _ num2: Int) -> String{
    let result: String = String(num) + String(num2)
    return result
}
print(getAdd(1, 5))
````

````
func addNum(_ num1 :Int,_ num2 :Int){
    print(String(num1) + String(num2))
}
addNum(1,2)
````

````
func addCharacter(first:String, second:String) -> String {
    let result = first + second
    print(result)
    return result
}
addCharacter(first: "1", second: "5")
````

