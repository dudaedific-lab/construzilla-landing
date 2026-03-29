# CONSTRUZILLA Landing Page

Landing page profissional para plataforma de gestão de construção.

## 🚀 Deploy no Vercel (GRÁTIS)

### Opção 1: Deploy via GitHub (Recomendado)

1. **Crie um repositório no GitHub:**
   - Acesse https://github.com/new
   - Nome: `construzilla-landing`
   - Deixe como público
   - Clique em "Create repository"

2. **Faça upload do código:**
   ```bash
   # No terminal, dentro desta pasta:
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/construzilla-landing.git
   git push -u origin main
   ```

3. **Deploy no Vercel:**
   - Acesse https://vercel.com
   - Clique em "Add New Project"
   - Importe o repositório do GitHub
   - Clique em "Deploy"
   - Pronto! Seu site estará no ar em ~2 minutos

### Opção 2: Deploy direto via CLI

```bash
# Instale o Vercel CLI
npm i -g vercel

# Faça login
vercel login

# Deploy (dentro desta pasta)
vercel --prod
```

## 🛠️ Desenvolvimento Local

```bash
# Instalar dependências
npm install

# Rodar em modo desenvolvimento
npm run dev

# Build de produção
npm run build
```

## 📦 Estrutura

```
construzilla-landing/
├── src/
│   ├── App.jsx          # Componente principal
│   ├── main.jsx         # Entry point
│   └── index.css        # Estilos globais
├── public/
│   └── favicon.svg      # Ícone do site
├── index.html           # HTML base
├── package.json         # Dependências
└── vite.config.js       # Configuração Vite
```

## 🎨 Cores da Marca

- Background: `#0B1220`
- Primary (Yellow): `#FACC15`
- Cyan: `#22D3EE`
- Magenta: `#F472B6`

## 📱 Responsivo

O site é totalmente responsivo e funciona perfeitamente em:
- 📱 Mobile
- 💻 Tablet
- 🖥️ Desktop

## 🔗 Links

Todos os botões redirecionam para: https://canteiro-pro-next.lovable.app/
