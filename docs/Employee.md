#### *Employee* (сотрудник)
+ Класс-наследник Person. Описывает сотрудника.
+ Атрибуты:
	* Position: string - должность
	* Login: string - логин
	* Password: string - пароль
	* Branch: Branch - филиал
	* Salary: float - зарплата
+ Функции:
	* +Employee () – конструктор класса
	* +Employee (ID) – получить экземпляр из БД по ID
	* +GetClient (TimeBeg, TimeEnd): List <Client>  -  получить список клиентов для объекта
	* +GetVoyage (TimeBeg, TimeEnd): List <Voyage> -  получить список рейсов для объекта
	* +GetTransport (TimeBeg, TimeEnd): List <Transport> -  получить список ТС для объекта
