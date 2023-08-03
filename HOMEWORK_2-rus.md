HOMEWORK_2

| Command | Description |
| ---- | --- |
|`git branch Postman; git branch Jmeter; git branch CheckLists; git branch Bug_Reports; git branch SQL; git branch Charles; git branch Mobile_testing ` |                                    1. В локальном репозитории сделать ветки для: Postman, Jmeter, CheckLists, Bug_Reports, SQL, Charles, Mobile_testing |
| `git push origin --all `|                           2. Запушить все ветки в удаленный репозиторий |
| `git checkout Bug_Reports  `|                      3. В ветке Bug_Reports сделать текстовый документ со структурой баг репорта |
| `vim bug_report.txt  `|                     |
| `git add .  `|                                      4. Запушить структуру багрепорта в удаленный репозиторий |
| `git commit -m "bug report structure"`| |
| `git push -u origin Bug_reports`| |
| `git checkout main `|                              5. Вмержить ветку Bug_Reports в main |
| `git merge Bug_reports`| |
| `git push      `|                                   6. Запушить main в удаленный репозиторий |
| `git checkout CheckLists `|                        7. В ветке CheckLists набросать структуру чек листа    |                                        
| `vim checklist.txt`| |
| `git add . `|                                      8. Запушить структуру в удаленный репозиторий |
| `git commit -m "checklist structure"`| |
| `git push -u origin Checklists`| |
| `   `|                                             9. На внешнем репозитории сделать Pull Request ветки CheckLists в main |
| `git checkout main    `|                           10. Синхронизировать удаленную и локальную ветки main |
| `git pull`| |
