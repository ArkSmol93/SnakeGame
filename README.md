# Dokumentacja projektu – Snake (C# Console)

## 1. Opis projektu

Snake to klasyczna gra konsolowa napisana w języku **C#**, działająca w oknie konsoli. Gracz steruje wężem, który porusza się automatycznie po planszy, zbiera jedzenie i unika kolizji ze ścianami oraz własnym ciałem.

Projekt ma charakter edukacyjny i służy do nauki:

* pętli gry
* obsługi klawiatury
* pracy z kolekcjami
* podstawowej logiki gier

---

## 2. Funkcje gry

* Automatyczny ruch węża
* Sterowanie kierunkiem za pomocą strzałek
* Losowe generowanie jedzenia (*)
* Zliczanie punktów (score)
* Kolizje:

  * ze ścianami planszy
  * z własnym ciałem
* Ekran końca gry (Game Over)

---

## 3. Sterowanie

| Klawisz | Akcja        |
| ------- | ------------ |
| ↑       | Ruch w górę  |
| ↓       | Ruch w dół   |
| ←       | Ruch w lewo  |
| →       | Ruch w prawo |

Wąż porusza się automatycznie w ostatnio wybranym kierunku.

---

## 4. Zasady gry

1. Wąż porusza się po planszy w sposób ciągły.
2. Gracz zmienia kierunek ruchu za pomocą klawiszy strzałek.
3. Zjedzenie jedzenia (*) zwiększa wynik.
4. Gra kończy się, gdy:

   * wąż uderzy w ścianę
   * wąż uderzy w samego siebie

---

## 5. Struktura projektu

* `Program.cs` – główna pętla gry i logika
* `Pixel.cs` – klasa reprezentująca elementy na planszy (np. głowa węża)

---

## 6. Instrukcja uruchamiania

### Wymagania:

* .NET SDK (np. .NET 6 lub nowszy)
* System Windows

### Kroki:

1. Otwórz projekt w **Visual Studio** lub **Visual Studio Code**
2. Upewnij się, że projekt jest aplikacją konsolową
3. Uruchom program (`Start` / `dotnet run`)
4. Gra uruchomi się w oknie konsoli

---

## 7. Zasady współpracy (jeśli projekt zespołowy)

* Każda zmiana w kodzie powinna być opisana w commit message
* Nie commitujemy niedziałającego kodu
* Zmiany testujemy lokalnie przed wysłaniem
* Czytelne nazwy zmiennych i komentarze w kodzie

---

## 8. Możliwe dalsze rozszerzenia

* Wzrost długości węża po zjedzeniu jedzenia
* Poziomy trudności (prędkość)
* Pauza gry
* Najlepszy wynik (High Score)
* Usunięcie migania ekranu

---

## 9. Autor

Projekt wykonany jako ćwiczenie edukacyjne w języku C#.
