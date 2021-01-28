# Java guide

# СОДЕРЖАНИЕ

- [ТЕМЫ](#ТЕМЫ)
    - ИСТОРИЯ JAVA
    
- [УПРАЖНЕНИЯ](#УПРАЖНЕНИЯ)
- [ПОЛЕЗНЫЕ ИСТОЧНИКИ](#ПОЛЕЗНЫЕ-ИСТОЧНИКИ)

---------------------------
# ТЕМЫ

## Java

- [ООП](https://github.com/OlgaKirshbaum/Android-Developer-Guide/blob/main/OOP%20Guide.md)

  
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
        
- Устройство платформы Java

    - История Java
    - Кроссплатформенность
    - JVM
        - Interpreter
        - JIT
        - Byte code verifier
        - Gardage collector (GC)
    - JRE, JDK, Interpreter, JIT
    - Vm start parametrs 
    
- Отладка и сборка мусора 
    - Логирование
    - Отладка 
        - Запуск в debug режиме
        - Debug окно
        - Настройки и параметры Breakpoints
        - Evaluate expression
    - Remote debug
    - jconsole
        - Подключение к процессу 
        - Память 
        - Процессор
        - Потоки
        
    - JMX, MBeans
    - Сборка мусора
        - Поиск недостижимых объектов
        - Освобождение памяти 
        - Вызов Finalize
        
    - Виды GC, алгоритмы GC
    - GC roots
    - Типы ссылок
    
- Коллекции в Java
    - Классы-контейнеры
        - Collections
        - HashSet
        - Map
        - Хэш-структуры
        
- Исключения

- Java INPUT/OUTPUT
    - Класс File
    - RandomAccessFile
    - InputStream / OutputStream
    - Обработка исключений
    - Символьные потоки Reader / Wtiter
    - PrintStream
   
-----------------------------------------------------------------------

# УПРАЖНЕНИЯ

# Упражнения по Java

<details>
<summary>Подробнее ...</summary>
Здесь собраны мои простые учебные коды по Java
//Можно использовать для тренировки: https://ideone.com/
</details>

----------------------------------------------------------------------------
# Упражнения по Java

### Список уроков

- [Урок 1](#Урок-1) - Знакомство. Создание объекта    
- [Урок 2](#Урок-2) - class Object и его основные методы    
- [Урок 3](#Урок-3)    

----------------------------------------------------------------------------

## Урок 1 

#### Знакомство.

- Создали объект в классе с которым можем производить действия.

```java

package ru.olgakirshbaum

public class MyFirstClass {

public static void main(String[]) {
// Здесь пишем код

//Создаем объекты
MyFirstClass my = null;
System.out.println(my);

}

}
```
###### В онлайн компияторе: 
```java
/* package whatever; // don't place package name! */

import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Ideone
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		
		Ideone my = null;
System.out.println(my);
	}
}
```

- [Список уроков](#Список-уроков)    
- [Содержание](#Содержание)    

----------------------------------------------------------------------------

## Урок 2

- class Object и его основные методы
- Массивы в java

```java
package ru.Arima

import java.util.Arrays;

public class Main {

    public static void main(String... args){
        System.out.println("start");
        throw new RuntimeException("hello");
        //System.out.println("finish");
    }

    private static void arraysHelperExample() {
        int[] values = new int[]{1, 1, 2, 3, 5, 8, 13};
        System.out.println(Arrays.binarySearch(values, 5));
        System.out.println(Arrays.toString(values));
    }

    private static void stringsExample() {
        String str1 = "abc";
        String str2 = new String(new char[]{'a', 'b', 'c'});

        System.out.println(str1);
        System.out.println(str2);
        System.out.println(str1.equals(str2));

        System.out.println(str1.contains("bc"));

        System.out.println("a" + "b" + "d");

        StringBuilder tmp = new StringBuilder();
        for (int i = 0; i < 100; i++) {
            tmp.append(i).append("_");
        }
        System.out.println(tmp.toString());
    }

    private static void arraysExample() {
        int[] anArray1 = new int[10];
        int[] anArray2 = {0, 1, 2, 3};
        MyClass[] objArray = new MyClass[5];

        System.out.println(objArray.toString());
        for (int i = 0; i < objArray.length; i++) {
            objArray[i] = new MyClass(i);
        }

        for (int i = 0; i < objArray.length; i++) {
            MyClass element = objArray[i];
            System.out.println(element);
        }
    }

    private static void equalsExample() {
        MyClass myClass1 = new MyClass();
        System.out.println(myClass1.toString());

        MyClass myClass2 = new MyClass();
        System.out.println(myClass2.toString());

        System.out.println(myClass1 == myClass2);
        System.out.println(myClass1.equals(myClass2));
    }
}
public class 

//Второй класс

package ru.Arima

public class MyClass {
    int a = 10;
    boolean t = true;

    public MyClass(){}

    public MyClass(int a) {
        this.a = a;
    }

    @Override
    public String toString() {
        return "MyClass{" +
                "a=" + a +
                ", t=" + t +
                '}';
    }
}

```
- [Список уроков](#Список-уроков)    
- [Содержание](#Содержание)      

----------------------------------------------------------------------------

## Урок 3

```java

```

- [Список уроков](#Список-уроков)    
- [Содержание](#Содержание)    

----------------------------------------------------------------------------

## Урок 

```java

```

- [Список уроков](#Список-уроков)    
- [Содержание](#Содержание)    

----------------------------------------------------------------------------


-----------------------------------------------------------------------

# ПОЛЕЗНЫЕ ИСТОЧНИКИ:

- [Официальная документация](https://docs.oracle.com/javase/tutorial/java/)

- Подготовить среду разработки. [Скачать](https://www.eclipse.org/downloads/) и установить Eclipse.    
- [Онлайн компилятор](https://ideone.com/).


- [Содержание](#Содержание)    

-----------------------------------------------------------------------

    
    
