## Описание интерфейса IRoute

Интерфейс предназначен для работы с методами класса [Route](Route.md)

### Реализация интерфейса

+ +Add (Route:[Route](Route.md)): string
  + Добавление в БД. 
  + Route:[Route](Route.md) – экземпляр класса [Route](Route.md)
  + String – строка с ответом
+ +Del (Route:[Route](Route.md)): string 
  + Удаление из БД. 
  + Route:[Route](Route.md) – экземпляр класса [Route](Route.md)
  + String – строка с ответом
+ +Edit (Route:[Route](Route.md)): string
  + Редактирование в БД
  + Route:[Route](Route.md) – экземпляр класса [Route](Route.md)
  + String – строка с ответом
+ +GetID (Route:[Route](Route.md)): int
  + Получение ID
  + Route:[Route](Route.md) – экземпляр класса [Route](Route.md)
  + int – искомый id
+ +GetList (sorting : String, ASKorDESK : String, filterA : T, filterB : A, count : int, page : int): List <[Route](Route.md)>
  + Функция с входными параметрами «sorting»(сортировка), «ASKofDESK»(по возрастанию или по убыванию), «filterA», «filterB»(фильтр), «count»(количество), «page»(страница).
  + Второй фильтр (filter B) необходим для интервала количественных атрибутов.
  + Функция возвращает список объектов класса.
+ +FindByID (ID : Integer): [Route](Route.md)
  + поиск экземпляра класса по ID.
  + ID – идентификатор. 
  + Возвращает экземпляр класса.
