# Используем базовый образ Dart
FROM dart:latest
WORKDIR /app

# Копируем файлы
COPY . /app

# Компилируем Dart-приложение
RUN dart compile exe calc.dart -o calc

# Команда для запуска приложения
CMD ["./calc"]