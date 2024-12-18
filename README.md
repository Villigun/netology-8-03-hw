# Домашнее задание к занятию "Git" - `Колесин Владимир`


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

`Приведите ответ в свободной форме........`

1. `После регистрации на github устанавливаем git на локальную машину, создаем форк и клон`
2. `Переходим в директорию ~/Documents/Git/pr1/netology-8-03-hw и выполняем git init.`
    Затем git config --global user.name и git config user.email, указывая свое имя и почту`
3. `Выполняем git commit -m 'First commit' и git push origin master, где вводим свои учетные данные и токен вместо пароля`
4. `Ссылка на первый commit:`

(https://github.com/netology-code/sys-pattern-homework/commit/6ea43b0f465d301b6c7bb2bd4de3809c4e5f50c9)

![alt text](https://github.com/Villigun/netology-8-03-hw/blob/main/img/hw-8-03-1-1.png)

![alt text](https://github.com/Villigun/netology-8-03-hw/blob/main/img/hw-8-03-1-2.png)

![alt text](https://github.com/Villigun/netology-8-03-hw/blob/main/img/hw-8-03-1-3.png)

---

### Задание 2

Ссылка на коммит:
![alt text](https://github.com/Villigun/netology-8-03-hw/blob/main/.gitignore)'

---

### Задание 3

1. `Для создания новой ветки и переключения на нее воспользуемся командой git checkout -b dev`
2. `Выполняем коммиты в ветке dev, переключаемся на ветку main командой git chekout main, создаем файл main.sh`
3. `Объединяем ветки командой git merge dev, выполняем push`

Результат выполнения команды git log --graph
![alt text](https://github.com/Villigun/netology-8-03-hw/blob/main/img/hw-8-03-3-1.png)'

Ссылка на граф - (https://github.com/Villigun/netology-8-03-hw/network)

### Задание 4

Результат выполнения команды git log --graph
![alt text](https://github.com/Villigun/netology-8-03-hw/blob/main/img/hw-8-03-4-1.png)'

Ссылка на граф - (https://github.com/Villigun/netology-8-03-hw/network)'

*Первый раз слияние не произошло по причине зависания терминала, пришлось повторить. Интересно то, что неудача отражается в логах*