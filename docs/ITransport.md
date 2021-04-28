## Описание интерфейса IClient

Интерфейс предназначен для работы с методами класса [Client](Client.md)

### Реализация интерфейса

+ Add (Transport:Transport): string – добавление в БД
Входные данные:
Transport:Transport – экземпляр класса Transport.
Выходные данные:
String – строка с ответом
+ Del (Transport:Transport): string – удаление из БД
Входные данные:
Transport:Transport – экземпляр класса Transport.
Выходные данные:
String – строка с ответом
+ Edit (Transport:Transport): string – Редактирование в БД
Входные данные:
Transport:Transport – экземпляр класса Transport.
Выходные данные:
String – строка с ответом
+ GetID (Transport:Transport): int – Получение ID
Входные данные:
Transport:Transport – экземпляр класса Transport.
Выходные данные:
int – искомый id 
+ GetList (sorting : String, ASKorDESK : String, filterA : T, filterB : A, count : int, page : int): List <Transport> – функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница). Второй фильтр (filter B) необходим для интервала количественных атрибутов. Функция возвращает список объектов класса.
+ FindByID (ID : Integer): Transport – поиск экземпляра класса по ID. ID – идентификатор. Возвращает экземпляр класса.
+ GetTransports(sorting : String, ASKorDESK : String, filterA : Transport, filterB : Transport, count : int, page : int) : List <Transports> - функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница). Второй фильтр (filter B) необходим для интервала количественных атрибутов. Функция возвращает список ТС.
+ GetBranch (TimeBeg, TimeEnd): List <Branch> -  получить список филиалов для объекта
TimeBeg – дата начала поиска.
TimeEnd – дата окончания поиска.
+ GetVoyage (TimeBeg, TimeEnd): List <Voyage> -  получить список рейсов для объекта
TimeBeg – дата начала поиска.
TimeEnd – дата окончания поиска.
+ GetRoute (TimeBeg, TimeEnd): List <Route> -  получить список маршрутов для объекта TimeBeg – дата начала поиска.
TimeEnd – дата окончания поиска.
+ GetEmployee (TimeBeg, TimeEnd): List <Employee> -  получить список работники для объекта.
TimeBeg – дата начала поиска.
TimeEnd – дата окончания поиска.
