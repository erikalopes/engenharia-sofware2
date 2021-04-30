![CI](https://github.com/erikalopes/engenharia-sofware2/workflows/CI/badge.svg?branch=main)

# Projeto Github Actions

## Tarefas a serem implementas no CI

- [x] fazer o checkout do projeto no CI
- [x] fazer a configuração do ambiente (versaão do node e instalação das dependencias)
- [x] executar os testes
- [x] quando enviado para o master, fazer o build do projeto
- [x] disponibilizar o relatorio de cobertura de testes e build ao fim do workflow
- [x] quando enviado para o master, fazer a implantação do projeto do projeto no [link](http://ci-erikalopes-es.surge.sh/)

## Scripts Disponíveis

Na raiz do projeto você poderá executar:

### `npm start`

Para executar a aplição em modo de desenvolvimento.\
Acesse [http://localhost:3000](http://localhost:3000) para visualizar no navegador.

A página deverá recarregar a cada edição.\
Você também poderá ver erros de `lint` no console.

