# MediApp - Sistema de Gestão Médica

> Sistema completo para gerenciamento de consultórios médicos, facilitando o agendamento de consultas, organização de prontuários eletrônicos e administração de pacientes. Projeto desenvolvido originalmente para a disciplina de Programação II e aprimorado com arquitetura moderna e novas funcionalidades.

![Arquitetura do Sistema](docs/ConsultorioMedico-drawio.png)

## Funcionalidades Principais

- **Prontuário Eletrônico:** Registro detalhado do histórico clínico dos pacientes.
- **Geração de Documentos:** Emissão automática de receitas médicas em PDF.
- **Gestão de Pacientes:** Cadastro completo e busca eficiente de dados.
- **Autenticação Segura:** Sistema de login com criptografia e tokens JWT.
- **Interface Responsiva:** Design moderno construído com Next.js e Tailwind.

## Tecnologias Utilizadas

### Frontend

- **Framework:** Next.js 14
- **Linguagem:** TypeScript
- **Estilização:** Tailwind CSS, Bootstrap
- **Comunicação:** Axios

### Backend

- **Runtime:** Node.js
- **Framework:** Express
- **Banco de Dados:** MongoDB (Mongoose)
- **Autenticação:** JWT (JSON Web Tokens), Bcrypt
- **Testes:** Jest, MongoDB Memory Server
- **Arquivos:** Multer (Uploads), PDFKit (Geração de PDFs)

## Como Executar

### Pré-requisitos

- Node.js instalado
- MongoDB rodando localmente ou string de conexão configurada

### Passo 1: Clone o repositório

```bash
git clone https://github.com/vitoriapguimaraes/medicalRecord.git
```

### Passo 2: Configurar e Rodar o Backend

Navegue até a pasta do servidor:

```bash
cd backend
```

Instale as dependências:

```bash
npm install
```

Execute o servidor:

```bash
# Para iniciar normalmente
node index.js

# Ou para rodar os testes
npm test
```

### Passo 3: Configurar e Rodar o Frontend

Em um novo terminal, navegue até a pasta da interface:

```bash
cd frontend
```

Instale as dependências:

```bash
npm install
```

Execute o projeto em modo de desenvolvimento:

```bash
npm run dev
```

O frontend estará acessível em `http://localhost:3000`.

## Estrutura de Diretórios

```
/medicalRecord
├── backend/            # API Servidora (Node.js + Express)
│   ├── models/         # Modelos do Banco de Dados
│   ├── routes/         # Rotas da API
│   ├── services/       # Lógica de negócio
│   └── ...
├── frontend/           # Interface do Usuário (Next.js + Tailwind)
│   ├── src/            # Componentes e páginas
│   ├── public/         # Arquivos estáticos
│   └── ...
├── docs/               # Documentação técnica e assets
│   ├── ConsultorioMedico-drawio.png
│   └── Collections do Postman
└── README.md
```

## Status

🚧 Em desenvolvimento

> Veja as [issues abertas](https://github.com/vitoriapguimaraes/medicalRecord/issues) para sugestões de melhorias e próximos passos.

## Mais Sobre Mim

Acesse os arquivos disponíveis na [Pasta Documentos](https://github.com/vitoriapguimaraes/vitoriapguimaraes/tree/main/DOCUMENTOS) para mais informações sobre minhas qualificações e certificações.
