# SQL-project

Zadanie 1
Na podstawie znormalizowanego modelu relacyjnego (patrz Dodatek) należy zaprojektować jeden model danych
dla hurtowni danych, na podstawie którego można byłoby dokonywać następujących analiz:
  - naliza wartości sprzedaży na poziomie dni dla danego produktu w kolejnych państwach
  - naliza wydatków na reklamę na dany produkt w danym województwie w kolejnych miesiącach
  - Analiza średniego okresu trwania reklamy na produkt w kolejnych miesiącach na poziomie sklepu
  - Analiza liczby promocji oferowanych przez sklep na dany typ produktu w kolejnych miesiącach.
Poszczególne tabele wymiarów powinny zawierać atrybuty, które opisują je w modelu znormalizowanym.
Uwaga: tabela reprezentująca czas na poziomie granulacji dnia powinna dodatkowo zawierać atrybuty:
  - który dzień tygodnia
  - który dzień miesiąca
  - który dzień roku
  - czy weekend
  - który numer tygodnia w roku
  - który kwartał roku
Uwaga: tabela reprezentująca czas na poziomie granulacji miesiąca oprócz numeru miesiąca oraz roku powinna
dodatkowo zawierać atrybuty reprezentujące nazwę miesiąca oraz numer kwartału roku.
Zadanie 2
Napisz procedurę(-y), które uzupełnią danymi wybraną tabelę faktów oraz jej tabele wymiarów. Wcześniej stwórz
odpowiednie tabele, które będą przechowywać fakty oraz wymiary. 
