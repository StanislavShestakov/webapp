Практика Java. Разработка Web приложения.
===============================

## Проект: https://github.com/JavaWebinar/webapp

## Урок 9
- <a href="https://www.hscripts.com/tutorials/jsp/variables.php">Predefined Variables in JSP</a>
- <a href="http://stackoverflow.com/questions/4764405/how-to-use-relative-paths-without-including-the-context-root-name">How to use relative paths in JSP</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFWnQ1WnBzM0ZTWms">JSTL. Разбор HW8</a>
- <a href="https://ru.wikipedia.org/wiki/JSTL">JSTL</a>
- <a href="http://devcolibri.com/1250">JSTL для написания JSP страниц</a>
- <a href="http://search.maven.org/#artifactdetails%7Cjstl%7Cjstl%7C1.2%7Cjar">Download form maven central</a>

### 2. HTTP POST. Редактирование.
### 3. ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFdVBBRTgzRWc0a1U">Реляционная СУБД. PostgreSQL. JDBC</a>

- <a href="http://habrahabr.ru/post/103021/">Реляционные базы</a>. SQL. Денормализация. PK, FK, Cascade
- <a href="http://ru.wikipedia.org/wiki/Java_Database_Connectivity">JDBC</a>. <a href="http://www.developersbook.com/jdbc/interview-questions/jdbc-interview-questions-faqs.php">JDBC Architecture</a>.
- ConnectionFactory. Простейшая реализация IStorage для DB.
- Ресурсы:
    - <a href="http://devcolibri.com/477">Работа с базами данных с помощью JDBC драйвера</a>
    - <a href="https://www.youtube.com/playlist?list=PLIU76b8Cjem5qdMQLXiIwGLTLyUHkTqi2">Обущающее видео по JDBC</a>

### ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Домашнее задание HW9
- Запустить `SqlStorageTest`
  - Тк. `SqlStorage` реализуем пока без секций, в `ResumeTestData` закомментарил секции.
  - Креденшелы к DB задаются в `src\webapp.properties`
  - Для работы с DB надо в проект и артефакты добавить нужный драйвер базы данных:
    - <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFdnVWWGJhenV4d0E">Oracle driver</a> или
    - <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFQ2RVNk92M3VKQTg">Postgres driver</a>

- Доделать SqlStorage без секций.
- Попробовать вынести общий код (`getConnection(), prepareStatement, catch (SQLException e)`) в класс SqlHelper.
