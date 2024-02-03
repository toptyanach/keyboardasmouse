# keyboardasmouse
Keyboard As Mouse Driver for Windows10/11 

KeyboardAsMouseDriver/
│
├── src/                        # Исходный код драйвера
│   ├── DriverEntry.cpp         # Точка входа драйвера
│   ├── DeviceAdd.cpp           # Обработчик добавления устройства
│   ├── QueueCallbacks.cpp      # Callbacks для обработки событий клавиатуры
│   └── Utilities.cpp           # Вспомогательные функции для обработки событий
│
├── include/                    # Заголовочные файлы
│   ├── DriverEntry.h
│   ├── DeviceAdd.h
│   ├── QueueCallbacks.h
│   └── Utilities.h
│
├── inf/                        # Каталог для файла установки драйвера
│   └── KeyboardAsMouseDriver.inf   # Файл установки драйвера
│
├── WDKBuildSettings.props      # Настройки сборки WDK
│
└── README.md                   # Документация проекта
