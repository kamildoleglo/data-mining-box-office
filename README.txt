== Box Office ==

Autorzy: Kamil Doległo, Rafał Stachura
Opiekun: dr inż. Anna Zygmunt

Opis:
Prognozowanie wyniku Box office na podstawie doboru elementów realizacji filmu

Instalacja wymaganych składników do uruchomienia projektu:

Cały projekt składa sie z zestawu notebooków Jupyter, w których zostały umieszczone poszczególne eksperymenty i kod źródłowy.

Do uruchomienia projektu potrzebne jest narzędzie Jupyter, którego instalacja jest opisana pod adresem:
https://jupyter.org/install
Informacje na temat użycia narzędzia i przykłady wykorzystania są dostępne na stronie:
https://jupyter.org/documentation

Kod źródłowy został zaimplementowany w języku Python 3.7 i taka wersja też powinna znajdować się na komputerze docelowym.
Informacje o instalacji można znaleźć pod poniższym adresem:
https://www.python.org/downloads/

W przypadku fragmentu projektu dotyczącego testowania i uczenia określonych modeli istnieje możliwość zaiportowania kodu do środowiska Google Colab, aby usprawnić wykonanie eksperymentów. 
Narzędzie jest dostępne pod adresem: 
https://colab.research.google.com

Kod jest w pełni przenośny i uruchamialny na wszytskich systemach posiadających wymagane narzędzia.

Uruchamianie projektu:

1. Każdy z notebooków stanowi oddzielną i w pełni samodzielną część projektu. W poszczególnych notebookach zawarte są wyyniki eksperymentów i fragmenty kodu zgodnie z ich nazwami.

2. Do uruchomienia niektórych notebooków potrzebne są dane, zatem w przypadu ich braku należy pobrać dane o filmach za pomocą zaimplementowanego downloadera.

3. Każdy notebook jest zorganizowany w taki sposób, aby możliwe było uruchamianie kodu znajdującego się w komórkach od najwyższej do najniższej.

4. Na początu zawsze należy zaimportować odpowiednie biblioteki, znajdujące się w każdym notebooku w sekcji import. 

5. W przypadku otryzmania błędu i braku danej biblioteki należy ją zainstalować za pomocą managera pakietów. 
W naszym przypadku korzystaliśmy z managera PIP dla języka Python 3.7. 
Manager jest instalowany domyślnie wraz z językiem Python.
Instalacja poszczególnych brakujących bibliotek odbywa się za pomocą komendy pip install <nazwa biblioteki>

6. Kod zawarty w poszczgólnych komórkach generuje wyniki w postaci tekstu oraz wykresów, które są widoczne w narzędziu Jupyter. 
Ponowne reużycie kodu może odbywać się poprzez wycięcie określonych fragmentów posiadających daną funckjonalność i zastoswoanie dla nowego zestawu danych.

