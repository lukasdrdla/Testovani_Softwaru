## Testování pomocí Selenium

Tato část popisuje, jak spustit automatizované testy pro webové stránky pomocí Selenium. Testy jsou napsány v jazyce Python a používají Selenium WebDriver pro automatizaci prohlížeče.

## Testovací Sady
---
### TestSada_100 - Hlavní stránka
- **TestSada_FE-001 - Testování Front-End**
- **TestSada_FE-002 - Cookies**
  - `TestCase_FE-100` – Kontrola viditelnosti tlačítek cookies
  - `TestCase_FE-101` – Kontrola funkčnosti tlačítek cookies
- **TestSada_FE-003 – Navigační menu**
- **TestSada_FE-004 – Tlačítka navigačního menu**
  - `TestCase_FE-102` – Kontrola viditelnosti tlačítek navigačního menu
  - `TestCase_FE-103` – Kontrola funkčnosti tlačítek (přesměrování)
- **TestSada_FE-005 – Vyhledávací pole**
  - `TestCase_FE-104` – Kontrola viditelnosti vyhledávacího pole
  - `TestCase_FE-105` – Kontrola funkčnosti vyhledávacího pole
  - `TestCase_FE-106` – Kontrola relevance výsledků
- **TestSada_FE-006 – Uživatelské přihlášení**
- **TestSada_FE-007 – Registrace**
- **TestSada_FE-008 – Registrační formulář**
  - `TestCase_FE-107` – Kontrola viditelnosti registračního formuláře
  - `TestCase_FE-108` – Kontrola validace polí formuláře
  - `TestCase_FE-109` – Kontrola Registrace
- **TestSada_FE-009 – Přihlášení**
- **TestSada_FE-010 – Přihlašovací formulář**
  - `TestCase_FE-110` – Kontrola viditelnosti přihlašovacího formuláře
  - `TestCase_FE-111` – Kontrola validace polí formuláře
  - `TestCase_FE-112` – Kontrola Zapomenutí hesla
  - `TestCase_FE-113` – Kontrola tlačítka pro zobrazení hesla
  - `TestCase_FE-114` – Kontrola Přihlášení pro neexistující účet
  - `TestCase_FE-115` – Kontrola Přihlášení
- **TestSada_FE-011 – Odhlášení**
  - `TestCase_FE-116` – Kontrola odhlášení

---

### TestSada_FE-012 – Hledání prodejen
- `TestCase_FE-117` – Kontrola vyhledávání
- `TestCase_FE-118` – Kontrola vyhledávání podle polohy
- `TestCase_FE-119` – Kontrola Filtrování
- `TestCase_FE-120` – Kontrola zobrazení prodejen

---

### TestSada_FE-013 – Správa profilu
- **TestSada_FE-014 – Můj profil**
  - **TestSada_FE-015 – Moje údaje**
    - `TestCase_FE-121` – Kontrola úpravy osobních údajů
  - **TestSada_FE-016 – Moje adresy**
    - `TestCase_FE-122` – Kontrola vložení nové adresy
    - `TestCase_FE-123` – Kontrola validace dat
    - `TestCase_FE-124` – Kontrola úpravy existující adresy
    - `TestCase_FE-125` – Kontrola smazaní adresy
  - **TestSada_FE-017 – Můj newsletter**
    - `TestCase_FE-126` – Kontrola nastavení newsletteru

---

### TestSada_FE-018 – Moje oblíbené produkty
- `TestCase_FE-127` – Kontrola přidání oblíbených produktů
- `TestCase_FE-128` – Kontrola smazaní oblíbených produktů
- `TestCase_FE-129` – Kontrola zobrazení oblíbených produktů

---

### TestSada_FE-019 – Nákupní košík
- `TestCase_FE-130` – Kontrola přidání produktu do košíku
- `TestCase_FE-131` – Kontrola odstranění produktu z košíku
- `TestCase_FE-132` – Kontrola změny množství produktu v košíku
- `TestCase_FE-133` – Kontrola celkové ceny v košíku
- `TestCase_FE-134` – Kontrola možnosti přejít k platbě

---

### TestSada_FE-020 – Slider
- `TestCase_FE-135` – Kontrola obrázků
- `TestCase_FE-136` – Kontrola přesměrování
- `TestCase_FE-137` – Kontrola posouvání obrázků

---

### TestSada_FE-021 – Všechny kategorie
- `TestCase_FE-138` – Kontrola kategorií
- `TestCase_FE-139` – Kontrola funkčnosti odkazů (přesměrování)
- `TestCase_FE-140` – Kontrola obsahu kategorií

---

### TestSada_FE-022 – Nově v sortimentu
- `TestCase_FE-141` – Kontrola produktů
- `TestCase_FE-142` – Kontrola posouvání produktů
- `TestCase_FE-143` – Kontrola přesměrování produktu (na detailnější stránku)

---

### TestSada_FE-023 – Feedback
- `TestCase_FE-144` – Kontrola funkčnosti tlačítek (smajlíků)

---

### TestSada_FE-024 - Stáhnout aplikaci Moje dm
- `TestCase_FE-145` – Kontrola viditelnosti tlačítek
- `TestCase_FE-146` – Kontrola funkčnosti tlačítek (přesměrování)

---

### TestSada_FE-025 – Filtrovaní
- `TestCase_FE-147` – Kontrola filtrování podle kategorie
- `TestCase_FE-148` – Kontrola filtrování podle značky
- `TestCase_FE-149` – Kontrola filtrování podle barvy

---

### TestSada_FE-026 - UI/UX
- `TestCase_FE-150` – Kontrola favicon na stránce
- `TestCase_FE-151` – Kontrola rozložení elementů na stránce
- `TestCase_FE-152` – Kontrola Responzivity

---

### TestSada_200 – Stránka produktů
- **TestSada_FE-201 - Testování Front-End**
- **TestSada_FE-202 – Obrázky**
  - `TestCase_FE-210` – Kontrola obrázků produktu (zobrazení)
  - `TestCase_FE-211` – Kontrola posouvání
  - `TestCase_FE-212` – Kontrola přiblížení
- **TestSada_FE-203 – Recenze**
  - `TestCase_FE-213` – Kontrola zobrazení recenzí u produktů
  - `TestCase_FE-214` – Kontrola filtrování recenzí
- **TestSada_FE-204 – BuyBox**
  - `TestCase_FE-215` – Kontrola zobrazení BuyBoxu
- **TestSada_FE-205 – Přidání do košíku**
  - `TestCase_FE-216` – Kontrola zobrazení základní ceny
- **TestSada_FE-206 – Tlačítko pro úpravu množství**
  - `TestCase_FE-217` – Kontrola zvýšení a snížení množství
  - `TestCase_FE-218` – Kontrola maximální a minimální hodnoty množství
  - `TestCase_FE-219` – Kontrola tlačítka pro přidání produktu do košíku
- **TestSada_FE-207 – Ověřit dostupnost v prodejně dm**
  - `TestCase_FE-220` – Kontrola tlačítka ověření dostupnosti produktu
- **TestSada_FE-208 – Popis produktu**
  - `TestCase_FE-221` – Kontrola zobrazení více informací k produktu

---
