# Praca inżynierska

## Adam Jochna
Wydział Podstawowych Problemów Techniki
**Politechnika Wrocławska**
___

**Cel i zakres pracy**:  Celem pracy inżynierskiej jest skonstruowanie modelu pozwalającego przewidzieć położenie pojazdu uczestniczącego w ruchu drogowym. Problem poddany analizie w tej pracy można przedstawić następująco. Mając dane wejściowe, czyli: pozycje granic dróg, kierunki jazdy, jakie obowiązują na drogach, pozycje świateł, kolory świateł, pozycje agentów (piesi, rowerzyści, pojazdy) w ustalonych chwilach [t, t-0.1, ... , t-1.0], trzeba wykorzystać te informacje do przewidzenia pozycji wybranego agenta (niekoniecznie pojazdu, może być np. pieszy) możliwie dokładnie w chwilach [t+0.1, t+0.2, ... , t+5.0].

**Charakter problemu**:  Problem przewidywania przyszłych pozycji obiektów uczestniczących w ruchu drogowym ma charakter praktyczny. Analizowany problem został zaczerpnięty z platformy Kaggle, gdzie firma Lyft ogłosiła konkurs na najlepszy system predykcyjny. Pula nagród wynosiła ponad 100 tys. zł. Firma Lyft ogłosiła konkurs w nadziei na pozyskanie inspiracji z interesujących rozwiązań, które mogłyby zostać zaimplementowane w autonomicznej flocie samochodów firmy Lyft. Zwiększenie skuteczności predykcji wiąże się bezpośrednio ze wzrostem bezpieczeństwa (pojazdy, mogą lepiej wnioskować na temat możliwych wariantów zachowań obiektów w otoczeniu), co w konsekwencji pozwoliłoby na zmniejszenie liczby ofiar oraz obrażeń ludzi w wypadkach z udziałem pojazdów autonomicznych (mowa tutaj o wszystkich markach samochodów, a nie tylko o samochodach organizatora konkursu).

**Struktura i opis pracy**: 

1. Analiza problemu
2. Rasteryzacja sceny
3. Funkcja kosztu
4. Naiwna metoda rozwiązania problemu
5. Głębokie sieci neuronowe
6. Agregacja modeli
7. Opis ostatecznego rozwiązania
8. Determinizm procesu trenowania

**Literatura**:
 1. John Houston, Guido Zuidhof, Luca Bergamini, Yawei Ye, Ashesh Jain, Sammy Omari, Vladimir Iglovikov, Peter Ondruska, "One Thousand and One Hours: Self-driving Motion Prediction Dataset"
 2. Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun, "Deep Residual Learning for Image Recognition"
 3. Mingxing Tan, Quoc V. Le, "EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks"
 4. Mingxing Tan, Quoc V. Le, "MixConv: Mixed Depthwise Convolutional Kernels"
 5. Jia Deng, Wei Dong, Richard Socher, Li-Jia Li, Kai Li, Li Fei-Fei, "ImageNet: A large-scale hierarchical image database"
 6. Dan Hendrycks, Kimin Lee, Mantas Mazeika, "Using Pre-Training Can Improve Model Robustness and Uncertainty"

## Zawartoś repozytorium

W katalogu `/latex` znajdują się pliki źródłowe opisowej części pracy.
