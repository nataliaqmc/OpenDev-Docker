# Servidor de desafios:

### Como inicializar o docker:
#### Criando um arquivo "users.csv":
Entre na pasta *src* com o comando:

    cd src
Dentro da pasta "src" crie um arquivo csv com **user, password, type** e sepois rode os comandos a seguir.

    sqlite3 quiz.db < quiz.sql
    python3 adduser.py
    cd ..
#### Para inicializar o docker, rode:
    docker build -t username/sd .
    docker run -p 8888:5000 username/sd

### O site estará aqui: https://127.0.0.1:8888

## Referencias:
    - https://docker-curriculum.com/
    - https://docs.docker.com/get-started/

