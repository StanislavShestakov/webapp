Практика Java. Разработка Web приложения.
===============================

## Проект: https://github.com/JavaWebinar/webapp

## Урок 7

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 1. <a href="">Разбор HW6</a>.

#### Патч <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFc0t5dmpzYVYxZTg">7-1-HW6-prepare.patch</a>
#### Патч <a href="https://drive.google.com/open?id=0B9Ye2auQ_NsFS3RzaU5WLXY5QlU">7-2-DataStreamFileStorage.patch</a>

### Сериализация. Работа с XML. Работа с JSON.
- <a href="http://www.intuit.ru/studies/courses/16/16/lecture/27133?page=3">Сериализация объектов (serialization)</a>
- Реализация Storage используя <a href="http://habrahabr.ru/post/60317/">сериализацию</a>.
- <a href="http://habrahabr.ru/post/216431/">Java 8 Time API.</a>
- Структурированное хранение данных: json, xml, Xsd, Xslt, xPath
- <a href="https://code.google.com/p/google-gson/">google-gson</a> и <a href="https://github.com/FasterXML/jackson">Jackson</a>. Реализация хранения в JSON.
- Java API: JAXB, StAX, XPath. Реализация хранения в XML.
- <a href="http://stackoverflow.com/questions/152313/xml-attributes-vs-elements">XML Attributes vs Elements</a>
- <a href="http://www.vogella.com/tutorials/JavaXML/article.html">Java and XML</a>
- <a href="http://www.duct-tape-architect.ru/?p=315">Все XML-технологии за 5 минут</a>

### ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Домашнее задание HW7
    Сделать SerializeFileStorage (Стандартная сериализация)
    Починить XmlStorage (обновите проект из github) с помощью XmlAdapter.
    Сделать рабочим JsonFileStorage (использовать isSectionSupported)</pre>

- <a href="http://www.eclipse.org/eclipselink/documentation/2.6/moxy/advanced_concepts006.htm">Using an XmlAdapter</a>

Optional:

    Реализовать JsonFileStorage с поддержкой секций.
    Сделать возможным выбор между Path и File для всех реализаций IStorage в файлах.</pre>

- <a href="http://stackoverflow.com/questions/5800433/polymorphism-with-gson#answer-8683689">Polymorphism with gson</a>
- <a href="http://habrahabr.ru/company/naumen/blog/228279/">Gson или «Туда и Обратно»</a>
