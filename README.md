# 🏢 Real Estate Truth Check

![Project Status](https://img.shields.io/badge/Status-MVP-success)
![Tech Stack](https://img.shields.io/badge/Stack-Full%20Stack-blue)
![AI Power](https://img.shields.io/badge/AI-Google%20Gemini-orange)

**Real Estate Truth Check** je inteligentna web aplikacija dizajnirana da demistifikuje tržište nekretnina. Koristeći napredne AI modele (Google Gemini), aplikacija analizira oglase za stanove, "čita između redova", detektuje skrivene mane i računa "Truth Score" (ocenu iskrenosti) za svaki oglas.

Ovo nije samo scraper – ovo je **AI konsultant** koji štiti kupca od manipulativnog marketinga.

## 🚀 Glavne Funkcionalnosti

* **🔍 Automatizovana Analiza:** Trenutno povlačenje podataka (tekst + slike) sa *Halo Oglasa*.
* **🧠 AI Detektiv:** Integracija sa **Google Gemini 2.0 Flash** modelom za dubinsku analizu.
* **📊 Truth Score:** Algoritamska procena validnosti oglasa na skali od 0 do 100.
* **🚩 Red Flags Detekcija:** Automatsko izdvajanje sumnjivih stavki (npr. nedostatak cene, lažni opisi, neslaganje slika i teksta).
* **🎨 Moderan UI:** "Cyberpunk" dark-mode interfejs izgrađen u React-u sa Tailwind CSS-om.
* **🖼️ Galerija:** Prikaz relevantnih slika stana direktno u aplikaciji.

## 🛠️ Tehnologije (Tech Stack)

Projekat je izgrađen kao moderna **Full-Stack** aplikacija:

### Backend 🐍
* **Python 3.10+**
* **FastAPI** (High-performance API framework)
* **Google Generative AI SDK** (Gemini integracija)
* **BeautifulSoup4** (Web Scraping)

### Frontend ⚛️
* **React.js** (Vite build tool)
* **Tailwind CSS** (Utility-first styling)
* **Responsive Design** (Mobile-first pristup)

## 📸 Kako radi?

1.  **Unos:** Korisnik unese URL oglasa sa Halo Oglasa.
2.  **Scraping:** Backend asinhrono skida podatke i slike sa sajta.
3.  **AI Procesiranje:** Podaci se šalju LLM-u sa inženjerskim promptom koji traži nekonzistentnosti.
4.  **Rezultat:** Frontend prikazuje ocenu, presudu, mane i vrline u realnom vremenu.

## 🔮 Budući planovi

* [ ] Istorija pretrage i čuvanje omiljenih analiza.
* [ ] Poređenje cene kvadrata sa prosekom na lokaciji.
* [ ] Chrome Extenzija za direktnu analizu na sajtu oglasa.

---
*Developed by Aleksa Rakočević / Alerak Studio*
