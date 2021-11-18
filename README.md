# LR6
Лабораторная работа №6

Для начала в гит ввожу имя пользователя и email

![image](https://user-images.githubusercontent.com/84862355/142496720-c1a821de-bbcb-4481-b20f-62c238f2739a.png)

Репозиторий клонирую на компьютер с помощью команды git clone, затем нахожу его и перехожу в папку, где он лежит. 
В GitHub я создала файл и теперь в локальный репозиторий надо добавить изменения

![image](https://user-images.githubusercontent.com/84862355/142497166-8e97d0cd-8a67-4497-b68d-608270e5fc62.png)

Так как я уже создала новую ветку, можно посмотреть изменения всех веток

![image](https://user-images.githubusercontent.com/84862355/142497430-c13d69dd-c7bc-437d-a58e-b575281d289f.png)

Смотрим последние изменения 

![image](https://user-images.githubusercontent.com/84862355/142497542-03bd94e8-2a79-4a57-aa7a-4b6fa7ddd7b8.png)

Добавляем файл с компьютера в репозиторий

![image](https://user-images.githubusercontent.com/84862355/142498897-88056a2d-5274-4d90-850e-9651541a4c3c.png)

Создаю новую ветку и делаю *слияние* её и ветки master

![image](https://user-images.githubusercontent.com/84862355/142498999-5c141cf8-a5ed-4c8c-84fd-025f69b385a9.png)

Удаляю *побочную* ветку 

![image](https://user-images.githubusercontent.com/84862355/142499055-373fce22-9fab-4e47-b5cd-209844740e06.png)

Делаю несколько коммитов и *откатываю* последний

![image](https://user-images.githubusercontent.com/84862355/142499142-fdffbf11-6b49-481a-9e07-a7e91920ba3b.png)

Лог команд

git clone https://github.com/angsheva/LR6.git

git config --global user.name ""

git config --global user.email ~~my mail~~

git add doc.txt

git push

git pull

git log -p

git reglog --all

git checkout -b main

git checkout master

git commit -m "one commit"

git push --set-upstream origin mk

git merge master


История операций

commit d1b6e85387d28590ea991a3e1be4ed51c517f080 (HEAD -> otchet_here, origin/otchet_here, origin/master, origin/HEAD, vetka, master)
Author: 4016 Derbisheva Angelina <derbisheva2002@mail.ru>
Date:   Thu Nov 18 23:27:40 2021 +0300
    make

commit 921f53b8d0cebf542c791cf31f04e9b792f385a4 (origin/mk)
Author: Kurtyanik <45309985+Kurtyanik@users.noreply.github.com>
Date:   Sat Nov 21 20:09:49 2020 +0300

    Обновление информации

commit c08a654a63cfc3a7146b2b7015884d9020f5cbf5
Author: Kurtyanik <45309985+Kurtyanik@users.noreply.github.com>
Date:   Sat Nov 21 20:02:16 2020 +0300

    Файл создан пустым

commit 3c6e9131bb47ed6009c28226afb0535c7f6d5964
Author: Kurtyanik <45309985+Kurtyanik@users.noreply.github.com>
Date:   Sat Nov 21 19:58:20 2020 +0300

    Initial commit

