# Google Integration - OAUTH2
Projeto de teste com o OAUTH2 da Google

## Deploy no HEROKU

**LINK HEROKU - [Google Drive](https://google-integration.herokuapp.com/).**

## Deploy

### Python ###

Download e instalação da versão mais recente do Python

**Windows** - [Python](https://www.python.org/downloads/).

**Linux** - A maioria das distribuições linux já vem com python3 instalado.

### PIP ###

Agora, faça a instalação do Pip para Python 3

**Linux**
```
sudo apt-get install python3-pip
```

**Não é necessário a instalação do PIP no windows**

### Clone do repositório ###

**Opção 1: Faça o download do repositório** - [Download](https://github.com/oguilhermelima/google-integration-py/archive/master.zip)

Extraia o ZIP, e acesse **google-integration**

**Opção 2: Faça o clone pelo Git Bash**
```
git clone https://github.com/oguilhermelima/google-integration-py.git
```
Depois digite
```
cd google-integration
```

### Pacotes

Agora faça a instalação dos pacotes necessários para rodar a aplicação.

**Opção 1: No mesmo diretório do requiriments.txt execute:**

**Windows**
```
pip3 install -r requirements.txt
```

**Linux**
```
sudo pip3 install -r requirements.txt
```

### Exportar e rodar a aplicação

Por fim, para inicializar a aplicação, digite os comandos abaixo:

**Windows**
```
set FLASK_APP=app.py
```
```
flask run
```
**Linux**
```
export FLASK_APP=app.py
```
```
flask run
```

**Agora é só acessar a url http://127.0.0.1:5000/**
