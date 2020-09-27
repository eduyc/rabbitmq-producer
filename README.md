# rabbitmq-producer

Nesse desenvolvimento escolhi utilizar a ferramenta RabbitMQ, que deve estar instalada com o usuário e senha guest.

Para inicializar o "Producer", executar na raiz do projeto "rabbitmq-producer" o seguinte comando:
mvn clean spring-boot:run
Após a aplicação inicializar, utilizar a ferramenta Postman para enviar uma mensagem no formato JSON do produto que será "cadastrado", através da URL http://localhost:8082/enviarProduto
Exemplo de um produto no formado JSON:

{
    "codigo": "222222222",
    "nome": "TV",
    "categoria": "Eletro",
    "fabricante": "LG"
}
