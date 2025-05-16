# Verifica Vincoli Idrogeologici

Applicazione per verificare la presenza di vincoli idrogeologici nella Regione Lazio.

## Struttura
- `public/index.html`: Frontend (GitHub Pages)
- `backend/proxy.php`: Backend PHP (Render)

## Configurazione
1. **Frontend**: 
   ```javascript
   fetch('https://tuo-backend.onrender.com/proxy.php', {
     method: 'POST',
     body: JSON.stringify({ lat: 41.89, lng: 12.48 })
   })
   ```

2. **Backend**:
   - Imposta `Access-Control-Allow-Origin` con il tuo dominio GitHub Pages
   - Variabili d'ambiente su Render:
     - `PHP_VERSION`: 8.1
     - `START_COMMAND`: `./start.sh`

## Link
- Demo: https://tuousername.github.io/verifica-vincoli
- Backend: https://verifica-vincoli-backend.onrender.com