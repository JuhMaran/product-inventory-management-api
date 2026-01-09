# API de Gerenciamento de Estoque de Produto

Esta API tem como objetivo o **gerenciamento de estoque de produtos**, utilizando o padrão de **Event Sourcing** para garantir rastreabilidade e histórico completo das operações realizadas. Cada produto é identificado por um **SKU** e possui atributos como **nome**, **cor** e **material**.

O estoque controla diferentes estados de quantidade do produto, incluindo **quantidade disponível**, **quantidade reservada** e **quantidade removida/vendida**, permitindo uma gestão precisa e consistente baseada em eventos.

A aplicação disponibiliza **endpoints de comando** para **adicionar**, **reservar** e **vender produtos**, além de **endpoints de consulta** para obtenção do **histórico de transações** e da **quantidade disponível em estoque**, seguindo boas práticas de arquitetura orientada a domínio.

---

## Tecnologias Principais

- Java 25
- Spring Boot 4.0.1
- Maven
- Event Sourcing
- Docker e Docker Compose
