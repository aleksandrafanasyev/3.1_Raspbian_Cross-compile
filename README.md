Программа hello

Для кроскомпиляции программы необходимо задать в переменной CROSS_COMPILE путь к toolchain.

make CROSS_COMPILE=toolchain_path target
или
make host

Программа линкуется с параметром -rpath=. , поэтому для загрузки библиотеки libhello.so необходимо 
запуск программы hello из текущей/рабочей директори.





Программа gpio

Для кроскомпиляции программы необходимо задать в переменной CROSS_COMPILE путь к toolchain.

make CROSS_COMPILE=toolchain_path target
или
make host

Использование gpio: gpio number_gpio_led number_gpio_button

Программа пишет ошибки в syslog.
