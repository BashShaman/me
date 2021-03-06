# Как организована компьютерная сеть?

Компьютерная сеть может быть представлена как набор уровней один над другим. Каждый уровень решает одну задачу или набор связанных задач. С понятием уровень связаны понятия **сервис**, **интерфейс** и **протокол**. 

**Сервис** - это то, что делает уровень (набор функций).

**Интерфейс** - это набор примитивных операций, предоставляемых нижестоящим уровнем вышестоящему. В рамках уровня возможно внесение любых изменений при условии неизменности интерфейса. 

**Протокол** - это правила общения устройств на одном уровне. Узлы одного уровня (за исключением физического) не связаны друг с другом, для их общения используются заголовки ([подробнее][1]). При изменении протокола изменяется лишь "язык общения" устройств на заданном уровне и ничего более.

**Архитектура сети** - это набор уровней и протоколов сети, но не интерфейсов.

**Стек протоколов** - набор протоколов, выстроенный в иерархию, достаточный для организации общения устройств в сети.

## Модели организации сети

* OSI
  *  юридический стандарт
  *  состоих из 7 уровней
  *  не содержит протоколы
  *  не используется на практике

* TCP/IP
  * фактический стандарт
  * стостоит из 4 уровней
  * содержит протоколы
  * состовляет основу Internet  

[1]: <zet/20220517094951/README.md>

        #networks #osi #tcp/ip #service #interface #protocol
