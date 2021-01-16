# Android Developer Guide - road-map

Справочник по тому, что надо знать андроид разработчику ссылки в перечне на официальные источники + самые понравившиеся.
<details>
<summary>Условные обозначения ...</summary>
    :red_circle: - Знать обязательно    
    :large_blue_circle:- Знать желательно    
    :white_circle: - Знать не обязательно    
    :black_square_button: - Не готово    
    :white_check_mark: - Готово    
</details>

> ### Рекомендация: 
> Если вы недостаточно хорошо знаете английский язык, можно воспользоваться например браузером яндекс. В нем есть переводчик. Это же можно использовать и с телефона. 

-----------------------------------------------

## Содержание
:red_circle:1. Programming Language
    - :red_circle: [Java](#Java)
        - :red_circle: [ООП](#ООП) 
    - :red_circle: [Kotlin](#Kotlin) 
       
:red_circle:2. Android Studio 
    - Debugger
    - CPU Profiler
    - [Android SDK](#Android-SDK) 
        - Android Debug Bridge
        - Emulator
        - SDK Manager
    - File formats 
        - XML
:red_circle:3. App Manifest
    - Data Backup
    - Permissions
    - App Components
:red_circle:4. App Components
:red_circle:5. User Interface
:red_circle:6. More User Interface
:red_circle:7. Accessibility
:red_circle:8. Storage
:red_circle:9. Architecture
:red_circle:10. Build Configuration
:red_circle:11. Thread Handling
:red_circle:12. Network Handling
:red_circle:13. Android Jetpack
:red_circle:14. Architecture components
:red_circle:15. Google Libraries
:red_circle:16. Security
:red_circle:17. Sensors
:red_circle:18. Content Providers
:red_circle:19. Animation
:red_circle:20. App Publishing

Keep learning...

:large_blue_circle: Hubrid
:large_blue_circle:


    
    
    
    - :large_blue_circle: [Git](#Git) 
    - :large_blue_circle: [GitHub](#GitHub)  

-----------------------------------------------

## Java
- [Официальная документация](https://docs.oracle.com/javase/tutorial/java/)
- Подготовить среду разработки. [Скачать](https://www.eclipse.org/downloads/) и установить Eclipse.    
  Или можно использовать [онлайн компилятор](https://ideone.com/).
  
- Базовые синтаксические конструкции и операторы в Java :white_check_mark:
    - Типы данных:
        - [Примитивные](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)
            - Преобразование типов
            - Битовые операторы, битовые маски
            - Логические и математические операторы
            - Приоритеты
            - Управление логикой работы приложения 
            - Циклы 
            - Структура консольного Java приложения
        - Ссылочные 
            - Класс и объект, создание объекта
            - Поля и методы класса 
            - Области видимости
            - Передача по ссылке
            
    - Работа с массивами и строками
        - class Object
            - Основные методы 
                - public String toString()
                - public boolean equals(Object obj)
                - public int hashCode()
                - protected Object clone()
                - public Class<?>getClass
                - public notify()
                - public notifyAll()
                - public wait()
                
        - == и equals()
        - массивы 
        - String
        - StringBuilder
        - перегрузка методов
        - java.util.Arrays
    

[:arrow_up: Содержание](#Содержание)

-----------------------------------------------

## ООП
- [Официальная документация](https://docs.oracle.com/javase/tutorial/java/concepts/index.html)

+ [Что такое _ООП_?](OOP.md#Что-такое-ООП)
- Наследование, extends
- Полиморфизм
- Абстракция, интерфейс, implements
- Ссылки между объектами
- Инкапсуляция, модификаторы доступа
- Ключевые слова this, super
- Generics


[:arrow_up: Содержание](#Содержание)

-----------------------------------------------

## Kotlin

- [Официальная документация Kotlin](https://kotlinlang.org/docs/reference/)
- [ПРАКТИКА по Kotlin](#https://github.com/OlgaKirshbaum/Android-Developer-Guide/blob/main/Kotlin%20упражнения.md)

[:arrow_up: Содержание](#Содержание)

-----------------------------------------------

## Git 

- Git [Официальное руководство](https://git-scm.com/book/ru/v2)

[:arrow_up: Содержание](#Содержание)

-----------------------------------------------
## GitHub

- GitHub [Официальное руководство](https://docs.github.com/en)

[:arrow_up: Содержание](#Содержание)

-----------------------------------------------

## Android SDK
- [Официальная документация](https://developer.android.com/studio)
1. Подготовка рабочего окружения
    1. Скачать и установить Android Studio [Скачать с официального сайта](https://developer.android.com/studio) :white_check_mark:
       <details>
       <summary>Подробнее ...</summary>
        JDK скачивать не надо. Он идет в комплекте. А вот Git пригодится.
       </details>

    2. Скачать и установить Git [Скачать с официального сайта](https://git-scm.com/downloads) :white_check_mark:
    3. Зарегистрироваться (например на GitHub) :white_check_mark:


[:arrow_up: Содержание](#Содержание)

-----------------------------------------------



