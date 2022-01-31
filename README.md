# IP6 Mission Wetter
Dieses Projekt wurde im Rahmen der Bachelor Thesis von Hannah Kühne & Tabea Eggler im Auftrag des Verkehrshaus Luzern im FS20 erstellt.

## Projektbeschrieb
https://www.fhnw.ch/plattformen/bachelor20/20FS_I4DS03/index.html

### lokale Nutzung:

**Frontend:**
`cd client` & `npm start`

**Backend:**

| Windows | macOS |
| ------ | ------ |
| `cd server` | `cd server`  |
| `python -m venv venv` | `python3 -m venv venv` | 
| `>venv\Scripts\activate` | `. venv/bin/activate` |
| `pip install -r requirements.txt` | `pip install -r requirements.txt` |
| `cd app` |  `cd app` |
| `flask run` | `flask run` |

**Run Unit-Tests:**
`cd server/app` & `python -m unittest test_app`
