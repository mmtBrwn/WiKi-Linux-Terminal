# Wiki systemd [OPTIONS...]

Запускает и контролирует системные и пользовательские службы.

Эта программа не принимает позиционных аргументов.

Параметры:
  -h --help Показать справку
     --version Показать версию
     --test Определить начальную транзакцию, сбросить ее и выйти.
     --system В сочетании с --test: работать в системном режиме
     --user Комбинируется с --test: работать в пользовательском режиме
     --dump-configuration-items Дамп элементов конфигурации понимаемого устройства
     --dump-bus-properties Дамп свойств открытой шины
     --bus-introspect=PATH Записать данные интроспекции в формате XML
     --unit=UNIT Установить единицу по умолчанию
     --dump-core[=BOOL] Выгрузка ядра при падении
     --crash-vt=NR Переход на указанный VT при сбое
     --crash-reboot[=BOOL] Перезагрузка при крахе
     --crash-shell[=BOOL] Запуск оболочки при крахе
     --confirm-spawn[=BOOL] Запрашивать подтверждение при порождении процессов
     --show-status[=BOOL] Показывать обновления статуса на консоли во время загрузки
     --log-target=TARGET Установить цель журнала (консоль, журнал, kmsg,
                                                 journal-or-kmsg, null)
     --log-level=LEVEL Установить уровень журнала (debug, info, notice, warning,
                                                err, crit, alert, emerg)
     --log-color[=BOOL] Выделять важные сообщения журнала
     --log-location[=BOOL] Включать местоположение кода в сообщения журнала
     --log-time[=BOOL] Префикс сообщений журнала с текущим временем
     --default-standard-output= Установить стандартный вывод по умолчанию для сервисов
     --default-standard-error= Установить стандартный вывод ошибок по умолчанию для сервисов
     --no-pager Не передавать вывод в пейджер.

Подробности см. на странице руководства systemd(1).

