# SMM_Backend

Jest to aplikacja backendowa do mojego systemu monitoringu wilgotności ziemi.
Do poprawnego uruchomienia potrzebny jest Docker, Docker Compose oraz Python. Proces inicjalizacji przebiega następująco:
1. W głównym katalogu należy stworzyć plik .env, plik ten powinien zawierać informacje dotyczące procesu autoryzacji, adres ip serwera oraz port. Plik .env powinien zawierać jedynie nazwę użytkownika, hasło, adres ip serwera oraz port i powinien wyglądać następująco:
   USERNAME=nazwa_użytkownika
   PASSWORD=hasło_użytkownika
   IP_ADDRESS=adres_ip_serwera
   PORT=port
2. Z gotowym plikiem .env możliwe jest zainstalowanie aplikacji poprzez uruchomienie polecenia **docker-compose up -d**.

========================================================================================================================================================================================


This is a backend application for my soil moisture monitoring system.
For proper setup Docker, Docker Compose and Python is necessary. Initialisation process goes as follows:

1. In main folder create a .env file, this file should contain information regarding authorisation process, servers ip address and port. The .env file should only contain username, password, servers ip address and port and should look like this:
   USERNAME=username
   PASSWORD=password
   IP_ADDRESS=server_ip_address
   PORT=port_number
2. With .env file ready you can set up application by running command **docker-compose up -d**.


