# 📘 Git & GitHub — Anotações Essenciais

**Unidade Curricular 1 - SENAC**

> Anotações pessoais para uso com Git e GitHub.  
> Sem informações sensíveis (tokens, senhas ou dados privados).

---

## 🔐 Token de Acesso (GitHub)

Caminho:  
Perfil → Settings → Developer Settings → Personal Access Tokens → Tokens (Classic) → Generate new token (classic)

**Observações:**
- Definir um nome para o token (ex: Senac)
- Marcar as permissões necessárias
- Gerar o token e guardar em local seguro
- Nunca versionar tokens em repositórios

---

## ⚙️ Configurações Iniciais do Git

Fazer sempre que mudar de computador.

### 📂 Abrir o terminal
- Abrir a pasta Documentos
- Abrir o Git Bash ou terminal

### 🧑 Identidade do usuário
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@email.com"
```
### 🛠️ Configurações úteis
```bash
git config --global core.editor vim
git config --global merge.tool vimdiff
git config --global color.ui true
```
### 🔍 Verificar configurações
```bash
git config --list
```

---

## 🔄 Tipos de Clonagem

### 1️⃣ GitHub → GitHub
- Fork de repositórios
- Sem sincronização automática

### 2️⃣ GitHub ↔ Git (Local)
- Clonagem com sincronização
- Permite pull e push

---

## 📥 Clonando um Repositório

1. Acessar o repositório no GitHub
2. Clicar em Code <>
3. Copiar a URL do repositório
```bash
git clone https://github.com/usuario/repositorio.git
```
- Clonar preferencialmente na pasta Documentos
- Abrir a pasta clonada no VS Code

---

## 🧪 Fluxo Básico de Trabalho com Git

### 🔍 Ver status
```bash
git status
```
### ✏️ Parte 1 — Trabalhar no projeto
- Criar, editar ou excluir arquivos

### ➕ Parte 2 — Adicionar alterações
```bash
git add .
git status
```
### 📝 Parte 3 — Commitar alterações
```bash
git commit -m "Descrição das alterações"
git status
```
### 🚀 Parte 4 — Enviar para o GitHub
```bash
git push
```
### 🔄 Parte 5 — Sincronizar do GitHub
```bash
git pull
```
O repositório precisa estar clonado para usar git pull

---

## 🐧 Criar Repositório no Linux Mint

**Passo a passo:**
1. Criar o repositório no GitHub
2. Abrir o terminal na pasta Documentos
3. Clonar o repositório:
```bash
git clone LINK_DO_REPOSITORIO
```
4. Abrir a pasta no VS Code
5. Abrir o terminal do VS Code:
```nginx
Ctrl + J
```
### Configurar Git no VS Code (se necessário)
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@email.com"
```

---

## 📄 Atualizando o README ou Arquivos

Sempre que fizer alterações no VS Code:
```bash
git add .
git commit -m "Mensagem da alteração"
git push
```
Fazer autenticação com o GitHub quando solicitado.
