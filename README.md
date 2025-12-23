# Site Oficial - Prosperidade FC

Projeto em React + Vite (compatível com Windows, Linux e macOS) e com layout responsivo para celular.

## Requisitos
- Node.js 18.18+ (recomendado Node 20+)
- npm

## Instalar e rodar
1. Abra a pasta do projeto no Visual Studio Code (ou “Open Folder” no Visual Studio).
2. No terminal, execute:
   - npm install
   - npm run dev
3. Abra o endereço que aparecer no terminal (normalmente http://localhost:3000).

## Gemini (prévia do jogo)
Para habilitar a prévia gerada por IA:
1. Copie `.env.local.example` para `.env.local`
2. Preencha `VITE_GEMINI_API_KEY` com sua chave.

> Observação: colocar a chave no front-end expõe a chave no navegador. Para produção, o ideal é mover isso para um back-end.
