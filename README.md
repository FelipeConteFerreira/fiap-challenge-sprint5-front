# 🏥 EaseHC - Sistema de Agendamento Médico

## 📋 Sobre o Projeto

O **EaseHC** é uma aplicação web moderna desenvolvida para facilitar o agendamento de consultas médicas. O sistema oferece uma interface intuitiva e responsiva que permite aos usuários agendar, remarcar e cancelar consultas de forma rápida e eficiente.

## 🚀 Tecnologias Utilizadas

- **React 18.3.1** - Biblioteca para construção da interface
- **TypeScript 5.5.4** - Tipagem estática para JavaScript
- **Vite 5.4.1** - Build tool e servidor de desenvolvimento
- **TailwindCSS 3.4.9** - Framework CSS para estilização
- **React Router DOM 6.26.1** - Roteamento para SPA
- **React Hook Form 7.52.0** - Gerenciamento de formulários

## 🏗️ Arquitetura

O projeto segue uma arquitetura **Single Page Application (SPA)** com:

- **Componentização modular** para reutilização de código
- **Roteamento dinâmico** com React Router
- **Tipagem TypeScript** em todos os componentes
- **Design responsivo** com TailwindCSS
- **Hooks do React** para gerenciamento de estado

## 📱 Funcionalidades

### ✅ Implementadas
- **Agendamento de consultas** com validação de formulário e integração com API Java
- **Remarcação de consultas** existentes via API
- **Cancelamento de consultas** com integração ao backend
- **Listagem de consultas** carregadas da API
- **Visualização da equipe** com detalhes dos membros
- **FAQ interativo** com perguntas frequentes
- **Navegação responsiva** entre páginas
- **Design adaptativo** para diferentes dispositivos
- **Integração completa com backend Java** (API REST)

### 🎯 Hooks Utilizados
- `useState` - Gerenciamento de estado local
- `useEffect` - Efeitos colaterais e ciclo de vida
- `useNavigate` - Navegação programática
- `useParams` - Parâmetros de rota dinâmica

## 🎨 Design e Responsividade

O sistema foi desenvolvido com foco em:

- **Consistência visual** com paleta de cores definida
- **Responsividade completa** para todos os dispositivos:
  - 📱 Extra Small (xs) - < 640px
  - 📱 Small (sm) - 640px+
  - 💻 Medium (md) - 768px+
  - 🖥️ Large (lg) - 1024px+
  - 🖥️ Extra Large (xl) - 1280px+

## 🚀 Como Executar

### Pré-requisitos
- Node.js (versão 16 ou superior)
- npm 
- Backend Java rodando (veja [INTEGRACAO_API.md](./INTEGRACAO_API.md))

### Instalação
```bash
# Clone o repositório
git clone https://github.com/FelipeConteFerreira/SPRINT-FRONT.git

# Entre na pasta do projeto
cd easehc

# Instale as dependências
npm install

# Configure a URL da API (crie arquivo .env)
# Veja .env.example ou INTEGRACAO_API.md para mais detalhes
echo "VITE_API_BASE_URL=http://localhost:8080/easehc-api/api" > .env

# Execute o projeto em modo de desenvolvimento
npm run dev
```

### 🔗 Integração com Backend Java

Este projeto está integrado com a API Java. Para mais detalhes sobre a integração, consulte:
- [Documentação de Integração](./INTEGRACAO_API.md)

### Scripts Disponíveis
```bash
npm run dev      # Servidor de desenvolvimento
npm run build    # Build para produção
npm run preview  # Preview do build
```

## 📁 Estrutura do Projeto

```
src/
├── components/          # Componentes reutilizáveis
│   ├── Header.tsx      # Cabeçalho com navegação
│   ├── Footer.tsx      # Rodapé
│   ├── ChatFAQ.tsx     # FAQ interativo
│   ├── FormField.tsx   # Campo de formulário
│   ├── Hero.tsx        # Seção hero
│   ├── HowItWorks.tsx  # Como funciona
├── pages/              # Páginas da aplicação
│   ├── Home.tsx        # Página inicial
│   ├── Contact.tsx     # Agendamento
│   ├── Features.tsx    # Funcionalidades
│   ├── Team.tsx        # Equipe
│   ├── MemberDetail.tsx # Detalhes do membro
│   ├── Reschedule.tsx  # Remarcação
│   └── Cancel.tsx      # Cancelamento
├── data/               # Dados estáticos
│   └── team.ts         # Informações da equipe
├── types.ts            # Definições de tipos
└── App.tsx             # Componente principal
```

## 🎯 Objetivos do Projeto

Este projeto foi desenvolvido como parte do **3º Sprint** do curso de Front-End Design Engineering, seguindo rigorosamente os requisitos estabelecidos:

- ✅ Reestruturação de HTML em React + Vite + TypeScript
- ✅ Implementação de SPA com roteamento
- ✅ Componentização e modularidade
- ✅ Uso obrigatório de hooks específicos
- ✅ Validação de formulários com React Hook Form
- ✅ Estilização exclusiva com TailwindCSS
- ✅ Design responsivo e acessível
- ✅ Versionamento com Git/GitHub

## 👥 Equipe de Desenvolvimento

- **Integrantes**: Felipe Conte, Altamir Lima, Jonathan Moreira
- **Turma**: 1TDSR
- **Instituição**: FIAP

## 📝 Licença

Este projeto foi desenvolvido para fins educacionais como parte do curso de Front-End Design Engineering da FIAP.

---

**Desenvolvido pela equipe EaseHC**

## 💻 Links
link do repositorio: https://github.com/FelipeConteFerreira/SPRINT-FRONT.git
link vercel : https://vercel.com/felipe-conte-ferreiras-projects/fiap-challenge-sprint5-front
