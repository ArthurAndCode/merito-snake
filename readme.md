# Gra Snake - Projekt C# w Konsoli

Prosta, klasyczna gra zręcznościowa Snake stworzona w języku C# jako aplikacja konsolowa. Projekt powstał w ramach pracy zespołowej z wykorzystaniem systemu kontroli wersji Git oraz platformy GitHub.

## 🎮 Funkcje gry

* **Płynne poruszanie się:** Gracz steruje wężem w czterech kierunkach za pomocą strzałek na klawiaturze.
* **Zbieranie punktów:** Celem gry jest zjadanie losowo pojawiających się na ekranie przeszkód (oznaczonych jako `*`), co powoduje wzrost wyniku.
* **Wykrywanie kolizji:** Gra automatycznie kończy się (wyświetlając ekran "Game Over"), gdy wąż uderzy w krawędź planszy (ścianę) lub ugryzie własny ogon.
* **Dynamiczny interfejs:** Kolorowa oprawa wizualna w oknie konsoli, z wyświetlanym na bieżąco wynikiem gracza.

## 🚀 Instrukcje uruchamiania

Aby uruchomić grę na swoim komputerze, postępuj zgodnie z poniższymi krokami:

1. **Wymagania wstępne:** Upewnij się, że masz zainstalowane środowisko **Visual Studio** (lub dowolny edytor obsługujący C#, np. VS Code) oraz **.NET SDK**.
2. **Klonowanie repozytorium:** Pobierz projekt na swój dysk za pomocą polecenia w terminalu:
   `git clone https://github.com/TWOJ_LOGIN/SnakeGame.git`
3. **Uruchomienie:**
   * **Opcja A (Visual Studio):** Otwórz plik projektu lub folder z plikami `.cs` w Visual Studio i naciśnij klawisz `F5`, aby skompilować i uruchomić grę.
   * **Opcja B (Terminal):** Przejdź do folderu z projektem i wpisz polecenie `dotnet run`.

## 🤝 Zasady współpracy w zespole

Projekt jest rozwijany przez dwie osoby. Aby utrzymać porządek i jakość kodu, stosujemy następujące zasady:

1. **Issues (Zgłoszenia):** Każde nowe zadanie, błąd do naprawienia lub pomysł na nową funkcję musi zostać najpierw opisane jako nowe Issue na GitHubie i przypisane do konkretnej osoby.
2. **Praca na gałęziach (Branches):** Nigdy nie commitujemy bezpośrednio do gałęzi `main`. Każde zadanie realizowane jest na osobnej gałęzi, np. `feature/nazwa-zadania` lub `fix/nazwa-bledu`.
3. **Pull Requests i Code Review:** Po zakończeniu pracy na gałęzi, programista otwiera Pull Request (PR) do gałęzi `main`. Druga osoba w zespole musi przeprowadzić recenzję kodu (Code Review) i zatwierdzić zmiany przed ich scaleniem.
4. **Zamykanie zgłoszeń:** W opisach commitów używamy słów kluczowych (np. `Closes #1`), aby automatycznie zamykać rozwiązane zgłoszenia podczas scalania.
