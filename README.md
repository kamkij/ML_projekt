# ML_projekt
Do mojego projektu wybrałam dataset z winami: Wine Quality Data Set ze strony http://archive.ics.uci.edu/ml/datasets.php .
Znajdują się tam dwa zbiory danych dotyczące czerwonych i białych odmian portugalskiego wina „Vinho Verde”.  Ze względu na kwestie prywatności i logistyki dostępne są tylko zmienne fizykochemiczne (dane wejściowe) i sensoryczne (dane wyjściowe) (np. Brak danych na temat rodzajów winogron, marki wina, ceny sprzedaży wina itp.).
Ponieważ klasy nie są zbilansowane (np. Jest o wiele więcej win normalnych niż doskonałych lub słabych) wykorzystuję metody analizy normalności rozkładu tzn. wyznaczam miary statystyczne taie jak: średnia, mediana, kurtoza i skońność, aby wybrać najlepsze atrybuty w modelu uczenia się.
Zbiory danych łączę w jeden plik a następnie zastosuję metodę klasyfikacji. 
