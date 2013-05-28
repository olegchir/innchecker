innchecker
==========

Проверка контрольной суммы ИНН для России с помощью Java

Имеет смысл посмотреть класс InnChecker и его статический метод checkInn

Проверить работу можно чем-нибудь вроде такого:
        System.out.println(InnChecker.checkInn("772772262840"));
        System.out.println(InnChecker.checkInn("5036032527"));

В нагрузку идет пакет com.olegchir.utils.innchecker и модуль для IntelliJ IDEA 12.1.3

Распространяется под лицензией Apache 2.0 (http://www.apache.org/licenses/LICENSE-2.0.html), т.е. можно использовать в коммерческих проектах