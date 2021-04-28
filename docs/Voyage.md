#### *Voyage* (рейс)
+ Класс-наследник Entity. Описывает рейс.
+ Атрибуты:
	* TimeOfPoints: List <Point> - лист пунктов со временем прибытия в пункт и отправления из него
	* Status: string – статутс (getting ready, en route, arrived)
	* Transport: Transport - транспорт
	* Employee: Employee - работник
	* Route: Route - маршрут
+ Функции:
	* +Voyage () – конструктор класса
	* +Voyage (ID) – получить экземпляр из БД по ID
	* +GetContract (TimeBeg, TimeEnd): List <Contract> -  получить список договоров для объекта
