# Используем образ Java
FROM openjdk:17-jdk-alpine
# Устанавливаем рабочий каталог /app/game
WORKDIR /app/game
# Копируем содержимое текущего каталога в контейнер в /app/game
COPY . /app/game
# Компилируем Java приложение
RUN javac game.java
# Устанавливаем команду по умолчанию для запуска Java приложения
CMD ["java", "game"]