# CSMS_backend

Jest to aplikacja backendowa do mojego systemu monitoringu wilgotności ziemi.
Do poprawnej instalacji potrzebny jest Docker, Docker Compose oraz Python. Proces instalacji przebiega następująco:
1. W głównym katalogu należy stworzyć plik .env, plik ten powinien zawierać informacje dotyczące procesu autoryzacji. Plik .env powinien zawierać jedynie nazwę użytkownika oraz hasło i powinien wyglądać następująco:
   USERNAME=nazwa_użytkownika
   PASSWORD=hasło_użytkownika
2. Z gotowym plikiem .env możliwe jest zainstalowanie aplikacji poprzez uruchomienie polecenia **docker-compose up -d**.

=========================================================================================================================================================================================================================

This is a backend application for my soil moisture monitoring system.
For proper instalation Docker, Docker Compose and Python is necessary. Instalation process goes as follows:

1. In main folder create a .env file, this file should contain information regarding authorisation process. The .env file should only contain username and password and should look like this:
   USERNAME=username
   PASSWORD=password
2. With .env file ready you can set up application by running command **docker-compose up -d**.
