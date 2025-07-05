Instruções como abrir o contrato de API

  * Pre-requisito: ter o docker instalado e rodando.

1. Clonar o repositorio Git: https://github.com/flauberjp/alitem.git 
1.1. Arquivos usados são (localizados na pasta contrato-de-api): docker-compose.yaml, openapi-config.yaml e openapi.yaml;
2. ⁠Ajustar no arquivo docker-compose.yaml o volume usado pelo serviço mock-server, por exemplo, mudar de ‘C:/Users/Vera/Documents/alitem/contrato-de-api’ para ‘C:/alitem’, caso tenha clonado o projeto para o razi do seu computador(assumindo voce esta usando uma maquina windows); 
3. ⁠Rodar o docker-compose.yaml file com o comando, onde dentro do diretorio contrato-de-api voce digita o comando: docker-compose up
4. ⁠⁠⁠Acessar o contrato no link: http://localhost:8080/_spec/#/
5. ⁠⁠⁠Acessar exemplo de endpoint no link: http://localhost:8080/v1/inicio


Referência: 
1. Buscar no google por “Build a mock REST API with Swagger UI using OPEN API Specification and Docker.”, o gemini vai dizer como fazer. De todo jeito aqui tem um link com mais detalhes: “https://nuvolar.medium.com/build-a-mock-rest-api-with-swagger-ui-using-open-api-specification-and-docker-4665b53b8d85”
2. https://hub.docker.com/r/outofcoffee/imposter-openapi
3. Volume binding using docker compose on Windows - https://stackoverflow.com/questions/41334021/volume-binding-using-docker-compose-on-windows