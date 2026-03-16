# Sistemas de Produção DESO

Editor visual de fluxogramas para sistemas hídricos da DESO.

## Como fazer o deploy (passo a passo)

### 1. Criar conta no GitHub (gratuito)
1. Acesse https://github.com e clique em **Sign up**
2. Crie sua conta com e-mail e senha

### 2. Criar repositório e subir o código
1. No GitHub, clique em **New repository** (botão verde)
2. Dê o nome: `deso-sistemas`
3. Deixe como **Public** e clique em **Create repository**
4. Na próxima tela, clique em **uploading an existing file**
5. Arraste **todos os arquivos e pastas** deste zip para a área de upload
6. Clique em **Commit changes**

### 3. Fazer o deploy na Vercel (gratuito)
1. Acesse https://vercel.com e clique em **Sign Up with GitHub**
2. Autorize a Vercel a acessar seu GitHub
3. Clique em **Add New Project**
4. Selecione o repositório `deso-sistemas`
5. Clique em **Deploy**
6. Aguarde ~2 minutos — seu app estará online!

### 4. Compartilhar o link
A Vercel vai gerar um link como:
`https://deso-sistemas-xxx.vercel.app`

Compartilhe esse link com quem você quiser para coletar feedback.

---

## Para atualizar o app no futuro
1. Edite os arquivos localmente (ou peça ao Claude para editar)
2. Vá ao repositório no GitHub
3. Clique no arquivo que quer atualizar → ícone de lápis (editar)
4. Cole o novo código → **Commit changes**
5. A Vercel faz o deploy automático em ~1 minuto ✅

---

## Estrutura do projeto
```
deso-app/
├── src/
│   ├── App.tsx       ← código principal do app
│   └── main.tsx      ← entrada do React
├── public/
│   └── favicon.svg   ← ícone da aba
├── index.html
├── package.json
├── vite.config.ts
└── tsconfig.json
```
