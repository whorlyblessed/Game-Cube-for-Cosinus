# 🎮 Cube Dash

Wykonal projekt: Valentyn Borysenko, Dmytro Kivshar 4D

## 📌 O projekcie

**Cube Dash** to dwuwymiarowa gra zręcznościowa stworzona przy użyciu technologii **HTML5, CSS3 oraz JavaScript** bez wykorzystania zewnętrznych silników gier.
Gracz steruje kostką, która automatycznie porusza się do przodu i musi omijać przeszkody, przechodząc kolejne poziomy o rosnącym poziomie trudności.

Projekt został w całości zrealizowany w jednym pliku HTML i zawiera:

* strukturę HTML,
* stylizację CSS,
* logikę gry napisaną w JavaScript.

---

# 🚀 Główne funkcje

## 🎯 Rozgrywka

* Automatyczny ruch postaci
* Skakanie za pomocą klawiatury lub dotyku ekranu
* System kolizji
* Licznik postępu poziomu
* Licznik śmierci gracza
* Ekran zwycięstwa po ukończeniu poziomu

---

# 🗺️ Poziomy

W grze zaimplementowano **3 unikalne poziomy**:

1. **The Basics**
2. **Split Paths**
3. **Gravity Core**

Każdy poziom zawiera:

* platformy,
* bloki,
* kolce,
* przeszkody o różnym poziomie trudności.

---

# ⚙️ Dodatkowe funkcje

## ✅ System checkpointów

Gracz może włączać lub wyłączać system punktów kontrolnych.

Po włączeniu:

* po śmierci postać odradza się bliżej miejsca zgonu.

---

## 🎨 Personalizacja postaci

W grze znajduje się osobne menu umożliwiające dostosowanie wyglądu kostki:

* wybór jednego z 3 skinów,
* zmiana koloru postaci,
* podgląd zmian w czasie rzeczywistym.

---

# 🛠️ Wykorzystane technologie

* **HTML5**
* **CSS3**
* **JavaScript**
* **Canvas API**

---

# 💻 Realizacja techniczna

W projekcie zaimplementowano:

* pętlę gry opartą na `requestAnimationFrame`,
* fizykę skoku i grawitacji,
* obracanie postaci,
* system kolizji,
* proceduralne generowanie tła,
* responsywność względem rozmiaru okna przeglądarki.

---

# 🖥️ Interfejs użytkownika

Projekt zawiera:

* menu główne,
* menu personalizacji,
* interfejs gry (HUD),
* ekran zwycięstwa.

Podczas gry wyświetlane są:

* postęp ukończenia poziomu,
* liczba śmierci,
* status checkpointów.

---

# 🎯 Cel projektu

Celem projektu było stworzenie w pełni funkcjonalnej gry przeglądarkowej przy użyciu możliwości JavaScript oraz HTML5 Canvas bez korzystania z gotowych silników gier.

---

# 📌 Podsumowanie

W rezultacie powstała funkcjonalna gra przeglądarkowa zawierająca:

* kilka poziomów,
* system przeszkód,
* interfejs użytkownika,
* personalizację postaci,
* system checkpointów.

Projekt prezentuje umiejętności pracy z:

* JavaScript,
* logiką gier,
* obsługą fizyki i animacji.

# 👨‍💻 Proces tworzenia projektu Cube Dash

## 📌 Informacje ogólne

Projekt **Cube Dash** został stworzony przez studentów:

* **Valentyn Borysenko**
* **Dmytro Kivshar**

Prace nad projektem były wykonywane wspólnie z podziałem obowiązków pomiędzy członków zespołu. Głównym celem projektu było stworzenie w pełni funkcjonalnej przeglądarkowej gry 2D przy użyciu HTML5 Canvas oraz JavaScript bez wykorzystania gotowych silników gier.

---

# 🧠 Etap planowania projektu

Na początku zespół wspólnie omawiał:

* koncepcję gry,
* gatunek projektu,
* styl graficzny,
* podstawowe mechaniki rozgrywki,
* strukturę poziomów,
* wygląd interfejsu użytkownika.

Po dyskusji zdecydowano się stworzyć dynamiczną grę zręcznościową inspirowaną Geometry Dash z własnym stylem oraz systemem poziomów.

---

# ⚙️ Podział obowiązków

## 👨‍💻 Valentyn Borysenko

Główne zadania:

* tworzenie logiki gry;
* implementacja ruchu postaci;
* realizacja fizyki skoku i grawitacji;
* programowanie kolizji z przeszkodami;
* stworzenie głównej pętli gry (`requestAnimationFrame`);
* implementacja systemu checkpointów;
* optymalizacja wydajności gry.

Dodatkowo Valentyn zajmował się:

* konfiguracją animacji,
* testowaniem mechanik,
* poprawianiem błędów w działaniu gry.

---

## 👨‍💻 Dmytro Kivshar

Główne zadania:

* projektowanie interfejsu gry;
* tworzenie menu oraz ekranów gry;
* stylizacja projektu przy użyciu CSS;
* implementacja systemu personalizacji postaci;
* konfiguracja wyświetlania postępu i statystyk;
* projektowanie poziomów i przeszkód.

Dodatkowo Dmytro zajmował się:

* opracowaniem części wizualnej projektu,
* doborem kolorystyki,
* tworzeniem interfejsu użytkownika (HUD),
* testowaniem wyglądu gry na różnych rozdzielczościach ekranu.

---

# 🛠️ Proces tworzenia projektu

Tworzenie projektu przebiegało w kilku etapach:

## 1️⃣ Utworzenie podstawowej struktury

Na początku została przygotowana struktura HTML projektu oraz podłączono Canvas API odpowiedzialne za renderowanie grafiki.

---

## 2️⃣ Implementacja mechaniki gry

Następnie zaimplementowano:

* system ruchu,
* skakanie,
* fizykę postaci,
* kolizje z obiektami.

---

## 3️⃣ Tworzenie poziomów

Kolejnym etapem było stworzenie kilku poziomów z różnorodnymi przeszkodami i stopniowo rosnącym poziomem trudności.

---

## 4️⃣ Projektowanie interfejsu

Zostały stworzone:

* menu główne,
* ekran zwycięstwa,
* interfejs wyświetlający postęp gry,
* menu personalizacji postaci.

---

## 5️⃣ Dodawanie dodatkowych funkcji

Na końcowym etapie zaimplementowano:

* system checkpointów,
* wybór skinów,
* zmianę koloru postaci,
* animacje obracania kostki,
* proceduralne tło.

---

# 🧪 Testowanie projektu

Po zakończeniu prac projekt był wielokrotnie testowany:

* sprawdzano stabilność działania,
* usuwano błędy,
* optymalizowano wydajność,
* poprawiano balans rozgrywki.

---

# 🎯 Efekt końcowy

W wyniku wspólnej pracy powstała w pełni funkcjonalna gra przeglądarkowa zawierająca:

* kilka poziomów,
* system przeszkód,
* interfejs użytkownika,
* personalizację postaci,
* system checkpointów,
* płynne animacje i fizykę.

Projekt pozwolił uczestnikom rozwinąć umiejętności związane z:

* programowaniem w JavaScript,
* wykorzystaniem HTML5 Canvas,
* pracą zespołową,
* projektowaniem mechanik gry,
* tworzeniem interfejsów oraz animacji.

