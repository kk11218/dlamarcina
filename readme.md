# System zarządzania pracownikami

System zarządzania pracownikami.

## Instalacja

1. Sklonuj repozytorium lub przenieś projekt do wybranego folderu.
2. Przejdź do katalogu projektu: `cd nazwa_projektu`
3. Zainstaluj zależności dla React:

   ```bash
   cd client
   npm install

Zainstaluj zależności dla Node.js:


    cd server
    npm install
Uruchamianie:  
Włącz serwer Node.js:


    cd server
    npm start


Włącz aplikację React:


    cd client
    npm run dev

   
Importowanie bazy danych do XAMPP:  
1.Zainstaluj jeśli nie masz XAMPPA'a z linku https://www.apachefriends.org/pl/download.html  
2.Uruchom XAMPP i upewnij się, że usługi Apache i MySQL są włączone.   
3.Otwórz przeglądarkę i przejdź do adresu http://localhost/phpmyadmin.   
4.Zaloguj się do panelu phpMyAdmin (jeśli nie zmieniałeś domyślnych ustawień, nazwa użytkownika to root, a hasło jest puste).  
5.Utwórz nową bazę danych o nazwie projekt.  
6.Kliknij na utworzoną bazę danych i wybierz zakładkę "Import".  
7.Wybierz plik z bazą danych który jest w przesłanym folderze (projekt.sql) do zaimportowania.  
8.Kliknij "Wykonaj".  
Baza danych powinna zostać zaimportowana do XAMPP.Można teraz już spokojnie wejść na adres aplikacji: http://localhost:5173/start.

