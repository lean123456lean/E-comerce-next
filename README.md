GamerStore - E-commerce de Produtos para Gamers - mobile
Sobre o Projeto
GamerStore é uma plataforma de e-commerce voltada para a venda de periféricos de alta performance para gamers. O projeto foi desenvolvido com Next.js, uma poderosa estrutura de React que oferece recursos avançados como renderização no servidor (SSR) e geração de páginas estáticas (SSG).

Principais Funcionalidades
Catálogo de produtos com imagens, descrições e preços.
Carrinho de compras funcional.
Sistema de checkout simplificado.
Navegação otimizada e responsiva para dispositivos móveis e desktops.
Integração com métodos de pagamento.
Scripts Disponíveis
Os seguintes comandos podem ser usados para gerenciar o projeto:

npm run dev: Inicia o servidor de desenvolvimento.
npm run build: Cria o build para produção.
npm start: Inicia o servidor em modo de produção.
npm run lint: Executa o linter para encontrar e corrigir problemas no código.
Como Configurar e Executar o Projeto
Clone o repositório:

bash
Copiar código
git clone <URL_DO_REPOSITÓRIO>
cd gamerstore
Instale as dependências:

bash
Copiar código
npm install
Configure as variáveis de ambiente: Crie um arquivo .env.local na raiz do projeto e adicione as variáveis necessárias, como credenciais de banco de dados e chaves de API (exemplo: Stripe).

Inicie o servidor de desenvolvimento:

bash
Copiar código
npm run dev
Acesse a aplicação no navegador em:
http://localhost:3000

Estrutura de Arquivos
/pages:
Contém as páginas da aplicação (rotas automáticas do Next.js).

/index.js: Página inicial com destaques de produtos.
/product/[id].js: Página de detalhes de um produto.
/cart.js: Página do carrinho de compras.
/checkout.js: Página de checkout.
/components:
Componentes reutilizáveis, como cabeçalho, rodapé e cards de produtos.

/styles:
Arquivos de estilização, usando CSS Modules ou Tailwind CSS.

/lib:
Funções utilitárias, como integração com APIs e banco de dados.

/public:
Arquivos estáticos, como imagens dos produtos.

Tecnologias Utilizadas
Next.js: Framework principal do projeto.
React: Biblioteca para a construção de interfaces.
Tailwind CSS: Framework de estilização para design responsivo.
Stripe: Integração para pagamentos online.
Axios: Requisições HTTP para APIs.
MongoDB: Banco de dados para armazenar os dados dos produtos e pedidos.
Planejamento Futuro
Implementar área do cliente para histórico de pedidos.
Melhorar o SEO com otimizações avançadas do Next.js.
Adicionar suporte para diferentes métodos de envio.
Integração com APIs de recomendação de produtos.

