#### *Route* (маршрут)
+ Класс-наследник Entity. Описывает маршрут.
+ Атрибуты:
	* Points: List <Point> - лист пунктов
+ Функции:
	* +Route () – конструктор класса
	* +Route (ID) – получить экземпляр из БД по ID
	* +GetVoyage (TimeBeg, TimeEnd): List <Voyage> -  получить список рейсов для объекта
	* +GetTransport (TimeBeg, TimeEnd): List <Transport> -  получить список ТС для объекта
