
## Odpowiedzi

1. **B** - Wskaźnik przechowuje adres w pamięci
2. **B** - Operator `&` (address-of) pobiera adres zmiennej
3. **C** - Operator `*` (dereferencja) zwraca wartość pod adresem
4. **B** - Poprawna deklaracja: `int* p;`
5. **B** - Przez `*p = 20` zmieniamy wartość x na 20
6. **B** - `nullptr` to bezpieczna wartość dla pustego wskaźnika
7. **A** - Tak, nazwa tablicy to wskaźnik na pierwszy element
8. **B** - `A[3]` = `*(A + 3)`
9. **C** - Wskaźnik `int*` przesuwa się o `sizeof(int)` = 4 bajty
10. **B** - Przez wskaźnik: `void func(int* x)` i wywołanie `func(&var)`
11. **B** - Funkcja zamienia wartości zmiennych x i y
12. **C** - Brak `delete[]` powoduje wyciek pamięci
13. **B** - Dla tablic używamy `delete[]`
14. **B** - `*(A + 1)` to wartość A[1] = 20
15. **B** - Operator `new` alokuje na stercie (heap)
16. **B** - Undefined behavior, możliwy crash programu
17. **B** - Iterujemy do `'\0'` (null terminator)
18. **B** - Zwraca liczbę elementów między wskaźnikami
19. **D** - Zwracanie wskaźnika do zmiennej lokalnej (dangling pointer)
20. **D** - Oba: pierwszy na stosie, drugi na stercie; pierwszy szybszy

---

## Ocenianie
- **18-20** poprawnych: Celujący ⭐⭐⭐⭐⭐
- **15-17** poprawnych: Bardzo dobry ⭐⭐⭐⭐
- **12-14** poprawnych: Dobry ⭐⭐⭐
- **9-11** poprawnych: Dostateczny ⭐⭐
- **Poniżej 9:** Powtórz materiał 📚