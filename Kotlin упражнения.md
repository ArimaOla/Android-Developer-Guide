
# Упражнения Kotlin 
<details>
<summary>Подробнее ...</summary>
Здесь собраны мои простые учебные коды по Kotlin 
//Можно использовать онлайн площадку для тренировки: https://developer.android.com/training/kotlinplayground
</details>

## Содержание

- [Урок 1](#Урок-1)
- [Урок 2](#Урок-2)


[Содержание](#Содержание)

----------------------------------------------------------------------------

## Урок 1 

### Кубики. Случайное число. 



```kotlin

fun main() {
    val myFirstDice = Dice(6)
    val diceRoll = myFirstDice.roll()
    println("Your ${myFirstDice.numSides} sided dice rolled ${diceRoll}!")
    
    val mySecondDice = Dice(20)
    println("Your ${mySecondDice.numSides} sided dice rolled ${mySecondDice.roll()}!")
}

class Dice (val numSides: Int) {

    fun roll(): Int {
        return (1..numSides).random()
    }
}
```

----------------------------------------------------------------------------

## Урок 2
