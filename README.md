# Inzyniera_oprogramowania
Repozytorium zawiera przykładowe implementacje popularnych wzorców projektowych oraz klasycznego problemu współbieżności, napisane w języku Python. Składa się z trzech głównych skryptów:

* Zadanie1.py (Problem Producent-Konsument / Obserwator): Symulacja działania magazynu z wykorzystaniem wielowątkowości (moduł threading). Implementuje mechanizm powiadamiania oparty na założeniach wzorca Obserwator, gdzie magazyn dynamicznie informuje producentów o wolnym miejscu, a konsumentów o dostępności towaru.

* Zadanie2.py (Wzorzec Kompozyt): Implementacja wzorca strukturalnego Kompozyt (Composite). Pokazuje, jak stworzyć drzewiastą strukturę składającą się z pojedynczych użytkowników (liści) i grup (kompozytów). Pozwala to na jednolite rozsyłanie wiadomości niezależnie od tego, czy odbiorcą jest płaska grupa, czy skomplikowana struktura z zagnieżdżonymi podgrupami.

* Zadanie3.py (Wzorzec Singleton): Klasyczna implementacja wzorca kreacyjnego Singleton przy użyciu metody magicznej __new__. Skrypt udowadnia, że niezależnie od liczby prób utworzenia obiektu, klasa zwraca zawsze tę samą, jedną instancję w pamięci.
