# Zastosowanie metody optymalizacyjnej do wyznaczania składu równowagowego w procesie reformingu metanu

## Początek



- ##### Reforming metanu- co to?

  Reforming parowy metanu jest powszechnie stosowanym procesem pozyskiwania wodoru; para wodna oraz węglowodór są substratem w reaktorze (paliwem), natomiast wodór oraz dwutlenek węgla powstają wskutek procesu jako produkty. Proces może być przedstawiony za pomocą równań:
  $$
  CH_4 + H_2O ↔ CO + 3H_2
  $$

  $$
  CO + H_2O ↔ CO_2 + H_2
  $$

  $$
  CH_4 + 2H_2O ↔ CO_2 + 4H_2
  $$

  Pierwsza z reakcji jest endotermiczna, więc proces zwykle przebiega w temperaturze około 850&deg;C, by osiągnąć pożądany efekt. Druga reakcja jest znana jako reakcja woda-gaz, gdzie gaz syntezowy reaguje w celu odzyskania wodoru z tlenku węgla. Konwencjonalnie proces przebiega w reaktorach wielorurowych ze złożem stałym w obecności metalicznego katalizatora ($Ni$). Całkowita reakcja jest ograniczana zarówno przez reforming parowy, jak i przejście woda- gaz, ponieważ podlegają one zasadom równowagi termodynamicznej. 

  Użycie jednostki służącej do reformingu parowego eliminuje problemy przechowania oraz dystrybucji zbiorników na wodór w pojazdach działających na wodór. Dodatkowo reforming parowy metanu jest najbardziej efektywną z dostępnych komercyjnie metod produkcji metanu (częściowa oksydacja ciężkiego oleju i węgla, zgazowanie węgla).

  Niestety, choć emisja dwutlenku węgla do atmosfery jest niższa w przypadku użycia ogniw paliwowych zasilanych gazem niż w przypadku silników spalinowych, to problem emisji gazów cieplarnianych nie jest eliminowany całkowicie. 

  Jednym z wyzwań, które niewątpliwie stoją przed każdym, kto pragnie, by wodór stał się konkurencyjny na rynku paliw jest obniżenie kosztów produkcji tego paliwa. W tym celu należy dokonać poprawy wydajności procesu produkcji, co prowadzi do jego optymalizacji między innymi na podstawie analiz składu równowagowego. 

- ##### Równowaga procesu reformingu parowego

  Równowaga procesu wpływa na tempo procesu. Stała równowagowa wskazuje w którą stronę zachodzi reakcja odwracalna. 
  $$
  K_p=\frac{P[CH_4]*P[H_2O]}{P[H_2]^3*P[CO]}
  $$
  Powyższe można zapisać w bardziej użytecznej formie:
  $$
  P[CH_4]=K_p\frac{P[H_2]^3*P[CO]}{P[H_2O]}
  $$
  Pozwala to na odniesienie ciśnienia parcjalnego metanu do pozostałych parametrów.

  Ponownie można uprościć równanie w następujący sposób: 
  $$
  [CH_4]=K_p\frac{P^2[H_2]^3*[CO]}{[H_2O]}
  $$
  Jest to forma najbardziej użyteczna do obecnych rozważań, ponieważ możemy na jej podstawie wywnioskować, że:

  - udział metanu jest proporcjonalny do $K_p$
  - udział metanu jest proporcjonalny do $P^2$
  - udział metanu jest odwrotnie proporcjonalny do udziału pary wodnej

  $K_p$ jest odwrotnie proporcjonalne do temperatury, a by uzyskać dobrą pozycję równowagi musimy zastosować wysoką temperaturę.

   

  Przejście woda- gaz również jest ograniczone równowagowo. 

  $$
  K_p=\frac{P[CO_2]*P[H_2]}{P[CO]*P[H_2O]}
  $$

  $$
  [CO]=\frac{[CO_2]*[H_2]}{K_p*[H_2O]}
  $$

  $[CO]$ nie jest zależne od ciśnienia; jest natomiast odwrotnie proporcjonalne do zawartości wody. Wnioskujemy zatem, że:

  - wyższy stosunek pary wodnej do węgla powoduje otrzymanie mniejszej ilości $CO$ oraz większej $CO_2$
  - $K_p$ jest zależne od temperatury
  - wyższa temperatura na wyjściu skutkuje większą ilością $CO$ oraz mniejszą $CO_2$

  =============00986445.2013.867257.pdf