# pulse-counter-AVR
8 MHz pulse counter on AVR microcontrollers
Счетчик импульсов на микроконтроллере AVR (в примерах использовались atmega328p и attiny88) позволит считать импульсы с частотой до половины частоты контроллера.
Счетчик использует внутренние таймеры контроллера: 

Принцип:
  Таймеры настраиваются таким образом чтобы использовать импульсы которые необходимо считать в качестве источка тактирования и выдают количество тактов.

В коде показаны варианты настройки напрямую через регистры, а также с помощью библиотеки DirectTimers (библиотека работает не со всеми контроллерами).
