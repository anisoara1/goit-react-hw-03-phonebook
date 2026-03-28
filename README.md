
# 📞 React Phonebook — Contact Management App

O aplicație React modernă pentru gestionarea contactelor, construită ca parte dintr-o serie de proiecte practice orientate spre consolidarea abilităților în React, componentizare, state management și interacțiunea cu localStorage.

🔗 **Demo Live:** https://anisoara1.github.io/goit-react-hw-03-phonebook/

---

## ✨ Funcționalități principale

- **Adăugare contacte** cu nume și număr de telefon.
- **Prevenirea duplicatelor** prin verificarea numelor existente.
- **Filtrare în timp real** a contactelor după nume.
- **Ștergere contacte** individuale.
- **Persistență locală** prin `localStorage` — datele rămân salvate după refresh.
- **Interfață simplă și intuitivă**, potrivită pentru utilizatori non-tehnici.
- **Componentizare curată** și separare logică a responsabilităților.

---

## 🛠️ Tehnologii utilizate

| Tehnologie | Rol |
|-----------|------|
| **React** | UI, componentizare, state management |
| **JavaScript (ES6+)** | logică aplicație |
| **CSS / Styled Components (dacă ai folosit)** | stilizare |
| **localStorage API** | salvarea datelor |
| **GitHub Pages** | hosting static |

---

## 📂 Structura proiectului

```
goit-react-hw-03-phonebook/
│── src/
│   ├── components/
│   │   ├── ContactForm/
│   │   ├── ContactList/
│   │   ├── Filter/
│   ├── App.jsx
│   ├── index.js
│── public/
│── package.json
│── README.md
```

---

## 🔍 Detalii despre implementare

### Gestionarea stării
Aplicația folosește `setState` (sau `useState` dacă ai migrat la hooks) pentru:

- lista de contacte
- filtrul de căutare

### Persistența datelor
Contactele sunt salvate automat în `localStorage`:

- la montarea aplicației, datele sunt încărcate
- la fiecare modificare, lista este rescrisă

### Validarea contactelor
Înainte de a adăuga un contact nou, aplicația verifică dacă numele există deja și afișează un mesaj de eroare.

---

## 📱 Responsive Design

Aplicația este optimizată pentru:

- telefoane mobile  
- tablete  
- desktop  

Layout-ul este simplu și clar, astfel încât utilizatorii să poată gestiona rapid contactele.

---

## 🎯 Obiectivul proiectului

Proiectul demonstrează:

- înțelegerea componentelor controlate
- gestionarea stării în React
- lucrul cu formulare
- persistența datelor în browser
- organizarea logică a componentelor
- implementarea unui flux CRUD simplu

Este un proiect excelent pentru a arăta recrutoriilor că stăpânești fundamentele React.

---

## 📬 Contact

- **GitHub:** https://github.com/anisoara1  
- **Live Demo:** https://anisoara1.github.io/goit-react-hw-03-phonebook/
