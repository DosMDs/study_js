## Что такое алгоритм?

**Алгоритм** — это пошаговая инструкция или набор правил, которые нужно выполнить, чтобы решить задачу. Алгоритмы используются не только в программировании, но и в повседневной жизни.

**Пример из жизни:**

Допустим, ты хочешь приготовить чай. Вот пример алгоритма:

Вскипятить воду.

Положить пакетик чая в кружку.

Налить кипяток в кружку.

Добавить сахар (если хочется).

Подождать 3 минуты.

Наслаждаться чаем.

В программировании алгоритмы работают так же: они описывают, как решить задачу шаг за шагом.

---

## Как решать задачи с помощью алгоритмов?

Давай разберем пошагово, как решать задачи с помощью алгоритмов.

---

### Пример задачи 1: Сложение двух чисел

**Задача:** Напишите программу, которая складывает два числа, введенных пользователем, и выводит результат.

---

#### Шаг 1: Понять задачу
- Нужно получить два числа от пользователя.
- Сложить эти числа.
- Показать результат.

---

#### Шаг 2: Разбить задачу на шаги
1. Спросить у пользователя первое число.
2. Спросить у пользователя второе число.
3. Сложить два числа.
4. Показать результат.

---

#### Шаг 3: Написать код на JavaScript

```javascript
// Шаг 1: Спросить у пользователя первое число
let number1 = prompt("Введите первое число:");

// Шаг 2: Спросить у пользователя второе число
let number2 = prompt("Введите второе число:");

// Шаг 3: Сложить два числа
// Преобразуем строки в числа с помощью Number()
let result = Number(number1) + Number(number2);

// Шаг 4: Показать результат
alert("Сумма чисел: " + result);
```

---

#### Шаг 4: Проверить алгоритм
1. Введи первое число: `5`
2. Введи второе число: `3`
3. Результат: `8`

---

### Пример задачи 2: Определение четности числа

**Задача:** Напишите программу, которая проверяет, является ли число четным или нечетным.

---

#### Шаг 1: Понять задачу
- Нужно получить число от пользователя.
- Проверить, делится ли оно на 2 без остатка.
- Если делится — число четное, если нет — нечетное.

---

#### Шаг 2: Разбить задачу на шаги
1. Спросить у пользователя число.
2. Проверить, делится ли число на 2.
3. Если делится, вывести "Четное".
4. Если не делится, вывести "Нечетное".

---

#### Шаг 3: Написать код на JavaScript

```javascript
// Шаг 1: Спросить у пользователя число
let number = prompt("Введите число:");

// Шаг 2: Проверить, делится ли число на 2
if (number % 2 === 0) {
    // Шаг 3: Если делится, вывести "Четное"
    alert("Число " + number + " — четное.");
} else {
    // Шаг 4: Если не делится, вывести "Нечетное"
    alert("Число " + number + " — нечетное.");
}
```

---

#### Шаг 4: Проверить алгоритм
1. Введи число: `4`
   - Результат: "Число 4 — четное."
2. Введи число: `7`
   - Результат: "Число 7 — нечетное."

---

### Пример задачи 3: Поиск максимального числа

**Задача:** Напишите программу, которая находит максимальное число из трех введенных пользователем чисел.

---

#### Шаг 1: Понять задачу
- Нужно получить три числа от пользователя.
- Найти самое большое из них.

---

#### Шаг 2: Разбить задачу на шаги
1. Спросить у пользователя первое число.
2. Спросить у пользователя второе число.
3. Спросить у пользователя третье число.
4. Сравнить числа и найти максимальное.
5. Показать результат.

---

#### Шаг 3: Написать код на JavaScript

```javascript
// Шаг 1: Спросить у пользователя первое число
let number1 = Number(prompt("Введите первое число:"));

// Шаг 2: Спросить у пользователя второе число
let number2 = Number(prompt("Введите второе число:"));

// Шаг 3: Спросить у пользователя третье число
let number3 = Number(prompt("Введите третье число:"));

// Шаг 4: Сравнить числа и найти максимальное
let maxNumber = Math.max(number1, number2, number3);

// Шаг 5: Показать результат
alert("Максимальное число: " + maxNumber);
```

---

#### Шаг 4: Проверить алгоритм
1. Введи первое число: `5`
2. Введи второе число: `12`
3. Введи третье число: `7`
   - Результат: "Максимальное число: 12"

---

## Как улучшить алгоритмы?

Хороший алгоритм должен быть:
1. **Понятным** — легко читать и понимать.
2. **Эффективным** — выполнять задачу быстро.
3. **Чистым** — код должен быть организован и легко поддерживаемым.

---
