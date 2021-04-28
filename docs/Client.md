#### *Client* (клиент)
+ Класс-наследник Person. Описывает клиента.
+ Атрибуты:
	* Debts : string - долги
+ Функции:
	* +Client () – конструктор класса
	* +Client (ID) – получить экземпляр из БД по ID
	* +GetEmployee (TimeBeg, TimeEnd): List <Employee> -  получить список сотрудников для объекта
	* +GetBranch (TimeBeg, TimeEnd): List <Branch> -  получить список филиалов для объекта
