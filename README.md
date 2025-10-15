# 🎮 EPLAY - Loja de Jogos

Uma aplicação web moderna de e-commerce especializada em jogos, desenvolvida como projeto educativo durante o curso da EBAC (Escola Britânica de Artes Criativas e Tecnologia).

## 🚀 Sobre o Projeto

EPLAY é uma plataforma completa de venda de jogos digitais que oferece uma experiência de usuário fluida e moderna. O projeto foi desenvolvido com foco em boas práticas de desenvolvimento front-end, arquitetura componentizada e design responsivo.

### ✨ Funcionalidades

- 🏠 **Página Inicial**: Banner de destaque e seções de promoções e lançamentos
- 🎯 **Catálogo de Produtos**: Listagem completa de jogos com filtros
- 🔍 **Detalhes do Produto**: Página individual com galeria, descrição e informações
- 🛒 **Carrinho de Compras**: Sistema completo de carrinho com Redux
- 💳 **Checkout**: Formulário de finalização com validação e múltiplas formas de pagamento
- 📱 **Design Responsivo**: Interface adaptável para todos os dispositivos

## 🛠️ Tecnologias Utilizadas

### Core
- **React** - Biblioteca principal para construção da UI
- **TypeScript** - Superset JavaScript com tipagem estática
- **React Router DOM** - Roteamento e navegação entre páginas

### Estado e Dados
- **Redux Toolkit** - Gerenciamento de estado global
- **RTK Query** - Fetch de dados e cache automático
- **React Redux** - Conectar React com Redux

### Estilização
- **Styled Components** - CSS-in-JS com componentes estilizados
- **Design System** - Paleta de cores e componentes consistentes

### Formulários e Validação
- **Formik** - Gerenciamento de formulários
- **Yup** - Validação de esquemas
- **React Input Mask** - Máscaras para inputs

## 📁 Estrutura do Projeto

```
src/
├── components/          # Componentes reutilizáveis
│   ├── Banner/         # Banner principal com destaque
│   ├── Button/         # Botão customizado
│   ├── Card/           # Card container
│   ├── Cart/           # Carrinho de compras
│   ├── Footer/         # Rodapé
│   ├── Gallery/        # Galeria de imagens/vídeos
│   ├── Header/         # Cabeçalho e navegação
│   ├── Hero/           # Seção hero
│   ├── Loader/         # Indicador de carregamento
│   ├── Product/        # Card do produto
│   ├── ProductsList/   # Lista de produtos
│   ├── Section/        # Seção genérica
│   └── Tag/            # Etiquetas e badges
├── pages/              # Páginas da aplicação
│   ├── Home/           # Página inicial
│   ├── Categories/     # Categorias de jogos
│   ├── Product/        # Detalhes do produto
│   └── Checkout/       # Finalização da compra
├── services/           # Serviços e APIs
│   └── api.ts          # Configuração RTK Query
├── store/              # Configuração Redux
├── assets/             # Imagens e recursos estáticos
├── styles.ts           # Estilos globais e tema
└── routes.tsx          # Configuração de rotas
```

## 🔌 API e Endpoints

O projeto consome uma API REST com os seguintes endpoints:

- `GET /destaque` - Jogo em destaque
- `GET /promocoes` - Jogos em promoção
- `GET /em-breve` - Jogos em lançamento
- `GET /categorias` - Categorias disponíveis

**Base URL**: `https://api-ebac.vercel.app/api/eplay`

## 🎯 Recursos Educativos

Este projeto foi desenvolvido como parte do aprendizado em:

- **Arquitetura de Componentes React**
- **Gerenciamento de Estado com Redux**
- **Roteamento SPA com React Router**
- **Styled Components e CSS-in-JS**
- **Formulários e Validação**
- **Consumo de APIs REST**
- **TypeScript em projetos React**
- **Testes automatizados**
