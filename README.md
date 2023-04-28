#      XML 
# (XML репозиторий)

1. _Создаем внешний репозиторий c названием XML_

`Repositories -> New -> Repos Name:XML -> Check "Add a README file" -> Press "Create repository"`

2. _Клонировать репозиторий XML на локальный компьютер_ 

`git clone <repository HTTPS>`

3. _Внутри локального XML создать файл "new.xml"_

`touch new.xml`

4. _Добавить файл под гит_ 

`git add .` или `git add new.xml`

5. _Закоммитить файл_

`git commit -m "любой комментарий"`

6. _Отправить файл на внешний GitHub репозиторий_

`git push`

7. _Отредактировать содержание файла “new.xml” написать информацию о себе в формате JSON (ФИО, возраст, количество домашних животных, будущая желаемая зарплата)._

`vim new.xml -> input data -> esc -> enter ":wq"`

8. _Отправить изменения на внешний репозиторий_

`git add . && git commit -m "любой комментарий"`

`git push`

9. _Создать файл preferences.xml_

`touch preferences.xml`

10. _В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML_

`vim preferences.xml -> insert data -> esc -> enter ":wq"`

11. _Создать файл skills.xml. Добавить информацию о скиллах которые будут изучены на курсе в формате XML_

`touch skills.xml`

12. _Отправить сразу 2 файла на внешний репозиторий_

`git add . && git commit -m "любой комментарий" && git push`

13. _На веб интерфейсе создать файл bug_report.xml_

`Add file -> Create new file -> Name: bug_report.xml`

14. _Сделать Commit changes (сохранить) изменения на веб интерфейсе_

`Commit New File`

15. _На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML_

`Choose bug_report.xml -> Edit this file`

16. _Сделать Commit changes (сохранить) изменения на веб интерфейсе_

`Commit changes`

17. _Синхронизировать внешний и локальный репозиторий XML_

`git pull`
