2. W nowym projekcie wykonaj czynności:
* stwórz klasę `Aaa` i dodaj w niej wrtualną metodę `Metoda()` typu `void` (ma wyświetlić string `"Aaa"`).
* stwórz klasę `Bbb` dziedziczącą po `Aaa`, w nowoutworzonej klasie przesłoń metodę `Metoda()` (ma wyświetlić string `"Bbb"`) i dodaj do metody modyfikator `sealed`.
* stwórz klasę `Ccc` dziedziczącą po `Bbb`, w nowoutworzonej klasie spróbuj przesłonić metodę `Metoda()`. Jaki komunikat błędu otrzymasz?
* stwórz obiekt typu `Ccc` i wywołaj dla niego metodę `Metoda()`.
