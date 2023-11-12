# Используем базовый образ Python версии 3.10.6
FROM python:3.10.6

# Устанавливаем рабочий каталог внутри контейнера
WORKDIR /app

# Обновляем установленный pip до последней версии
RUN pip install --upgrade pip

# Копируем файл requirements.txt во временный каталог контейнера
ADD ./requirements.txt /tmp/requirements.txt

# Устанавливаем зависимости из файла requirements.txt
RUN pip install -r /tmp/requirements.txt