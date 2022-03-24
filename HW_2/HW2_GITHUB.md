<div align="center">

### ***"JSON"*** 
</div>

+ Создать внешний репозиторий c названием `JSON`: Заходим в `GITHUB`.Находимся в своем профиле. Выбираем `Repositories` и выбираем `New`. В `Repository name` пишем название.Если нужно `Discription`. 
В радиобаттоне нажимаем `Public`.В чекбокс форме нажимаем `Add a README file`.Тапнем на кнопку `"Create repository"`.
 + Клонировать репозиторий `JSON` на локальный компьютер: `git clone https://github.com/Anastasiya1805/JSON.git`.
 + Внутри локального `JSON` создать файл: `“new.json”. cat > new.json`.
 + Добавить файл под гит: `git add new.json`.     
    + Проверим статус: `git status`.
 + Закоммитить файл: `git commit -m "new.json"`.
 + Отправить файл на внешний `GitHub` репозиторий: `git push`.
 + Отредактировать содержание файла: `“new.json” `- написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате `JSON.` 
`cat > new.json`

```json
  { 
    "firstname": "Анастасия",
     "lastname": "Колесникович",
   "patronymic": "Романовна",
         "pets": 1,
       "salary": "Чем больше,тем лучше)"
}
```

 + Отправить изменения на внешний репозиторий: `git commit -am new.json; git push`.
 + Создать файл preferences: `json  cat > preferences.json`.
 + В файл `preferences.json` добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате `JSON`:
`cat > preferences.json`.
``` JSON
{ 
"likemovie": "Наркоз",
"likeserial": "Сверхъестественное",
"likefood": "Роллы",
"likeseason": "Лето",
"likecountry": "Греция"
}
```
 + Создать файл `sklls.json` добавить информацию о скиллах которые будут изучены на курсе в формате `JSON`: `cat > sklls.json`.
 ```JSON
 {
"GIT":"GITBUSH",
"API": "Postman",
"SQL": "MySQL",
"Bug-treking_system": "JIRA",
"Chrome": "Dev Tools"
}
```
 + Отправить сразу 2 файла на внешний репозиторий.
 `git add .; git commit -m 'new'; git push`.
 + На веб интерфейсе создать файл `bug_report.json`. Выбрать `Add fail; Create file`.Напишем название `bug_report.json`.
 + Сделать `Commit changes` (сохранить) изменения на веб интерфейсе. Введем название нашего файла.Нажмем сохранить `Create file`.
 + На веб интерфейсе модифицировать файл `bug_report.json`, добавить баг репорт в формате `JSON`. Изменим файл.Зайдем в файл `bug_report.json`.Справа есть карандашик `Edit this file`.Нажимаем и вносим изменения.Нажимаем `Commit changes`.
 ```JSON
 {
"ID":1,
"Summary": "Во вкладке Поля и выборе поля в его описании площадь поля для учета отображается с округлением до сотых",
"Steps": ["1.Выбрать вкладку Хозяйство в левом нижнем углу",
          "2.Тапнуть на любое из хозяйств",
          "3.В левом углу тапнуть на любой из имеющихся полей",
          "4. Длинным тапом снизу-вверх вытянуть информацию о выбранном поле",
          "5. Посмотреть в каком формате написана площадь для учета"],
"Expected result": "Площадь для учета написана в Га с округлением до десятых",
"Actual result": "Площадь для учета написана в Га с округлением до сотых",
"Enviroment": "Окружение SkyScout, версия 3.9.0.0001 iPhone 7+ IOS 15.1",
"Severity": "Low",
"Priority": "Normal"
}
```
 + Сделать `Commit changes` (сохранить) изменения на веб интерфейсе. Введем составные части `Bug Report` в формате `json.Нажмем Commit changes.
 + Синхронизировать внешний и локальный репозиторий JSON: `git pull`.

<div align="center">

### ***"TXT"*** 
</div>

 + Создать внешний репозиторий c названием `TXT`. Заходим в `GITHUB`.Находимся в своем профиле. Выбираем `Repositories` и выбираем `New`.В `Repository name` пишем название.Если нужно `Discription`. 
В радиобаттоне нажимаем `Public`.В чекбокс форме нажимаем `Add a README file`.Тапнем на кнопку `Create repository`.
 + Клонировать репозиторий `TXT` на локальный компьютер: 
`git clone https://github.com/Anastasiya1805/TXT.git`.
 + Внутри локального `TXT` создать файл: `“new.txt”. touch new.txt`.
 + Добавить файл под гит: `git add new.txt; git status`.
 + Закоммитить файл: `git commit -m "new.txt"`.
 + Отправить файл на внешний `GitHub` репозиторий: `git push`.
 + Отредактировать содержание файла `new.txt` - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате `TXT`: `vim new.txt`.
Нажием `i`. Вводим текст.
```
Kolesnikovich Anastasiya Romanovna
I have one pet
500$
```
+ Жмем `esc`. И снизу в левом
углу вводим : `:wq` (сохранили и вышли из режима).
+ Отправить изменения на внешний репозиторий. `git commit -am "new.txt", git push`.
+ Создать файл `preferences.txt`: `touch preferences.txt`.
+ В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT:
`vim preferences.txt`.
```
Like movie: Anesthtesia,
Like serial: Supernatural,
Like food: Sushi,
Like season: Summer,
Like country: Greece.
```
 + Создать файл `sklls.txt` добавить информацию о скиллах которые будут изучены на курсе в формате TXT: `touch sklls.txt. vim skills.txt`.
 ```
 Hard skills: Git, GitBush, SQL, JMeter, Charls, Postman.
 ```
 + Сделать коммит в одну строку: `git add . && git commit -m "preferences.txt"/"skills.txt"`.
 + Отправить сразу 2 файла на внешний репозиторий: `git push`.
 + На веб интерфейсе создать файл `bug_report.txt`. Выбрать `Add fail`. Напишем название `Create file` .
 + Сделать `Commit changes` (сохранить) изменения на веб интерфейсе.Введем название нашего файла.Нажмем сохранить `Create file`.
