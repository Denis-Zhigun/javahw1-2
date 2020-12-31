# Отчёт о тестировании Credit Card Number Validator

Дата начала тестирования - 30.12.2020 г. Дата окончания тестирования - 30.12.2020. 

Было проведено функциональное тестирование приложения "Credit Card Number Validator".

На тестирование затрачено: 2 часа

### В результате тестирования выявлены следующие дефекты:
- [Не проходят валидацию банковские карты American Express](https://github.com/Denis-Zhigun/javahw1-2/issues/1#issue-776611486)
- [Ошибка при валидации банковских карт](https://github.com/Denis-Zhigun/javahw1-2/issues/2#issue-777060904)

## Описание процесса тестирования:
### В процессе тестирования использовались следующие артефакты:
- тест-кейсы для проверки функциональности валидации номеров банковских карт.

### В качестве тестовых данных использовались данные с сайтов (https://www.getcreditcardnumbers.com/ и https://www.freeformatter.com/credit-card-number-generator-validator.html):
- Карты Visa. Имеют результат - валидных данных - (https://yadi.sk/i/MhQSAGVmvTQZsQ, https://yadi.sk/i/Vwc-Fp864bZSHw, https://yadi.sk/i/Wh-y2smjyC6QDA);
- Карты Mastercard. Имеют результат - валидных данных - (https://yadi.sk/i/WVO87YUnBhVZSw, https://yadi.sk/i/Up3nm94FpIW5cw, https://yadi.sk/i/4EKO1qanBDCC2g);
- Карты Discover. Имеют результат - валидных данных - (https://yadi.sk/i/-n3Dl533WZ5zZg, https://yadi.sk/i/JrtD2fEHEPl4gw, https://yadi.sk/i/hOwJd8YXSjzjfw);
- Карты Maestro. Имеют результат - валидных данных (https://yadi.sk/i/mvLg5dzGzWe4Mw, https://yadi.sk/i/eW_M_UIV2fBj2w, https://yadi.sk/i/4u41ehH8-_TWmw)
- Карты American Express. Невалидные - (https://github.com/Denis-Zhigun/javahw1-2/issues/1#issue-776611486)
- Карты Diners Club - Carte Blanche. Невалидные - (https://github.com/Denis-Zhigun/javahw1-2/issues/2#issue-777060904)

### Тестирование производилось в следующем окружении:
- Ноутбук Lenovo (17'')
- Windows 10 x64
- IntelliJ IDEA Community Edition

