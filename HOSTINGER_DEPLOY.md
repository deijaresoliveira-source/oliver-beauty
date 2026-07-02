# Deploy Hostinger - Oliver Beauty

Configuração recomendada no app Node.js da Hostinger:

- Framework: Other
- Node.js: 20.x
- Install command: npm install
- Build command: npm run build
- Start command: npm start
- Entry file: dist/server/index.js
- Output directory: dist/client

O build foi ajustado para separar frontend e backend:

```
dist/client  -> arquivos do React/Vite
dist/server  -> servidor Express/API
```

Variáveis de ambiente devem ser cadastradas no painel da Hostinger, não no GitHub.
