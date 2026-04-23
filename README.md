# 🏠 SpaceDomiciles 🚀

E se potessi comprare casa su Marte? SpaceDomiciles è una web app full-stack che simula proprio questo: un marketplace immobiliare interplanetario dove gli utenti possono esplorare pianeti e corpi celesti, scoprirne i dettagli e simulare l'acquisto di una proprietà spaziale — certificato incluso.

Il progetto nasce come lavoro di gruppo durante il corso **Boolean Web Developer**, e successivamente è stato riadattato come applicazione portfolio per mostrare competenze su frontend, backend e integrazione API REST.

---

## 🌍 Do you wanna try? 💻

Puoi provare l'app direttamente online:

- 🖥️ **Frontend** → [space-domiciles.vercel.app](https://space-domiciles.vercel.app)
- ⚙️ **Backend API** → [spacedomiciles-portfolio.onrender.com](https://spacedomiciles-portfolio.onrender.com)

---

## 🪐 Cosa puoi fare 🌌

- Sfogliare un catalogo dinamico di pianeti e sistemi solari
- Visualizzare informazioni dettagliate su ogni corpo celeste
- Aggiungere proprietà al carrello e simulare un acquisto
- Ricevere un certificato di proprietà spaziale
- Godere di un'interfaccia animata e tematizzata

---

## 🌳 Struttura del progetto 🌲

```
SpaceDomiciles/
│
├── frontend/
│   ├── src/
│   │   ├── Components/
│   │   ├── Pages/
│   │   └── Context/
│   ├── public/
│   │   └── img/
│   └── index.html
│
└── backend/
    ├── routers/
    ├── controllers/
    ├── models/
    └── app.js
```

---

## 🛠️ Tecnologie utilizzate 🧰

| Layer | Tecnologie |
|---|---|
| **Frontend** | React, Vite, JavaScript, CSS |
| **Backend** | Node.js, Express, MySQL2 |
| **Database** | TiDB Cloud (compatibile MySQL) |
| **Deploy** | Vercel · Render · TiDB Cloud |

---

## 💻 Installazione locale 🖥️

Hai bisogno di **Node.js** e di un database MySQL (o accesso a TiDB Cloud).

```bash
# 1. Clona la repository
git clone https://github.com/ClaudiaSgalippa/SpaceDomiciles.git
cd SpaceDomiciles

# 2. Avvia il backend
cd backend && npm install && npm start

# 3. In un altro terminale, avvia il frontend
cd frontend && npm install && npm run dev
```

## ✨ Il team 🌟

Sviluppato da cinque studenti Boolean:

[Claudia Sgalippa](https://github.com/ClaudiaSgalippa) · [Christian Zaboli Vedovi](https://github.com/christianzaboli) · [Daniel Di Fraia](https://github.com/Daniel-Di-Fraia) · [Alessandro Iacovelli](https://github.com/Aleiaco02) · [Stefano Sala](https://github.com/StefanoSalaa98)

> 🔗 Repository originale: [Aleiaco02/SpaceDomiciles](https://github.com/Aleiaco02/SpaceDomiciles)

---

## 📄 Licenza 📜

Questo progetto è distribuito a scopo didattico.
