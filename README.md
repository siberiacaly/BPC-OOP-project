# Projekt do předmětu BPC-OOP

## Zadání projektu

Cílem semestrální práce bylo vytvořit aplikaci v jazyce **C#** demonstrující principy **objektově orientovaného programování (OOP)**.
Tématem projektu je **filmová databáze / správa herců**. Aplikace umožňuje evidenci osob (herců, režisérů), správu filmových titulů a manipulaci s daty.
Důraz byl kladen na využití dědičnosti, polymorfismu, zapouzdření a práci se soubory.

---

## 1. Funkcionalita aplikace

Systém slouží jako evidence pro správu filmových tvůrců a děl. Uživatel může provádět operace nad databází, která je inicializována ze souboru.

**Hlavní funkce:**
- **Evidence osob:** Správa herců a režisérů (třídy dědící ze společného základu).
- **Práce s filmy:** Přiřazování herců k filmům, hodnocení a výpis informací.
- **Načítání dat:** Aplikace zpracovává vstupní textový soubor `gang.txt`, který obsahuje seznam herců/postav pro naplnění databáze.
- **Výpisy:** Filtrování osob a děl podle zadaných kritérií.

### Ukázka práce s daty:

Aplikace demonstruje parsování textového souboru:
> *Soubor `gang.txt` slouží jako externí zdroj dat (např. seznam obsazení), který se při startu načte do paměti objektů.*

---

## 2. Použité principy OOP

Projekt prakticky demonstruje klíčová paradigmata na příkladu filmového průmyslu:

* **Třídy a objekty:** Reprezentace entit jako `Film`, `Herec`, `Režisér`.
* **Dědičnost:** Vytvoření hierarchie, např. abstraktní třída `Osoba`, ze které dědí konkrétní profese.
* **Polymorfismus:** Využití virtuálních metod pro specifické chování (např. výpis detailů se liší pro herce a pro film).
* **Kolekce:** Použití `List<>` nebo `Dictionary<>` pro správu seznamů v paměti.

---

## Odkaz na kód

- [💾 Zdrojové kódy](./PROJEKT)

## Shrnutí funkcionality

- ✅ Objektový návrh v C# (.NET)
- ✅ Evidence filmů a herců
- ✅ Načítání a zpracování textových souborů (File I/O)
- ✅ Implementace vztahů mezi objekty (např. Film má seznam Herců)

---

## Použité platformy a technologie

- Jazyk: **C#**
- Prostředí: **Visual Studio**
- Technologie: **.NET Console Application**
- Koncepty: **OOP, String parsing, Collections**

---

> Projekt byl vypracován Tomášem Calábkem (ID: 237881) pro kurz **BPC-OOP** (Objektově orientované programování) na VUT FEKT.
