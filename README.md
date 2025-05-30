# Symulacja II tury wyborów prezydenckich 2025

Link do pobrania projektu z OneDrive: https://1drv.ms/u/c/5acb985c73202279/EWie-KcwuFNNovYSru2g53IB7jk1FnqcwaeQZtiyK4vHcw?e=aKFw7r
Link do danych źródłowych ze strony PKW: https://wybory.gov.pl/prezydent2025/data/csv/wyniki_gl_na_kandydatow_po_gminach_csv.1747645331.zip

📊 Ten projekt to mój autorski dashboard stworzony w Microsoft Power BI Desktop, który umożliwia symulację wyników II tury wyborów prezydenckich na podstawie rzeczywistych danych z I tury oraz założonych przepływów głosów między kandydatami.

## Co znajdziesz w tym repozytorium?  
- 📁 Link do pliku projektu Power BI (`.pbix`) z modelem danych i dashboardem  
- 📊 Link do danych źródłowych (wyniki I tury z PKW w formacie „one big table”)  
- 🧮 Przykładowe miary DAX do obliczania prognozowanych wyników  
- 📖 Instrukcje dotyczące wykorzystania i możliwości konfiguracji symulacji (frekwencja, przepływy elektoratów, nowi wyborcy)  
- 🖼️ Zrzuty ekranu pokazujące interfejs i przykładowe wizualizacje  

## Funkcjonalności  
- 📈 Modelowanie wyników II tury w oparciu o dane z I tury  
- 🔄 Możliwość modyfikacji przepływów wyborców między kandydatami  
- ✅ Uwzględnienie frekwencji wśród elektoratów  
- ➕ Dodanie nowych wyborców i ich rozkład głosów  
- 🎛️ Interaktywne wizualizacje pozwalające eksperymentować z różnymi scenariuszami  

## 🛠️ Co do naprawy przede mną? 
- ⚠️ Można ustawić 100% przepływu głosów dla obu kandydatów jednocześnie, co nie ma sensu w rzeczywistych scenariuszach.  
- 🔧 Suwak liczby nowych wyborców (0–10 mln) jest mało wydajny i nie udało mi się go jeszcze usprawnić.  

## Jak korzystać?  
1. 📂 Otwórz plik `.pbix` w Power BI Desktop  
2. 🎛️ Przeglądaj dashboard i eksperymentuj z ustawieniami przepływów oraz frekwencji  
3. 📊 Analizuj symulowane wyniki i porównuj z rzeczywistymi danymi

------------------------------------------------------------------------------------------------------------------------
# Simulation of the 2025 Presidential Election Second Round

Download link to the project from OneDrive: https://1drv.ms/u/c/5acb985c73202279/EWie-KcwuFNNovYSru2g53IB7jk1FnqcwaeQZtiyK4vHcw?e=aKFw7r

📊 This project is my original dashboard created in Microsoft Power BI Desktop, enabling simulation of the second round of presidential election results based on real data from the first round and assumed vote flows between candidates.

## What you’ll find in this repository:
📁 Link to the Power BI project file (.pbix) containing the data model and dashboard
📊 Link to the source data (1st round election results from PKW in a “one big table” format)
🧮 Sample DAX measures for calculating projected results
📖 Instructions on usage and configuration options for the simulation (turnout, voter flows, new voters)
🖼️ Screenshots showcasing the interface and example visualizations

## Features  
- 📈 Modeling second round results based on first round data  
- 🔄 Ability to modify voter flows between candidates  
- ✅ Inclusion of turnout among voter groups  
- ➕ Adding new voters and their vote distribution  
- 🎛️ Interactive visualizations to experiment with different scenarios  

## 🛠️ Known issues to fix  
- ⚠️ It’s possible to set 100% vote flow for both candidates simultaneously, which doesn’t make sense in real scenarios.  
- 🔧 The new voters slider (0–10 million) is inefficient and hasn’t been improved yet.  

## How to use?  
1. 📂 Open the `.pbix` file in Power BI Desktop  
2. 🎛️ Browse the dashboard and experiment with vote flow and turnout settings  
3. 📊 Analyze simulated results and compare with actual data  

