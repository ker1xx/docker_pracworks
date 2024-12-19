# Используем базовый образ с поддержкой JDK
FROM openjdk:17
WORKDIR /app

# Копируем исходные файлы
COPY . /app

# Компилируем Java-приложение
RUN javac game.java

# Команда для запуска игры
CMD ["java", "game"]