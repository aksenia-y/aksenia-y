Exercises for lecture №19 - String
В середині exercises створіть піддиректорію lecture-19. В середині lecture-19 створіть файли index.html та app.js

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

	<link rel="shortcut icon" href="/favicon.ico" type="image/x-icon">

</head>
<body>

    <script src="app.js"></script>

</body>
</html>
Маємо код
let str1 = 'I\'m a string!';
let str2 = "I'm a string!";
Чи мають рядки str1 та str2 однакову довжину. Перевірити на рівність (недбалу та строгу) рядки str1 та str2.

Повернути перший символ рядка string5. Виконайте завдання, використовуючи індекс та метод charAt.
let string5 = 'Hello World';
повернути символ J рядка str3:
// повернути символ J рядка:
let str3 = "Hello Javascript";
Використовуючи індекс, отримати доступ до останнього символу рядка двома способами

Напишіть три варіанти функції lastChar, що повертає останній символ рядка

Маємо код

let a = 'When candles are out,';
let b = 'all cats are grey.';
Використовуючи метод concat, вивести на консоль: When candles are out, all cats are grey

Маємо код
let fact = "Fifteen is the same as"
let a = 5;
let b = 10;
Використовуючи змінні a, b, fact, змінити значення fact та вивести його на консоль, щоб результат виглядав так: Fifteen is the same as 15

Маємо код
let firstName = "Tom";
let lastName = "Cat";
Напишіть функцію getFullName, що повертає результат: "Tom Cat"

Напишіть функцію greeting, що використовує виклик функції getFullName та повертає такий результат: Hello, Tom Cat!

Використовуючи функцію greeting, створити такий шаблон:

<div><h1>Hello, Tom Cat!</h1></div>
Маємо наступний код:
let string1 = "  The name of our game  ";

// Потрібно отримати такі результати
// "The name of our game"
// "The name of our game  "
// "  The name of our game"


const phoneNumber = '\t  555-123\n ';
// Потрібно отримати такі результати
// => '555-123'
// => '555-123 \n'
Маємо наступний код:
let sentence = 'Always look on the bright side of life';
Перевірити, чи містить рядок значення 'look up'
Перевірити, чи містить рядок значення 'look on'
Перевірити, чи містить рядок значення 'look on'Б починаючи з 8-ї позиції
Маємо наступний код
let sentence = 'Always look on the bright side of life';
Знайти індекс символу 'l'
Знайти індекс символу 'l', починаючи з 3-ї позиції
Знайти індекс символу 'L'
Маємо наступний код:
let sentence = 'Always look on the bright side of life';
Отримати підрядок 'look on the bright side of life'
Отримати підрядок 'Always'
Отримати підрядок 'look'
Створити регулярний вираз, який призначений для перевірки імені користувача, що може містити цифри, літери у нижньому регістрі та символи - і _. Довжину імені користувача встановити від 8 до 16 знаків.

Створити регулярний вираз, який призначений для перевірки email на коректність.

Маємо наступний код:

let sentence = 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi in sapien eu velit eleifend ullamcorper eget vitae nulla. Aenean euismod purus sed neque dictum, nec lobortis ante faucibus.';
Напишіть функцію truncateText скорочення тексту до 50 символів, використовуючи метод substring
Напишіть функцію truncateText скорочення тексту до 50 символів, використовуючи метод substr