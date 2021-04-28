## Описание интерфейса IPount

Интерфейс предназначен для работы с методами класса [Point](Point.md)

### Реализация интерфейса

+ +Add (Point:[Point](Point.md)): string
  + Добавление в БД
  + Point:[Point](Point.md) – экземпляр класса [Point](Point.md).
  + String – строка с ответом
+ +Del (Point:[Point](Point.md)): string
  + Удаление из БД
  + Point:[Point](Point.md) – экземпляр класса [Point](Point.md).
  + String – строка с ответом
+ +Edit (Point:[Point](Point.md)): string
  + Редактирование в БД
  + Point:[Point](Point.md) – экземпляр класса [Point](Point.md).
  + String – строка с ответом
+ +GetID (Point:[Point](Point.md)): int
  + Получение ID
  + Point:[Point](Point.md) – экземпляр класса [Point](Point.md).
  + int – искомый id
+ +GetList (sorting : String, ASKorDESK : String, filterA : T, filterB : A, count : int, page : int): List <[Point](Point.md)>
  + Функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница).
  + Второй фильтр (filter B) необходим для интервала количественных атрибутов.
  + Функция возвращает список объектов класса.
+ +FindByID (ID : Integer): [Point](Point.md) 
  + Поиск экземпляра класса по ID.
  + ID – идентификатор.
  + Возвращает экземпляр класса.
+ +GetPoints(sorting : String, ASKorDESK : String, filterA : Point, filterB : Point, count : int, page : int) : List <[Point](Point.md)>
  + Функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница).
  + Второй фильтр (filter B) необходим для интервала количественных атрибутов.
  + Функция возвращает список пунтов.
+ +GetVoyage (TimeBeg, TimeEnd): List: <[Voyage](Voyage.md)>
  + Получить список рейсов для объекта.
  + TimeBeg – дата начала поиска.
  + TimeEnd – дата окончания поиска.
+ +GetRoute (TimeBeg, TimeEnd): List <[Route](Route.md)>
  + Получить список маршрутов для объекта.
  + TimeBeg – дата начала поиска.
  + TimeEnd – дата окончания поиска.
