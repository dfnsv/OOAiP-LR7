## Описание интерфейса ITransport

Интерфейс предназначен для работы с методами класса [Transport](Transport.md)

### Реализация интерфейса

+ +Add (Transport:[Transport](Transport.md)): string
  + добавление в БД
  + Transport:[Transport](Transport.md) – экземпляр класса [Transport](Transport.md)
  + String – строка с ответом
+ +Del (Transport:[Transport](Transport.md)): string
  + удаление из БД
  + Transport:[Transport](Transport.md) – экземпляр класса [Transport](Transport.md)
  + String – строка с ответом
+ +Edit (Transport:[Transport](Transport.md)): string
  + Редактирование в БД
  + Transport:[Transport](Transport.md) – экземпляр класса [Transport](Transport.md)
  + String – строка с ответом
+ +GetID (Transport:[Transport](Transport.md)): int
  + Получение ID
  + Transport:[Transport](Transport.md) – экземпляр класса [Transport](Transport.md)
  + int – искомый id 
+ +GetList (sorting : String, ASKorDESK : String, filterA : T, filterB : A, count : int, page : int): List <[Transport](Transport.md)>
  + функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница).
  + Второй фильтр (filter B) необходим для интервала количественных атрибутов.
  + Функция возвращает список объектов класса.
+ +FindByID (ID : Integer): [Transport](Transport.md)
  + поиск экземпляра класса по ID.
  + ID – идентификатор.
  + Возвращает экземпляр класса.
+ +GetTransports(sorting : String, ASKorDESK : String, filterA : [Transport](Transport.md), filterB : [Transport](Transport.md), count : int, page : int) : List <[Transport](Transport.md)>
  + функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница).
  + Второй фильтр (filter B) необходим для интервала количественных атрибутов.
  + Функция возвращает список ТС.
+ +GetBranch (TimeBeg, TimeEnd): List <[Branch](Branch.md)>
  + получить список филиалов для объекта
  + TimeBeg – дата начала поиска.
  + TimeEnd – дата окончания поиска.
+ +GetVoyage (TimeBeg, TimeEnd): List <[Voyage](Voyage.md)>
  + получить список рейсов для объекта
  + TimeBeg – дата начала поиска.
  + TimeEnd – дата окончания поиска.
+ +GetRoute (TimeBeg, TimeEnd): List <[Route](Route.md)>
  + получить список маршрутов для объекта
  + TimeBeg – дата начала поиска.
  + TimeEnd – дата окончания поиска.
+ +GetEmployee (TimeBeg, TimeEnd): List <[Employee](Employee.md)>
  + получить список работники для объекта.
  + TimeBeg – дата начала поиска.
  + TimeEnd – дата окончания поиска.
