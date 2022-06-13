# DotNet-ININ3-PR1

Zdefiniować szkielet okna głównego aplikacji oraz zasoby aplikacji.

Okno główne powinno się składać z umieszczonych na siatce:
- WrapPanel-u u góry lub dołu okna, z umieszczonymi na nim (poziomo z zawijaniem) przyciskami.
- StackPanel-u po lewej lub prawej stronie okna, z umieszczonymi na nim etykietami opisującymi grupy przycisków

W zasobach należy zdefiniować:
- Styl dla Label - pogrubiony tekst, font size na 24,
- Specjalny styl dla Label (wystarczy na jednej wybranej) definiowany z użyciem BasedOn, który poza tym co wyżej zmienia kolor tekstu (np: #900)
- Styl dla Button - standardowe tło zmienione na inny odcień (np: #EEE), font size na 20
- Drugi styl dla Button (np osobny dla WrapPanelu) - font size na 20 i modyfikacja kolorów: statycznego, przy najechaniu i przy kliknięciu (np: #DDF, #99D, #99F)
- Wszystkie opisane kolory mają być definiowane jako nazwane zasoby (SolidColorBrush)
