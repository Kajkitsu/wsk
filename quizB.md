## Pytania

### 2. Jaki operator służy do pobrania adresu zmiennej?
A) `*`  
B) `&`  
C) `#`  
D) `@`  

### 4. Jak prawidłowo zadeklarować wskaźnik na zmienną typu `int`?
A) `int p*;`  
B) `int* p;`  
C) `*int p;`  
D) `pointer<int> p;`  

### 6. Czym jest `nullptr`?
A) Wskaźnikiem na wartość zerową  
B) Bezpieczną wartością inicjalizującą wskaźnik (pusty wskaźnik)  
C) Funkcją zwracającą adres  
D) Typem zmiennej  

### 8. Co jest równoważne z `A[3]` w notacji wskaźnikowej?
A) `*A + 3`  
B) `*(A + 3)`  
C) `&A[3]`  
D) `A + *3`  

### 10. Jak przekazać zmienną do funkcji, aby funkcja mogła ją zmodyfikować?
A) Przez wartość: `void func(int x)`  
B) Przez wskaźnik: `void func(int* x)`  
C) Przez kopię: `void func(int& x)`  
D) Nie można modyfikować zmiennych w funkcjach  

### 12. Który kod powoduje wyciek pamięci (memory leak)?
A) `int* p = new int(42); delete p;`  
B) `int* p = new int[10]; delete[] p;`  
C) `int* p = new int[10];` (bez delete)  
D) `int x = 42; int* p = &x;`  

### 14. Co wypisze poniższy kod?
```cpp
int A[3] = {10, 20, 30};
cout << *(A + 1);
```
A) 10  
B) 20  
C) 30  
D) Adres A[1]  

### 16. Co się stanie przy próbie użycia niezainicjalizowanego wskaźnika?
```cpp
int* p;
*p = 42;
```
A) Wartość 42 zostanie zapisana bezpiecznie  
B) Program może ulec awarii (undefined behavior)  
C) Kompilator zgłosi błąd  
D) Wskaźnik automatycznie zostanie zainicjalizowany na nullptr  

### 18. Co zwraca wyrażenie `p2 - p1` dla dwóch wskaźników tego samego typu?
A) Różnicę adresów w bajtach  
B) Liczbę elementów między wskaźnikami  
C) Sumę wskaźników  
D) Błąd kompilacji  

### 20. Jaka jest różnica między `int q = 42;` a `int* q = new int(42);`?
A) Brak różnicy, to samo  
B) Pierwszy tworzy zmienną na stosie, drugi na stercie  
C) Pierwszy jest szybszy, drugi wolniejszy  
D) B i C są prawdziwe
