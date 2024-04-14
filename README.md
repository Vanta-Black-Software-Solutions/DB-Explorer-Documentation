# BD Explorer

This is a utility for dumping data from MySQL databases to CSV and SQL formats. The program is designed to handle large volumes of data and provides multithreaded processing to increase performance.

## Usage

1. Install the program through the provided Installer.
2. Edit the configuration file `config.ini` in the root of the program according to your requirements. Please note that changing the keys in the configuration (for example, `Key_1`, `Key_2`, etc.) is not recommended, since they are used by the program to read the settings.

Detailed documentation is available [here](https://docs.google.com/document/d/1UDyJc1x98Ah5bOM7qGne7AxeF78_pQqGgKSA9U7Qkes/edit?usp=sharing).

## Features

- Multithreaded data processing for optimal resource utilization.
- Support for dumping data to CSV and SQL formats.
- Configurability through a configuration file.
- Advanced logging features for tracking the progress of the operation.


## Launching the program

- Run the program after making sure that all dependencies are installed.
- The program will start checking the availability of databases as valid databases are received, their backup copy (Dump) will be made.
- The results of the program execution will be displayed in the console.
- The results of the check are recorded in 
- "C:\Users \"Username"\Documents\Dumps"


---


# BD Explorer

Это утилита для дампа данных из баз данных MySQL в формат CSV и SQL. Программа разработана для работы с большим объемом данных и обеспечивает многопоточную обработку для увеличения производительности.

## Использование

1. Установите программу через предоставленный Installer.
2. Отредактируйте файл конфигурации `config.ini` в корне программы согласно вашим требованиям. Обратите внимание, что изменять ключи в конфигурации (например, `Key_1`, `Key_2` и т.д.) не рекомендуется, так как они используются программой для чтения настроек.


Подробная документация доступна [здесь](https://docs.google.com/document/d/1UDyJc1x98Ah5bOM7qGne7AxeF78_pQqGgKSA9U7Qkes/edit?usp=sharing).

## Особенности

- Многопоточная обработка данных для оптимального использования ресурсов.
- Поддержка дампа данных в форматы CSV и SQL.
- Возможность настройки через конфигурационный файл.
- Расширенные функции логирования для отслеживания процесса работы.

## Запуск программы

- Запустите программу, предварительно убедившись, что все зависимости установлены.
- Программа начнет проверку доступности баз данных по мере поступления валидных баз будет сделана их резервная копия (Dump).
- Результаты выполнения программы будут отображены в консоли.
- Результаты проверки записываются в 
- "C:\Users\"Имя Пользователя"\Documents\Dumps"


