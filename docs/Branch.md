#### *Branch* (филиал)
+ Класс-наследник Entity. Описывает филиал.
+ Атрибуты:
	* Address: string – адрес 
+ Функции:
	* +Branch () – конструктор класса
	* +Branch (ID) – получить экзепляр из БД по ID
	* +CargoReadyToDelivery (TimeBeg, TimeEnd): List <Contract> -  получить список готовых к отправке грузов для объекта
	* +GetEmployee (TimeBeg, TimeEnd): List <Employee> -  получить список сотрудников для объекта
	* +GetContract (TimeBeg, TimeEnd): List <Contract> -  получить список договоров для объекта
	* +GetClient (TimeBeg, TimeEnd): List <Client> -  получить список клиентов для объекта
	* +GetTransport (TimeBeg, TimeEnd): List <Transport> -  получить список ТС для объекта
