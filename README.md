# TriagemPro AI ⚖️🤖

## Sistema Inteligente de Triagem Jurídica com Inteligência Artificial

O **TriagemPro AI** é uma plataforma moderna desenvolvida para auxiliar escritórios de advocacia na organização, análise e gerenciamento de demandas jurídicas.

Utilizando recursos de **Inteligência Artificial**, o sistema permite realizar uma triagem inicial de casos, analisar documentos, organizar informações de clientes e acelerar processos internos, reduzindo tarefas manuais e aumentando a produtividade dos profissionais jurídicos.

---

# 🚀 Visão Geral

O TriagemPro foi desenvolvido com uma arquitetura moderna, segura e escalável, preparada para atender escritórios de advocacia de diferentes tamanhos.

A plataforma oferece:

* Cadastro e gerenciamento de clientes
* Cadastro e acompanhamento de casos jurídicos
* Upload seguro de documentos
* Análise inteligente utilizando IA
* Dashboard administrativo
* Controle de usuários e permissões
* Proteção de dados conforme LGPD
* Histórico de atividades
* Estrutura preparada para expansão nacional

---

# 🧠 Inteligência Artificial

A camada de IA do TriagemPro auxilia profissionais jurídicos através de:

* Classificação automática de documentos
* Resumo inteligente de processos
* Identificação de informações importantes
* Organização de dados jurídicos
* Sugestão de próximos passos
* Análise inicial de demandas recebidas

A IA funciona como uma ferramenta de apoio ao advogado, aumentando eficiência sem substituir a análise profissional.

---

# 🏗️ Arquitetura do Sistema

## Backend

Tecnologias utilizadas:

* Node.js
* Express.js
* PostgreSQL
* JWT Authentication
* Sequelize/ORM
* Upload seguro de arquivos
* APIs REST

Responsável por:

* Regras de negócio
* Autenticação
* Gerenciamento de usuários
* Controle de clientes
* Processamento dos casos
* Integração com serviços externos

---

## Frontend

Tecnologias:

* React
* Vite
* JavaScript/JSX
* Interface responsiva

Responsável por:

* Dashboard
* Login
* Cadastro
* Visualização de processos
* Gerenciamento de documentos
* Experiência do usuário

---

## Infraestrutura

Ambiente preparado utilizando:

* Docker
* Docker Compose
* Nginx
* PostgreSQL Containerizado
* Variáveis de ambiente protegidas
* Deploy em nuvem

---

# 🔐 Segurança

O TriagemPro possui recursos voltados para proteção das informações jurídicas:

* Autenticação via JWT
* Controle de permissões
* Senhas protegidas com hash seguro
* Proteção contra ataques comuns
* Headers de segurança
* Validação de uploads
* Separação entre frontend e backend
* Boas práticas de proteção de dados

---

# 📜 LGPD

O sistema segue princípios da Lei Geral de Proteção de Dados:

* Consentimento do usuário
* Controle de acesso aos dados
* Proteção de informações sensíveis
* Armazenamento seguro
* Transparência no tratamento de dados
* Possibilidade de gerenciamento das informações pessoais

---

# 📂 Estrutura do Projeto

```
TriagemPro/

├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── routes/
│   │   ├── middleware/
│   │   ├── services/
│   │   └── config/
│   ├── Dockerfile
│   └── package.json
│
├── frontend/
│   ├── src/
│   ├── pages/
│   ├── components/
│   └── package.json
│
├── nginx/
│
├── postgres/
│
├── docker-compose.yml
│
└── README.md
```

---

# ⚙️ Instalação

## Pré-requisitos

Instale:

* Docker
* Docker Compose
* Node.js 22+

---

## Clonar projeto

```bash
git clone https://github.com/seu-repositorio/triagempro.git

cd triagempro
```

---

## Configurar variáveis de ambiente

Crie os arquivos:

```
backend/.env
frontend/.env
```

Exemplo:

```env
DATABASE_URL=postgres://usuario:senha@postgres:5432/triagempro

JWT_SECRET=sua_chave_segura

AI_API_KEY=sua_chave_ia
```

---

## Executar com Docker

```bash
docker compose up --build
```

---

# 🌐 Serviços

Após iniciar:

Frontend:

```
http://localhost:3000
```

Backend:

```
http://localhost:5000
```

Banco:

```
PostgreSQL
```

---

# 👥 Perfis de Usuário

## Administrador

* Gerenciar usuários
* Configurar sistema
* Visualizar relatórios

## Advogado

* Cadastrar clientes
* Criar casos
* Analisar documentos
* Utilizar IA

## Assistente

* Organizar informações
* Atualizar registros
* Auxiliar no fluxo operacional

---

# 📈 Roadmap

## Versão 1.0

✅ Cadastro de usuários
✅ Login seguro
✅ Clientes
✅ Casos jurídicos
✅ Upload de documentos
✅ Dashboard

## Versão 2.0

🔄 IA avançada para documentos
🔄 Integração com tribunais
🔄 Automação de tarefas
🔄 Relatórios inteligentes

## Versão 3.0

🔄 Marketplace jurídico
🔄 Aplicativo mobile
🔄 Expansão internacional

---

# 💼 Modelo de Negócio

O TriagemPro pode operar como:

* Assinatura mensal/anual para escritórios
* Licenciamento empresarial
* Implantação personalizada
* Solução SaaS jurídica

---

# 🏢 Desenvolvido por

**LHS Solutions**

Tecnologia, inovação e inteligência artificial aplicada ao setor jurídico.

---

# 📄 Licença

Este projeto possui direitos reservados.

Uso comercial, distribuição ou alteração somente mediante autorização.
