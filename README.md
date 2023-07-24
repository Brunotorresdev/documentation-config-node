# Configuração do Ambiente - Ubuntu

Este é um guia passo a passo para configurar o ambiente no sistema Ubuntu, incluindo a instalação do Node.js usando o NVM (Node Version Manager).

## Passo 1: Abrir o Terminal
Para iniciar o processo, abra o Terminal pressionando as teclas `CTRL + ALT + T`.

## Passo 2: Atualizar o Gerenciador de Pacotes APT
Antes de prosseguir, é importante garantir que o gerenciador de pacotes APT esteja atualizado. Digite o seguinte comando no Terminal e pressione Enter:

```bash
sudo apt update
```
## Passo 3: Instale as dependências necessárias para o NVM usando o seguinte comando:

```bash
sudo apt install curl
```
##Passo 4: Com as dependências instaladas, agora você pode baixar e instalar o NVM usando o comando curl. O seguinte comando instalará a versão mais recente do NVM:
  ```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/latest/install.sh | bash
```

## Passo 5: Para verificar se o NVM foi instalado corretamente, digite o seguinte comando:
  ```bash
nvm --version
```
## Passo 6: Agora que o NVM está instalado, você pode usar comandos como nvm install, nvm use e nvm run para gerenciar facilmente diferentes versões do Node.js em seu sistema Ubuntu. Por exemplo, para instalar a versão mais recente do Node.js, você pode executar:

  ```bash
nvm install node
```
## Passo 7: Para verificar se o node foi instalado corretamente, digite o seguinte comando:

  ```bash
node --version
```
