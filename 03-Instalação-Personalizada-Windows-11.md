# Instalação Personalizada do Windows 11

**Unidade Curricular 4 - SENAC**

> Documentação feita pelo professor José de Assis.

---

## Criação do Windows 11

Pré-requisitos:
- 8Gb RAM
- CPU com 4 núcleos
- (Se possível com HD ou SSD)

Baixar o criador de mídia de instalação do Windows 11.

Link: https://www.microsoft.com/pt-br/software-download/windows11

---

## Personalizando o Windows 11 para PCs que não tem os recursos obrigatórios

Após a escolha da versão do Windows, se aparecer a mensagem que não é possível instalar, voltar para a tela de escolha da versão e pressionar SHIFT + F10 para abrir o prompt de comando, digite `regedit`.

No registro do Windows, expandir:
1. HKey_Local_Machine
2. System
3. Setup

Selecionar o Setup com botão direito do mouse e criar uma chave de nome "LabConfig".

No lado direito (em branco) criar 5 Valor DWORD (32bits)

- ByPassTPMCheck  
- ByPassSecureBootCheck  
- ByPassRAMCheck  
- ByPassStorageCheck  
- ByPassCPUCheck  

Modificar os valores hexadecimal para 1

Fechar o registro do Windows e prosseguir.

---

## Instalação do Windows sem internet

Após a primeira reinicialização, depois da escolha do idioma e teclado dê SHIFT + F10 e digite `oobe\bypassnro`.
