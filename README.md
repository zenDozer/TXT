# TXT

***1. Создать внешний репозиторий c названием TXT***

```
github.com -> Repositories -> New -> "TXT" -> Create repository
```

***2. Клонировать репозиторий TXT на локальный компьютер***

```
Enter to repo TXT -> "<>Code" -> SSH -> Copy url -> go to Terminal:

git clone git@github.com:zenDozer/TXT.git
```

***3. Внутри локального TXT создать файл “new.txt”***

```
cd TXT
touch new.txt
```

***4. Добавить файл под гит***

```
git add .
```

***5. Закоммитить файл***

```
git commit - m "Add new.txt file
```

***6. Отправить файл на внешний GitHub репозиторий***

```
git push
```

***7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT***

```
vim new.txt

fio: Malko Oleksandr
age: 42
pet: 1
salary: 750
```

***8. Отправить изменения на внешний репозиторий***

```
git add .
git commit -m "Update new.txt"
git push
```

***9. Создать файл preferences.txt***
***10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT***

```
vim preferences.txt

Film: The Social Network
TV series: Silicon Valley
Favorite food: Borsch
Favorite season: Spring
Country: USA
```

***11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT***

```
vim sklls.txt

Skills:
- Basic theory
- Client-server architecture
- HTTP
- JSON/XML
- Postman
- Charles
- Fidler
- Dev Tools
- VPN
- Mobile testing
- Android Studio
- Terminal
- Git
- SQL basic
- Jmeter
- Scrum
- Python basic
```

***12. Сделать коммит в одну строку***

```
git add . && git commit -m "Add 2 files"
```

***13. Отправить сразу 2 файла на внешний репозиторий***

```
git push
```

***14. На веб интерфейсе создать файл bug_report.txt***

```
Enter to repo TXT -> Add file -> Create new file ->  bug_report.txt
```

***15. Сделать Commit changes (сохранить) изменения на веб интерфейсе***

```
Commit changes -> Commit message: "Add bug_report.txt" -> Commit changes
```

***16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT***

```
Select bug_report.txt file -> add changes:

ID: LF-001
Summary: The Login button should be blue - not red
Severity: Minor
Priority: Low
Environment: PC, Windows 11, Chrome
Steps to reproduce: Open example_site.com, click on sign in button
Expected result: Login button is blue
Actual result: Login button is red
Attachments: Screenshot.jpg
Reported By: Oleksandr Malko
```

***17. Сделать Commit changes (сохранить) изменения на веб интерфейсе***

```
Commit changes -> Commit message: "Update bug_report.txt" -> Commit changes
```

***18. Синхронизировать внешний и локальный репозиторий TXT***

```
Go to Terminal and type:

git pull
```