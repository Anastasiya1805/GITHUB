<div align="center">

### ***"HITHUB"*** 
</div>

- На локальном репозитории сделать ветки для:
    - Postman 
`git branch Postman`;
    - Jmeter 
`git branch Jmeter`;
    - CheckLists 
`git branch CheckLists`;
    - Bug Report
`git branch Bug Report`;
    - SQL
`git branch SQL`;
    - Charles
`git branch Charles`;
    - Mobile testing
`git branch Mobile testing`.

- Запушить все ветки на внешний репозиторий:
    - `git push -u origin Postman`;
    - `git push -u origin Jmeter`;
    - `git push -u origin CheckLists`;
    - `git push -u origin Bug_Report`;
    - `git push -u origin SQL`;
    - `git push -u origin Charles`;
    - `git push -u origin Mobile testing`.

- Зайдем в ветку  `Bug_Report`:
    - `git checkout Bug_Report`.

- Создадим файл:
    - `touch bug_report.txt`.

- Напишем `Bug Report` в нем:
    - `vim bug_report.txt
insert`

```TXT
ID: 1
Summary: 
Incident 
Pre-condition: 
Steps: 
Actual result:
Expected result: 
Environment: 
Build:
Attempts to repeat:  
Severity:3
Priority:3
Attachment
```

`esc :wq(сохранить и выйти)`

- Запушить структуру багрепорта на внешний репозиторий 
    - Для отслеживания файла 
`git add bug_report.txt
git status`
    - Закоммитим:
`git commit -m "bug_report.txt"
git push`

- Вмержить ветку `Bug Reports` в `Main`
Находимся в ветке `Main(git checkout main)`:
`git merge Bug_Report`

- Запушить `main` на внешний репозиторий: 
`git push`

- В ветке `CheckLists` набросать структуру чек листа.

- Зайдем в ветку  `CheckLists`
`git checkout CheckLists`:

`touch CheckLists.txt
vim CheckLists.txt
insert`

```Checklists
Id:
Summury:
Status
Comment
```
`esc :wq`

- Запушить структуру на внешний репозиторий

`git add CheckLists.txt
git status`
- Закоммитим:
`git commit -m "CheckLists.txt"
git push`

- На внешнем репозитории сделать `Pull Request `ветки `CheckLists` в `main`
 Нажмем  `compare&pull request` (`merge` на внешнем репозитории)
Из ветки `Checklists` в `main`
В `write` напишем коммент
`Confern merge`

- Синхронизировать Внешнюю и Локальную ветки `Main`:
`git pull`