W dołączonym pliku przedstawiam trzy proste aplikacje internetowe stworzone przy pomocy Vue.js czyli jednego z popularniejszych i prostych w użyciu frameworków.

--- App 1 ---
Ten kod tworzy prostą stronę internetową z dwoma przyciskami: "Zwiększ" i "Zmniejsz". Po kliknięciu przycisku "Zwiększ" wartość licznika zostaje zwiększona o 1, a po kliknięciu przycisku "Zmniejsz" wartość zostaje zmniejszona o 1. Aktualna wartość licznika jest wyświetlana na stronie.

--- App 2 ---
Ten kod tworzy prostą listę zadań do zrobienia. Użytkownik może wprowadzać nowe zadania w polu tekstowym i dodawać je do listy za pomocą przycisku "Dodaj". Każde zadanie wyświetlane jest jako element listy wraz z przyciskiem "Usuń", który umożliwia usunięcie danego zadania.
Aplikacja wykorzystuje dwie metody: addTask i removeTask. Metoda addTask sprawdza, czy wprowadzone zadanie nie jest puste, a następnie tworzy nowy obiekt zadania i dodaje go do tablicy tasks. Metoda removeTask usuwa zadanie o określonym identyfikatorze z tablicy tasks za pomocą metody filter.

--- App 3 ---
Ten kod tworzy prosty katalog filmów. Na górze strony znajduje się pole tekstowe, które umożliwia użytkownikowi wprowadzenie frazy do wyszukiwania filmów. Poniżej wyświetlane są wyniki wyszukiwania w postaci listy filmów, które pasują do wprowadzonej frazy. Każdy film składa się z tytułu i roku produkcji.
Aplikacja korzysta z dwóch głównych elementów Vue.js: data i computed. Tablica movies przechowuje informacje o filmach, a searchTerm jest powiązane z polem tekstowym za pomocą dyrektywy v-model. Wartość searchTerm jest używana w obliczeniowym właściwości filteredMovies, która filtruje filmy na podstawie wprowadzonej frazy.
