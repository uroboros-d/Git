HOMEWORK_2

| Command | Description |
| ---- | --- |
|`git clone https://github.com/uroboros-d/Branches.git`|1. В локальном репозитории сделать ветки для: Postman, Jmeter, CheckLists, BugReports, SQL, Charles, MobileTesting|
|`cd Branches`||
|`git commit --allow-empty -m 'Initial commit'`|
|`git branch Postman; git branch Jmeter; git branch CheckLists; git branch BugReports; git branch SQL; git branch Charles; git branch MobileTesting ` |                                     |
| `git push origin -u --all `|                           2. Запушить все ветки в удаленный репозиторий |
| `git checkout BugReports  `|                      3. В ветке BugReports сделать текстовый документ со структурой баг репорта |
| `vim bug_report.txt  `|                     |
| `git add bug_report.txt  `|                                      4. Запушить структуру багрепорта в удаленный репозиторий |
| `git commit -m "bug_report.txt"`| |
| `git push`| |
| `git checkout main `|                              5. Вмержить ветку BugReports в main |
| `git merge BugReports`| |
| `git push     `|                                   6. Запушить main в удаленный репозиторий |
| `git checkout CheckLists `|                        7. В ветке CheckLists набросать структуру чек листа    |                                        
| `vim check_list.txt`| |
| `git add check_list.txt `|                                      8. Запушить структуру в удаленный репозиторий |
| `git commit -m "check_list.txt"`| |
| `git push `| |
| |                                             9. На внешнем репозитории сделать Pull Request ветки CheckLists в main |
| `git checkout main    `|                           10. Синхронизировать удаленную и локальную ветки main |
| `git pull`| |
