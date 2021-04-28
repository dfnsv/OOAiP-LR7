## Описание интерфейса IClient

Интерфейс предназначен для работы с методами класса [Client](Client.md)

### Реализация интерфейса

+ Add (Client:Client): string – добавление в БД
Входные данные:
Client:Client – экземпляр класса Client.
Выходные данные:
String – строка с ответом
+ Del (Client:Client): string – удаление из БД
Входные данные:
Client:Client – экземпляр класса Client.
Выходные данные:
String – строка с ответом
+ Edit (Client:Client): string – Редактирование в БД
Входные данные:
Client:Client – экземпляр класса Client.
Выходные данные:
String – строка с ответом
+ GetID (Client:Client): int – Получение ID
Входные данные:
Client:Client – экземпляр класса Client.
Выходные данные:
int – искомый id
+ GetList (sorting : String, ASKorDESK : String, filterA : T, filterB : A, count : int, page : int): List <Client> – функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница). Второй фильтр (filter B) необходим для интервала количественных атрибутов. Функция возвращает список объектов класса.
+ FindByID (ID : Integer): Client – поиск экземпляра класса по ID. ID – идентификатор. Возвращает экземпляр класса.
+ GetClients(sorting : String, ASKorDESK : String, filterA : Client, filterB : Client, count : int, page : int) : List <Clients> - функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница). Второй фильтр (filter B) необходим для интервала количественных атрибутов. Функция возвращает список клиентов.
+ GetEmployee (TimeBeg, TimeEnd): List <Employee> -  получить список сотрудников для объекта
TimeBeg – дата начала поиска.
TimeEnd – дата окончания поиска
+GetBranch (TimeBeg, TimeEnd): List <Branch> -  получить список филиалов для объекта
TimeBeg – дата начала поиска.
TimeEnd – дата окончания поиска
