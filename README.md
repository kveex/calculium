
# Calculium

Калькулятор, который считает методами хорд `(chord)`, касательных `(tangent)` и комбинированным `(combined)` методом
## Установка

Скачать zip файл с сайта или выполнить команду в терминале

```bash
  git clone https://github.com/kveex/calculium.git 
```
Войти в папку с клонированным проектом

```bash
  cd ./calculium
```
Создать venv

```bash
python -m venv .venv
```

Активировать venv (Windows)
```psh
.venv\Scripts\activate.bat
```

Активировать venv (Linux)
```bash
source .venv\Scripts\activate
```

Установить зависимости
```pip
pip install sympy, dearpygui
```

Запустить
```python
python ./ui.py
```