# 💎 Remaining Luxury — Marketplace de Moda de Luxo de Segunda Mão

> **Luxo que continua valendo.**

Projeto acadêmico desenvolvido para a disciplina de **Experiência Criativa** — PUCPR, 2026/1. Consiste em uma plataforma web completa (full stack) de **revenda de produtos e acessórios de altíssimo luxo**, acompanhada de um pitch de vendas apresentando o problema, o mercado e o modelo de negócio da solução.

---

## 📋 Sumário

- [O Problema](#-o-problema)
- [A Solução](#-a-solução)
- [Diferenciais Competitivos](#-diferenciais-competitivos)
- [Mercado](#-mercado)
- [Modelo de Negócio](#-modelo-de-negócio)
- [Roadmap de Tração](#-roadmap-de-tração)
- [Funcionalidades do Sistema](#-funcionalidades-do-sistema)
- [Tecnologias](#-tecnologias)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Como Executar](#-como-executar)
- [Usuários de Teste](#-usuários-de-teste)
- [Equipe](#-equipe)

---

## 😖 O Problema

Você tem uma peça de luxo parada no armário. As alternativas atuais para revendê-la são ruins:

- Na **OLX**, ela fica anunciada ao lado de um sofá usado — sem curadoria e sem passar confiança.
- No **Instagram**, a negociação é feita diretamente com desconhecidos, sem garantia de autenticidade e com bastante incerteza sobre pagamento e entrega.

Não existe hoje, no Brasil, um espaço pensado especificamente para o comprador e o vendedor de itens de altíssimo luxo.

## 💡 A Solução

A **Remaining
Luxury** é uma plataforma de revenda de produtos e acessórios de altíssimo luxo, oferecendo **segurança, autenticidade e confiança** para compradores e vendedores em cada negociação — unindo desejo, sustentabilidade e acessibilidade em uma jornada de compra imersiva e com design sofisticado, feita para o mercado *second-hand* de luxo.

### Os 3 pilares

| Pilar | Descrição |
|---|---|
| 🔒 **Confiança** | Chat direto e seguro entre usuários antes da compra, com suporte dedicado e humanizado da nossa equipe em todo o processo, garantindo transações totalmente rastreáveis. |
| ✅ **Verificação** | Vendedores submetidos a uma rigorosa análise de histórico, com selo dourado visível nos anúncios, assegurando a legitimidade e procedência premium de cada peça cadastrada. |
| ✨ **Experiência** | Jornada de compra imersiva e design sofisticado, unindo desejo, sustentabilidade e acessibilidade — pensada para o mercado second-hand de luxo. |

## 🥊 Diferenciais Competitivos

| Concorrente | Limitação |
|---|---|
| **Vestiaire Collective** | Feita para o mercado europeu — processo burocrático, suporte em inglês, não adaptada ao Brasil. |
| **Enjoei / OLX** | Marketplaces genéricos, que tratam uma bolsa Chanel da mesma forma que um tênis usado, sem curadoria de luxo. |

A Remaining Luxury nasce como uma alternativa **nacional**, **especializada em luxo** e com verificação de autenticidade como parte central da experiência.

## 📈 Mercado

- O mercado brasileiro de luxo de segunda mão movimentou **R$ 25 bilhões em 2024** e cresceu **18% em um único semestre**.
- O mercado global de revenda de luxo cresce **10% ao ano** — três vezes mais rápido que o mercado de luxo primário, com projeção de **US$ 360 bilhões até 2030**.
- O Brasil conta com mais de **100 mil brechós ativos**, já sendo um dos maiores mercados emergentes de revenda da América Latina.

## 💰 Modelo de Negócio

| Fonte de receita | Detalhes |
|---|---|
| **Comissão — 20%** | Cobrada sobre o valor de cada venda concluída. Zero custo para listar, zero mensalidade — o vendedor só paga quando a transação acontece. |
| **Visibilidade paga — R$ 199/mês** | Plano de destaque com posição privilegiada no catálogo, badge de vendedor premium e presença na seção de destaques da home. |
| **Autenticação premium** | Incluída na comissão: um especialista autentica fisicamente o item antes da venda, gerando selo de procedência no anúncio e garantia de originalidade ao comprador. |

## 🚀 Roadmap de Tração

| Fase | Iniciativas | Indicadores-alvo | Receita mensal projetada |
|---|---|---|---|
| **Lançamento** | Campanha com micro-influenciadores de moda | 500 usuários ativos · 50 vendedores verificados · 75 transações/mês · ticket médio R$ 2.500 | **R$ 37.500/mês** |
| **Crescimento** | Expansão para categorias de relógios e joias + sistema de lances | 2.000 usuários ativos · 200 vendedores verificados · 250 transações/mês · ticket médio R$ 3.500 | **R$ 175.000/mês** |
| **Escala** | Equipe própria de peritos físicos + parcerias com joalherias e influenciadores | 10.000 usuários ativos · 850 transações/mês · ticket médio R$ 5.000 | **R$ 510.000/mês** |

## ⚙️ Funcionalidades do Sistema

O sistema já está **funcional, testado e pronto para uso**, incluindo:

- 🔐 Autenticação de usuários com JWT (registro, login, sessão) e fluxo de **verificação de vendedor** com selo.
- 🛍️ Catálogo de produtos com **filtros**, destaques na home e itens relacionados.
- 🖼️ Upload de fotos dos produtos (JPEG/PNG/WEBP, até 5 imagens por anúncio).
- 💬 **Chat em tempo real** entre comprador e vendedor (conversas e mensagens).
- ❤️ Sistema de **favoritos**.
- ⭐ **Avaliações** de vendedores (reviews).
- 🛒 Carrinho de compras e **checkout**.
- 📦 Gestão de **pedidos** (criação, listagem e detalhe de pedido).
- 👤 Perfis públicos de usuário/vendedor.

## 🛠️ Tecnologias

**Frontend:**
React 19 + Vite · Tailwind CSS 4 · Zustand (state management) · React Router DOM 7 · React Hook Form + Zod (validação) · Axios · date-fns

**Backend:**
Node.js · Express 5 · MySQL 8.0 (via `mysql2`) · JWT (`jsonwebtoken`) · Bcrypt (`bcryptjs`) · Multer (upload de arquivos) · CORS · dotenv

## 🗂️ Estrutura do Projeto

```
ModadeLuxoFinalizado2/
├── modaluxo_completo.sql        # Script completo: cria banco, tabelas e dados de exemplo
├── frontend/                    # Aplicação React (Vite)
│   └── src/
│       ├── components/          # Componentes comuns, de layout e de features
│       ├── pages/                # Home, Catalog, ProductDetail, SellItem, Cart, Orders,
│       │                         # Profile, Login, Register, Messages, NotFound
│       ├── routes/               # Definição das rotas (AppRoutes.jsx)
│       ├── services/             # Camada de API (auth, produtos, pedidos, favoritos, etc.)
│       ├── store/                 # Estado global (auth, carrinho, tema) via Zustand
│       └── hooks/, config/, utils/, data/, styles/
└── backend/                     # API REST (Node.js + Express)
    └── src/
        ├── controllers/         # auth, produtos, pedidos, favoritos, reviews, conversas, usuários
        ├── routes/                # Endpoints REST correspondentes a cada controller
        ├── middlewares/          # Autenticação (auth.js) e validação de IDs
        ├── config/                # Conexão com o banco de dados (db.js)
        └── uploads/               # Imagens dos produtos enviadas pelos usuários
```

## ▶️ Como Executar

### Pré-requisitos
- Node.js 18 ou superior
- MySQL 8.0

### 1. Banco de dados
1. Abra o MySQL Workbench ou o terminal do MySQL.
2. Execute o arquivo `modaluxo_completo.sql` — ele cria o banco, as tabelas e já insere os dados de exemplo automaticamente.

### 2. Backend
```bash
cd backend
cp .env.example .env
```
Edite o `.env` e preencha:
- `DB_PASSWORD`: senha do seu MySQL local
- `JWT_SECRET`: qualquer string secreta (ex.: `minha_chave_secreta`)

```bash
npm install
npm run dev
```
O servidor sobe em **http://localhost:8000**.

### 3. Frontend
```bash
cd frontend
cp .env.example .env
npm install
npm run dev
```
O site abre em **http://localhost:3000**.

> ⚠️ **Importante:** o banco de dados precisa estar rodando antes de iniciar o backend, e o backend sempre deve subir **antes** do frontend. Os dois processos (frontend e backend) precisam ficar rodando ao mesmo tempo.

## 🧪 Usuários de Teste

| E-mail | Senha |
|---|---|
| isabela@modaluxo.com | 12345678 |
| fernanda@modaluxo.com | 12345678 |
| carolina@modaluxo.com | 12345678 |

## 👥 Equipe

| Integrante | Responsabilidade |
|---|---|
| **Ana Carolina Afonso Meiado** | Parte visual do website e experiência do usuário |
| **Ana Carolina Curi de Sales** | Segurança dos dados e parte técnica do website |
| **Anna Navarro** | Suporte técnico ao usuário em tempo real via chat |

---

*Projeto acadêmico — PUCPR, Experiência Criativa, 2026/1.*
