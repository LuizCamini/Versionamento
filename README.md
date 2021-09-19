# Versionamento e Deploy

### Comandos PIP (Gerenciamento de pacotes para Python)

#### 1 - Instalar Pacote
```shell
pip install <nome do pacote>
```

#### 2 - Mostra todos os pacotes instalados
```shell
pip freeze > requeriments.txt
```

#### 3 - Instala todos os pacotes salvos em requirements.txt
```shell
pip install -r requirements.txt
```

#### 4 - URL principal repositorio de software para linguagem Python

<https://pypi.org/>



## Ambiente - Versionamento de Deploy

### Linux:

#### 1 - Criando o ambiente
```shell
python3 -m venv venv
```
#### 2 - Atualizando o ambiente coms as bibloptecas dp projeto
```shell
source ./venv/bin/activate
```

```shell
pip install -r requirements.txt
```

#### 3 -  Inserindo nova biblioteca

```shell
source ./venv/bin/activate
```

```shell
pip install <biblioteca>
```

```shell
pip freeze > requirements.txt
```

#### 4 -  Ativando Ambiente
```shell
source ./venv/bin/activate
```

#### 5 - Desativando ambiente
```shell
deactivate
```

### Windows:

#### 1 Criando o ambiente (utilizando o GIT BASH)
```shell
pwd (Identifica o caminho completo do diretorio)
```

```shell
python3 -m venv < caminho completo do diretorio > /venv
```

#### 2 Atualizando o ambiente com as bibliotecas do projeto
```shell
source ./venv/Scripts/activate
```

```shell
pip install -r requirements.txt
```

#### 3 Inserindo nova biblioteca
```shell
source ./venv/Scripts/activate
```

```shell
pip install < biblioteca >
```

```shell
pip freeze > requirements.txt
```

#### 4 Ativando o ambiente
```shell
source ./venv/Scripts/activate
```

#### 5 Desativando ambiente
```shell
deactivate
```


