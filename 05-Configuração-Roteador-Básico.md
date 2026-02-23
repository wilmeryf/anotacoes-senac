# 🌐 Configuração Básica de Roteador (Rede Local)

> Anotações de aula prática sobre configuração de roteadores em rede local.  
> Conteúdo básico, voltado para testes, aprendizado e entendimento do funcionamento.

---

## 📡 Observações Iniciais

- Nenhuma rede sem fio vem aberta por padrão
- Sempre é necessário configurar **nome da rede (SSID)** e **senha**
- Cada roteador pode ter um endereço IP e credenciais diferentes

---

## 🔍 Verificando Conexão com o Roteador

### Teste de ping
Exemplo de resposta:

Ping statistics for 192.168.0.1

Isso indica que o roteador está acessível na rede.

---

## 🔌 Conexão Física

1. Conectar o roteador à energia
2. Conectar o computador ao roteador:
   - Via **cabo de rede (Ethernet)** ou
   - Via **Wi-Fi padrão do roteador**
3. Caso necessário, desconectar o cabo de rede da internet externa
4. Usar o roteador apenas para rotear o PC (ambiente de teste)

---

## 🖥️ Verificando Configuração de Rede no Windows

### Abrir o Prompt de Comando (CMD)
- Pressionar `Win + R`
- Digitar `cmd` e pressionar Enter

### Comando:
```bash
ipconfig
```
- Procurar pelo Gateway Padrão

- Exemplo comum:

```nginx
Gateway Padrão . . . . . . . : 192.168.0.1
```

---

## 📍 Acessando o Roteador
1. Abrir o navegador

2. Digitar o endereço do gateway (ex: 192.168.0.1)

3. Pressionar Enter

---

## 🔑 Usuário e Senha Padrão
- Pesquisar na internet:

```pgsql
username password default + modelo do roteador
```
Exemplo:

```pgsql
username password default linksys wrt300n
```
Outras possibilidades:

- Informações na etiqueta embaixo do roteador

- Manual do fabricante

- Site oficial do fabricante

---

## 🧠 Identificação do Roteador
- Verificar o nome técnico / modelo

- Exemplo de roteador usado:

```
TP-Link AX3000
```

> Saber o modelo ajuda a encontrar:
>
> - **"IP padrão"**
>
> - **"Login e senha"**
>
> - **"Manual"**
>
> - **"Interface de configuração correta"**

---

## 🔐 Segurança Básica

### Alterações recomendadas:
- Alterar a senha padrão do roteador

- Evitar manter credenciais de fábrica

- Usar senha forte (mín. 8 caracteres)

---

## 📶 Configuração da Rede Wi-Fi
### Banda:
- 2.4 GHz

  - Maior alcance

  - Menor velocidade

### Configurações básicas:
- Nome da rede (SSID):

```nginx
GRUPO 3
```
- Senha da rede:

```scss
(definir senha segura)
```

---

## 🧪 Testes Finais
- Conectar o PC ou celular à rede Wi-Fi criada

- Testar conexão:

```bash
ping 192.168.0.1
```
- Verificar se o roteador está distribuindo IP corretamente

---

## 📘 Observação Final
Esta configuração foi realizada em aula prática, com foco em:

- Entender como um roteador funciona

- Acessar a interface administrativa

- Configurar rede local básica

- Realizar testes de conectividade
