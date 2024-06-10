# ReadME dedicado a facilitar o setup de novos ambientes de desenvolvimentos.

Para atualizar a lista de pacotes disponveis:
```
sudo apt-get updated
```

Para baixar e instalar a lista de pacotes disponveis:
```
sudo apt-get upgrade
```

## PYENV:

### Setup do Pyenv:

```
sudo apt update; sudo apt install build-essential libssl-dev zlib1g-dev \
libbz2-dev libreadline-dev libsqlite3-dev curl \
libncursesw5-dev xz-utils tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev
```

### README para instalação do Pyenv:
https://github.com/pyenv/pyenv?tab=readme-ov-file#installation

## GITHUB

Gerando uma nova chave SSH:

```
ssh-keygen -t ed25519 -C "your_email@example.com"
```

Após gerar a nova chave SSH, acessar a pasta .ssh e copiar a chave .pub gerada:

```
cd ~/.ssh/
```
