## Описание интерфейса IBranch

Интерфейс предназначен для работы с методами класса [Branch](Branch.md)

### Реализация интерфейса

+ +Add (Branch:[Branch](Branch.md)): string 
  + добавление в БД
  + Branch:[Branch](Branch.md) – экземпляр классa [Branch](Branch.md).
  + String – строка с ответом
+ +Del (Branch:[Branch](Branch.md)): string
  + удаление из БД
  + Branch:[Branch](Branch.md) – экземпляр классa [Branch](Branch.md)
  + String – строка с ответом
+ +Edit (Branch:[Branch](Branch.md)): string
  + Редактирование в БД
  + Branch:[Branch](Branch.md) – экземпляр классa [Branch](Branch.md)
  + String – строка с ответом
+ GetID (Branch:[Branch](Branch.md)): int
  + Получение ID
  + Branch:[Branch](Branch.md) – экземпляр классa [Branch](Branch.md)
  + int – искомый id
+ +GetList (sorting : String, ASKorDESK : String, filterA : T, filterB : A, count : int, page : int): List <[Branch](Branch.md)>
  + функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница).
  + Второй фильтр (filter B) необходим для интервала количественных атрибутов.
  + Функция возвращает список объектов класса.
+ +FindByID (ID : Integer): [Branch](Branch.md)
  + поиск экземпляра класса по ID.
  + ID – идентификатор.
  + Возвращает экземпляр класса.
+ +GetBranches (sorting : String, ASKorDESK : String, filterA : [Branch](Branch.md), filterB : [Branch](Branch.md), count : int, page : int) : List <[Branch](Branch.md)>
  + функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница).
  + Второй фильтр (filter B) необходим для интервала количественных атрибутов.
  + Функция возвращает список филиалов.
+ +GetEmployee (TimeBeg, TimeEnd): List <[Employee](Employee.md)>
  + получить список сотрудников для объекта
  + TimeBeg – дата начала поиска.
  + TimeEnd – дата окончания поиска
+ +GetContract (TimeBeg, TimeEnd): List <[Contract](Contract.md)>
  + получить список договоров для объекта
  + TimeBeg – дата начала поиска.
  + TimeEnd – дата окончания поиска
+ +GetClient (TimeBeg, TimeEnd): List <[Client](Client.md)>
  + получить список клиентов для объекта
  + TimeBeg – дата начала поиска.
  + TimeEnd – дата окончания поиска
+ +GetTransport (TimeBeg, TimeEnd): List <[Transport](Transport.md)>
  + получить список ТС для объекта
  + TimeBeg – дата начала поиска.
  + TimeEnd – дата окончания поиска
