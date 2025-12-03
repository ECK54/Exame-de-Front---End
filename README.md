# Sistema de Baralho - Exame Front-end / FIAP

## Descrição

Aplicação web para visualização e gerenciamento de um baralho completo de cartas, desenvolvida com Next.js.

## Como usar

### Passo 1: Instalar dependências

```bash
npm install
```

### Passo 2: Configurar ambiente

Adicione um arquivo `.env.local` na raiz do projeto:

```
AUTH_PASSWORD=senha_aqui
```

### Passo 3: Iniciar servidor

```bash
npm run dev
```

Abra o navegador em `http://localhost:3000`

## Funcionalidades principais

- Sistema de autenticação
- Visualização completa do baralho (52 cartas)
- Filtro por naipe (Copas, Ouros, Paus, Espadas)
- Função de embaralhar cartas
- Salvamento automático no localStorage
- Interface responsiva

## Tecnologias utilizadas

- Next.js 14
- React 18
- TypeScript
- CSS

## Produção

Para gerar a versão de produção:

```bash
npm run build
npm start
```

## Deploy

Deploy na Vercel: (link a ser adicionado)

