# GitHub. HomeWork_1

# ***JSON***

 ### Создать внешний репозиторий c названием JSON.
 > Enter ***"New repository"***
 >> Create repository ***"JSON"***
 ### Клонировать репозиторий JSON на локальный компьютер.
 ```bash
 $ git clone https://github.com/Nikukulin/JSON.git
 ```
 ### Внутри локального JSON создать файл “new.json”.
 ```bash
 $ cd JSON/
 $ cat > new.json
 123
 ```
 ### Добавить файл под гит.
 ```bash
 $ git add new.json
 ```
 ### Закоммитить файл.
 ```bash
 $ git commit -m "add new file"
 ```
 ### Отправить файл на внешний GitHub репозиторий.
 ```bash
 $ git push
 ```
 ### Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
 ```bash
 $ vim new.json
    {

	    "Full name":"Nikulin Nikolay Sergeevich",
	    "Age":"25",
	    "Pets":"2",
	    "Salary":"1500$"
    }
```
 ### Отправить изменения на внешний репозиторий.
 ```bash
 $ git commit -am "added information about youself"
 ```
 ### Создать файл preferences.json
 ```bash
 $ touch preferences.json
 ```
 ### В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
```bash
 $ vim preferences.json
 {
	"Favorite film":"Harry Potter Saga",
	"Favorite show":"Shameless",
	"Favorite food":"Pasta",
	"Favorite time of the year":"Summer",
	"The contry i would like to visit":"Norway"
}
```
 ### Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
 ```bash
 $ touch skills.json
 $ vim skills.json
 {
	"Future skills":
            "Знание работы в программе Postman",
		   "Умение работать в Terminal Linux",
	        "Составление тестовой документации",
		   "Знание SQL",
		   "Навыки мобильного тестирования ПО",
		   "Знание теории тестирования ПО",
		   "Знание клиент-серверной архитектуры",
		   "Умение работать с инструментом Jmeter для нагрузочного тестирования",
		   "Умение работать с инструментом Fiddler",
		   "Умение работать с Android Studio",
		   "Знание основ програмирования на JavaScript  и на Python",
		   "Умение работать с багтрекинговыми системами",
		   "Написание автотестов"
}
```
 ### Отправить сразу 2 файла на внешний репозиторий.
 ```bash
 $ git add .
 $ git commit -m "Add new files"
 $ git push
 ```
 ### На веб интерфейсе создать файл bug_report.json.
 > Выбираем ***"Add file"*** и ***"Create new falis"***
 ### Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 > Пишем сообщение ***"Add bug_report.json"*** и нажимаем ***"Commit changes"***
 ### На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
 > Нажимаем ***"Edit this file"***
 ```json
 {
  "Bug_report":[
    "Summary",
    "Project",
    "Version",
    "Severity",
    "Priority",
    "Description",
    "Attachment",
    "Author",
    "Status"]
}
```
 ### Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 > ***"Change bug_report.json"***
 ### Синхронизировать внешний и локальный репозиторий JSON
 ```bash
 $ git pull
 ```


# ***XML***
 ### Создать внешний репозиторий c названием XML.
 > Enter ***"New repository"***
 >> Create repository ***"XML"***
 ### Клонировать репозиторий XML на локальный компьютер.
 ```bash
 $ git clone https://github.com/Nikukulin/XML.git
 ```
 ### Внутри локального XML создать файл “new.xml”.
 ```bash
 $ cd XML/
 $ touch new.xml
 ```
 ### Добавить файл под гит.
 ```bash
 $ git add new.xml
 ```
 ### Закоммитить файл.
 ```bash
 $ git commit -m "add new file"
 ```
 ### Отправить файл на внешний GitHub репозиторий.
 ```bash
 $ git push
 ```
 ### Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
 ```bash
 $ vim new.xml
 ```
 ```xml
 <Info>
	<FullName>Nikulin Nikolay Sergeevich<FullName>
	<Age>25<Age>
	<Pets>2<Pets>
	<Salary>1500$<Salary>
</Info>				
```
 ### Отправить изменения на внешний репозиторий.
 ```bash
  $ git commit -am "added information about youself"
  ```
 ### Создать файл preferences.xml
 ```bash
 $ touch preferences.xml
 ```
 ### В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
 ```bash
 $ vim preferences.xml
 ```
 ```xml
 <Intersts>
	<Favoritefilm>Harry Potter Saga<Favoritefilm>
	<FavoritesHow>Shameless<FavoritesHow>
	<Favoritefood>Pasta<Favoritefood>
	<FavoriteTimeOfTheYear>Summer<FavoriteTimeOfTheYear>
	<TheContryIWouldLikeToVisit>Norway<TheContryIWouldLikeToVisit>
</Interests>
```
 ### Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
 ```bash
 $ touch skills.xml
 $ vim skills.xml
 ```
 ```xml
 <FutureSkills>
    		<skill1>Знание работы в программе Postman<skill1>
			<skill2>Умение работать в Terminal Linux<skill2>
	 		<skill3>Составление тестовой документации<skill3>
	 		<skill4>Знание SQL<skill4>
	 		<skill5>Навыки мобильного тестирования ПО<skill5>
	 		<skill6>Знание теории тестирования ПО<skill6>
	 		<skill7>Знание клиент-серверной архитектуры<skill7>
	 		<skill8>Умение работать с инструментом Jmeter для нагрузочного тестирования<skill8>
	 		<skill9>Умение работать с инструментом Fiddler<skill9>
	 		<skill10>Умение работать с Android Studio<skill10>
	 		<skill11>Знание основ програмирования на JavaScript  и на Python<skill11>
	 		<skill12>Умение работать с багтрекинговыми системами<skill12>
	 		<skill13>Написание автотестов<skill13>
</FutureSkills>
```
 ### Сделать коммит в одну строку.
 ```bash
 $ git add . ; git commit -m "add new files"
 ```
 ### Отправить сразу 2 файла на внешний репозиторий.
 ``` bash
 $ git push
 ```
 ### На веб интерфейсе создать файл bug_report.xml.
 > Выбираем ***"Add file"*** и ***"Create new falis"***
 ### Сделать Commit changes (сохранить) изменения на веб интерфейсе.
  > Пишем сообщение ***"Add bug_report.xml"*** и нажимаем ***"Commit changes"***
 ### На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 > Нажимаем ***"Edit this file"***
 ```xml
 <BugReport>
    <b1>Summary<b1>
    <b2>Project<b2>
    <b3>Version<b3>
    <b4>Severity<b4>
    <b5>Priority<b5>
    <b6>Description<b6>
    <b7>Attachment<b7>
    <b8>Author<b8>
    <b9>Status<b9>
</BugReport>
```
 ### Сделать Commit changes (сохранить) изменения на веб интерфейсе.
  > ***"Change bug_report.xml"***
 ### Синхронизировать внешний и локальный репозиторий XML
 ```bash
 $ git pull
 ```