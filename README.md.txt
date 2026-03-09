# Checkpoint 1 - WebService SOAP

Projeto desenvolvido para a disciplina de Arquitetura SOA e Web Services.

## Integrantes
- Lorenzzo Vendruscolo Dias - RM558305
- Gabriel Martins Vannucci - RM556883
- Miguel Marques Lourenço - RM555426
- Pedro Henrique Ferronato - RM554757

## Descrição
Este projeto tem como objetivo desenvolver um WebService SOAP do lado da publicação e do lado do consumo dos serviços.

Foram criados:
- Um projeto Publisher chamado WinerySys01
- Um projeto Client chamado WineStockClient para consumir o método getMenu()
- Um projeto Client chamado WineOrderClient para consumir os métodos placeOrder() e sendWarn()

## Tecnologias utilizadas
- Java
- Maven
- JAX-WS
- IntelliJ IDEA

## Serviços criados

### WineStockService
- getMenu()
- placeOrder(String name, int quantity)

### WineWarningService
- sendWarn()

## Como executar
1. Executar a classe Loader no projeto WinerySys01
2. Verificar os WSDLs no navegador:
   - http://localhost:8085/WineStockService?wsdl
   - http://localhost:8086/WineWarningService?wsdl
3. Executar a classe ApplicationClient1 no projeto WineStockClient
4. Executar a classe ApplicationClient2 no projeto WineOrderClient