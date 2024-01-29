# nauczaniemaszynowe

2.Czy architektura sieci ma znaczny wpływ na jakość klasyfikacji ?
Tak, architektura sieci neuronowej ma ogromny wpływ na jakość klasyfikacji. Wybór odpowiedniej architektury może być kluczowy dla skuteczności modelu w rozwiązaniu danego problemu. Kilka kluczowych aspektów, które zależą od architektury, obejmuje:
Głębokość sieci: Określa, ile warstw ma sieć. W przypadku bardziej skomplikowanych problemów, głębsze sieci neuronowe mogą zwykle lepiej modelować złożone zależności w danych. Jednak zbyt głęboka sieć może prowadzić do problemów, takich jak zanikające lub eksplodujące gradienty.

Szerokość sieci: Liczba neuronów w każdej warstwie ma wpływ na to, jak szeroko sieć może reprezentować dane. Większa szerokość może pomóc w uczeniu bardziej złożonych wzorców, ale również wymaga większej mocy obliczeniowej.

Rodzaj warstw: Wybór rodzaju warstw, takich jak warstwy konwolucyjne, rekurencyjne czy gęsto połączone, jest kluczowy w zależności od rodzaju danych i problemu. Na przykład, warstwy konwolucyjne są często używane do przetwarzania obrazów, podczas gdy warstwy rekurencyjne są przydatne w zadaniach przetwarzania sekwencji.

Funkcje aktywacji: Wybór funkcji aktywacji, takich jak ReLU, sigmoid czy tanh, ma wpływ na to, jak sieć przekształca dane i jak skutecznie uczony jest model. Odpowiedni wybór funkcji aktywacji może pomóc w zapobieganiu problemom, takim jak zanikające gradienty.

Hiperparametry: Takie parametry jak współczynnik uczenia, batch size czy momentum również wpływają

3.Czy szybkość trenowania ma wpływ na jakość klasyfikacji. 
Szybkość trenowania może mieć wpływ na jakość klasyfikacji, ale to jest bardziej związane z procesem uczenia niż z samą jakością. Oto kilka kwestii, które warto rozważyć:
Zbyt szybkie uczenie (wysoka szybkość uczenia): Jeśli ustawisz zbyt wysoką szybkość uczenia, model może przeskakiwać po minimum lokalnym i nie nauczyć się optymalnych wag dla danych. To może prowadzić do niskiej jakości klasyfikacji na danych testowych, ponieważ model może nie być w stanie dokładnie generalizować do nowych, nieznanych danych.

Zbyt wolne uczenie (niska szybkość uczenia): Przy zbyt niskiej szybkości uczenia model może potrzebować znacznie więcej epok, aby osiągnąć zbieżność, co może prowadzić do długiego czasu trenowania. Ponadto, model może utknąć w minimum lokalnym i nie zdążyć odkryć optymalnych wag.

Dopasowanie hiperparametrów: Odpowiednie dostosowanie hiperparametrów, takich jak szybkość uczenia, jest kluczowe. Czasem stosuje się techniki takie jak harmonogramy szybkości uczenia, gdzie wartość ta zmienia się dynamicznie w trakcie treningu, co może pomóc w uniknięciu problemów zbyt szybkiego lub zbyt wolnego uczenia.

Zrównoważone podejście: Optymalna szybkość uczenia zależy od specyfiki problemu, wielkości danych, a także samego modelu. W praktyce często stosuje się próby i błędy w celu znalezienia optymalnej szybkości uczenia dla danego zadania.

4.Czy rodzaj optymalizatora ma wpływ na jakość klasyfikacji.
Tak, rodzaj optymalizatora używanego podczas trenowania sieci neuronowej ma wpływ na jakość klasyfikacji. Optymalizator jest odpowiedzialny za aktualizowanie wag modelu w trakcie uczenia, minimalizując funkcję kosztu. Oto kilka popularnych rodzajów optymalizatorów i ich wpływ na jakość klasyfikacji:
Stochastic Gradient Descent (SGD): Jest to podstawowy optymalizator, który aktualizuje wagi w kierunku przeciwnym do gradientu funkcji kosztu. SGD może być skuteczny, ale czasem ma tendencję do poruszania się wzdłuż "wąskich dolin" funkcji kosztu, co może spowolnić proces uczenia.

Adam: Adam (Adaptive Moment Estimation) to popularny optymalizator, który łączy cechy optymalizatorów RMSprop i Momentum. Adam dostosowuje tempo uczenia dla każdego parametru, co może przyspieszyć proces uczenia. Jest często używany ze względu na swoją efektywność w praktyce.

RMSprop: Optymalizator RMSprop (Root Mean Square Propagation) również dostosowuje tempo uczenia, ale używa ruchomego średniego kwadratu gradientów, co pomaga radzić sobie z różnymi skalami gradientów.

Adagrad: Adagrad dostosowuje tempo uczenia dla każdego parametru, zwiększając je dla rzadkich gradientów i zmniejszając dla często występujących. Jednak w niektórych przypadkach może prowadzić do zbyt szybkiego zmniejszania tempo uczenia, co może zatrzymać proces uczenia.

Nadam: Nadam to połączenie Adam i SGD with Momentum. Jest to adaptacyjny optymalizator z korektą momentum, co może pomóc w szybkim osiąganiu minimum funkcji kosztu.

Płatne usługi Colab - Tutaj możesz anulować umowy
