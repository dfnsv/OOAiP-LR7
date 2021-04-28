## Описание интерфейса IVoyage

Интерфейс предназначен для работы с методами класса [Voyage](Voyage.md)

### Реализация интерфейса

+ +Add (Voyage:[Voyage](Voyage.md)): string
  + добавление в БД.
  + Voyage:[Voyage](Voyage.md) – экземпляр класса [Voyage](Voyage.md)
  + String – строка с ответом
+ +Del (Voyage:[Voyage](Voyage.md)): string
  + удаление из БД
  + Voyage:[Voyage](Voyage.md) – экземпляр класса [Voyage](Voyage.md)
  + String – строка с ответом
+ +Edit (Voyage:[Voyage](Voyage.md)): string
  + Редактирование в БД
  + Voyage:[Voyage](Voyage.md) – экземпляр класса [Voyage](Voyage.md)
  + String – строка с ответом
+ +GetID (Voyage:[Voyage](Voyage.md)): int
  + Получение ID
  + Voyage:[Voyage](Voyage.md) – экземпляр класса [Voyage](Voyage.md)
  + int – искомый id
+ +GetList (sorting : String, ASKorDESK : String, filterA : T, filterB : A, count : int, page : int): List <[Voyage](Voyage.md)>
  + функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница).
  + Второй фильтр (filter B) необходим для интервала количественных атрибутов.
  + Функция возвращает список объектов класса
+ +FindByID (ID : Integer): [Voyage](Voyage.md)
  + поиск экземпляра класса по ID.
  + ID – идентификатор.
  + Возвращает экземпляр класса.
+ +GetVoyages(sorting : String, ASKorDESK : String, filterA : [Voyage](Voyage.md), filterB : [Voyage](Voyage.md), count : int, page : int) : List <[Voyage](Voyage.md)>
  + функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница).
  + Второй фильтр (filter B) необходим для интервала количественных атрибутов.
  + Функция возвращает список рейсы.
+ +GetContract (TimeBeg, TimeEnd): List <[Contract](Contract.md)>
  + получить список договоров для объекта
  + TimeBeg – дата начала поиска.
  + TimeEnd – дата окончания поиска
