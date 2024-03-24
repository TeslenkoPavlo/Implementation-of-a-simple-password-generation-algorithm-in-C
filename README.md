# Генератор паролів

Цей код представляє собою простий генератор паролів, написаний на C++. Він генерує випадковий пароль заданої користувачем довжини, використовуючи символи ASCII у діапазоні від 33 до 126.

## Постановка задачі

Необхідно реалізувати програму, яка буде генерувати випадкові паролі заданої довжини.

## Опис роботи програми

1. Установка локалізації для виведення кириличних символів.

   ![1](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/1.png)

3. Ініціалізація генератора випадкових чисел поточним часом, щоб забезпечити генерацію різних випадкових чисел кожен раз при запуску програми.

   ![2](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/2.png)
   
5. Запит для користувача ввести бажану довжину пароля та зчитує введення у змінну 'length'.

   ![3](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/3.png)

7. Створення рядка для зберігання всіх можливих символів пароля, починаючи з символу з кодом 33 ('!') і закінчуючи символом з кодом 126 ('~') у таблиці ASCII.

   ![4](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/4.png)

9. Перевірка, чи довжина пароля введена користувачем є від'ємною, і виведення відповідного повідомлення про помилку, якщо так.

   ![5](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/5.png)

10. Перевірка, чи введена довжина пароля дорівнює нулю, і виведення повідомлення про помилку, якщо так.

    ![6](https://github.com/TeslenkoPavlo/Implementation-of-a-simple-password-generation-algorithm-in-C/blob/main/PNG/6.png)

12. Створення згенерованого пароля заданої користувачем довжини, вибираючи випадкові символи з рядка 'password'.

    ![7](7.png)

14. Виведення згенерованого пароля на екран.

    ![8](8.png)

16. Успішне завершення програми.

    ![9](9.png)
