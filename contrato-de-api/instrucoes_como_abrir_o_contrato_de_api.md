consegui rodar localmente o contrato de API, aqui ta o bizu:

  * pre-requisito: ter o docker instalado e rodando.

1. descompactar o arquivo alitem.zip, no diretório ‘alitem’ dentro do home do usuário, por exemplo: /Users/Flaviano.Marinho/Projects/alitem. Arquivos usados são: docker-compose.yaml, openapi-config.yaml e openapi.yaml;
2. ⁠Ajustar no arquivo docker-compose.yaml o volume usado pelo serviço mock-server, por exemplo, mudar de ‘/Users/Flaviano.Marinho/Projects/alitem’ para ‘/alitem’ (caso tenha extraido o .zip para a pasta raiz do seu computador); 
3. ⁠⁠rodar o docker-compose.yaml file com o comando: docker-compose up
4. ⁠⁠⁠Acessar o contrato no link: http://localhost:8080/_spec/#/
5. ⁠⁠⁠Acessar exemplo de endpoint no link: http://localhost:8080/v1/inicio


Referência: 
1. Buscar no google por “Build a mock REST API with Swagger UI using OPEN API Specification and Docker.”, o gemini vai dizer como fazer. De todo jeito aqui tem um link com mais detalhes: “https://nuvolar.medium.com/build-a-mock-rest-api-with-swagger-ui-using-open-api-specification-and-docker-4665b53b8d85”
2. https://hub.docker.com/r/outofcoffee/imposter-openapi
3. Volume binding using docker compose on Windows - https://stackoverflow.com/questions/41334021/volume-binding-using-docker-compose-on-windows