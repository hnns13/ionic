## Setup für Ionic Projekte

Grundpakete:
```
sudo apt install -y nodejs npm git
```

Globale Ionic Installation:
```
npm i -g @ionic/cli
```

Neues Ionic Projekt (React, leeres Template):
```
npx @ionic/cli@latest start testname blank --type=react --no-interactive
```

Starten der App (im Projektordner, wenn Ionic global installiert):
```
ionic serve
```

Starten der App (im Projektordner, wenn Ionic nicht global installiert):
```
npx ionic serve
```