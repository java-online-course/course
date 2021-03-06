### Java - Collections
1. Что такое коллекция? Для чего она необходима?
1. Назовите основную иерархию коллекций (интерфейсы и их основные реализации).
1. Расскажите кратко о предназначении каждого вида коллекции. Чем она удобна? Каковые особенности ее работы?
1. В чем преимущество коллекций на фоне массивов?
1. Как создать коллекцию из массива?
1. Как внутри устроен `ArrayList`?
1. Как внутри устроен `LinkedList`? 
1. Чем отличается `ArrayList` от `LinkedList`? В каких случаях лучше использовать первый, а в каких второй?
1. Как происходит удаление элементов из `ArrayList`? Как меняется в этом случае размер `ArrayList`?
1. Как происходит удаление элементов из `LinkedList`? Что происходит с элементами в `LinkedList` при удалении одного из них?
1. Как сравнить элементы двух коллекий? Как узнать, что первая коллекция содержит все те же элементы, что и вторая?
1. Дайте определение понятиям `Iterator` и `Iterable`.
1. Для чего нужно коллекция `TreeSet`? Что такое `Comparator` и `Comparable`, как они связаны с этой коллекцией?
1. Устройство `HashMap`? Как зависит `HashMap` от реализации метода `hashCode`? Что такое корзины (бакеты) в `HashMap`?
1. Как получить все ключи `HashMap`?
1. Как получить все значения `HashMap`?
1. Расскажите по шагам, что происходит при вставке элементов в `HashMap`? А если будет вставка по одинаковому ключу? Если по разным? Что лучше использовать в качетве ключа?
1. В чем разница между `HashMap`, `SortedMap`, `TreeMap`?
1. Какие коллекции реализуют интерфейс `Set`? В чем особенность данных коллекций? Как они работают? Как зависят коллекции типа `Set` от реализации метода `equals`?
1. В каких случаях стоит использовать `Queue`? Чем `Queue` отличается от `Deque`?

### Java - Generics
1. Что такое ковариантность, контрвариантность и инвариантность? Приведите примеры из языка Java
1. Что отличает `List<String> parsedWords = ...` от просто `List parsedWords = ...`?
1. При объявлении типов переменных, что предпочтительнее `List<Student> student = ...` или `ArrayList<Student> student = ...`?
1. Что такое дженерики? Для чего они нужны?
1. Что означает `List<?>`? Стоит ли использовать эту запись?

### Java - Stream Api
1. Что такое Stream? Как создать Stream? Что он позволяет? В чем разница между Collection и Stream?
1. Какие существуют способы создания стрима?
1. Что такое Optional?
1. Для чего нужен метод collect() в стримах? Какие стандартные реализации коллекторов существуют?
1. Для чего в стримах применяются методы forEach() и forEachOrdered()?
1. Для чего в стримах предназначены методы map() и mapToInt(), mapToDouble(), mapToLong()?
1. Какова цель метода filter() в стримах?
1. Для чего в стримах предназначен метод limit()?
1. Для чего в стримах предназначен метод sorted()?
1. В чем разница между терминальными и конвейерными операциями?
1. Что будет выведено в консоль?
```java
String collect = IntStream.range(1, 4)
        .mapToObj(i -> "a" + i)
        .map(String::toUpperCase)
        .sorted(Comparator.reverseOrder())
        .collect(Collectors.joining("-"));
System.out.println(collect);
```
