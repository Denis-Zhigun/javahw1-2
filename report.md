# Отчёт о тестировании Credit Card Number Validator

Дата начала тестирования - 30.12.2020 г. Дата окончания тестирования - 30.12.2020. 

Было проведено функциональное тестирование приложения "Credit Card Number Validator".

На тестирование затрачено: 2 часа

### В результате тестирования выявлены следующие дефекты:
- [Не проходят валидацию банковские карты American Express](https://github.com/Denis-Zhigun/javahw1-2/issues/1#issue-776611486)

## Описание процесса тестирования:
### В процессе тестирования использовались следующие артефакты:
- тест-кейсы для проверки функциональности валидации номеров банковских карт.

### В качестве тестовых данных использовались данные [с сайта](https://www.getcreditcardnumbers.com/):
- Карты Visa. Имеют результат - валидных данных - (https://yadi.sk/i/MhQSAGVmvTQZsQ);
- Карты Mastercard. Имеют результат - валидных данных - (https://yadi.sk/i/WVO87YUnBhVZSw);
- Карты Discover. Имеют результат - валидных данных - (https://yadi.sk/i/-n3Dl533WZ5zZg)
- Карты American Express. Невалидные - (https://github.com/Denis-Zhigun/javahw1-2/issues/1#issue-776611486)

### Тестирование производилось в следующем окружении:
- Ноутбук Lenovo (17'')
- Windows 10 x64
- IntelliJ IDEA Community Edition

