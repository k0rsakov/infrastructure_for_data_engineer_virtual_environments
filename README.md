# Инфраструктура для Data-Engineer виртуальные окружения

Статья на [habr](https://habr.com/ru/articles/861412/).

## Настройка окружения:

### venv

```bash
python3.12 -m venv venv && \
source venv/bin/activate && \
pip install --upgrade pip
```

### poetry

```bash
python3.12 -m venv poetry_venv && \
source poetry_venv/bin/activate && \
pip install --upgrade pip && \
pip install poetry && \
poetry lock && \
poetry install
```
___

Если вам необходима консультация/менторство/мок-собеседование и другие вопросы по дата-инженерии, то вы можете
обращаться ко мне. Все контакты указаны по
[ссылке](https://www.notion.so/korsak0v/Data-Engineer-185c62fdf79345eb9da9928356884ea0).


