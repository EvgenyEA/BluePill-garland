# BluePill-garland
Ёлочная гирлянда на STM32 BluePill

![Подключение BluePill](https://github.com/EvgenyEA/ExactTime/blob/main/BluePill_connection.png)
 
## Подключение гирлянды
Зашейте в STM32F103 BluePill файл STM32F103_BluPill_bootloader.bin. Прошивка включает DFU загрзучик USB и программу для управления адресными светодиодами. После подключения к ПК через USB плата определится как виртуальный COM-порт. Запустите на ПК терминал blue_pill_terminal.exe, подключителсь к порту. 

![Подключение BluePill](https://github.com/EvgenyEA/ExactTime/blob/main/BluePill_terminal.jpg)

Подключите к выходу PA0 гирлянду на адресных светодиодах или светодиодную матрицу и управляйте ею при помощи терминала. 