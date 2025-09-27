# Analiza trendów badań nad karotenoidami: likopen vs beta-karoten

## Opis projektu
Celem projektu jest porównanie trendów liczby publikacji naukowych w latach **2000–2025** dla dwóch karotenoidów:  
- **Likopenu (lycopene)**  
- **Beta-karotenu (beta carotene)**  

Analiza bazuje na wynikach wyszukiwania w bazie **PubMed** (publicznie dostępne źródło).  

---

## Dane źródłowe
Wyszukiwania wykonano w PubMed przy użyciu zapytań w polu **Title/Abstract**:

- `lycopene[Title/Abstract]`  
- `beta carotene[Title/Abstract]`

Liczba publikacji dla poszczególnych lat została pobrana ręcznie z PubMed i umieszczona w notebooku.  

🔗 Link do bazy PubMed: [https://pubmed.ncbi.nlm.nih.gov/](https://pubmed.ncbi.nlm.nih.gov/)

---

## Pliki w repozytorium
- **pubmed_trends_lycopene_vs_beta_carotene.ipynb** – notebook Jupyter z analizą danych i wizualizacjami  
- **README.md** – opis projektu  

---

## Metody
Analiza została wykonana w Pythonie (wersja 3).  
Użyte biblioteki:
- `pandas` – do obróbki danych  
- `matplotlib` – do wizualizacji trendów  

Etapy:
1. Wczytanie danych publikacyjnych dla obu karotenoidów (2000–2025).  
2. Stworzenie zbiorczego zestawienia liczby publikacji w czasie.  
3. Wizualizacja trendów na wykresach liniowych.  

---

## Wyniki
- **Beta-karoten**: znacznie większa liczba publikacji naukowych, szczególnie w latach 2000–2025.  
- **Likopen**: liczba publikacji jest istotnie mniejsza, ale stabilna – wykazuje rosnące zainteresowanie w ostatnich dekadach.  

---

## Rola Autorki
- Przygotowanie zapytań i zebranie danych z PubMed  
- Analiza i interpretacja wyników  
- Opracowanie notebooka w Pythonie  

---

## Identyfikacja projektu
- **Nazwa projektu**: Analiza trendów publikacji dotyczących likopenu i beta-karotenu w PubMed  
- **Okres realizacji**: 2025  
- **Źródło danych**: [PubMed](https://pubmed.ncbi.nlm.nih.gov/)  
