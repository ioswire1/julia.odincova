# julia.odincova

Воспользовавшись https://restcountries.eu API, создать приложение для iPhone устройства, с минимальной версией iOS 8.0.

Приложение должно отображать список стран мира в табличном виде, с помощью запроса к АПИ и последующим преобразованием ответ от сервиса в понятный для пользователя вид. Ячейки в таблице есть ничто иное как запись о стране, по тапу на конкретной стране, отображать лист городов(файл со списком городов), в алфавитном порядке с дополнительной информацией о популяции(если есть такие данные) для каждого отдельного города.
По тапу на конкретный город (если указаны широта и долгота), показать карту (MKMapView) в позиции этого города. Карта не должна реагировать на пользовательское взаимодействие, только отображать подходящую позицию.

Дополнительное задание: Изучить framework MapKit.
