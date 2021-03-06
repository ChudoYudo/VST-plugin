# Результаты тестирования

| №| Название | Прохождение | Предполагаемый результат | Фактический результат | Оценка|
|---|---|---|---|---|---|
| 1 | Получение звуковой дорожки | 1. Включение программы-обработчика звука.  2. Внесение плагина в список плагинов данной программы.  3. Включение звуковой дорожки для обработки. 4. Подключение данного плагина для обработки звуковой дорожки. | Плагин получает доступ к звуковой дорожке и готов для ее обработки. | Плагин получил доступ к звуковой дорожке | 9 |  
|2|Преобразование звуковой дорожки|1. Проверка того, что плагин подключен к проекту с нужной звуковой дорожкой. 2. Изменение положения ползунка, который отвечает в программе за эффект плагина (адаптивный интерфейс). 3. Получение преобразованной звуковой дорожки.|Получение преобразованной звуковой дорожки|Получение преобразованной звуковой дорожки|9|  
|3|Вывод преобразованной звуковой дорожки|1. Предварительное преобразование звуковой дорожки. 2. Обращение к внешней программе-обработчику для получения преобразованной плагином звуковой дорожки. 3. Получение звуковой дорожки на устройство вывода.|Получение звуковой дорожки без задержки во времени|Получение звуковой дорожки с задержкой в 1с|7|  
|4|Взаимодействие с различными программами по обработке звука|Протестировать работу плагина на нескольких программах для обработки звуковых дорожек. В данном случае использовались REAPER и FL Studio|Плагин работает|Плагин работает|9|

# Вывод:
Функциональная полнота - 100%.  
Функциональная корректность - 83%.  
Временная характеристика - 70%.  
Понятность - 100%

По итогам тестирования ясно, что приложение обладает полной функциональностью, заявленной на этапе проектирования. Все заявленные эксплуатационные требования выполнены.