![splash](https://github.com/user-attachments/assets/6363223a-8554-4554-b55a-d668ffed114e)


GamerStore - E-commerce Web
Sobre o Projeto
O GamerStore é um e-commerce moderno e responsivo desenvolvido com Next.js. Ele foi projetado para atender gamers que buscam periféricos de alta performance, como teclados, mouses, headsets e outros acessórios essenciais para elevar sua experiência de jogo.

Estrutura do Projeto
Scripts Disponíveis
npm run dev: Inicia o servidor de desenvolvimento na porta padrão (http://localhost:3000).
npm run build: Gera o build otimizado para produção.
npm run start: Inicia o servidor em modo de produção (após o build).
npm run lint: Executa o ESLint para encontrar e corrigir problemas no código.
Tecnologias Utilizadas
Principais
Next.js: Framework para renderização no servidor (SSR) e geração de páginas estáticas (SSG).
React: Biblioteca principal para a construção de interfaces.
Tailwind CSS: Framework utilitário para estilização responsiva e moderna.
Complementares
@tabler/icons-react: Ícones prontos para uso no React.
@gstore/core: Biblioteca personalizada (talvez usada para gerenciamento de estado ou lógica de negócio).
Desenvolvimento
TypeScript: Tipagem estática opcional.
ESLint: Linter para manutenção da qualidade do código.
Como Configurar e Executar o Projeto
Clone o repositório:

bash
Copiar código
git clone <URL_DO_REPOSITÓRIO>
cd frontend
Instale as dependências:

bash
Copiar código
npm install
Configure as variáveis de ambiente: Crie um arquivo .env.local na raiz do projeto e adicione as variáveis necessárias, como URLs de APIs, chaves de autenticação, entre outras.

Inicie o servidor de desenvolvimento:

bash
Copiar código
npm run dev
Acesse a aplicação no navegador: http://localhost:3000

Estrutura de Arquivos
/pages:
Diretório que contém as páginas principais do projeto (rotas do Next.js).

index.js: Página inicial.
/products/[id].js: Página de detalhes do produto.
/cart.js: Página do carrinho de compras.
/checkout.js: Página de finalização de compra.
/components:
Componentes reutilizáveis, como cabeçalho, rodapé, cards de produtos e botões.

/styles:
Diretório com os estilos do Tailwind CSS ou arquivos CSS adicionais.

/public:
Arquivos estáticos, como imagens e ícones.

/lib:
Funções utilitárias, como requisições à API e lógica de manipulação de dados.



GamerStore - Backend
Sobre o Projeto
O backend do GamerStore é uma API desenvolvida com NestJS, que fornece funcionalidades para gerenciar o e-commerce gamer. Ele inclui autenticação, gerenciamento de produtos, pedidos e integração com banco de dados utilizando Prisma.

Estrutura do Projeto
Scripts Disponíveis
npm run build: Compila o código TypeScript para JavaScript em dist/.
npm run start: Inicia o servidor em modo de produção.
npm run dev: Inicia o servidor no modo de desenvolvimento com monitoramento de mudanças.
npm run lint: Verifica e corrige automaticamente problemas de estilo de código usando ESLint.
npm run format: Formata o código com Prettier.
npm run test: Executa os testes unitários.
npm run test:watch: Executa os testes em modo de observação.
npm run test:debug: Executa os testes com suporte a debugging.
npm run test:e2e: Executa os testes end-to-end (E2E).
npm run prisma:seed: Executa o script de seed do Prisma para popular o banco de dados.
Tecnologias Utilizadas
Principais
NestJS: Framework Node.js para construir aplicações escaláveis e modulares.
Prisma: ORM para interação com o banco de dados relacional.
TypeScript: Linguagem para desenvolvimento com tipagem estática.
Bibliotecas
RxJS: Biblioteca para programação reativa.
Reflect-Metadata: Suporte à metaprogramação no TypeScript.
Testes
Jest: Framework para testes unitários e de integração.
Supertest: Biblioteca para testes HTTP.
Como Configurar e Executar o Projeto
Clone o repositório:

bash
Copiar código
git clone <URL_DO_REPOSITÓRIO>
cd backend
Instale as dependências:

bash
Copiar código
npm install
Configure o Banco de Dados:

Crie um arquivo .env na raiz do projeto com as seguintes variáveis (exemplo):
env
Copiar código
DATABASE_URL="postgresql://usuario:senha@localhost:5432/gamerstore"
Execute as migrações do Prisma para criar as tabelas:
bash
Copiar código
npx prisma migrate dev
Popule o Banco de Dados (opcional):

bash
Copiar código
npm run prisma:seed
Inicie o servidor em modo de desenvolvimento:

bash
Copiar código
npm run dev
Acesse a API na porta padrão: http://localhost:3000

Estrutura de Arquivos
/src: Contém o código-fonte do projeto.

/modules: Módulos organizados por funcionalidades (ex.: autenticação, produtos, pedidos).
/prisma: Contém o arquivo de esquema schema.prisma e o script de seed para popular o banco de dados.
/main.ts: Arquivo de entrada da aplicação.
/test: Contém os arquivos de testes unitários e E2E.

Funcionalidades Implementadas
Gerenciamento de Produtos: Adicionar, editar, remover e listar periféricos para gamers.
Autenticação: Registro e login de usuários com validação JWT.
Gerenciamento de Pedidos: Criação e acompanhamento de pedidos feitos no sistema.
Banco de Dados: Estrutura e manipulação de dados com Prisma e PostgreSQL.




