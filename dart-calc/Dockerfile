# Используем образ Dart
FROM google/dart AS build
# Устанавливаем рабочий каталог /app/calc
WORKDIR /app/calc
# Копируем содержимое текущего каталога в контейнер в /app/calc
COPY . /app/calc
# Устанавливаем команду по умолчанию для запуска Dart приложения
CMD ["dart", "calc.dart"]