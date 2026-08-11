We can simply get have have a if else block compressed like this in Kotlin

```
fun fish_congradulator(number_of_fish:Int){  
  
    when(number_of_fish){  
        0 -> println("Where is the fish bruhhh")  
        in 1..50 -> println("We have between 1 and 50 fish")  
        else -> println("We have a lot a fish and this is how much we have: ${number_of_fish}" )  
    }  
}  
  
fun main (){  
    fish_congradulator(55)  
}  
  
main()
```

