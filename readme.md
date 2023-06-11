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

Aplikacja React będzie dostępna pod adresem: http://localhost:5173/start.
   
Importowanie bazy danych do XAMPP:  
1.Uruchom XAMPP i upewnij się, że usługi Apache i MySQL są włączone.   
2.Otwórz przeglądarkę i przejdź do adresu http://localhost/phpmyadmin.   
3.Zaloguj się do panelu phpMyAdmin (jeśli nie zmieniałeś domyślnych ustawień, nazwa użytkownika to root, a hasło jest puste).  
4.Utwórz nową bazę danych o nazwie projekt.  
5.Kliknij na utworzoną bazę danych i wybierz zakładkę "Import".  
6.Wybierz plik z bazą danych który jest w przesłanym folderze (projekt.sql) do zaimportowania.  
7.Kliknij "Wykonaj".  
Baza danych powinna zostać zaimportowana do XAMPP.

