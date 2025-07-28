# Micro-Saas

**Micro-Saas** é uma aplicação moderna desenvolvida com foco em arquitetura SaaS escalável, utilizando as melhores práticas de engenharia de software e tecnologias de ponta. Este projeto foi criado como parte da aula do **Sujeito Programador**, sendo totalmente refeito e aprimorado para fins de aprendizado, domínio de stack fullstack TypeScript e demonstração de habilidades avançadas em desenvolvimento web.

## Resumo Profissional

O Micro-Saas é uma plataforma que exemplifica o modelo de Software as a Service (SaaS) em microescala, permitindo fácil adaptação, customização e potencial expansão para múltiplos clientes (multi-tenancy). Toda a estrutura foi pensada para máxima manutenibilidade, segurança e performance, tornando-o um excelente ponto de partida para produtos SaaS reais.

## Principais Tecnologias Utilizadas

- **TypeScript** – Linguagem principal do projeto, garantindo tipagem estática e maior robustez no desenvolvimento fullstack.
- **Next.js** (presumido pelo padrão de projetos SaaS modernos e uso de TypeScript)
- **React** (presumido, pois normalmente utilizado com Next.js)
- **CSS3** – Customizações visuais e responsividade.
- **JavaScript** – Scripts de integração e utilitários.
- **APIs REST/GraphQL** – Para comunicação eficiente entre frontend e backend (ajustável de acordo com o foco do projeto).
- **Vercel** – Hospedagem e deploy contínuo ([Acesse o projeto online](https://micro-saas-alpha.vercel.app))
- **ESLint/Prettier** – Garantia de padrões de código e qualidade técnica.
- **Controle de versão GitHub** – Fluxo colaborativo e rastreamento completo das alterações.

## Estrutura do Projeto

A arquitetura segue o padrão de projetos escaláveis, com separação clara de responsabilidades:

```
Micro-Saas/
├── public/           # Arquivos estáticos e assets
├── src/
│   ├── components/   # Componentes reutilizáveis de UI
│   ├── pages/        # Rotas e páginas principais (Next.js)
│   ├── services/     # Serviços de API e integrações externas
│   ├── styles/       # Folhas de estilo (CSS/SCSS)
│   ├── utils/        # Funções utilitárias e helpers
│   └── ...           # Outras pastas conforme a necessidade
├── package.json      # Dependências e scripts NPM/Yarn
├── tsconfig.json     # Configuração do TypeScript
└── README.md         # Documentação do projeto
```

## Funcionalidades Principais

- Estrutura pronta para multi-tenancy (multi-clientes)
- Cadastro, autenticação e gerenciamento de usuários
- Painel administrativo intuitivo
- Consumo e exposição de APIs seguras
- Layout responsivo e adaptável a dispositivos móveis
- Facilidade de deploy contínuo (CI/CD) via Vercel

## Como Executar Localmente

1. **Clone o repositório**
   ```
   git clone https://github.com/EraldoOL/Micro-Saas.git
   ```
2. **Instale as dependências**
   ```
   npm install
   ```
3. **Configure as variáveis de ambiente**  
   (Crie um arquivo `.env.local` com as configurações necessárias)
4. **Inicie o servidor**
   ```
   npm run dev
   ```
5. **Acesse em:**  
   [http://localhost:3000](http://localhost:3000)

## Licença

Este projeto está licenciado sob a **MIT License**.

---
