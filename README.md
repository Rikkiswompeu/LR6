# LR6
Лабораторная работа №6

Настройка после установки Git, введено имя пользователя (4018к Nogovitsyna Z.E.) и email.
![username img](pic/username.png)

Добавляется файл через интерфейс GitHub. Подтягиваются изменения в локальный репозиторий с помощью команды ```git pull```.
![gitpull img](pic/gitpull.png)

Получены истории операций для каждой из веток с помощью команды ```git log```.
![gitlog(master) img](gitlog(master).png)
![gitlog(branch1) img](gitlog(branch1).png)

Просмотрены последние изменения с помощью команды ```git log -p```.
![gitlog-p img](gitlog-p.png)

Выполнено слияние в ветку master с помощью команды ```git merge branch1```, возникает конфликт, решаем его, используя команду ```git add mergefile.txt```, и оставляем коммит с помощью команды ```git commit -m "mergefile conflict solved"```.
![gitmerge img](gitmerge.png)
![catmergefile img](catmergefile.png)
![gitadd_gitcommit img](gitadd_gitcommit.png)

Удалена побочная ветка после успешного слияния с помощью команды ```git branch -d branch1``` для локального репозитория и команды ```git push https://github.com/Rikkiswompeu/LR6.git --delete branch1``` для удаленного репозитория.
![gitbranch-d img](gitbranch-d.png)
![gitpush--delete img](gitpush--delete.png)

Изменения сделаны и зафиксированы с помощью команды ```git add .```, оставлен коментарий ```git commit```.
![gitadd_gitcommit(changefile) img](gitadd_gitcommit(changefile).png)

Сделан "хард" откат коммита командой ```git reset --hard HEAD~1```.
![gitreset--hard img](gitreset--hard.png)

Создана ветка для отчета с помощью команд ```git branch report``` и ```git checkout repor```.
![gitbranch(report) img](gitbranch(report).png)

Оформлен отчет в файле README.md 

Получена история операций в форматированном виде, сделана финальная фиксация изменений.
![gitlog img](gitlog.png)

Отчет зафиксирован с помощью команды ```git add .```, оставлен коментарий ```git commit```.

Отправлены локальные изменения в сетевое хранилище GitHub с помощью команды ```git push``.
