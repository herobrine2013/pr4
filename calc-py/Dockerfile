# Используем образ Python
FROM python:alpine
# Устанавливаем рабочий каталог /app/calc
WORKDIR /app/calc
# Копируем содержимое текущего каталога в контейнер в /app/calc
COPY . /app/calc
# Устанавливаем команду по умолчанию для запуска Python приложения
CMD ["python", "calc.py"]