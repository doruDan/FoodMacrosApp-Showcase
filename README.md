# FoodApp-Showcase

### 🚀 Status: Proiect în curs de dezvoltare (MVP)
Acest proiect reprezintă o aplicație web dezvoltată în limbajul **C#**, utilizând arhitectura **ASP.NET Core MVC**. Scopul aplicației este de a facilita accesul utilizatorilor la informații nutriționale precise, transformând date brute din baze de date globale în informații ușor de parcurs.

---

## 💡 Conceptul MVP (Minimum Viable Product)
În versiunea actuală, aplicația funcționează ca un motor de căutare nutrițional simplificat:
* **Interacțiune:** Utilizatorul introduce denumirea unui produs alimentar.
* **Răspuns instantaneu:** Aplicația procesează datele și afișează indicatorii esențiali:
    * 📝 **Descrierea completă** a produsului.
    * 🔥 **Numărul de calorii** (Kcal).
    * 💪 **Proteine**, **Fibre**, **Carbohidrați**.
    * 🥑 **Grăsimi** și **Zahăruri**.

<img width="2870" height="1646" alt="Captură de ecran 2026-05-10 180647" src="https://github.com/user-attachments/assets/170eedea-58fa-495f-b4a6-942cdec4193c" />
<img width="2850" height="1532" alt="Captură de ecran 2026-05-16 214959" src="https://github.com/user-attachments/assets/0fc3e22d-772f-4499-b240-eda1b6c6f793" />

Implementarea serviciului de interogare asincronă a API-ului extern, utilizând IHttpClientFactory pentru un management eficient al resurselor.

<img width="2844" height="1684" alt="Captură de ecran 2026-05-10 180621" src="https://github.com/user-attachments/assets/e643c77e-3f00-4f03-b9d0-711601596ba1" />
Controlerul MVC care gestionează fluxul de date între logica de business și interfața utilizatorului (View), asigurând o experiență fluidă.


## 🛠️ Detalii Tehnice
* **Limbaj:** C#
* **Arhitectura:** Model-View-Controller (MVC) - pentru o separare clară a logicii de business de interfața utilizatorului.
* **Sursa datelor:** Integrare cu API-ul **USDA FoodData Central** pentru acuratețe științifică.
* **Unelte:** Visual Studio 2022, .NET Core 10.0, JSON Deserialization.

## 📈 Plan de Dezvoltare
Proiectul este într-o fază activă de expansiune. Următoarele module planificate includ:
1. **Sistem de Filtrare Avansat:** Implementarea unei liste de sugestii multiple după introducerea denumirii, permițând utilizatorului să aleagă varianta exactă a produsului (ex: "Mere roșii" vs "Mere verzi").
2. **User History:** Salvarea căutărilor frecvente într-o bază de date SQL locală.
3. **Calcul de Macros:** Adunarea valorilor pentru o masă completă.

---

### 👨‍💻 Despre Dezvoltator
Sunt un elev la profilul **Umanist** (clasa a XII-a, IPLT „Academia Copiilor”) care crede în puterea interdisciplinarității. Această aplicație este rezultatul studiului autodidact în C# și dorința de a rezolva probleme practice prin tehnologie.

> *Notă: Din motive de securitate, acest repository public conține documentația și arhitectura proiectului. Codul sursă complet și cheile de acces API sunt gestionate într-un mediu privat.*
