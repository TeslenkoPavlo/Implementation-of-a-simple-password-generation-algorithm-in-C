# Генератор паролів

Цей код представляє собою простий генератор паролів, написаний на C++. Він генерує випадковий пароль заданої користувачем довжини, використовуючи символи ASCII у діапазоні від 33 до 126.

## Постановка задачі

Необхідно реалізувати програму, яка буде генерувати випадкові паролі заданої довжини.

## Опис роботи програми

1. Установка локалізації для виведення кириличних символів.

   ![1](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/1.png)

2. Ініціалізація генератора випадкових чисел поточним часом, щоб забезпечити генерацію різних випадкових чисел кожен раз при запуску програми.

   ![2](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/2.png)
   
3. Запит для користувача ввести бажану довжину пароля та зчитує введення у змінну 'length'.

   ![3](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/3.png)

4. Створення рядка для зберігання всіх можливих символів пароля, починаючи з символу з кодом 33 ('!') і закінчуючи символом з кодом 126 ('~') у таблиці ASCII.

   ![4](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/4.png)

5. Перевірка, чи довжина пароля введена користувачем є від'ємною, і виведення відповідного повідомлення про помилку, якщо так.

   ![5](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/5.png)

6. Перевірка, чи введена довжина пароля дорівнює нулю, і виведення повідомлення про помилку, якщо так.

    ![6](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/6.png)

7. Створення згенерованого пароля заданої користувачем довжини, вибираючи випадкові символи з рядка 'password'.

    ![7](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/7.png)

8. Виведення згенерованого пароля на екран.

    ![8](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/8.png)

# Шифрування та дешифрування пароля

Цей код представляє собою просту програму для шифрування та дешифрування пароля на мові програмування C++.

## Постановка задачі

Необхідно створити програму, яка здатна шифрувати та дешифрувати введений користувачем пароль.

## Опис роботи програми

1. Виводиться рядок "Перевірка пароля" на екран.

   ![9](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/8.png)
   
2. Оголошується змінна C типу char і рядок password1.

   ![10](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/10.png)
   
3. Цикл do-while, який повторюється, поки введений користувачем пароль password1 не буде рівний genpassword.

   ![11](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/11.png)
   
4. Очищення рядка password1, щоб попередні введення не зберігалися.

   ![12](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/12.png)
   
5. Виведення повідомлення, що просить користувача ввести пароль.

   ![13](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/13.png)
   
6.  Використання цикла while, щоб продовжувати зчитування символів, доки не буде введено символ з ASCII-кодом 13 (відповідає клавіші Enter). Кожен символ, який не є Enter, додається до рядка паролю (password1) і виводиться на екран у вигляді зірочки.
      
      ![14](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/14.png)
7. Виконується перевірка, чи введений пароль (password1) співпадає зі згенерованим паролем (genpassword). Якщо пароль невірний, виводиться відповідне повідомлення про помилку, разом з правильним паролем для зручності користувача. Після цього змінна C ініціалізується пробілом, щоб очистити її значення.

    ![15](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/15.png)
    
8. Перші два рядки виводять порожні рядки для створення простору між повідомленнями. Наступні два рядки виводять повідомлення про те, що пароль введено правильно, та сам пароль, який було введено.

    ![16](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/16.png)
    
