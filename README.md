### Instrukcja zainstalowania backendu Iperfa
- git clone https://github.com/NightGrimalkin/IperfBackEnd.git
- w katalogu głównym uruchamiamy mvn clean install
- w katalogu target generowany jest plik jar uruchamiany komendą java -jar nazwa_jara
- w katalogu target powinna znajdować się baza danych IperfDataBase.sqlite3 
	- baza powinna zawierać domyślne konto admina tabelkę z rolami (ROLE_USER, ROLE_ADMIN) oraz tabele zawierającą porty z których będą mogli korzystać użytkownicy do uruchamiania sesji iperfa  
- Zainstalowany Iperf3 na serwerze 
- upewnienie się, że wszystkie wartości w pliku application.properties się zgadzają  
### Instrukcja zainstalowania frontendu Iperfa
- git clone https://github.com/NightGrimalkin/IperfFrontEnd.git
- w katalogu głównym uruchamiamy npm install
-  w katalogu głównym uruchamiamy npm run build
-  w katalogu głównym uruchamiamy npx serve