+ На веб интерфейсе модифицировать файл `bug_report.txt`, добавить баг репорт в формате `TXT`. Зайдем в файл `bug_report.txt`. Отредактируем файл. Справа есть карандашик `Edit this file`.
Нажимаем и вносим изменения. Нажимаем `Commit changes`.
```
ID:1,
Summary: "Во вкладке Поля и выборе поля в его описании площадь поля для учета отображается с округлением до сотых",
Steps: 1.Выбрать вкладку Хозяйство в левом нижнем углу,
          2.Тапнуть на любое из хозяйств,
          3.В левом углу тапнуть на любой из имеющихся полей,
          4. Длинным тапом снизу-вверх вытянуть информацию о выбранном поле,
          5. Посмотреть в каком формате написана площадь для учета,
Expected result: Площадь для учета написана в Га с округлением до десятых,
Actual result: "Площадь для учета написана в Га с округлением до сотых,
Enviroment: Окружение SkyScout, версия 3.9.0.0001 iPhone 7+ IOS 15.1,
Severity: Low,
Priority: Normal
```
+ Сделать `Commit changes` (сохранить) изменения на веб интерфейсе .Введем `Bug Report` в формате `txt`. Нажмем Commit changes.
+ Синхронизировать внешний и локальный репозиторий `TXT`: `git pull`.

<div align="center">

### ***"XML"*** 
</div>

+ Создать внешний репозиторий c названием `XML`. 
+ Клонировать репозиторий `XML` на локальный компьютер: `git clone https://github.com/Anastasiya1805/XML-.git`.
+ Внутри локального `XML` создать файл: `“new.xml”.touch new.xml`.
+ Добавить файл под гит: `git add new.xml git status`.
+ Закоммитить файл: `git commit -m new.xml`.
+ Отправить файл на внешний `GitHub` репозиторий: `git push`.
+ Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML: 
`vim new.xml`.
```XML
<?xml version="1.1" encoding="UTF-8" ?>
<ABOUTME>
  <NAME>Anastasiya</NAME>
  <LASTNAME>Kolesnikovich</LASTNAME>
  <PATRONUMIK>Romanovna</PATRONUMIK>
  <PETS>1</PETS>
  <SALARY>500$</SALARY>
</ABOUTME>
```
+ Отправить изменения на внешний репозиторий: `git commit -am "new.xml" ; git push`.
+ Создать файл `preferences.xml`: `touch preferences.xml`.
+ В файл `preferences.xml` добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате `XML`:
`vim preferences.xml`.
```XML
<?xml version="1.0" encoding="UTF-8" ?>
<Preferences>
<Likemovie>Anesthtesia</Likemovie>
<Likeserial>Supernatural</Likeserial>
<Likefood>Sushi</Likefood>
<Likeseason>Summer</Likeseason>
<Likecountry>Greece</Likecountry>
</Preferences>
```
+ Создать файл `sklls.xml`. Добавить информацию о скиллах которые будут изучены на курсе в формате XML: `touch skills.xml; vim skills.xml`.
```XML
<?xml version="1.0" encoding="UTF-8" ?>
<Hardskills>Git,GitBush,SQL,JMeter,Charls,Postman</Hardskills> 
```
+ Сделать коммит в одну строку: `git add . && git commit -m preferences.xml/skills.xml`.
+ Отправить сразу 2 файла на внешний репозиторий: `git push`.
+ На веб интерфейсе создать файл `bug_report.xml`. Выбрать `Add fail`. Напишем название `Create file`.
+ Сделать `Commit changes` (сохранить) изменения на веб интерфейсе. Введем название нашего файла.Нажмем сохранить `Create file`.
+ На веб интерфейсе модифицировать файл `bug_report.xml`, добавить баг репорт в формате `XML`. Зайдем в файл `bug_report.xml`. Справа есть карандашик `Edit this file`. Нажимаем и вносим изменения. Нажимаем `Commit changes`.
```XML
<?xml version="1.0" encoding="UTF-8" ?>
<Bug_report>
  <ID>1</ID>
  <Summary>Во вкладке Поля и выборе поля в его описании площадь поля для учета отображается с округлением до сотых</Summary>
  <Steps>1.Выбрать вкладку Хозяйство в левом нижнем углу</Steps>
  <Steps>2.Тапнуть на любое из хозяйств</Steps>
  <Steps>3.В левом углу тапнуть на любой из имеющихся полей</Steps>
  <Steps>4. Длинным тапом снизу-вверх вытянуть информацию о выбранном поле</Steps>
  <Steps>5. Посмотреть в каком формате написана площадь для учета</Steps>
<Expectedresult>Площадь для учета написана в Га с округлением до десятых</Expectedresult>
<Actualresult>Площадь для учета написана в Га с округлением до сотых</Actualresult>
<Enviroment>Окружение SkyScout, версия 3.9.0.0001 iPhone 7+ IOS 15.1</Enviroment>
<Severity>Low</Severity>
<Priority>Normal</Priority>
</Bug_report>					
```
+ Сделать `Commit changes` (сохранить) изменения на веб интерфейсе. Введем `Bug Report` в формате `xml`. Нажмем `Commit changes`.
+ Синхронизировать внешний и локальный репозиторий `XML`: `git pull`.

