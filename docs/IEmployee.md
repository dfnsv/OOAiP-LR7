## Описание интерфейса IEmployee

Интерфейс предназначен для работы с методами класса [Employee](Employee.md)

### Реализация интерфейса

Функции IEmployee:
+ +Add (Employee:[Employee](Employee.md)): string
  + Добавление в БД.
  + Employee:[Employee](Employee.md) – экземпляр класса Employee.
  + String – строка с ответом
+ +Del (Employee:[Employee](Employee.md)): string
  + Удаление из БД.
  + Employee:[Employee](Employee.md) – экземпляр класса [Employee](Employee.md).
  + String – строка с ответом
+ +Edit (Employee:[Employee](Employee.md)): string
  + Редактирование в БД.
  + Employee:[Employee](Employee.md) – экземпляр класса [Employee](Employee.md).
  + String – строка с ответом
+ +GetID (Employee:[Employee](Employee.md)): int
  + Получение ID.
  + Employee:[Employee](Employee.md) – экземпляр класса [Employee](Employee.md).
  + int – искомый id
+ +GetList (sorting : String, ASKorDESK : String, filterA : T, filterB : A, count : int, page : int): List <[Employee](Employee.md)>
  + Функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница).
  + Второй фильтр (filter B) необходим для интервала количественных атрибутов.
  + Функция возвращает список объектов.
+ +FindByID (ID : Integer): [Employee](Employee.md)
  + Поиск экземпляра класса по ID.
  + ID – идентификатор.
  + Возвращает экземпляр класса.
+ +GetEmployees(sorting : String, ASKorDESK : String, filterA : [Employee](Employee.md), filterB : [Employee](Employee.md), count : int, page : int) : List <[Employee](Employee.md)>
  + Функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница).
  + Второй фильтр (filter B) необходим для интервала количественных атрибутов.
  + Функция возвращает список сотрудников.
+ +GetClient (TimeBeg, TimeEnd): List <[Client](Client.md)>
  + Получить список клиентов для объекта
  + TimeBeg – дата начала поиска.
  + TimeEnd – дата окончания поиска
+ +GetVoyage (TimeBeg, TimeEnd): List <[Voyage](Voyage.md)>
  + Получить список рейсов для объекта
  + TimeBeg – дата начала поиска. TimeEnd – дата окончания поиска
+ +GetTransport (TimeBeg, TimeEnd): List <[Transport](Transport.md)>
  + Получить список ТС для объекта
  + TimeBeg – дата начала поиска.
  + TimeEnd – дата окончания поиска
