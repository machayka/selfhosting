Przydatne komendy:

# 1. Uruchom raz

docker-compose up -d

# 2. Edytuj pliki (VS Code, nano, cokolwiek)

# 3. Odśwież przeglądarkę (Ctrl+R)

# 4. Zmiany widoczne OD RAZU! ⚡

# Zatrzymaj gdy skończysz

docker-compose down

Wdrożenie na Ubuntu:

Wystarczy:

1. Sklonować repo na serwer Ubuntu
2. docker build -t self-hosting .
3. docker run -d -p 80:80 self-hosting
4. Skonfigurować domenę i SSL (certbot)
