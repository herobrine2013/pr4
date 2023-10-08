# Используем образ Python
FROM python:alpine
# Устанавливаем рабочий каталог /app/rpsgame
WORKDIR /app/rpsgame
# Копируем содержимое текущего каталога в контейнер в /app/rpsgame
COPY . /app/rpsgame
# Устанавливаем команду по умолчанию для запуска Python приложения
CMD ["python", "RockPaperScissorsGame.py"]