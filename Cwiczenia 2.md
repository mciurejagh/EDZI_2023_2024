# Ćwiczenie 2: Prosty crawler z użyciem find_all()

## Cel:
Celem ćwiczenia jest napisanie kodu w Pythonie, który wyszuka wszystkie linki na podanej stronie, a następnie w losowy sposób wybierze z nich następną stronę do odwiedzenia. Program powinien powtórzyć swoje działanie do momentu wyświetlenia na ekranie 100 linków. Skorzystaj z funkcji find_all() oraz dowolnego pakietu i funkcji losującej w celu randomizacji kolejnej strony do odwiedzenia.

Jako strony startowej użyj : `https://www.onet.pl/`

Zadanie możecie Państwo wykonać w formie podstawowej lub rozbudowanej. Wersja rozbudowana jest warta +10% do oceny z aktywności (odsyłam do prezentacji z Ćwiczen 1, po więcej szczegółów).

Forma podstawowa obejmuje:
	1. Pobranie wszystkich linków ze strony początkowej
	2. Losowe wybranie kolejnej strony z której pobierzecie wszystkie linki
	3. Powtórzenie kroków 1 i 2 aż do uzyskania listy stu linków, które są ze sobą powiązane
	
W przypadku zakleszczeń (strona nie ma linków lub odsyła jedynie do siebie), ponawiamy losowanie i liczymy na lepszy wynik przy kolejnej próbie.

Forma rozszerzona obejmuje:
Formę podstawową + obsługę zakleszczeń tzn: 
	1. Losowanie nowej strony, jeżeli aktualnie wylosowana nie posiada odnośników (strona bez linków nie powinna być wtedy wypisywana na ekranie)
	2. Obsługę wyjątków, które mogą wystąpić podczas działania programu : obsługa SSL, martwy link itp. Itd.

W przypadku formy podstawowej akceptowalna jest wersja, gdzie możliwe jest uzyskanie 100 linków w odpowiednich warunkach testowych. Forma rozszerzona MUSI za każdym razem zwracać 100 (unikalnych) linków.
