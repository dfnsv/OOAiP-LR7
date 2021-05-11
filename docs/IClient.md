## Описание интерфейса IClient

Интерфейс предназначен для работы с методами класса [Client](Client.md)

### Реализация интерфейса

+ +Add (Client:[Client](Client.md)): string
  + добавление в БД
  + Client:[Client](Client.md) – экземпляр класса [Client](Client.md).
  + String – строка с ответом
+ +Del (Client:[Client](Client.md)): string
  + удаление из БД
  + Client:[Client](Client.md) – экземпляр класса [Client](Client.md).
  + String – строка с ответом
+ +Edit (Client:[Client](Client.md)): string
  + Редактирование в БД
  + Client:[Client](Client.md) – экземпляр класса [Client](Client.md).
  + String – строка с ответом
+ +GetID (Client:[Client](Client.md)): int
  + Получение ID
  + Client:[Client](Client.md) – экземпляр класса [Client](Client.md).
  + int – искомый id
+ +GetList (sorting : String, ASKorDESK : String, filterA : T, filterB : A, count : int, page : int): List <[Client](Client.md)>
  + функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница).
  + Второй фильтр (filter B) необходим для интервала количественных атрибутов.
  + Функция возвращает список объектов класса.
+ +FindByID (ID : Integer): [Client](Client.md)
  + поиск экземпляра класса по ID.
  + ID – идентификатор.
  + Возвращает экземпляр класса.
