# Home-Assistant-and-Mercury230
Home Assistant, ESPhome  и  счетчик Меркурий 230 AR-01

- Очень советую использовать аппаратный UART.
- Драйвер RS485 без ноги направления передачи, с защитными диодами и предохранителями (только так).
- Счетчику требуется подача пятивольтового питания из вне.
- Счетчик должен иметь пароль по умолчанию (111111).
- Адрес счетчика не нужен, устройство найдет его само. По этой причине счетчик на шине RS485 должен быть один.
- Не совмещайте этот компонент с другими в одном устройстве, скорее всего будут глюки.
