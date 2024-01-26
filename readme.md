# OScanner

## Обзор

OScanner - это простая программа-симулятор загрузки, созданная с использованием PyQt5 на языке Python. Она имитирует процесс сканирования на предмет угроз и предоставляет визуальное представление хода выполнения.

## Возможности

- Визуальное представление хода выполнения сканирования с использованием полосы прогресса.
- Имитация этапов сканирования с соответствующими сообщениями о статусе и прогрессе.
- Отображение отчета после завершения процесса сканирования.

## Предварительные требования

Убедитесь, что у вас установлены Python и PyQt5 на вашем компьютере. Вы можете установить PyQt5 с помощью следующей команды:

```bash
pip install PyQt5
```

## Как запустить

1. Клонируйте репозиторий:

```bash
git clone https://github.com/your-username/OScanner.git
cd OScanner
```

2. Запустите программу:

```bash
python app.py
```

## Зависимости

- PyQt5
- base64 (часть стандартной библиотеки Python)
- random (часть стандартной библиотеки Python)

## Использование

- Полоса прогресса отображает общий прогресс процесса сканирования.
- Окно приложения показывает текущий статус и прогресс этапов сканирования.
- Программа имитирует процесс сканирования в течение предопределенного времени (3600 секунд) и отображает отчет в конце.

## Лицензия

Эта программа является открытым исходным кодом и доступна под [лицензией MIT](LICENSE).

## Благодарности

- Эта программа представляет собой демонстрацию и не следует рассматривать как реальное средство безопасности.
- Иконки, используемые в приложении, предназначены исключительно для иллюстрации и не представляют конкретного бренда.

Не стесняйтесь вносить свой вклад или сообщать об ошибках!