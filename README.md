# 'Матрица Судьбы' - автоматизация расчета нумерологической матрицы.

## Описание

Данный проект представляет собой автоматизированный процесс создания нумерологической матрицы на основе введенной даты рождения. С помощью набора формул, веб-интерфейс производит расчет параметров изображения и создает графическое представление матрицы. Результаты представлены в формате PDF c расшифровкой параметров матрицы, текстовое описание которых хранится в SQLite базе данных. Пользователи могут управлять каждым разделом базы данных через веб-интерфейс, включая добавление, удаление или изменение записей. Также возможно экспортировать базу данных в формате CSV.

Интерфейс проекта основан на доработанном Bootstrap и имеет адаптивный дизайн для работы на любых устройствах, включая мобильные. 

Обратите внимание, что база данных содержит только тестовую информацию, необходимую для демонстрации работы проекта.

### Технологии
- Python 3.9
- Flask 2.1.3
- Flask-SQLAlchemy 2.5.1
- FPDF 2.5.5
- Pillow 9.2.0

## Как запустить проект (локально):

1. Скопируйте репозиторий и перейдите в него в командной строке:

```
git clone https://https://github.com/3gr1v750v/fate_matrix-web
```

```
cd fate_matrix-web
```

2. Создайте и активируйте виртуальное окружение:

```
python -m venv env
```

```
source env/bin/activate
```

3. Установите зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

4. Запустите проект:

```
python main.py
```
