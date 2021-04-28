#### *Transport* (ТС)
+ Класс-наследник Entity. Описывает ТС.
+ Атрибуты:
	* Model: string – модель
+ Функции:
	* +Transport () – конструтор класса
	* +Transport (ID) – получить экземпляр из БД по ID
	* +GetBranch (TimeBeg, TimeEnd): List <Branch> -  получить список филиалов для объекта
	* +GetVoyage (TimeBeg, TimeEnd): List <Voyage> -  получить список рейсов для объекта
	* +GetRoute (TimeBeg, TimeEnd): List <Route> -  получить список маршрутов для объекта
	* +GetEmployee (TimeBeg, TimeEnd): List <Employee> -  получить список работники для объекта
