# Google Integration


## Google OAUTH2

## Google Drive API 

## Deploy no HEROKU

**LINK HEROKU - [Google Drive](https://sasdrivetest.herokuapp.com/).**

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

**Opção 1: Faça o download do repositório** - [Download](https://github.com/oguilhermelima/Google-Integration/archive/master.zip)

Extraia o ZIP, e acesse **Google-Integration**

**Opção 2: Faça o clone pelo Git Bash**
```
git clone https://github.com/oguilhermelima/Google-Integration.git
```
Depois digite
```
cd Google-Integration
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
