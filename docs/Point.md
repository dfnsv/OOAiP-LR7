#### *Point* (пункт)
+ Класс-наследник Entity. Описывает пункт.
+ Атрибуты:
	* Address: string – адрес
	* TimeOfDeparture: DateTime – время прибытия в пункт
	* TimeOfArrival: DateTime – время отправления из пункта
+ Функции:
	* +GetVoyage (TimeBeg, TimeEnd): List: <Voyage> -  получить список рейсов для объекта
	* +GetRoute (TimeBeg, TimeEnd): List <Voyage> - получить список маршрутов для объекта
