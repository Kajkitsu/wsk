## Pytania

### 1. Co przechowuje wskaźnik w C++?
A) Wartość zmiennej  
B) Adres w pamięci  
C) Typ zmiennej  
D) Rozmiar zmiennej  

### 3. Co robi operator dereferencji `*` użyty na wskaźniku?
A) Zwraca adres wskaźnika  
B) Usuwa wskaźnik z pamięci  
C) Zwraca wartość przechowywaną pod adresem wskaźnika  
D) Inkrementuje wskaźnik  

### 5. Co wypisze poniższy kod?
```cpp
int x = 10;
int* p = &x;
*p = 20;
cout << x;
```
A) 10  
B) 20  
C) Adres zmiennej x  
D) Błąd kompilacji  

### 7. Czy nazwa tablicy w C++ jest wskaźnikiem na jej pierwszy element?
A) Tak, zawsze  
B) Nie, nigdy  
C) Tylko dla tablic dynamicznych  
D) Tylko dla tablic znakowych  

### 9. O ile bajtów przesuwa się wskaźnik `int*` po operacji `p++`?
A) 1 bajt  
B) 2 bajty  
C) 4 bajty (sizeof(int))  
D) 8 bajtów  

### 11. Co robi funkcja `swap_int(int* a, int* b)` wywołana jako `swap_int(&x, &y)`?
A) Wypisuje wartości x i y  
B) Zamienia wartości zmiennych x i y  
C) Dodaje x do y  
D) Nic, bo nie można modyfikować zmiennych przez wskaźniki  

### 13. Jak poprawnie zwolnić pamięć zaalokowaną dla tablicy?
A) `delete p;`  
B) `delete[] p;`  
C) `free(p);`  
D) `remove p;`  

### 15. Gdzie jest alokowana pamięć przy `int* p = new int(42);`?
A) Na stosie (stack)  
B) Na stercie (heap)  
C) W pamięci statycznej  
D) W rejestrach procesora  

### 17. Jak iterować przez napis C-style wskaźnikiem?
A) `while (*p != 0)`  
B) `while (*p != '\0')`  
C) `while (p != NULL)`  
D) `while (p < end)`  

### 19. Który kod jest niebezpieczny?
A) `int* p = nullptr;`  
B) `int x = 10; int* p = &x;`  
C) `int* p = new int(42); delete p;`  
D) `int* get_ptr() { int x = 10; return &x; }`
