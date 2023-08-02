HOMEWORK_2

| Command | Description |
| --- | --- |
|                                                |       4. Создать удалённый репозиторий c названием JSON |
| `git clone https://github.com/uroboros-d/JSON.git`|    5. Клонировать репозиторий на локальный компьютер |
| `touch JSON/new.json  `|                               6. Создать файл new.json |
| `cd JSON  `|                                    7. Добавить файл в индекс |
| `git add new.json  `|
| `git commit  -m "create new.json"`|                       8. Закоммитить файл new.json |
| `git push  `|                                           9. Отправить файл в удалённый репозиторий |
| `vim new.json `|                                        10. Внести в new.json информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON |
| `git commit -am "fill new.json with info"`|             11. Отправить изменения в удалённый репозиторий |
| `git push`||
| `> preferences.json  `|                                 12. Создать файл preferences.json |
| `vim preferences.json  `|                            13.  Добавить в preferences.json информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON |
| `echo '{"How to google effectively": "In English"}' > skills.json`| 14. Создать файл sklls.json, добавить информацию о скиллах, которые будут изучены на курсе в формате JSON |
| `git add . `|                                          15. Отправить сразу 2 файла в удалённый репозиторий |
| `git commit -m "Create two new files"`|
| `git push`| |
|                                                    | 16. Создать файл bug_report.json в удалённом репозитории|
|                                                    | 17. Сделать Commit changes (сохранить изменения) |
 |                                                    | 18. Модифицировать файл bug_report.json, добавить баг репорт в формате JSON |
|                                                    | 19. Сделать Commit changes (сохранить изменения) |
| `git pull`|                                           20. Синхронизировать удалённый и локальный репозитории |
| ||
|||
|                                                     | Create a remote XML repository |
| `git clone https://github.com/uroboros-d/XML.git`|       Clone the XML repository to a local machine |
| `touch new.xml`|                                         Create new.xml |
| `git add new.xml `|                                      Add new.xml under Git |
| `git commit  -m "create new.xml"`|                       Commit new.xml |
| `git push `|                                             Push the file to GitHub |
| `vim new.xml `|                                          Add info about yourself (name, surname, age, number of pets, salary) in XML format to new.xml |
| `git commit -am "fill new.xml with info" `|              Push changes to GitHub |
| `git push`|
| `> preferences.xml `|                                    Create preferences.xml |
| `cat >> preferences.xml  `|                              Add info about your preferences (movie, series, food, season, country) in XML format to preferences.xml |
| `vim skills.xml `|                                       Create skills.xml and fill with info about skills studied in the course |
| `git add . `|                                            Send preferences.xml and skills.xml to GitHub |
| `git commit -m "Create and fill preferences.xml and skills.xml with info"`|
| `git push`|
 |                                                   |  Create bug_report.xml in GitHub |
|                                                    |  Make Commit changes in GitHub |
|                                                    |  Modify bug_report.xml in GitHub |
|                                                    |  Make Commit changes in GitHub |
| `git pull `|                                             Syncronize remote and local XML repositories |
| |
|                                                   |   Create a remote TXT repository |
| `git clone https://github.com/uroboros-d/TXT.git`|       Clone the TXT repository to a local machine |
| `touch new.txt `|                                        Create new.txt |
| `git add new.txt `|                                      Add new.txt under Git |
| `git commit  -m "create new.txt"  `|                     Commit new.txt |
| `git push `|                                             Push the file to GitHub |
| `vim new.txt  `|                                         Add info about yourself (name, surname, age, number of pets, salary) in TXT format to new.txt |
| `git commit -am "fill new.xml with info" `|              Push changes to GitHub |
| `git push`|
| `> preferences.txt `|                                    Create preferences.txt |
| `cat >> preferences.txt `|                               Add info about your preferences (movie, series, food, season, country) in TXT format to preferences.txt |
| `vim skills.txt `|                                       Create skills.txt and fill with info about skills studied in the course |
| `git add .   `|                                          Send preferences.txt and skills.txt to GitHub |
| `git commit -m "Create and fill preferences.txt and skills.txt with info"`|
| `git push`|
 |                                                  |   Create bug_report.txt in GitHub |
|                                                    |  Make Commit changes in GitHub |
|                                                    |  Modify bug_report.txt in GitHub |
|                                                   |   Make Commit changes in GitHub |
| `git pull`|                                              Syncronize remote and local XML repositories |
