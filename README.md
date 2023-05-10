XML

# 1. **Создать внешний репозиторий c названием XML.** - *Зайти на сайт Git Hub, создать новый репозиторий XML*
# 2. **Клонировать репозиторий XML на локальный компьютер.** - *скопировать ссылку на сайте в реопзитории, зайти в терминал и написать git clone https://github.com/HannaKarsanova/XML.git*
# 3. **Внутри локального XML создать файл “new.xml”.** - *touch new.xml*
# 4. **Добавить файл под гит.** - *git add .*
# 5. **Закоммитить файл. ** - *git commit -m «new.xml»*
# 6. **Отправить файл на внешний GitHub репозиторий. **- *git push*
# 7. **Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.** - *cat > new.xml*
'''
- <?xml version="1.0" encoding="UTF-8"?>
- <fullName> Hanna Karsanova </fullName>
- <age>29</age>
- <numberOfPets>2</numberOfPets>
- <futureDesireSalary>3000</futureDesireSalary> 
'''
# 8. **Отправить изменения на внешний репозиторий. **- *git commit -a -m «new.xml»     git push*
# 9. **Создать файл preferences.xml**  - *touch preferences.xml*
# 10. **В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML. **-* cat > preferences.xml*
- <favouriteFilm>Spirit</favouriteFilm>
- <favouriteSerial>Sex and the sity</favouriteSerial>
- <favouriteFood>Pizza</favouriteFood>
- <favouriteSeason>Winter</favouriteSeason>
- <countryToVisit>Japan</countryToVisit>
# 11. **Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML **- *cat > skills.xml*
- <?xml version="1.0" encoding="UTF-8"?>
- <skill> Write Bash commands</skill>
- <skill> Git Hub and Git </skill>
- <skill> Test design techniques </skill>
- <skill> Postman </skill>
- <skill> Charles and Fiddler </skill>
- <skill> SQL basics </skill>
- <skill> Jmeter </skill>

# 12. **Сделать коммит в одну строку.** - *git add .     Git commit -a -m «new files»*
# 13.** Отправить сразу 2 файла на внешний репозиторий. **- *git push*
# 14. **На веб интерфейсе создать файл bug_report.xml. -** 
	1. Нажать кнопку add file
	2. Нажать create new file
	3. Написать название файла 
# 15.* Сделать Commit changes (сохранить) изменения на веб интерфейсе. **- *нажать Сommit changes*
# 16. **На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML. **- *Нажать  edit file*
- <ID> Json </ID>
- <Title> What?Where?When? </Title>
- <Severity> "Medium </Severity>
- <Priority> High </Priority>
- <Precondition> Preparation reproduce </Precondition>
- <Environment> Devices </Environment>
- <STR> Steps to reproduce </STR>
- <ER> Expected result </ER>
- <AR> Actual Result </ER>
- <Attachment> link </Attachment>
# 17. **Сделать Commit changes (сохранить) изменения на веб интерфейсе.** - *нажать commit changes*
# 18.** Синхронизировать внешний и локальный репозиторий XML** - *git pull* 
