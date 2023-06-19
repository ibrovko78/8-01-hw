# Домашнее задание к занятию "`Git`" - `Бровко Иван Геннадьевич`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

1. `Аккаунт на GitHub зарегистрирован`  ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/1-1.png)
2. `Публичный репозиторий создан` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/1-2.png)
   * Галочка в поле «Initialize this repository with a README» проставлена. 
3. `Склонирую репозиторий используя SSH ключ`
   * Добавляю ключ в github 
   * Выполняю git clone git@github.com:ibrovko78/ibrovko.git  ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/1-3.png)
4. `Перехожу в каталог с клоном репозитория.` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/1-4.png)
5. `Произвожу первоначальную настройку Git` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/1-5.png)
   * git config --global user.name ibrovko78
   * git config --global user.email i.brovko@internet.ru
6. `Выполняю команду git status и запомниаю результат` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/1-6.png)
7. `Редактирую файл README.md при помощи nano, файл в состоянии Modified.` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/1-7.png)
8. `Ещё раз выполняю git status и продолжу проверять вывод этой команды после каждого следующего шага.` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/1-8.png)
9. `Смотрю изменения в файле README.md, выполняю команды git diff и git diff --staged.` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/1-9.png)
10. `Перевожу файл в состояние staged, добавляю файл в коммит, командой git add README.md.` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/1-10.png)
11. `Ещё раз выполню команды git diff и git diff --staged.` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/1-11.png)
12. `Сделаю коммит git commit -m 'First commit'.` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/1-12.png)
13. `Делаю git push origin .` ![скрин1](https://github.com/ibrovko78/8-01-hw/tree/main/img/1-13.png) ![скрин2](https://github.com/ibrovko78/8-01-hw/tree/main/img/1-13.1.png)

![ссылка на коммит First commit](https://github.com/ibrovko78/ibrovko/commit/4a54b5e302f4de6f9971b75aa31c43a12fceddfa)

---

### Задание 2

1. `Создаю файл .gitignore, проверяю его статус сразу после создания.` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/2-1.png)
2. `Добавляю файл .gitignore в коммит git add .gitignore` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/2-2.png)
3. `Добавляю правила в файл .gitignore, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/2-3.png)
4. `Делаю комит и пуш` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/2-4.png)
   * git commit -m 'Second commit'
   * git push origin

![ссылка на коммит Second Commit](https://github.com/ibrovko78/ibrovko/commit/394939919f31caba0d6440cdf1ccee0f3d2a730a)

---

### Задание 3

1. `Создаю новую ветку dev и сразу переключаюсь на неё. git checkout -b dev` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/3-1.png)
2. `Создаю файл test.sh с произвольным содержимым.` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/3-2.png)
3. `Сделаю несколько коммитов и пушей, имитируя активную работу над файлом test.sh.` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/3-3.png)
4. `Сделайте мердж этой ветки в основную. Сначала нужно переключиться на неё, а потом вызывать git merge.` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/3-4.png)
5. `Сделайте коммит и пуш.` ![скрин](https://github.com/ibrovko78/8-01-hw/tree/main/img/3-5.png)


![ссылка на граф коммитов](https://github.com/ibrovko78/ibrovko/network)

