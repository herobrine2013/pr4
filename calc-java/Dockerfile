# Используем образ Java в качестве родительского образа
FROM openjdk:alpine
# Устанавливаем рабочий каталог /app/calc
WORKDIR /app/calc
# Копируем содержимое текущего каталога в контейнер в /app/calc
COPY . /app/calc
# Компилируем Java приложение
RUN javac calc.java
# Устанавливаем команду по умолчанию для запуска Java приложения
CMD ["java", "calc"]