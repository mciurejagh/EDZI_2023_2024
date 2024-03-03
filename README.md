# Zasady oddawania ćwiczeń laboratoryjnych
Instrukcje do ćwiczeń będą udostępniane przez prowadzącego za pomocą tego repozytorium kodu.
Każdy student zobowiązany jest do:

1. **Stworzenia repozytorium GitHub o następującym nazewnictwie:** `EDZI_2023_2024_GR_{nr_grupy}_{nazwisko}_{imie}` przykład: `EDZI_2023_2024_GR_1_Ciurej_Maciej`
2. **Dodanie prowadzącego jako „kolaboratora” do swojego prywatnego repozytorium, zgodnie z instrukcją znajdującą się pod tym adresem:** `https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository`
3. **Dostarczania rozwiązań w repozytorium najpóźniej w terminie określonym przez prowadzącego**

Rozwiązania proszę umieszczać w osobnych folderach w następującej konwencji nazw: `Cwiczenia_{nr_zajęc}` przykład : `Cwiczenia_1`

Mój adres mailowy pod którym znajdziecie mnie na portalu GitHub w celu dodania do repozytorium to : `mciurej@agh.edu.pl` oraz  nazwa użytkownika: `mciurejagh`


Każdy student jest zobowiązany do umieszczenia rozwiązań ćwiczeń wewnątrz swojego repozytorium znajdującego się na platformie GitHub,  

## Kroki do wykonania:
1. **Pobranie zawartości strony internetowej:**
    - Użyj pakietu `requests` w celu pobrania zawartości strony z Wikipedii.
    - Użyj `BeautifulSoup` aby sparsować zawartość kodu HTML.

2. **Procesowanie tekstu:**
    - Przekształć tekst do małych liter (lowercase).
    - Usuń znaki specjalne oraz interpunkcję.

3. **Znajdź 100 najczęściej występujących w tekście słów:**
    - Podziel tekst na słowa.
    - Zlicz ilość wystąpień dla każdego słowa.
    - Znajdź 100 najpopularniejszych w tekście słów.

4. **Zapisz wyniki do pliku tekstowego:**
    - Zapisz rezultaty do pliku tekstowego o nazwie `output.txt` w formacie `ranking;słowo;ilość wystąpień`

## Użyj następującego kodu, aby zacząć pracę nad rozwiązaniem:
