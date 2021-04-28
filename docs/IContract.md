## Описание интерфейса IContract

Интерфейс предназначен для работы с методами класса [Contract](Contract.md)

### Функции IContract:
+ +Add (Contract:[Contract](Contract.md)): string
  + Добавление в БД
  + Contract:[Contract](Contract.md) – экземпляр класса [Contract](Contract.md).
  + String – строка с ответом.
+ +Del (Contract:[Contract](Contract.md)): string
  + Удаление из БД
  + Contract:[Contract](Contract.md) – экземпляр класса [Contract](Contract.md).
  + String – строка с ответом
+ +Edit (Contract:[Contract](Contract.md)): string
  + Редактирование в БД
  + Contract:[Contract](Contract.md) – экземпляр класса [Contract](Contract.md).
  + String – строка с ответом
+ +GetID (Contract:[Contract](Contract.md)): int
  + Получение ID
  + Contract:[Contract](Contract.md) – экземпляр класса [Contract](Contract.md).
  + int – искомый id
+ +GetList (sorting : String, ASKorDESK : String, filterA : T, filterB : A, count : int, page : int): List <[Contracts](Contract.md)>
  + функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница).
  + Второй фильтр (filter B) необходим для интервала количественных атрибутов.
  + Функция возвращает список объектов.
+ +FindByID (ID : Integer): [Contract](Contract.md)
  + Поиск экземпляра класса по ID.
  + ID – идентификатор.
  + Возвращает экземпляр класса.
+ +GetContracts(sorting : String, ASKorDESK : String, filterA : Contract, filterB : Contract, count : int, page : int) : List <[Contracts](Contract.md)>
  + функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница).
  + Второй фильтр (filter B) необходим для интервала количественных атрибутов.
  + Функция возвращает список договоров.
