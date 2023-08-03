HOMEWORK_2

| Command | Description |
| ---- | --- |
|`git branch Postman; git branch Jmeter; git branch CheckLists; git branch Bug_Reports; git branch SQL; git branch Charles; git branch Mobile_testing ` |                                    В локальном репозитории сделать ветки для: Postman, Jmeter, CheckLists, Bag Reports, SQL, Charles, Mobile testing |
| `git push origin --all `|                           Запушить все ветки в удаленный репозиторий |
| `git checkout Bug_Reports  `|                      В ветке Bug_Reports сделать текстовый документ со структурой баг репорта |
| `vim bug_report.txt  `|                     |
| `git add .  `|                                      Запушить структуру багрепорта в удаленный репозиторий |
| `git commit -m "bug report structure"`| |
| `git push -u origin Bug_reports`| |
| `git checkout main `|                              Вмержить ветку Bag Reports в main |
| `git merge Bug_reports`| |
| `git push      `|                                   Запушить main в удаленный репозиторий |
| `git checkout CheckLists `|                        В ветке CheckLists набросать структуру чек листа    |                                        
| `vim checklist.txt`| |
| `git add . `|                                      Запушить структуру в удаленный репозиторий |
| `git commit -m "checklist structure"`| |
| `git push -u origin Checklists`| |
| `   `|                                             На внешнем репозитории сделать Pull Request ветки CheckLists в main |
| `git checkout main    `|                           Синхронизировать удаленную и локальную ветки main |
| `git pull`| |
