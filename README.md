# 🚀 SOS Connect - Frontend Web

[![React](https://img.shields.io/badge/React-19.2.5-blue.svg)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-~6.0.2-blue.svg)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-^8.0.10-yellow.svg)](https://vitejs.dev/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-^4.2.4-blue.svg)](https://tailwindcss.com/)
[![Leaflet](https://img.shields.io/badge/Leaflet-^1.9.4-green.svg)](https://leafletjs.com/)

Uma plataforma web moderna para conectar pessoas em situação de vulnerabilidade com unidades de apoio, doações e missões de resgate. Desenvolvida com tecnologias de ponta para uma experiência fluida e responsiva.

## ✨ Funcionalidades

- 🔐 **Autenticação**: Sistema seguro de login e gerenciamento de usuários
- 🏢 **Unidades de Apoio**: Cadastro e gerenciamento de instituições de suporte
- 💰 **Doações**: Plataforma para criar e gerenciar campanhas de doação
- 🎯 **Missões**: Organização de missões de resgate e apoio comunitário
- 📍 **Mapas Interativos**: Integração com Leaflet para localização geográfica
- 📱 **Interface Responsiva**: Design adaptável para desktop e mobile
- 🔔 **Notificações**: Sistema de toast para feedback ao usuário
- 📊 **Dashboard**: Painéis para monitoramento de candidaturas e atividades

## 🛠️ Tecnologias Utilizadas

### Frontend
- **React 19** - Biblioteca para construção de interfaces
- **TypeScript** - Tipagem estática para JavaScript
- **Vite** - Ferramenta de build rápida e moderna
- **TailwindCSS** - Framework CSS utilitário
- **React Router DOM** - Roteamento para aplicações React
- **Leaflet & React-Leaflet** - Mapas interativos
- **Axios** - Cliente HTTP para requisições API
- **React Toastify** - Notificações elegantes
- **Phosphor React** - Ícones modernos

### Ferramentas de Desenvolvimento
- **ESLint** - Linting e formatação de código
- **TypeScript ESLint** - Regras específicas para TypeScript

## 📦 Instalação

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/sos-connect-frontend.git
   cd sos-connect-frontend/frontend-web
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```

3. **Configure as variáveis de ambiente:**
   Crie um arquivo `.env` na raiz do projeto com as configurações necessárias (ex: URL da API).

4. **Execute o projeto em modo desenvolvimento:**
   ```bash
   npm run dev
   ```

5. **Acesse a aplicação:**
   Abra [http://localhost:5173](http://localhost:5173) no seu navegador.

## 🚀 Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Compila o projeto para produção
- `npm run lint` - Executa o linter para verificar o código
- `npm run preview` - Visualiza a build de produção localmente

## 📁 Estrutura do Projeto

```
frontend-web/
├── public/                 # Arquivos estáticos
│   └── icons/             # Ícones da aplicação
├── src/
│   ├── assets/            # Imagens e recursos
│   ├── components/        # Componentes reutilizáveis
│   │   ├── Header/        # Cabeçalho da aplicação
│   │   ├── Sidebar/       # Barra lateral
│   │   ├── Map/           # Componente de mapa
│   │   └── ...            # Outros componentes
│   ├── contexts/          # Contextos React (ex: Auth)
│   ├── pages/             # Páginas da aplicação
│   │   ├── Home/          # Página inicial
│   │   ├── Login/         # Página de login
│   │   ├── SupportUnits/  # Unidades de apoio
│   │   └── ...            # Outras páginas
│   ├── routes/            # Configuração de rotas
│   ├── services/          # Serviços (API calls)
│   └── utils/             # Utilitários
├── package.json           # Dependências e scripts
├── vite.config.ts         # Configuração do Vite
└── tsconfig.json          # Configuração TypeScript
```

## 🎨 Design System

O projeto utiliza **TailwindCSS** para estilização, garantindo:
- Design responsivo e moderno
- Componentes consistentes
- Tema customizável
- Performance otimizada

## 🤝 Contribuição

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

**SOS Connect** - Conectando vidas, salvando vidas! 💙