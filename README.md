# react-2023-03-30

# ДЗ

## Как делать

0. Сделать форк этого репозитория в свой аккаунт (только 1 раз в самом начале).

1. Перед выполнением ДЗ сделайте пул мастера этого репозитория себе в форк (чтобы иметь актуальный код);
2. Обновить зависимости `yarn` или `npm i`;
3. Создайте новую ветку от актуального мастера для выполнения ДЗ;
4. Выполните ДЗ в этой ветке;
5. Сделайте Pull Request этой ветки в мастер моего репозитория;
6. Напишите мне в личные сообщения дискорда ссылку на PR.

**Важно! В результате всех этих манипуляций в вашем мастере должны быть только мои комиты, все ваши комиты должны быть в отдельных ветках под каждую домашку.**

Дедлайн – 23:00 по GMT+3 за день до занятия.


## HW1
1. Необходимо отрисовать блюда из меню и отзывы.
2. Реализуем следующие компоненты:
    1. Menu - принимает массив блюд и рисует их список;
    2. Dish - принимает блюда и рисует информацию о нем;
    3. Reviews - принимает массив отзывов и рисует их список;
    4. Review - принимает отзыв и рисует информацию о нем;


            ==> Menu => Dish, Dish, Dish
Restaurant 
            ==> Reviews => Review, Review, Review

## HW2

1. Создать компонент Рейтинг;
2. Принимать он будет максимальный рейтинг(maxRating) и текущий рейтинг(value);
3. Отображает кол-во звезд соответствующие максимальному рейтингу, золотыми отображает текущий рейтинг;
4. Используем в комопненте Review для отображения рейтинга отзыва.