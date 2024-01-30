# nauczaniemaszynowe

1.	Dlaczego wyniki trenowania dają lepsze rezultaty niż w poprzednim zbiorze. Uzasadnić odpowiedź.

Większy zbiór danych treningowych,Zastosowanie lepszego modelu,Przetwarzanie wstępne danych:,

2,Czy architektura sieci ma znaczny wpływ na jakość klasyfikacji.

Tak, architektura sieci neuronowej ma znaczący wpływ na jakość klasyfikacji w zadaniach uczenia maszynowego. Różnice w architekturze mogą wpływać na zdolność modelu do uczenia się z danych, generalizacji na nowe dane oraz skuteczności klasyfikacji

3.	Czy szybkość trenowania ma wpływ na jakość klasyfikacji.

Zbyt szybkie trenowanie ,Zbyt wolne trenowanie,Zastosowanie optymalizatorów,Dopasowanie współczynnika uczenia

4.	Czy rodzaj optymalizatora ma wpływ na jakość klasyfikacji.

Tak, rodzaj optymalizatora ma wpływ na jakość klasyfikacji w sieciach neuronowych. Optymalizator odpowiada za dostosowanie wag modelu w trakcie procesu uczenia w celu minimalizacji funkcji kosztu
5	Jaki wpływ ma struktura sieci na rozpoznawanie i klasyfikację?
Struktura sieci neuronowej ma istotny wpływ na jej zdolność do rozpoznawania i klasyfikacji danych,a tu przedstawiam wazne aspekty:
Liczba warstw
Liczba neuronów w warstwie
Typy warstw
6.	Jaki wpływ ma zastosowanie warstw dropout na klasyfikację?

Warstwy dropout to technika regularyzacji w uczeniu maszynowym, która polega na losowym wyłączaniu niektórych neuronów w warstwie sieci neuronowej. Ma to na celu zmniejszenie ryzyka przeuczenia modelu, czyli sytuacji, w której model zbyt dobrze dopasowuje się do zbioru treningowego, a przez to nie jest w stanie generalizować na nowych danych.

W przypadku klasyfikacji, zastosowanie warstw dropout może mieć następujący wpływ:

Zmniejszenie ryzyka przeuczenia - dropout uniemożliwia sieci neuronowej nadmiernego dopasowania się do zbioru treningowego, ponieważ zmusza ją do uczenia się na danych, w których niektóre informacje są niedostępne.
Poprawa wydajności na zbiorze testowym - dropout może poprawić wydajność modelu na zbiorze testowym, ponieważ zmusza go do uczenia się bardziej ogólnych cech, które są mniej podatne na przeuczenie.
Zwiększenie stabilności modelu - dropout może zwiększyć stabilność modelu, ponieważ zmniejsza jego wrażliwość na losowe wahania zbioru treningowego.

User
7.	Jaki wpływ ma szybkość uczenia na klasyfikację.

Szybkość uczenia, czyli tempo aktualizacji wag w trakcie procesu uczenia sieci neuronowej, ma istotny wpływ na zdolność sieci do skutecznej klasyfikacji danych. Oto kilka aspektów, które warto rozważyć:

Zbieżność:

Zbyt niska szybkość uczenia: Może skutkować długim czasem potrzebnym do osiągnięcia zbieżności. Jeśli tempo aktualizacji wag jest zbyt małe, model może potrzebować wielu epok treningu, aby nauczyć się poprawnej reprezentacji danych.
Zbyt wysoka szybkość uczenia: Może prowadzić do niestabilności i trudności w zbieganiu. Model może przeskakiwać po minimum lokalnym i mieć trudności z nauką 
Przeuczenie (Overfitting) i Niedouczenie (Underfitting):

8	Jaki wpływ ma jakość zbioru trenującego na uczenie.

Jakość zbioru trenującego ma zasadniczy wpływ na jakość modelu uczenia maszynowego. Zbiór trenujący powinien być reprezentatywny dla danych, na których model będzie później używany. Oznacza to, że powinien zawierać dane z różnych klas, z różnych źródeł i w różnych formatach.
Oto kilka czynników, które wpływają na jakość zbioru trenującego:

Rozmiar zbioru - im większy zbiór, tym lepszy model można wytrenować.
Różnorodność zbioru - zbiór powinien zawierać dane z różnych klas, z różnych źródeł i w różnych formatach.
Dokładność danych - dane w zbiorze powinny być dokładne i bez błędów.
Wyrównanie zbioru - proporcje danych z różnych klas powinny być zbliżone do proporcji danych, na których model będzie później używany.
9.	Czy sieć zawsze będzie dobrze trenować?

Nie, sieć neuronowa nie zawsze będzie dobrze trenować. Istnieje wiele wyzwań i potencjalnych problemów, które mogą wpłynąć na skuteczność treningu sieci. Oto kilka czynników, które mogą prowadzić do trudności w treningu:

Niewystarczające dane treningowe:

Niewłaściwa architektura sieci:

10.Czy ilość epok miała wpływ na trenowanie obrazów?
Tak, ilość epok ma wpływ na trenowanie obrazów. Im więcej epok, tym dłużej model będzie się uczyć i tym lepsze może osiągnąć wyniki. Jednak zbyt duża liczba epok może prowadzić do przeuczenia, co może negatywnie wpłynąć na wydajność modelu na danych testowych. 

11.Czy uczenie z transferem daje dobre wyniki?

Uczenie z transferem (transfer learning) to podejście, w którym model jest trenowany na jednym zadaniu i następnie używany lub dostosowywany do innego zadania.

Oto kilka powodów, dla których uczenie z transferem może być skuteczne:

Wykorzystanie wiedzy z innych zadań:
Uczenie reprezentacji cech:
Zapobieganie przeuczeniu:
Szybszy trening:

12.Czy jest coś co można zrobić aby klasyfikator poprawił jakość trenowania?

Tak, jest wiele rzeczy, które można zrobić, aby poprawić jakość trenowania klasyfikatora. Oto kilka wskazówek:

Upewnij się, że zbiór treningowy jest wysokiej jakości. Zbiór treningowy powinien być reprezentatywny dla danych, na których model będzie później używany. Powinien zawierać dane z różnych klas, z różnych źródeł i w różnych formatach.

Użyj technik regularyzacji, aby zmniejszyć ryzyko przeuczenia. Przeuczenie występuje, gdy model zbyt dobrze dopasowuje się do danych treningowych, a przez to nie jest w stanie generalizować na nowych danych. Techniki regularyzacji, takie jak dropout lub L1/L2 regularyzacja, mogą pomóc w zmniejszeniu ryzyka przeuczenia. 

Techniki regularyzacji

Użyj optymalnych parametrów treningowych. Parametry treningowe, takie jak współczynnik uczenia się i funkcja straty, mogą mieć znaczący wpływ na jakość modelu. Eksperymentuj z różnymi wartościami parametrów, aby znaleźć optymalne rozwiązanie dla danego problemu. 



