W tym pliku opiszę jak uruchamia się kod programu dla tego projektu. 
Został on wykonany w oparciu o poradnik zanieszczony pod tym likiem: https://www.kaggle.com/pavansanagapati/simple-tutorial-on-object-recognition

Na początku z katalogu images-dataset pobierane są obrazy które będą używane do wyuczenia programu rozpoznawania obiektów znajdujących się na nich.
Program wypisuje ile obrazów znajduje się w pliku. Zamienia również ich rozmiar na 128x128 pixeli. Przedstawia również przykładowy obraz.
Następnie następuje trening modelu CNN prze Keras oraz wizualizacja strat podczas treningu i walidacji, na wykresie.
Później model jest oceniany pod względem strat i trafności podczas treningu. Przewidywana jest również klasa wyjściowa obrazu.
Następuje wizualizacja wyników warstwy pośredniej oraz wykreślenie macierzy pomyłek, aby zaobserwować wynik.