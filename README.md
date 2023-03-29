# despectre-ai

Projekt Machine Learning odzyskujący audio ze spektrogramów

### Plan projektu:
* Zebranie danych do trenowania [Marek]
  * Pliki audio 
    * HuggingFace oferuje "training sets" 
* Zdefiniowanie sieci neuronowej 
* Zbudowanie "pipeline" (przetwarza dane do formatu rozumianego przez sieć neuronową i odbiera z niej dane do docelowego formatu) 
  * Program przetwarzający zbiorowo audio na spektrogramy  
     * Biblioteka python 
* System treningu 
  * "Loss function" - różnice między zamierzonym efektem a otrzymanym 
    * Plik audio przetworzony na spektrogram – rekreacja od sieci 
* Sama funkcja modyfikacji sieci (pewnie Pytorch już coś takiego ma) 

* TRENOWANIE 
  * Początkowo lokalnie, testowo, na małą skalę 
  * Próbowanie z parametrami uczenia, wielkości sieci, wejść, itd. 
  * Ew. Potem na usłudze sieciowej lub przez dłuższy czas na czyimś kompie 
