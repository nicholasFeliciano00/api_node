# CRUD com Angular 8

### Front-End

1) Instalar os pacotes com o comando: (dentro da pasta `front`)

``` 
> npm install
```

2) Depois executar o seguinte comando para executar a aplicação (dentro da pasta `front`):

```
> ng serve -o
```

Depois bastam abrir o browser em **localhost:4200** (porta padrão de uma aplicação Angular)

### Back-End

1) Instalar os pacotes com o comando: (dentro da pasta `api`)

``` 
> npm install
```

2) Depois executar o seguinte comando para executar a aplicação (dentro da pasta `api`):

```
> nodemon
```

Depois bastam abrir o postamn em **localhost:8000** e testar as requisições

## Atualização Limpa para a versão atual do Angular 7:

Executar os passos abaixo:

1) Executar os comandos abaixo:

```
> npm cache verify
```

```
> npm install -g @angular/cli
``` 

2) Porém, se executou os comandos acima e não resolveu o problema, tenta executar os seguintes comandos abaixo:

```
> npm uninstall -g angular-cli (abrindo o Power Shell como Administrador)
> npm cache verify
> npm cache clean
> npm install -g @angular/cli@latest
> ng --version
```

3) Se mesmo assim depois de executar os passos acima, com o Power Shell executando como **Administrador** e você não conseguiu atualizar para o Angular 7, execute os seguintes comandos abaixo:

```
> ng update @angular/cli
> ng --version
```

4) Se tudo der certo (numa dessas 3 maneiras sempre vai dar). Sempre execute os comandos abaixo:

```
> npm cache verify
> npm cache clean (para versões antigas do npm)

