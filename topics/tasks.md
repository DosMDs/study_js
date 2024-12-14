Конечно! Вот набор задач для закрепления следующих тем: **Переменные**, **Типы данных**, **Условия**, **Циклы**, **Массивы** и **Функции**. Каждая задача сопровождается решением.

---

### 1. **Переменные**

#### Задача 1: Объявление переменных
Создайте три переменные: `name`, `age` и `isStudent`. Присвойте им значения: ваше имя, ваш возраст и булево значение, указывающее, являетесь ли вы студентом. Выведите значения переменных в консоль.

<details>
    <summary>Решение</summary>
    ```javascript
    let name = "Алексей";
    let age = 25;
    let isStudent = true;

    console.log("Имя:", name);
    console.log("Возраст:", age);
    console.log("Студент:", isStudent);
    ```
</details>

**Вывод:**
```
Имя: Алексей
Возраст: 25
Студент: true
```

---

### 2. **Типы данных**

#### Задача 2: Определение типов данных
Создайте переменные с разными типами данных: строка, число, булево значение, массив и объект. Используя оператор `typeof`, выведите тип каждой переменной в консоль.

<details>
    <summary>Решение</summary>
    ```javascript
    let str = "Привет";
    let num = 42;
    let bool = true;
    let arr = [1, 2, 3];
    let obj = { name: "Алексей", age: 25 };

    console.log(typeof str); // string
    console.log(typeof num); // number
    console.log(typeof bool); // boolean
    console.log(typeof arr); // object
    console.log(typeof obj); // object
    ```
</details>

**Вывод:**
```
string
number
boolean
object
object
```

---

### 3. **Условия**

#### Задача 3: Проверка возраста
Создайте переменную `age` и присвойте ей значение 17. Напишите условие, которое проверяет, является ли человек совершеннолетним (возраст >= 18). Если да, выведите "Вы совершеннолетний", иначе выведите "Вы несовершеннолетний".

<details>
    <summary>Решение</summary>
    ```javascript
    let age = 17;

    if (age >= 18) {
    console.log("Вы совершеннолетний");
    } else {
    console.log("Вы несовершеннолетний");
    }
    ```
</details>

**Вывод:**
```
Вы несовершеннолетний
```

---

### 4. **Циклы**

#### Задача 4: Вывод чисел
Создайте цикл `for`, который выводит числа от 1 до 10 в консоль.

<details>
    <summary>Решение</summary>
    ```javascript
    for (let i = 1; i <= 10; i++) {
    console.log(i);
    }
    ```
</details>

**Вывод:**
```
1
2
3
4
5
6
7
8
9
10
```

---

### 5. **Массивы**

#### Задача 5: Работа с массивом
Создайте массив `fruits` с элементами: "яблоко", "банан", "груша". Добавьте в конец массива "апельсин". Удалите первый элемент массива. Выведите массив в консоль.

<details>
    <summary>Решение</summary>
    ```javascript
    let fruits = ["яблоко", "банан", "груша"];
    fruits.push("апельсин");
    fruits.shift();

    console.log(fruits); // ["банан", "груша", "апельсин"]
    ```
</details>

**Вывод:**
```
["банан", "груша", "апельсин"]
```

---

### 6. **Функции**

#### Задача 6: Сумма чисел
Создайте функцию `sum`, которая принимает два числа и возвращает их сумму. Вызовите функцию с аргументами 5 и 7 и выведите результат в консоль.

<details>
    <summary>Решение</summary>
    ```javascript
    function sum(a, b) {
    return a + b;
    }

    console.log(sum(5, 7)); // 12
    ```
</details>

**Вывод:**
```
12
```

---

### 7. **Комбинированные задачи**

#### Задача 7: Поиск максимального числа
Создайте массив `numbers` с числами: 10, 5, 20, 15. Напишите функцию `findMax`, которая принимает массив и возвращает максимальное число. Вызовите функцию и выведите результат в консоль.

<details>
    <summary>Решение</summary>
    ```javascript
    function findMax(numbers) {
    let max = numbers[0];
    for (let i = 1; i < numbers.length; i++) {
        if (numbers[i] > max) {
        max = numbers[i];
        }
    }
    return max;
    }

    let numbers = [10, 5, 20, 15];
    console.log(findMax(numbers)); // 20
    ```
</details>

**Вывод:**
```
20
```

---

### 8. **Задача с использованием всех тем**

#### Задача 8: Фильтрация массива
Создайте массив `numbers` с числами: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10. Напишите функцию `filterEven`, которая принимает массив и возвращает новый массив, содержащий только четные числа. Вызовите функцию и выведите результат в консоль.

<details>
    <summary>Решение</summary>
    ```javascript
    function filterEven(numbers) {
    let evenNumbers = [];
    for (let num of numbers) {
        if (num % 2 === 0) {
        evenNumbers.push(num);
        }
    }
    return evenNumbers;
    }

    let numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
    console.log(filterEven(numbers)); // [2, 4, 6, 8, 10]
    ```
</details>

**Вывод:**
```
[2, 4, 6, 8, 10]
```

---