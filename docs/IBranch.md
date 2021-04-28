## Описание интерфейса IClient

Интерфейс предназначен для работы с методами класса [Client](Client.md)

### Реализация интерфейса

+ Add (Branch:Branch): string – добавление в БД
Входные данные:
Branch:Branch – экземпляр классa Branch.
Выходные данные:
String – строка с ответом
+ Del (Branch:Branch): string – удаление из БД
Входные данные:
Branch:Branch – экземпляр классa Branch.
Выходные данные:
String – строка с ответом
+ Edit (Branch:Branch): string – Редактирование в БД
Входные данные:
Branch:Branch – экземпляр классa Branch.
Выходные данные:
String – строка с ответом
+ GetID (Branch:Branch): int – Получение ID
Входные данные:
Branch:Branch – экземпляр классa Branch.
Выходные данные:
int – искомый id
+ GetList (sorting : String, ASKorDESK : String, filterA : T, filterB : A, count : int, page : int): List <Branch> – функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница). Второй фильтр (filter B) необходим для интервала количественных атрибутов. Функция возвращает список объектов класса.
+ FindByID (ID : Integer): Branch – поиск экземпляра класса по ID. ID – идентификатор. Возвращает экземпляр класса.
+ GetBranches (sorting : String, ASKorDESK : String, filterA : Branch, filterB : Branch, count : int, page : int) : List <Branches> - функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница). Второй фильтр (filter B) необходим для интервала количественных атрибутов. Функция возвращает список филиалов.
+ GetEmployee (TimeBeg, TimeEnd): List <Employee> -  получить список сотрудников для объекта
TimeBeg – дата начала поиска.
TimeEnd – дата окончания поиска
+ GetContract (TimeBeg, TimeEnd): List <Contract> -  получить список договоров для объекта
TimeBeg – дата начала поиска.
TimeEnd – дата окончания поиска
+ GetClient (TimeBeg, TimeEnd): List <Client> -  получить список клиентов для объекта
TimeBeg – дата начала поиска.
TimeEnd – дата окончания поиска
+ GetTransport (TimeBeg, TimeEnd): List <Transport> - получить список ТС для объекта
TimeBeg – дата начала поиска.
TimeEnd – дата окончания поиска
