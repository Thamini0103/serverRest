# Projeto serverRest
Testes do ap]i rest do manual a CI/CD

## O que é
Este repositório foi criado para teste de API rest

## Tecnologias utilizadas
* Postman web
* Node v24.13.1
* Newman 6.2.2
* Newman-reporter-htmlextra 1.23.1

## Documentações
DOC da API: [Consulte Swagger](https://serverest.dev/?lang=pt-BR)

## Como instalar o ambiente
1. Instale o node em seu computador [baixe aqui](https://nodejs.org/en/download)
2. Realize a instalaçãodo Newman de forma global [baixe aqui a dependência](https://www.npmjs.com/package/newman)
```
npm install -g newman
```
3. Realiza a instalação da dependência dos relatórios (opcional) [newman-reporter-htmlextra](https://www.npmjs.com/package/newman-reporter-htmlextra)
```
npm install -g newman-reporter-htmlextra
```
## Como rodar os testes
### Pelo Postman web ou desktop
- Import a collection e o environment
- Execute os testes de forma manual ou automatizada
### Pelo Newman
- Abra seu console de preferência
- Execute a seguinte linha de comando para rodar os testes
```
newman run ServerRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli
```
- Execute a seguinte linha de comando para rodar os testes com relatório
```
newman run ServerRest.postman_collection.json -e serveRest_env.postman_environment.json -r htmlextra
```
### Report
Se você optou por rodar os testes vom o report htmlextra, foi gerado um arquivo html com o resultado. PAra verificar as validações, vocÊ pode abrir a pasta Newman que foi criada no local em que os arquivos de  collection e environment se encontram.

## Entre em contato
Rede social: [linkedin](https://www.linkedin.com/in/thamini-garcia-guimar%C3%A3es-vila-real-ba851b127/)
