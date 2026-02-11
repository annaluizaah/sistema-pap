# Sistema PAP - Gestão de Provas de Aptidão Profissional

## 📋 Descrição
Aplicação web para gerir e acompanhar as Provas de Aptidão Profissional (PAPs) realizadas pelos alunos do curso de Programador Informático.

## 🎯 Objetivos
- Centralizar a gestão e acompanhamento das PAPs
- Criar sistema com login de diferentes níveis de acesso (aluno, professor, coordenador)
- Permitir registo e atualização das PAPs pelos alunos
- Possibilitar avaliação e comentários dos professores
- Armazenar e visualizar relatórios, vídeos e notas
- Implementar gráficos e estatísticas
- Permitir exportação de relatórios em PDF/Excel

## 🛠️ Tecnologias
- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: PHP 7.4+
- **Banco de Dados**: MySQL 5.7+
- **Bibliotecas**: Chart.js (gráficos), PHPMailer (email)

## 📁 Estrutura do Projeto
```
sistema-pap/
├── config/              # Configurações
├── public/              # Arquivos públicos (CSS, JS, uploads)
├── src/
│   ├── controllers/     # Lógica de negócio
│   ├── models/          # Camada de dados
│   ├── views/           # Templates HTML/PHP
│   └── utils/           # Funções utilitárias
├── database/            # Scripts SQL
├── index.php            # Ponto de entrada
└── composer.json        # Dependências
```

## ✨ Funcionalidades Principais
### 🔐 Autenticação
- Login com diferentes perfis (aluno, professor, coordenador)
- Registro de novos utilizadores
- Recuperação de senha

### 📋 CRUD de PAPs
- Criar, ler, atualizar e eliminar PAPs
- Upload de relatórios, vídeos e código
- Acompanhamento de progresso

### 📊 Dashboard
- Estatísticas gerais (total de PAPs, relatórios, vídeos)
- Gráfico de progresso das PAPs
- Média de notas
- Comentários recentes

### 📥 Exportação
- Exportar relatórios em PDF
- Exportar dados em Excel

### 👥 Gestão de Utilizadores
- CRUD de utilizadores
- Atribuição de perfis
- Controle de acesso

## 🚀 Como Começar
1. Clone o repositório
2. Configure o banco de dados em `config/database.php`
3. Importe o schema: `database/schema.sql`
4. Acesse a aplicação no navegador

## 📝 Licença
Projeto educacional - IPS

## 👤 Autor
annaluizaah