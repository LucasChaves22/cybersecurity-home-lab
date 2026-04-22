 ## Lab 02 - Port Scan com Nmap

## Objetivo
Realizar escaneamento de portas em um alvo autorizado para identificar serviços ativos.

## ⚠️ Importante
Este teste foi realizado em ambiente autorizado (scanme.nmap.org).

## Ferramenta utilizada
Nmap

## O que é Nmap?
O Nmap é uma ferramenta utilizada para descoberta de rede e auditoria de segurança, permitindo identificar hosts ativos, portas abertas e serviços em execução.

## Comando utilizado

- nmap scanme.nmap.org

## O que o comando faz?
Realiza um scan básico nas portas mais comuns do alvo, identificando quais estão abertas.

## Evidência

![Scan](../images/lab02-nmap.png)

## Resultado

Foram identificadas portas abertas no servidor, indicando serviços ativos disponíveis para conexão.

Exemplo:
- Porta 22 → SSH (acesso remoto)
- Porta 80 → HTTP (servidor web)

## Análise

A identificação de portas abertas é importante pois cada serviço exposto pode representar um possível ponto de entrada para ataques.

Serviços mal configurados ou desatualizados podem ser explorados por invasores.

## Aprendizado

- Entendimento básico de scan de portas  
- Identificação de serviços em rede  
- Importância da exposição de portas  
- Noção inicial de superfície de ataque  
