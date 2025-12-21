# Pagina con download - Istruzioni

File creati:
- [index.html](index.html)
- [styles.css](styles.css)
- [document.pdf](document.pdf)

Come testare in locale (PowerShell con Python 3):

```powershell
cd "C:/Users/sara9/Documents/Sara/UNIVERSITA' PEGASO/Tesi/ProjectWork"
python -m http.server 8000
```

Apri nel browser: `http://localhost:8000/index.html`

Alternative con `http-server` (Node.js):

```powershell
npm install --global http-server
http-server -p 8000
```

Note:
- L'attributo `download` nell'`<a>` forza il download del file quando supportato dal browser.
- Sostituisci `document.pdf` con il tuo file reale nella stessa cartella del progetto.