В Java SDK есть класс `java.lang.ThreadLocal`. Класс очень удобный и довольно распространенный – сложно представить себе более-менее крупный Java-проект, в котором не используется `ThreadLocal`.


Если на минуту представить себе что в SDK "забыли" добавить такой удобный класс, то встает вопрос – а можно ли его реализовать самостоятельно, не имея доступа к закрытым частям SDK и native-методам?


В этом тестовом задании я предлагаю вам попробовать сделать именно это – реализовать свой собственный аналог класса ThreadLocal с тремя базовыми методами – `get`, `set` и `remove`. При реализации задания хорошо бы учесть возможные concurrency-проблемы и то, что потоки в JVM могут умирать "без предупреждения".


Немного деталей:
- По всем вопросам смело писать на join@ecwid.com
- Использовать можно только возможности стандартной библиотеки Java/Kotlin
- Писать нужно на Java (версия 11 и выше) или Kotlin.
- Сделанное задание необходимо разместить на GitHub
