## Описание интерфейса IClient

Интерфейс предназначен для работы с методами класса [Point](Point.md)

### Реализация интерфейса

+ +Add (Point:Point): string
  + Добавление в БД
  + Point:Point – экземпляр класса Point.
  + String – строка с ответом
+ +Del (Point:Point): string
  + Удаление из БД
  + Point:Point – экземпляр класса Point.
  + String – строка с ответом
+ +Edit (Point:Point): string
  + Редактирование в БД
  + Point:Point – экземпляр класса Point.
  + String – строка с ответом
+ +GetID (Point:Point): int
  + Получение ID
  + Point:Point – экземпляр класса Point.
  + int – искомый id
+ +GetList (sorting : String, ASKorDESK : String, filterA : T, filterB : A, count : int, page : int): List <Point>
  + Функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница).
  + Второй фильтр (filter B) необходим для интервала количественных атрибутов.
  + Функция возвращает список объектов класса.
+ +FindByID (ID : Integer): Point 
  + Поиск экземпляра класса по ID.
  + ID – идентификатор.
  + Возвращает экземпляр класса.
+ +GetPoints(sorting : String, ASKorDESK : String, filterA : Point, filterB : Point, count : int, page : int) : List <Points>
  + Функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница).
  + Второй фильтр (filter B) необходим для интервала количественных атрибутов.
  + Функция возвращает список пунтов.
+ +GetVoyage (TimeBeg, TimeEnd): List: <Voyage>
  + Получить список рейсов для объекта.
  + TimeBeg – дата начала поиска.
  + TimeEnd – дата окончания поиска.
+ +GetRoute (TimeBeg, TimeEnd): List <Voyage>
  + Получить список маршрутов для объекта.
  + TimeBeg – дата начала поиска.
  + TimeEnd – дата окончания поиска.
