# HW_GitHub
## XML

 1. Создать внешний репозиторий c названием XML.
 2. Клонировать репозиторий XML на локальный компьютер.
 
	`git clone https://github.com/setter-getter/XML.git`
 3. Внутри локального XML создать файл “new.xml”
 
	`touch new.xml`
 4. Добавить файл под гит.
 
    `git add new.xml`
  
 5. Закоммитить файл.
 
	 `git commit -m "add new.xml"`
   
 6. Отправить файл на внешний GitHub репозиторий.
 
	 `git push`
    
 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
```
	vim new.xml
	i
	
<about_myself>
	<first_name>Dmitry</first_name>
	<last_name>Bondarenko</last_name>
	<patronymic>Anatolevich</patronymic>
	<age>33</age>
	<number_of_pets>1</number_of_pets>
	<desired_salary>350</desired_salary>
</about_myself>
	
	Esc
	:wq
  ```
  
 8. Отправить изменения на внешний репозиторий.
 ```
	git add new.xml
	git commit -m "update new.xml"
	git push
 ```
 9. Создать файл preferences.xml
 
	`touch preferences.xml`
  
 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
```
	vim preferences.xml
	i
 
 <preferences>
    <favorite_movie> 1+1</favorite_movie>
    <favorite_TV_series>Friends</favorite_TV_series>
    <favorite_food>Borsch</favorite_food>
    <favorite_time_of_the_year>Summer</favorite_time_of_the_year>
    <favorite_country>Iceland</favorite_country>
</preferences>

	Esc
	:wq
```
 11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
 ```
	touch skills.xml
	
	vim skills.xml
	i
	
<skills>
    <testing_theory>
        <sdlc>SDLC</sdlc>
        <stlc>STLC</stlc>
        <bug_reports>Bug reports</bug_reports>
        <documentation>Documentation</documentation>
    </testing_theory>
    <skills_of_working_whith>
        <bash>Bash</bash>
        <github>Github</github>
        <postman>Postman</postman>
        <sql>SQL</sql>
        <fidler>Fidler</fidler>
    </skills_of_working_whith>
</skills>

	Esc
	:wq
```
 12. Отправить сразу 2 файла на внешний репозиторий.
 ```
	git add preferences.xml skills.xml
	git commit -m "add preferences.xml skills.xml"
	git push
 ``` 
 13. На веб интерфейсе создать файл bug_report.xml.
 ```
	Add file -> create new file -> bug_report.xml
```
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

`	"create bug_report.xml" -> commit new file`

 15. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
	
  `	"Edit this file"`
```
<bug_report>
    <id>ID</id>
    <summary>Summary</summary>
    <str>Steps to reproduce</str>
    <actual_result>Actual result</actual_result>
    <expected_result>Expected result</expected_result>
    <severity>Major</severity>
    <priority>High</priority>
</bug_report>
```
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

 ` "update bug_report.xml" -> commit changes`

 17. Синхронизировать внешний и локальный репозиторий XML
 
 `git pull`
