# 🪟 Windows 11 — Instalação e Configuração Passo a Passo

> Documentação criada a partir de atividades práticas em aula.
> O passo a passo pode ser aplicado tanto em máquina física
> quanto em ambiente de teste.

---

## 🎯 Objetivo

Realizar a instalação do Windows 11 e aplicar configurações
iniciais de desempenho, drivers e otimização do sistema.

---

## 💿 Instalação do Windows 11

### Etapas iniciais
- Iniciar a instalação do Windows 11
- Selecionar **Instalar o Windows**
- Aceitar os termos de licença
- Selecionar **Não tenho a chave do produto**
- Escolher a edição:
  - **Windows 11 Pro**
- Avançar

---

### Disco e Partição
- Selecionar **Disco inteiro**
- Avançar
- Iniciar a instalação

> Caso a tela fique preta durante o processo, reiniciar a máquina.

---

## 🌍 Configurações Iniciais do Sistema

### Região e idioma
- País: Brasil
- Teclado: **ABNT2**
- Pular segundo teclado (se solicitado)

---

### Nome do dispositivo
- Definir nome do computador: PC-1

---

### Tipo de uso
- Configurar como **uso corporativo**
- Avançar

---

### Conta de acesso
- Opção: **Ingresso no domínio**
- Nome do usuário: admin
- Senha: *(não definir senha)*
- Avançar

---

### Privacidade
- Não permitir localização
- Desativar opções não obrigatórias
- Avançar até concluir
- Aguardar instalação e atualizações iniciais

---

## 🔄 Atualizações do Sistema

### Windows Update
1. Abrir a barra de pesquisa
2. Buscar por: Windows Update
3. Atualizar **tudo** o que estiver disponível
4. Reiniciar se necessário

---

## 🧩 Instalação de Drivers

### Verificação de dispositivos
1. Abrir: Painel de Controle → Sistema e Segurança → Sistema
2. Acessar: Configurações avançadas do sistema → Hardware → Gerenciador de Dispositivos

---

### Atualização de drivers
- Utilizar um software auxiliar para identificar drivers faltantes
- Realizar a atualização completa
- Reiniciar o computador após a conclusão
- Desinstalar o software auxiliar após o uso

---

### Driver de vídeo
- Instalar o **driver de vídeo diretamente do fabricante da GPU**
- Após isso, seguir o uso normal do sistema

---

## ⚡ Configurações de Desempenho

### Informações do sistema
- Acessar: Este Computador → Botão direito no Disco Local (C:) → Propriedades
- Verificar:
  - CPU
  - Frequência (ex: 3,8 GHz)

---

### Plano de energia
1. Barra de pesquisa: Energia
2. Alterar configurações do plano
3. Desligar disco rígido: 0 minutos
4. Criar plano de energia
5. Selecionar: Alto desempenho

> Priorizar desempenho em todas as opções disponíveis.

---

## 🧹 Limpeza e Otimização

### Desinstalar programas desnecessários
- Painel de Controle → Programas → Desinstalar programas
- Menu Iniciar → Todos os aplicativos → Desinstalar o que não usa

---

### Limpeza de disco
1. Barra de pesquisa: Limpeza de disco
2. Selecionar o disco
3. Marcar todos os arquivos
4. Excluir

---

### Proteção do sistema
Painel de Controle → Sistema e Segurança → Sistema → Configurações avançadas → Proteção do sistema

- Configurar
- Excluir pontos existentes
- Desativar proteção

---

## 🚀 Inicialização e Serviços

### Gerenciador de Tarefas
- Aba **Inicialização**
- Desabilitar:
  - CAudio
  - FamApp
  - Microsoft Edge
  - Microsoft Teams

---

## 🎨 Ajustes Visuais e Interface

### Assistência remota
Painel de Controle → Sistema → Configurações avançadas → Remoto

- Desmarcar assistência remota

---

### Efeitos visuais
Configurações avançadas do sistema → Avançado → Desempenho → Configurações

- Selecionar **Ajustar para melhor desempenho**
- Desmarcar os 8 primeiros efeitos

---

### Memória virtual
Configurações avançadas do sistema → Avançado → Desempenho → Avançado

- Alterar
- Gerenciar
- Definir tamanho personalizado

---

### Personalização
- Configurações → Personalização → Cores
  - Desativar efeitos de transparência

- Configurações → Sistema → Multitarefas
  - Desativar ajuste de janelas

- Configurações da barra de tarefas:
  - Desativar Visão de Tarefas
  - Desativar Widgets
  - Ocultar Pesquisa

---

## 🌐 Navegador

- Preferir **Google Chrome** ao invés do Edge
- Definir Chrome como navegador padrão
- Configurações do Chrome: Desempenho → Memória → Máxima economia

---

## 📝 Observação Final

Este procedimento tem como foco:
- Melhor desempenho
- Menor consumo de recursos
- Ambiente limpo e funcional
