# Instrukcja obsługi - Konwerter Systemów Liczbowych

## Wprowadzenie

Aplikacja "Konwerter Systemów Liczbowych" pozwala na konwersję liczb pomiędzy różnymi systemami liczbowymi, w tym także nietypowymi systemami, jak system piątkowy (5), siódemkowy (7) czy dziewiątkowy (9). Program został zaprojektowany w prosty sposób, aby każdy mógł z niego łatwo korzystać.

---

## Funkcje

- Konwersja liczb z jednego systemu liczbowego na inny.
- Obsługa standardowych systemów (np. binarny, dziesiętny, szesnastkowy) oraz nietypowych (np. piątkowy, siódemkowy).

---

## Jak korzystać z programu

1. **Wprowadź liczbę do konwersji**
   - W polu oznaczonym jako "Wprowadź liczbę" wpisz liczbę, którą chcesz przekonwertować.
   - Przykłady:
     - "101" (dla liczby w systemie binarnym).
     - "2A" (dla liczby w systemie szesnastkowym).

2. **Podaj system liczbowy, z którego liczba pochodzi**
   - W polu "Z systemu" wpisz podstawę systemu liczbowego, z którego pochodzi liczba.
   - Wartość minimalna: 2.
   - Przykłady:
     - "2" (dla systemu binarnego).
     - "16" (dla systemu szesnastkowego).

3. **Wybierz system docelowy**
   - W polu "Na system" wpisz podstawę systemu liczbowego, na który chcesz przekonwertować liczbę.
   - Wartość minimalna: 2.
   - Przykłady:
     - "10" (dla systemu dziesiętnego).
     - "8" (dla systemu ósemkowego).

4. **Kliknij przycisk "Konwertuj"**
   - Program dokona konwersji liczby i wyświetli wynik w dolnej części aplikacji w polu "Wartość po konwersji".

---

## Obsługa błędów

- **Nieprawidłowe dane wejściowe:**
  - Jeśli wprowadzone dane są błędne lub niekompletne, aplikacja wyświetli komunikat: "Proszę podać prawidłowe dane we wszystkich polach."

- **Nieprawidłowa liczba:**
  - Jeśli liczba nie jest zgodna z podanym systemem liczbowym, pojawi się komunikat: "Nieprawidłowa liczba dla określonego systemu."

- **Inny błąd:**
  - W przypadku niespodziewanego błędu wyświetli się komunikat: "Wystąpił błąd podczas konwersji."

---

## Przykłady

### Przykład 1: Konwersja liczby binarnej na dziesiętną
- **Liczba wejściowa:** 101
- **Z systemu:** 2
- **Na system:** 10
- **Wynik:** 5

### Przykład 2: Konwersja liczby szesnastkowej na ósemkową
- **Liczba wejściowa:** 2A
- **Z systemu:** 16
- **Na system:** 8
- **Wynik:** 52

---

## Uwagi

- Wartości wprowadzane do pól "Z systemu" i "Na system" muszą być liczbami całkowitymi większymi lub równymi 2.
- Systemy liczbowe powyżej 36 nie są obsługiwane (z powodu ograniczeń w JavaScript `toString()` i `parseInt()`).

## Autor

Maciej B