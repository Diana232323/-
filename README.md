<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Учимся программировать!</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- Подключаем Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Fredoka+One&family=Nunito:wght@400;700&display=swap" rel="stylesheet">
  <style>
    /* Сброс стилей */
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Nunito', sans-serif;
      background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%);
      color: #333;
      line-height: 1.6;
    }
    a { color: #ff6f61; text-decoration: none; transition: color 0.3s; }
    a:hover { color: #e6554d; }
    /* Заголовок */
    header {
      background-image: url('https://source.unsplash.com/1600x900/?coding,programming');
      background-size: cover;
      background-position: center;
      color: #fff;
      padding: 80px 20px;
      text-align: center;
      position: relative;
    }
    header::after {
      content: "";
      position: absolute; top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(0, 0, 0, 0.4);
      z-index: 0;
    }
    header h1, header p { position: relative; z-index: 1; }
    header h1 { font-family: 'Fredoka One', cursive; font-size: 2.8em; margin-bottom: 20px; }
    header p { font-size: 1.3em; }
    /* Навигация */
    nav {
      background-color: #333;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }
    nav a {
      display: inline-block;
      padding: 16px 24px;
      color: #f2f2f2;
      transition: background-color 0.3s, color 0.3s;
    }
    nav a:hover { background-color: #ff6f61; color: #fff; }
    /* Контейнер */
    .container {
      max-width: 1200px;
      margin: 20px auto;
      padding: 0 20px;
    }
    /* Карточки */
    .card {
      background-color: #fff;
      border-radius: 12px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.15);
      padding: 20px;
      margin-bottom: 20px;
      transition: transform 0.3s;
    }
    .card:hover { transform: translateY(-4px); }
    /* Заголовки в карточках */
    h2 { font-family: 'Fredoka One', cursive; margin-bottom: 12px; font-size: 2em; color: #ff6f61; }
    /* Стили для списков */
    ul { list-style: none; padding: 0; }
    li { border-bottom: 1px dashed #ddd; padding: 12px 0; margin-bottom: 10px; }
    /* Стили для блоков с кодом */
    .code-block {
      background: #e8e8e8;
      padding: 12px;
      border-radius: 6px;
      overflow-x: auto;
      font-family: Consolas, "Courier New", monospace;
      margin-top: 10px;
    }
    /* Иллюстрации */
    .illustration {
      display: block;
      max-width: 100%;
      margin: 20px auto;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.15);
    }
    /* Подвал */
    footer {
      background-color: #ff6f61;
      color: #fff;
      text-align: center;
      padding: 20px;
      box-shadow: 0 -2px 5px rgba(0,0,0,0.2);
      margin-top: 40px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <!-- Заголовок сайта -->
  <header>
    <h1>Весёлое программирование!</h1>
    <p>Весёлые уроки и готовые проекты для начинающих программистов</p>
  </header>
  
  <!-- Навигация -->
  <nav>
    <a href="#intro">Главная</a>
    <a href="#lessons">Весёлый код</a>
    <a href="#projects">Попробуй создать проект!</a>
    <a href="#about">О сайте</a>
    <a href="#contact">Контакты</a>
  </nav>
  
  <!-- Основное содержимое -->
  <div class="container">
    <!-- Раздел "О сайте" (главная страница) -->
    <section id="intro" class="card">
      <h2>О сайте</h2>
      <p>Если ты находишься здесь, значит ты уже выполнил основные задания на урок, теперь смело можешь попробывать дополнительные "Весёлые коды!". 

"Программирование — это как решать головоломки! Чем больше загадок разгадаешь, тем круче становишься!".</p>
      <img class="illustration" src="https://source.unsplash.com/800x400/?coding,cartoon" alt="Весёлое программирование">
    </section>
    
    <!-- Раздел "Весёлые коды" (скрыт по умолчанию) -->
    <section id="lessons" class="card">
      <h2>Весёлые коды</h2>
      <p>60 веселых примеров кода, которые добавят улыбку и вдохновение!</p>
      <ul>
        <!-- Каждый элемент списка содержит название и блок с кодом, который всегда виден -->
        <li>
          <strong>Весёлый код от 1: Весёлое приветствие</strong>
          <div class="code-block">
            <code># Весёлый старт:
print("Привет! Готов к приключениям в мире Python? Давай веселиться!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 2: Необычное приветствие</strong>
          <div class="code-block">
            <code># Вместо простого Hello, world!:
print("Привет, мир! Ты сегодня выглядишь потрясающе!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 3: Весёлые переменные</strong>
          <div class="code-block">
            <code># Весёлые переменные:
magic_number = 42
joke = "Почему число 6 боится 7? Потому что 7 8 9!"
print("Магическое число:", magic_number)
print("Смешная загадка:", joke)</code>
          </div>
          <div class="code-block">
            <code># Форматирование строки:
age = 12
print(f"Привет, друг! Тебе уже {age} лет, а мир Python ждет тебя!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 4: Весёлая математика</strong>
          <div class="code-block">
            <code>import random
a = random.randint(1, 10)
b = random.randint(1, 10)
print(f"Случайные числа: a = {a}, b = {b}")
print("Сумма a и b =", a + b, "— магия математики!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 5: Строковые фокусы</strong>
          <div class="code-block">
            <code>text = "Программирование – это круто!"
print(text.upper())
print(text.lower())
print(text.replace("круто", "невероятно весело"))</code>
          </div>
        </li>
        <!-- Для краткости приведены примеры уроков 6–30; можно добавить аналогичные блоки для всех 60 уроков -->
        <li>
          <strong>Весёлый код от 6: Весёлые коллекции</strong>
          <div class="code-block">
            <code>fruits = ["арбуз", "дыня", "манго", "банан"]
fruits.append("киви")
print("Фрукты для супер-кода:", fruits)</code>
          </div>
          <div class="code-block">
            <code>colors = ("радужный", "блестящий", "волшебный")
print("Волшебные цвета:", colors)</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 7: Весёлые условия</strong>
          <div class="code-block">
            <code>mood = "счастлив"  # или "грустный"
if mood == "счастлив":
    print("Сегодня отличный день для весёлого кода!")
else:
    print("Давайте напишем код, чтобы поднять настроение!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 8: Циклы с улыбкой</strong>
          <div class="code-block">
            <code>for i in range(3):
    print("Это уже", i+1, "раз, и код становится всё веселее!")</code>
          </div>
          <div class="code-block">
            <code>i = 0
while i < 3:
    print("Весёлый цикл while, итерация", i+1)
    i += 1</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 9: Функция для позитива</strong>
          <div class="code-block">
            <code>def cheer_up(name):
    return f"{name}, ты супер! Продолжай творить чудеса с Python!"
print(cheer_up("Алиса"))</code>
          </div>
          <div class="code-block">
            <code>double = lambda x: x * 2
print("Дважды 5 =", double(5))</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 10: Ввод с весёлым диалогом</strong>
          <div class="code-block">
            <code>name = input("Как тебя зовут, герой кода? ")
print(f"Приятно познакомиться, {name}! Приготовься к весёлым приключениям!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 11: Магия математики</strong>
          <div class="code-block">
            <code>import math
print("Квадратный корень из 49 =", math.sqrt(49), "— чистая магия чисел!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 12: Файловая забава</strong>
          <div class="code-block">
            <code># Запись в файл с весёлым сообщением
with open("fun.txt", "w") as file:
    file.write("Программирование – это праздник, и ты его участник!")
with open("fun.txt", "r") as file:
    content = file.read()
print("Содержимое файла:", content)</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 13: Игра "Угадай волшебное число"</strong>
          <div class="code-block">
            <code>import random
number = random.randint(1, 10)
guess = int(input("Угадай волшебное число от 1 до 10: "))
if guess == number:
    print("Ура! Ты волшебник, число угадано!")
else:
    print("Ой, не угадал. Волшебное число было:", number)</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 14: Весёлая дата</strong>
          <div class="code-block">
            <code>import datetime
print("Сейчас время для весёлых приключений:", datetime.datetime.now())</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 15: Рисуем с turtle</strong>
          <div class="code-block">
            <code>import turtle
t = turtle.Turtle()
t.color("blue")
for i in range(4):
    t.forward(100)
    t.right(90)
turtle.done()</code>
          </div>
          <div class="code-block">
            <code>import turtle
t = turtle.Turtle()
t.color("purple")
for i in range(5):
    t.forward(150)
    t.right(144)
turtle.done()</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 16: Весёлый график</strong>
          <div class="code-block">
            <code>import matplotlib.pyplot as plt
plt.plot([1, 2, 3, 4], [10, 20, 25, 30], marker='o')
plt.title("График весёлых чисел")
plt.xlabel("Номер эксперимента")
plt.ylabel("Результат волшебства")
plt.show()</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 17: Коллекции с изюминкой</strong>
          <div class="code-block">
            <code>numbers = [7, 42, 100]
print("Чудесные числа:", numbers)
student = {"имя": "Боб", "настроение": "радостное"}
print("Наш весёлый студент:", student)</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 18: ООП с юмором</strong>
          <div class="code-block">
            <code>class Joke:
    def __init__(self, text):
        self.text = text
    def tell(self):
        return "Смешной анекдот: " + self.text

j = Joke("Почему программисты путают Рождество и Хэллоуин? Потому что OCT 31 == DEC 25!")
print(j.tell())</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 19: Создание класса питомца</strong>
          <div class="code-block">
            <code>class Pet:
    def __init__(self, name):
        self.name = name
    def play(self):
        return f"{self.name} играет и весело мурлыкает!"

my_pet = Pet("Мурзик")
print(my_pet.play())</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 20: Модули – специи в коде</strong>
          <div class="code-block">
            <code>print("Модули делают код веселее, как специи в блюде!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 21: Сортировка с улыбкой</strong>
          <div class="code-block">
            <code>numbers = [5, 3, 9, 1, 7]
sorted_numbers = sorted(numbers)
print("Весёлое сортирование чисел:", sorted_numbers)</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 22: Время веселья</strong>
          <div class="code-block">
            <code>import datetime
now = datetime.datetime.now()
print("Весёлое время:", now.strftime("%H:%M:%S"), "— пора для кода!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 23: Весёлый калькулятор</strong>
          <div class="code-block">
            <code>def funny_calculator(a, b, op):
    if op == '+':
        return a + b
    elif op == '-':
        return a - b
    elif op == '*':
        return a * b
    elif op == '/':
        return a / b
    else:
        return "Операция неизвестна – попробуй что-то веселее!"

print("Результат:", funny_calculator(10, 5, '+'))</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 24: Случайная удача</strong>
          <div class="code-block">
            <code>import random
print("Ваше случайное число удачи:", random.randint(1, 100))</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 25: Игра "Камень, ножницы, бумага"</strong>
          <div class="code-block">
            <code>import random
choices = ["камень", "ножницы", "бумага"]
computer = random.choice(choices)
user = input("Выберите: камень, ножницы или бумага? ").lower()
print("Компьютер выбрал:", computer)
if user == computer:
    print("Ничья! Давайте сыграем ещё раз!")
elif (user == "камень" and computer == "ножницы") or \
     (user == "ножницы" and computer == "бумага") or \
     (user == "бумага" and computer == "камень"):
    print("Поздравляем! Вы выиграли весёлый бой!")
else:
    print("Компьютер победил – но игра была забавной!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 26: Весёлые условные конструкции</strong>
          <div class="code-block">
            <code>number = int(input("Введите число, и узнаем его секрет: "))
if number % 2 == 0:
    print("Число четное – знак баланса!")
else:
    print("Число нечетное – как жизнь, непредсказуемо!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 27: Угадай волшебное слово</strong>
          <div class="code-block">
            <code>secret_word = "python"
guess = input("Угадайте волшебное слово: ").lower()
if guess == secret_word:
    print("Поздравляем! Вы раскрыли тайну волшебного слова!")
else:
    print("Неправильно! Волшебное слово –", secret_word)</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 28: Весёлый GUI с Tkinter</strong>
          <div class="code-block">
            <code>import tkinter as tk
root = tk.Tk()
root.title("Весёлое окно Tkinter")
label = tk.Label(root, text="Привет! Это окно создано с любовью к коду!", font=("Nunito", 16))
label.pack(padx=20, pady=20)
root.mainloop()</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 29: API с улыбкой</strong>
          <div class="code-block">
            <code>import requests
response = requests.get("https://api.github.com")
if response.status_code == 200:
    print("Успех! Данные из GitHub получены с улыбкой!")
    print(response.json())
else:
    print("Ошибка при получении данных.")</code>
          </div>
          <div class="code-block">
            <code>import requests
response = requests.get("https://api.github.com")
data = response.json()
print("Текущее значение URL пользователя GitHub:", data.get("current_user_url", "нет данных"))</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 30: Итоговая игра "Угадай число"</strong>
          <div class="code-block">
            <code>import random
def play_game():
    print("Добро пожаловать в весёлую игру 'Угадай число'!")
    number = random.randint(1, 10)
    attempts = 0
    while True:
        guess = int(input("Попробуй угадать число от 1 до 10: "))
        attempts += 1
        if guess == number:
            print(f"Ура! Ты угадал число за {attempts} попыток! Отличная работа!")
            break
        else:
            print("Не угадал, попробуй ещё раз!")
play_game()</code>
          </div>
        </li>
        <!-- Уроки 31–60 -->
        <li>
          <strong>Весёлый код от 31: Функция-счетчик</strong>
          <div class="code-block">
            <code>def counter(n):
    for i in range(1, n+1):
        print(f"Счетчик: {i} — шаг к успеху!")
        
counter(5)</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 32: Генерация случайной шутки</strong>
          <div class="code-block">
            <code>import random
jokes = [
    "Почему программисты путают Рождество и Хэллоуин? Потому что OCT 31 == DEC 25!",
    "Сколько программистов нужно, чтобы вкрутить лампочку? Ни одного — это аппаратная проблема!",
    "Программисты не летают, они просто отлаживают код!"
]
print(random.choice(jokes))</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 33: Рисуем круг с turtle</strong>
          <div class="code-block">
            <code>import turtle
t = turtle.Turtle()
t.color("green")
t.circle(100)
turtle.done()</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 34: Пузырьковая сортировка с юмором</strong>
          <div class="code-block">
            <code>def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n-i-1):
            if arr[j] > arr[j+1]:
                arr[j], arr[j+1] = arr[j+1], arr[j]
    return arr

numbers = [5, 2, 9, 1, 5, 6]
print("Отсортированный список:", bubble_sort(numbers))
print("Пузырьковая сортировка — пузырьки счастья!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 35: Игра "Угадай слово" с подсказками</strong>
          <div class="code-block">
            <code>secret = "python"
guess = input("Угадайте слово (подсказка: это язык программирования): ").lower()
if guess == secret:
    print("Поздравляем! Вы угадали волшебное слово!")
else:
    print("Неверно! Попробуйте еще раз. Подсказка: оно начинается с 'p'.")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 36: Условия if-elif с юмором</strong>
          <div class="code-block">
            <code>score = int(input("Введите ваш балл за задачу: "))
if score >= 90:
    print("Отлично! Вы чемпион!")
elif score >= 70:
    print("Хорошо! Но можно лучше!")
else:
    print("Не отчаивайтесь — практика делает мастера!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 37: Цикл for с фан-эффектами</strong>
          <div class="code-block">
            <code>for i in range(1, 6):
    print(f"Фан-итерация {i}: код идёт и веселье растёт!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 38: Функция, возвращающая случайное сообщение</strong>
          <div class="code-block">
            <code>import random
def random_message():
    messages = [
        "Сегодня отличный день для кода!",
        "Улыбнись и пиши Python!",
        "Каждая строка кода – шаг к успеху!"
    ]
    return random.choice(messages)

print(random_message())</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 39: Весёлый калькулятор</strong>
          <div class="code-block">
            <code>def calc(a, b, op):
    if op == '+':
        return a + b
    elif op == '-':
        return a - b
    elif op == '*':
        return a * b
    elif op == '/':
        return a / b
    else:
        return "Неверная операция! Попробуй что-то другое."

print("2 * 3 =", calc(2, 3, '*'))
print("Весёлый калькулятор считает с улыбкой!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 40: Работа с множествами</strong>
          <div class="code-block">
            <code>set_a = {1, 2, 3, 4}
set_b = {3, 4, 5, 6}
print("Объединение:", set_a | set_b)
print("Пересечение:", set_a & set_b)
print("Множества — это как семья, объединяются и пересекаются!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 41: Перестановка элементов в списке</strong>
          <div class="code-block">
            <code>import random
items = ["яблоко", "банан", "вишня", "киви"]
random.shuffle(items)
print("Перемешанный список:", items)</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 42: Вложенные циклы с узором</strong>
          <div class="code-block">
            <code>for i in range(1, 4):
    for j in range(1, 4):
        print(i * j, end="\t")
    print("\nВесёлый узор завершён!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 43: Расширенная игра "Камень, ножницы, бумага"</strong>
          <div class="code-block">
            <code>import random
choices = ["камень", "ножницы", "бумага"]
computer = random.choice(choices)
user = input("Выберите (камень, ножницы или бумага): ").lower()
print("Компьютер выбрал:", computer)
if user == computer:
    print("Ничья! Повторите попытку!")
elif (user == "камень" and computer == "ножницы") or \
     (user == "ножницы" and computer == "бумага") or \
     (user == "бумага" and computer == "камень"):
    print("Вы победили! Отличная игра!")
else:
    print("Компьютер победил, но главное — удовольствие от игры!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 44: Переворот строки</strong>
          <div class="code-block">
            <code>text = "Весёлый код"
reversed_text = text[::-1]
print("Оригинал:", text)
print("Перевернуто:", reversed_text)
print("Иногда нужно перевернуть взгляд на мир!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 45: Игра "Угадай число" с подсказками</strong>
          <div class="code-block">
            <code>import random
number = random.randint(1, 50)
print("Я загадал число от 1 до 50. Попробуй угадать!")
while True:
    guess = int(input("Ваше предположение: "))
    if guess < number:
        print("Слишком маленькое число! Подумай еще.")
    elif guess > number:
        print("Слишком большое число! Попробуй меньше.")
    else:
        print("Поздравляем, ты угадал число!")
        break</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 46: Рекурсия — Факториал с шуткой</strong>
          <div class="code-block">
            <code>def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

print("Факториал 5 =", factorial(5))
print("Рекурсия — волшебная штука!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 47: Простой чат-бот</strong>
          <div class="code-block">
            <code>def chat():
    print("Привет! Я веселый бот. Спроси меня что-нибудь или скажи 'пока'.")
    while True:
        user_input = input("Ты: ").lower()
        if user_input == "пока":
            print("Бот: До встречи!")
            break
        else:
            print("Бот: Интересно! Расскажи подробнее.")

chat()</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 48: Словарь — числа в слова</strong>
          <div class="code-block">
            <code>num_to_word = {1: "один", 2: "два", 3: "три", 4: "четыре"}
number = int(input("Введите число от 1 до 4: "))
print("Вы ввели:", num_to_word.get(number, "неизвестное число"))</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 49: List comprehension с юмором</strong>
          <div class="code-block">
            <code>squares = [x**2 for x in range(1, 6)]
print("Квадраты чисел:", squares)
print("Гениально и весело!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 50: Функция, возвращающая мем</strong>
          <div class="code-block">
            <code>def get_meme():
    memes = [
        "Кодить — значит жить!",
        "Python — это как магия!",
        "Смейся, пока пишешь код!"
    ]
    import random
    return random.choice(memes)

print("Ваш мем дня:", get_meme())</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 51: Весёлые даты</strong>
          <div class="code-block">
            <code>import datetime
today = datetime.date.today()
print("Сегодняшняя дата:", today)
print("Каждый день — шанс на новый код!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 52: Генерация случайного пароля</strong>
          <div class="code-block">
            <code>import random, string
def generate_password(length=8):
    chars = string.ascii_letters + string.digits
    return ''.join(random.choice(chars) for _ in range(length))

print("Ваш случайный пароль:", generate_password(10))</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 53: Работа с файлами — запись случайных строк</strong>
          <div class="code-block">
            <code>import random
lines = ["Кодить весело!", "Python — магия!", "Программирование — праздник!"]
with open("random_lines.txt", "w") as f:
    for line in lines:
        f.write(line + "\n")
print("Записали случайные строки в файл!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 54: Викторина с Python</strong>
          <div class="code-block">
            <code>questions = {
    "Какой язык программирования мы изучаем?": "python",
    "Сколько байт в килобайте (приблизительно)?": "1024"
}
for q, a in questions.items():
    answer = input(q + " ").lower()
    if answer == a:
        print("Верно!")
    else:
        print("Неправильно!")</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 55: Генератор списков</strong>
          <div class="code-block">
            <code>evens = [x for x in range(1, 21) if x % 2 == 0]
print("Четные числа от 1 до 20:", evens)</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 56: Lambda для степеней</strong>
          <div class="code-block">
            <code>power = lambda x, y: x ** y
print("2 в степени 3 =", power(2, 3))</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 57: Игра "Угадай цвет"</strong>
          <div class="code-block">
            <code>import random
colors = ["красный", "синий", "зелёный", "желтый"]
secret_color = random.choice(colors)
guess = input("Угадайте цвет: ").lower()
if guess == secret_color:
    print("Правильно! Вы отличный наблюдатель!")
else:
    print("Неправильно! Загаданный цвет был:", secret_color)</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 58: API с улыбкой (демо)</strong>
          <div class="code-block">
            <code>def get_joke():
    jokes = [
        "Почему программисты не плачут? Потому что код не умеет скучать!",
        "Кодить весело, если рядом друзья!"
    ]
    import random
    return random.choice(jokes)

print("Случайная шутка:", get_joke())</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 59: Простой веб-сервер</strong>
          <div class="code-block">
            <code>import http.server
import socketserver

PORT = 8000
Handler = http.server.SimpleHTTPRequestHandler
with socketserver.TCPServer(("", PORT), Handler) as httpd:
    print("Сервер запущен на порту", PORT)
    httpd.serve_forever()</code>
          </div>
        </li>
        <li>
          <strong>Весёлый код от 60: Итоговый проект — Собери все веселые идеи</strong>
          <div class="code-block">
            <code>def project_overview():
    print("Добро пожаловать в итоговый проект!")
    print("1. Весёлый калькулятор")
    print("2. Игра 'Угадай число'")
    print("3. Генератор шуток")
    print("4. Персональный чат-бот")
    print("Выбери номер проекта, чтобы увидеть код.")

choice = input("Ваш выбор: ")
if choice == "1":
    print("Запустите веселый калькулятор!")
elif choice == "2":
    print("Запустите игру 'Угадай число'!")
elif choice == "3":
    print("Получите случайную шутку!")
elif choice == "4":
    print("Начните диалог с чат-ботом!")
else:
    print("Неверный выбор. Попробуйте еще раз!")

project_overview()</code>
          </div>
        </li>
      </ul>
    </section>
    
    <!-- Раздел "Попробуй создать проект!" (скрыт по умолчанию) -->
    <section id="projects" class="card">
      <h2>Попробуй создать проект!</h2>
      <p>Ниже представлены несколько готовых проектов, которые можно сразу запустить и изучить.</p>
      <details open>
        <summary>Проект 1: Личный веб-сайт</summary>
        <div class="code-block">
          <code>&lt;!DOCTYPE html&gt;
&lt;html lang="ru"&gt;
  &lt;head&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;title&gt;Мой личный сайт&lt;/title&gt;
    &lt;style&gt;
      body { font-family: 'Nunito', sans-serif; background: #fff; color: #333; padding: 20px; }
      header { background: #ff6f61; color: #fff; padding: 20px; text-align: center; }
      section { padding: 20px; }
    &lt;/style&gt;
  &lt;/head&gt;
  &lt;body&gt;
    &lt;header&gt;
      &lt;h1&gt;Привет, мир!&lt;/h1&gt;
    &lt;/header&gt;
    &lt;section&gt;
      &lt;p&gt;Добро пожаловать на мой личный сайт.&lt;/p&gt;
    &lt;/section&gt;
  &lt;/body&gt;
&lt;/html&gt;</code>
        </div>
      </details>
      <details open>
        <summary>Проект 2: Игра "Угадай число"</summary>
        <div class="code-block">
          <code>import random

def play_game():
    number = random.randint(1, 100)
    print("Я загадал число от 1 до 100. Попробуй угадать!")
    attempts = 0
    while True:
        guess = int(input("Ваше предположение: "))
        attempts += 1
        if guess < number:
            print("Слишком маленькое число!")
        elif guess > number:
            print("Слишком большое число!")
        else:
            print(f"Поздравляем! Вы угадали число за {attempts} попыток!")
            break

play_game()</code>
        </div>
      </details>
      <details open>
        <summary>Проект 3: Весёлый калькулятор</summary>
        <div class="code-block">
          <code>def funny_calculator(a, b, op):
    if op == '+':
        return a + b
    elif op == '-':
        return a - b
    elif op == '*':
        return a * b
    elif op == '/':
        return a / b
    else:
        return "Ой, я не знаю такой операции! Попробуй снова."

print("Весёлый калькулятор в действии:")
print("3 + 7 =", funny_calculator(3, 7, '+'))
print("10 - 2 =", funny_calculator(10, 2, '-'))</code>
        </div>
      </details>
      <details open>
        <summary>Проект 4: Приложение "Заметки" на Tkinter</summary>
        <div class="code-block">
          <code>import tkinter as tk

def add_note():
    note = entry.get()
    if note:
        listbox.insert(tk.END, note)
        entry.delete(0, tk.END)

root = tk.Tk()
root.title("Приложение Заметки")

frame = tk.Frame(root)
frame.pack(padx=10, pady=10)

entry = tk.Entry(frame, width=40)
entry.pack(side=tk.LEFT, padx=(0, 10))

button = tk.Button(frame, text="Добавить заметку", command=add_note)
button.pack(side=tk.LEFT)

listbox = tk.Listbox(root, width=50)
listbox.pack(padx=10, pady=10)

root.mainloop()</code>
        </div>
      </details>
    </section>
    </div>

    <div id="tasks" style="display: none;">
        <h2>Задания по Python</h2>

        <div class="task-card">
            <h3>Задание 1: Программа "Привет, мир!"</h3>
            <p>Напишите программу, которая выводит сообщение "Привет, мир!".</p>
        </div>

        <div class="task-card">
            <h3>Задание 2: Сумма двух чисел</h3>
            <p>Напишите программу, которая запрашивает два числа и выводит их сумму.</p>
        </div>

        <div class="task-card">
            <h3>Задание 3: Периметр прямоугольника</h3>
            <p>Напишите программу, которая запрашивает длину и ширину прямоугольника и выводит его периметр.</p>
        </div>

        <div class="task-card">
            <h3>Задание 4: Четное или нечетное</h3>
            <p>Напишите программу, которая проверяет, является ли число четным или нечетным.</p>
        </div>

        <div class="task-card">
            <h3>Задание 5: Квадрат числа</h3>
            <p>Напишите программу, которая запрашивает число и выводит его квадрат.</p>
        </div>

        <div class="task-card">
            <h3>Задание 6: Возведение в степень</h3>
            <p>Напишите программу, которая запрашивает число и его степень, а затем выводит результат возведения в степень.</p>
        </div>
</div>
    <!-- Раздел "О нас" (скрыт по умолчанию) -->
    <section id="about" class="card">
      <h2>О нас</h2>
      <p>Я ваш учитель, Марусова Диана Егоровна, стремящийся сделать обучение программированию интересным и доступным для Вас. Этот сайт поможет открыть мир IT с первых шагов в программировании!</p>
      <img class="illustration" src="https://source.unsplash.com/800x400/?team,programming" alt="учитель информатики">
    </section>
    
    <!-- Раздел "Контакты" (скрыт по умолчанию) -->
    <section id="contact" class="card">
      <h2>Контакты</h2>
      <p>Если у вас возникли вопросы или предложения,вы можете обратиться на прямую ко мне, либо написать мне письмо на почту:
         <a href="dikomarusova@mail.ru">dikomarusova@mail.ru</a>
      </p>
    </section>
  </div>
  
  <!-- Подвал -->
  <footer>
    <p>&copy; 2024-2025 уч. год Весёлое программировние!. Все права защищены.</p>
  </footer>
  
  <!-- JavaScript для управления отображением разделов -->
  <script>
    document.addEventListener("DOMContentLoaded", function() {
      // По умолчанию показываем только раздел "intro"
      const sections = document.querySelectorAll("section.card");
      sections.forEach(section => {
        if (section.id !== "intro") {
          section.style.display = "none";
        }
      });
      
      // При клике на навигационные ссылки скрываем все разделы и показываем выбранный
      const navLinks = document.querySelectorAll("nav a");
      navLinks.forEach(link => {
        link.addEventListener("click", function(e) {
          e.preventDefault();
          sections.forEach(section => section.style.display = "none");
          const targetId = this.getAttribute("href").substring(1);
          const targetSection = document.getElementById(targetId);
          if (targetSection) {
            targetSection.style.display = "block";
          }
          window.scrollTo(0, 0);
        });
      });
    });
  </script>
</body>
</html>
