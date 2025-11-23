# Nexo Futuro

<img width="1904" height="719" alt="image" src="https://github.com/user-attachments/assets/035504d2-3ff6-4cb5-94de-f376d2623f69" />

## 📋 Sobre o Projeto

O **Nexo Futuro** é uma aplicação web moderna desenvolvida como parte da disciplina de Front-End Design Engineering. Trata-se de uma Single Page Application (SPA) construída com React, Vite e TypeScript, seguindo princípios de arquitetura modular e componentização.

## 🎯 Objetivo

Desenvolver uma aplicação front-end que se integre perfeitamente com a API desenvolvida na disciplina de Domain Drive Design Using Java, proporcionando uma experiência de usuário coesa e responsiva em todos os dispositivos.

## 🚀 Tecnologias Utilizadas

- **React** - Biblioteca para construção da interface
- **Vite** - Build tool e dev server
- **TypeScript** - Superset JavaScript com tipagem estática
- **Tailwind CSS** - Framework CSS utilitário
- **React Router** - Gerenciamento de rotas
- **React Hot Toast** - Sistema de notificações

## 📁 Estrutura do Projeto
nexo-futuro/

├── public/

│ ├── images/ # Imagens e ícones

├── src/

│ ├── components/ # Componentes reutilizáveis

│ ├── pages/ # Páginas da aplicação

│ │ ├── Home/

│ │ ├── Integrantes/

│ │ ├── Sobre/

│ │ ├── FAQ/

│ │ └── Contato/

│ ├── router/ # Configuração de rotas

│ ├── services/ # Integração com APIs

│ ├── types/ # Definições TypeScript

│ ├── App.tsx

│ ├── main.tsx

│ └── index.css

├── package.json

├── tailwind.config.js

├── tsconfig.json

├── vite.config.ts

└── README.md

text

## 🖼️ Screenshots do Projeto

### Tela Principal
<img width="817" height="916" alt="image" src="https://github.com/user-attachments/assets/670e9c5f-b7b4-448e-8ce9-d25885f8d322" />

### Página de Integrantes
<img width="1903" height="605" alt="image" src="https://github.com/user-attachments/assets/a21bd40b-b249-4bbd-a4e8-2e78f7daf2d6" />

### Layout Responsivo
<img width="377" height="816" alt="image" src="https://github.com/user-attachments/assets/92ba5deb-3d5a-47fc-b377-66628fcd2752" />

## 🛠️ Configurações

- **TypeScript**: Configurado com tipagem estrita
- **Vite**: Build otimizado e hot reload
- **Tailwind CSS**: Estilização utilitária e responsiva
- **ESLint**: Análise estática de código

## 📦 Dependências Principais


{
  "react": "^18.2.0",
  "react-dom": "^18.2.0",
  "typescript": "^5.2.0",
  "vite": "^5.0.0",
  "tailwindcss": "^3.3.0",
  "react-hot-toast": "^2.4.1"
}


🏃‍♂️ Como Executar
Pré-requisitos
Node.js (versão 16 ou superior)

npm, yarn ou pnpm

Instalação e Execução
Clone o repositório

bash
git clone <url-do-repositorio>
cd nexo-futuro
Instale as dependências

bash
npm install
# ou
pnpm install
# ou
yarn install
Execute em modo desenvolvimento

bash
npm run dev
# ou
pnpm run dev
# ou
yarn dev
Acesse a aplicação

text
http://localhost:5173
Build para Produção
bash
npm run build
# ou
pnpm run build
# ou
yarn build

🌐 Deploy
O projeto está implantado na Vercel e pode ser acessado através do link:

🔗 URL de Produção: [https://nexo-futuro.vercel.app](http://localhost:5173/)

🔗 Integração com API
A aplicação consome a API desenvolvida na disciplina de Domain Drive Design Using Java, seguindo as melhores práticas de consumo de APIs RESTful.

Endpoints Implementados
GET /api/resources - Listar recursos

POST /api/resources - Criar recurso

PUT /api/resources/:id - Atualizar recurso

DELETE /api/resources/:id - Excluir recurso

Tratamento de Erros
Mensagens de erro personalizadas

Loading states durante requisições

Validação de dados de entrada

📱 Responsividade
A aplicação é totalmente responsiva, utilizando Tailwind CSS para adaptar o layout aos seguintes breakpoints:

Breakpoint	Tamanho	Dispositivo
xs	< 640px	Mobile
sm	640px - 767px	Tablet Pequeno
md	768px - 1023px	Tablet
lg	1024px - 1279px	Laptop
xl	1280px+	Desktop

👥 Integrantes do Projeto
Nome	RM	Turma	Contribuição
Gustavo Cordeiro de Souza  RM: 565514  Turma: 1TDSPO - Front-end, Integração API, Roteamento
Pedro dos Anjos Viana Moraes	RM: 563832	Turma: 1TDSPO - Design, Componentes, Deploy

📊 Versionamento
GitHub
🔗 Repositório: https://github.com/seu-usuario/nexo-futuro <!-- Substitua pelo link real -->

Commits por Integrante
[Pedro dos Anjos Viana Moraes]: 1

Total: 1

🎥 Vídeo de Apresentação
📺 Assista ao vídeo no YouTube: Link do Vídeo <!-- link  -->

📞 Contato
Para mais informações sobre o projeto, entre em contato através do [formulário de contato] na aplicação

🎯 Funcionalidades Implementadas
✅ Requisitos Atendidos
React + Vite + TypeScript

Roteamento estático e dinâmico

Tipos TypeScript avançados

Estilização com Tailwind CSS

Design responsivo

Integração com API Java

Deploy na Vercel

Versionamento no GitHub

Páginas obrigatórias (Home, Integrantes, Sobre, FAQ, Contato)

🚀 Funcionalidades Técnicas
Single Page Application (SPA)

Componentização modular

Tipagem estática com TypeScript

Gerenciamento de estado

Tratamento de erros

Loading states

Notificações toast
