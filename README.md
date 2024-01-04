# COMANDOS DOCKER
## DOCKER NETWORK

```
	• DETALHES SOBRE REDE DOCKER ESPECÍFICA
docker network inspect minha-rede

	• LISTAR REDES DISPONÍVEIS
docker network ls

	• CONECTA UM CONTÊINER A UMA REDE ESPECÍFICA
docker network connect minha-rede meu-container

	• DESCONECTA UM CONTÊINER DE UMA REDE ESPECÍFICA
docker network disconnect minha-rede meu-container

	• REMOVE UMA REDE EXISTENTE NO DOCKER
docker network rm minha-rede



	• REMOVE TODAS AS REDES DOCKER QUE NÃO ESTÃO ASSOCIADAS 
	A UM CONTÊINER EM EXECUÇÃO
docker network prune

	• CRIAR NOVA REDE DOCKER
docker network create minha-rede

	• ENCONTRAR O ENDEREÇO IP DA INTERFACE DE REDE PADRÃO DO DOCKER HOST
ip addr show docker0 | grep -Po 'inet \K[\d.]+'
```
