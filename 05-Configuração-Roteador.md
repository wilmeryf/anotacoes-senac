# 🌐 Configuração Básica de Roteador (Rede Local)

**Unidade Curricular 5 - SENAC**

> Anotações de aula prática sobre configuração de roteadores em rede local.  
> Conteúdo básico, voltado para testes, aprendizado e entendimento do funcionamento.

---

## 📡 Observações Iniciais

- Nenhuma rede sem fio vem aberta por padrão
- Sempre é necessário configurar **nome da rede (SSID)** e **senha**
- Cada roteador pode ter um endereço IP e credenciais diferentes

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

Abrir o Prompt de Comando (CMD)
- Pressionar `Win + R`
- Digitar `cmd`
- Enter

Comando:
```bash
ipconfig
```
Procurar pelo Gateway Padrão.

---

## 📍 Acessando o Roteador

1. Abrir o navegador
2. Digitar o endereço do gateway (ex: 192.168.0.1)
3. Pressionar Enter
4. Por usuário e senha padrão

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
