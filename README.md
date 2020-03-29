# Predykcja miejsc występowania wypadków drogowych w woj. śląskim

W niniejszym repozytorium zawarty jest projekt predykcji miejsc wypadków drogowych w woj. śląskim na 2019 r.
Ogólny opis w/w projektu znajduje się w pliku: Kwartalnik_policyjny.pdf 
Miejsca, które zostały wytypowane w woj. śląskim znajdują się na mapie google (zgodnie z założeniem punkt zaznaczony na mapie jest środkiem kwadratu o bokach 5 na 10 sekund):
https://drive.google.com/open?id=17nnW3yQ_w7E_X3Xudlal55g8HhRrdHlp&usp=sharing

Budoawa_siatki_predykcji.ipynb
Jest to notebook, który agreguje dane zdarzeń drogowych. Tzn przypisuje konkretne zdarzenie drogowe do danego miejsca w siatce predykcji. Kolejne metody, które są wywoływane w w/w notebooku to „faktoryzacjia” miejscowości, drogi i ulicy na dane numeryczne.

Budowa_modelu_predykcyjnego.ipynb
W tym notebooku podjęta zostaje próba budowy modeli do predykcji miejsc wystąpowania zdarzeń drogowych.
