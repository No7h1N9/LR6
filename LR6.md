# LR6
Лабораторная работа №6

Ход работы:
1 Аккаунт GitHub был создан до выполнения лабораторной работы: No7h1N9 (github.com)

2 Сделана копия (Fork)

![1 скрин](https://github.com/No7h1N9/LR6/blob/master/3.jpg)

3 Настройка клиента git

Изменено имя пользователя.
git config --global user.name "4216 Kostiunin A. O."

Изменен email.
git config --global user.email Levaanoga631@gmail.com

![Локальное изображение](https://github.com/No7h1N9/LR6/blob/master/1.jpg)


4 Клонирование репозитория

git clone No7h1N9/LR6: Лабораторная работа №6 (github.com)

![4 скрин](https://github.com/No7h1N9/LR6/blob/master/2.jpg)


5 Добавлен файл через GitHub, подтянуты изменения в локальный репозиторий Добавлен файл через GitHub.



![Локальное изображение](https://github.com/No7h1N9/LR6/blob/master/8.png)


Подтянуты изменения в локальный репозиторий.

git pull

![5 скрин](https://github.com/No7h1N9/LR6/blob/master/4.jpg)

6 История операций для каждой из веток Для master

git log --all --graph --oneline

![Локальное изображение](https://github.com/No7h1N9/LR6/blob/master/5.jpg)


7 Последние изменения

git diff

![Локальное изображение](https://github.com/No7h1N9/LR6/blob/master/6.jpg)

8 Выполнено слияние в ветку master, конфликт решен Слияние веток.

Конфликт решён с помощью текстового редактора

![Локальное изображение](https://github.com/No7h1N9/LR6/blob/master/9.png)

git merge branch1

Зафиксированы изменения.

git add mergefile.txt
git commit -m"conflict resolution"

9 Удалена побочная ветка после успешного слияния

При слиянии ветка удалилась автоматически.

Удаление ветки на GitHub

git push origin --delete branch1



10 Создана ветка для отчета

git branch отчет
git checkout отчет


файл README.md добавлен в ветку отчёт

touch README.md

!Локальное изображение](https://github.com/No7h1N9/LR6/blob/master/10.png)

11 Получена история операций в форматированном виде

![sss](https://github.com/No7h1N9/LR6/blob/master/7.jpg)

12 Изменения загружены на гит 

![asd](https://github.com/No7h1N9/LR6/blob/master/11.png)
