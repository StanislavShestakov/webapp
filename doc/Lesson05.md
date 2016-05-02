Практика Java. Разработка Web приложения.
===============================

## Проект: https://github.com/JavaWebinar/webapp

## Урок 5
### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 1. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFcDBpWjZDdVVoVHM">Контейнеры/коллекции.</a>
- <a href="http://en.wikipedia.org/wiki/Java_collections_framework">Java Сollections Framework.</a>
- <a href="http://www.intuit.ru/studies/courses/16/16/lecture/27131?page=2">List, Set, Map, Queue, Iterator, ListIterator</a>
- Устаревшие thread-safe реализации Hashtable, Vector, Stack
- <a href="http://habrahabr.ru/users/tarzan82/topics/">Структуры данных в картинках</a>
- <a href="http://info.javarush.ru/tag/Collection/">Часто-задаваемые-на-собеседованиях-вопросы-по-классам-коллекций.</a>
- <a href="http://appliedjava.wordpress.com/2010/09/23/java-collections-framework/">Коллекции Java (Java Collections Framework)</a>
- Посмотреть реализацию Map. <a href="http://habrahabr.ru/post/162017/">Проверить себя по статье</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 2. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFd1ZUNkNJUkYwZGs">Вопрос про Stack. Разбор HW4.</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 3. <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFYmlKOVFseXE3clk">Вложенные, внутренние, локальные и анонимные классы.</a>
- <a href="http://easy-code.ru/lesson/java-nested-classes">Вложенные и внутренние классы</a>. Примеры в Collections API: Arrays.asList, Map.Entry, LinkedList.Node, Collections, Iterator
- <a href="http://easy-code.ru/lesson/local-anonymous-nested-classes-java">Локальные и анонимные классы.</a> Comparator.

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 4. <a href="">Логгирование</a>
- Логирование. <a href="http://habrahabr.ru/post/130195/">Настройка логирования</a>
- <a href="http://habrahabr.ru/post/113145/">Java Logging: история кошмара (Optional)</a>
- <a href="http://skipy.ru/useful/logging.html">Ведение лога приложения (Optional)</a>

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png)  5. <a href="http://www.youtube.com/watch?v=_PDIVhEs6TM">Доступно о Java 8 Lambda</a>

-  <a href="http://devcolibri.com/4137#t2">Java 8: Lambda выражения</a>
-  <a href="http://devcolibri.com/4274#t7">Java 8: Потоки</a>
-  <a href="http://prologistic.com.ua/polnoe-rukovodstvo-po-java-8-stream.html">Pуководство по Java 8 Stream</a>
-  <a href="http://habrahabr.ru/post/224593/">Лямбда-выражения в Java 8</a>
-  <a href="https://github.com/winterbe/java8-tutorial">A Guide to Java 8</a>
-  <a href="http://habrahabr.ru/company/luxoft/blog/270383/">Шпаргалка Java Stream API</a>
-  <a href="https://stepic.org/lesson/Stream-API-12781">Stream API. Видеурок от Алексея Владыкина</a>
-  <a href="http://stackoverflow.com/questions/28319064/java-8-best-way-to-transform-a-list-map-or-foreach">stream.map vs forEach</a>

### ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Домашнее задание HW5
    Зарефакторить хранение секций и контактов на основе Map.
    Выделить общий класс AbstractStorage и реализовать подклассы ListStorage и MapStorage 
                                                                 (выбор реализации List и Map за вами).
    Сделать Position внутрениим/вложенным классом. Проверить его созадние через new