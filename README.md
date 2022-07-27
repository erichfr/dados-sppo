# Consumo de dados por API externa

Projeto em MVC PHP para consumo de dados em tempo real do sistema de ônibus da cidade do Rio de Janeiro


Exemplo de retorno:
```
Ordem: B10001
Latitude: -22,81456
Longitude: -43,1871
Data/Hora: 25-11-2020 19:30:09
Velocidade: 40
Linha: 298
```

## Instalação

Na raiz do projeto execute:
> composer install

## Configuração
Todos os arquivos de **configuração** e aplicação estão dentro da pasta *src*.

As configurações de Banco de Dados e URL estão no arquivo *src/Config.php*

É importante configurar corretamente a constante *BASE_DIR*:
> const BASE_DIR = '/**PastaDoProjeto**/public';

## Uso
Acessar a pasta *public* do projeto.

## Status
O projeto se encontra em fase de iniciação.<br>
O projeto está sendo desenvovido somente por mim.


