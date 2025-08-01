# 📊 CreditMetrics (PL)

> 📁 *Symulator ryzyka kredytowego portfela obligacji oparty na metodologii CreditMetrics (JP Morgan)*

---

## 🇵🇱 Wersja Polska

### 👨‍💻 Autor
- **Mateusz Strojek**  
- 🗓️ *Data utworzenia: 23 marca 2024*
- Projekt stworzony na przedmiot: Modelowanie ryzyka kredytowego i operacyjnego.
---

### 🧾 Zawartość repozytorium
- `Creditmetrics.html` – interaktywna aplikacja HTML/JavaScript (frontend-only)
- `README.md` – ten plik

---

### ⚙️ Funkcje i opis projektu

Aplikacja symuluje zmiany wartości portfela obligacji na podstawie zmian ratingów kredytowych, wykorzystując uproszczoną wersję metody **CreditMetrics**. Głównym celem jest oszacowanie ryzyka kredytowego poprzez obliczenie miar takich jak:

- **Value-at-Risk (VaR)**  
- **Expected Shortfall (ES)**

---

### 📥 Dane wejściowe (parametry głównej funkcji symulacyjnej):

- 📊 **Macierz korelacji ratingów** – opisuje współzależność pomiędzy obligacjami
- 🔁 **Macierz przejścia** – prawdopodobieństwo migracji między ratingami
- 🎲 **Liczba scenariuszy Monte Carlo** – np. 1000, 10000
- 🏦 **Ratingi początkowe** – np. AAA, BBB, BB
- 💰 **Stopy procentowe** – dopasowane do ratingów, używane przy dyskontowaniu
- 🧾 **Stopy odzysku (recovery rates)** – określają wartość odzyskaną w przypadku defaultu
- 📆 **Lata do wykupu** – czas życia każdej obligacji
- 💸 **Ceny wykupu (nominały)** – wartości końcowe obligacji
- 📈 **Kupony roczne** – oprocentowanie wypłacane co rok
- 🧮 **Typ obligacji** – bullet (pełna spłata na końcu) lub amortizing (częściowa spłata)
- ✅ **Poziom ufności (confidence level)** – np. 95% lub 99% (dla VaR i ES)


---

### 🚀 Uruchomienie

1. Pobierz repozytorium lub sam plik `Creditmetrics.html`
2. Otwórz plik w przeglądarce (Chrome, Firefox, Edge)
3. ✅ Gotowe — działa lokalnie, bez instalacji

---


## 🌐 English Version

### 👨‍💻 Author
- **Mateusz Strojek**  
- 🗓️ *Created: March 23, 2024*
- Project made during my studies, subject: Credit and operational risk modeling.
---

### 🧾 Repository Contents
- `Creditmetrics.html` – interactive HTML/JS frontend-only application
- `README.md` – this file

---

### ⚙️ Features & Project Description

This application simulates changes in a bond portfolio's value due to credit rating migration using a simplified version of **CreditMetrics (JP Morgan)**. It computes key credit risk measures:

- **Value-at-Risk (VaR)**  
- **Expected Shortfall (ES)**

---

### 📥 Input Parameters (main simulation function):

- 📊 **Rating correlation matrix** – correlation of credit events across bonds
- 🔁 **Transition matrix** – rating migration probabilities
- 🎲 **Number of Monte Carlo scenarios** – e.g. 1000, 10000
- 🏦 **Initial credit ratings** – e.g. AAA, BBB, BB
- 💰 **Interest rates** – per rating, used to discount cash flows
- 🧾 **Recovery rates** – used in case of default
- 📆 **Years to maturity** – bond lifetime
- 💸 **Redemption values** – face value of bonds
- 📈 **Coupon rates** – annual payments
- 🧮 **Bond types** – bullet (final payment) or amortizing (partial repayments)
- ✅ **Confidence level** – e.g. 95% or 99% for VaR / ES
- ⚠️ **Draw recovery value from distribution?** – boolean flag

---

### 🚀 How to Run

1. Download the repo or just the `Creditmetrics.html` file
2. Open it in a browser (Chrome, Firefox, Edge)
3. ✅ Done — no installation needed

---



🎓 Projekt edukacyjny — brak licencji komercyjnej  
🎓 Educational project — no commercial license included
