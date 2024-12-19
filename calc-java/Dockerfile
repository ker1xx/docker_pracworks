# Используем базовый образ с поддержкой JDK
FROM openjdk:17
WORKDIR /app

# Копируем исходники
COPY . /app

# Компилируем Java-приложение
RUN javac calc.java

# Команда для запуска приложения
CMD ["java", "calc"]