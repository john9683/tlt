Пример изолированного рабочего кода июля 2024 года 

## Анкета результатов проведения ТЛТ (тромболитическая терапия), разработанная по заданию заказчика 

### Основные функции 
1. Выбор периода для ввода и редактирования данных
2. Ввод данных измерений по периодам
3. Визуализация (выделение цветом) периодов с заполненными данными
4. Визуализация (выделение цветом) периодов с данными, не заполненными полностью
5. Визуализация (выделение цветом бордера инпута) не заполненных данных
6. Вывод данных для просмотра
7. Функция (директория functions), которая выводит данные анкеты на печать в часть системы, работающей на PHP5 (легаси)

Примечания:
1. Вид таблицы продиктован возможностями DomPDF корректно генерировать PDF из переданной разметки (из документа, созданного функцией в п.7 генерируется PDF)
2. Директория functions существует в старой части проекта, которая изолирована от части проекта на Symfony, поэтому нет возможности не повторяться



