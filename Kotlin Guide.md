# Kotlin

# СОДЕРЖАНИЕ

- [](#)
- [Упражнения Kotlin](#)
- [Полезные источники](#Полезные-источники)



---------------------------------------------------------------------------------------------------------------------

# Упражнения Kotlin 

<details>
<summary>Подробнее ...</summary>
Здесь собраны мои простые учебные коды по Kotlin 
//Можно использовать онлайн площадку для тренировки: https://developer.android.com/training/kotlinplayground
</details>

## Список уроков

- [Урок 1](#Урок-1)
- [Урок 2](#Урок-2)

- ПРАКТИЧЕСКИЕ КУРСЫ ПО КОТЛИН (ОФИЦИАЛЬНЫЕ):
     - [ИГРОВАЯ ПЛОЩАДКА от Kotlin](https://play.kotlinlang.org/#eyJ2ZXJzaW9uIjoiMS40LjIwIiwicGxhdGZvcm0iOiJqYXZhIiwiYXJncyI6IiIsImpzQ29kZSI6IiIsIm5vbmVNYXJrZXJzIjp0cnVlLCJ0aGVtZSI6ImlkZWEiLCJjb2RlIjoiLyoqXG4gKiBZb3UgY2FuIGVkaXQsIHJ1biwgYW5kIHNoYXJlIHRoaXMgY29kZS4gXG4gKiBwbGF5LmtvdGxpbmxhbmcub3JnIFxuICovXG5cbmZ1biBtYWluKCkge1xuICAgIHByaW50bG4oXCJIZWxsbywgd29ybGQhISFcIilcbn0ifQ==)
     - Котлин [Практические Занятия](https://play.kotlinlang.org/hands-on/overview) 
     - [Котлинские Коаны](https://play.kotlinlang.org/koans/overview) 
     - [Онлайн компилятор для Kotlin от Android](https://developer.android.com/training/kotlinplayground)



----------------------------------------------------------------------------

## Урок 1 

### Кубики. Случайное число. 
- Полностью упражнение [ЗДЕСЬ](https://developer.android.com/codelabs/basic-android-kotlin-training-create-dice-roller-in-kotlin#0)

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

[Содержание](#Содержание)

----------------------------------------------------------------------------

## Урок 2






[Содержание](#Содержание)

----------------------------------------------------------------------------






[:arrow_up: Список уроков](#Список-уроков)    
[:arrow_up: Содержание](#Содержание) 
---------------------------------------------------------------------------------------------------------------------

# ПОЛЕЗНЫЕ ИСТОЧНИКИ

- [Официальная документация Kotlin](https://kotlinlang.org/docs/reference/)
- [ПРАКТИКА по Kotlin](#https://github.com/OlgaKirshbaum/Android-Developer-Guide/blob/main/Kotlin%20упражнения.md)
- [Руководство по стилю Котлина](https://developer.android.com/kotlin/style-guide)
- [онлайн площадку для тренировки](https://developer.android.com/training/kotlinplayground)

[:arrow_up: Содержание](#Содержание) 
