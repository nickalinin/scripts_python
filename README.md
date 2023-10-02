# geocoding
Cкрипт геокодирования по адресам c использованием библиотеки selenium и карты YandexMap.

### Модули
- [Selenium, version 4.9.0](https://www.selenium.dev/)
- [Pandas, version 1.4.4](https://pandas.pydata.org/)
- Re, version 2.2.1

### Использование
Файл **data.xlsx** со столбцом адресов (_Adress_) добавляется в директорию скрипта.
Получаем файл **geo_data.xlsx** со столбцами _Adress_, _geo_.
Значение __NaN__ в столбце _geo_ - означает, что адрес не загеокодился (некорректный адрес).





