# LAB2

## Процесс установки

Проект содержит файл `pyproject.toml`, содержащий конфигурацию и список зависимостей, необходимых для работы программы. Установку и настройку можно провести следующим образом:

### Перед установкой

- Нужно убедиться, что Python3.10+ установлен

```bash
python --version
```

### Установка при помощи poetry

- Проверить что poetry установлен

```bash
poetry --version
```

- Если poetry не установлен

```bash
pip install -m poetry
```

- Чтение конфигурации и установка проекта

```bash
poetry install
```

### Установка при помощи pip

- Автоматическая настройка

```bash
python -m pip install -e .
```

- Установка отдельных пакетов (лучше не надо)

```bash
python -m pip install tk pytest importlib tkcalendar
```
