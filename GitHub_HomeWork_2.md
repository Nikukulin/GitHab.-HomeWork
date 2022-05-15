# GitHub. HomeWork_2

### На локальном репозитории сделать ветки для:
- #### ***Postman***
- #### ***Jmeter***
- #### ***CheckLists***
- #### ***Bug Reports***
- #### ***SQL***
- #### ***Charles***
- #### ***Mobile testing***
```bash
$ git branch Postman
$ git branch Jmeter
$ git branch CheckLists
$ git branch Bug_reports
$ git branch SQL
$ git branch Charles
$ git branch Mobile_testing
```

### Запушить все ветки на внешний репозиторий
```bash
$ git push --all
```
### В ветке Bug Reports сделать текстовый документ со структурой баг репорта
```bash
$ git checkout Bug_reports
$ touch bug_report.txt
$ vim bug_report.txt
Summary:
Project:
Version:
Severity:
Priority:
Description:
Attachment:
Author:
Status:
```
### Запушить структуру багрепорта на внешний репозиторий
```bash
$ git add bag_report.txt
$ git commit -m "add file bug report"
$ git push
```
### Вмержить ветку Bag Reports в Main
```bash
$ git checkout main
$ git merge Bug_reports
```
> Затем нужно подтвердить слияние веток во вкладке ***"Pull requests"***
### Запушить main на внешний репозиторий.
```bash
$ git push -u origin main
```
### В ветке CheckLists набросать структуру чек листа.
```bash
$ git checkout CheckLists
$ touch check_list.txt
$ vim check_list.txt
```
Регистрация нового пользователя.
- Через номер мобильного телефона : Ok
- Через email адрес : Ok
Авторизация пользователя.
- Через номер мобильного телефона : Filed
- Через email адрес : Ok
- Через имя пользователя : Ok
Формат пароля.
- Содержит не менее 8 символов : Ok
- Содержит заглавные буквы : Ok
- Содержит цифры : Ok
- Содержит спецсимволы : Filed
- Содержит менее 8 символов : Filed
- Содержит русские буквы : Ok
- Содержит латинские буквы : Ok


### Запушить структуру на внешний репозиторий
```bash
$ git add check_list.txt
$ git commit -m "added file check list"
$ git push
```
### На внешнем репозитории сделать Pull Request ветки CheckLists в main
> Войти во вкладку ***"Pull request"*** и подтвердить слияние веток.
### Синхронизировать Внешнюю и Локальную ветки Main
```bash
$ git pull
```