# Tópicos Avançados em Programação (TAPR)
## Introdução sobre Microsserviços

### [Link: Definição de Microsserviços](https://learn.microsoft.com/en-us/dotnet/architecture/microservices/architect-microservice-container-applications/microservices-architecture?WT.mc_id=AZ-MVP-5003638)

### Perguntas
- Como se dá a comunicação entre os microsserviços?
- Como é feito o armazenamento dos dados de cada microsserviço?
- Qual a relação entre o tamanho do microsserviço e seu [acoplamento](https://pt.wikipedia.org/wiki/Acoplamento_fraco)?
- Existe uma relação entre microsserviços e as técnicas de [DEVOPS](https://pt.wikipedia.org/wiki/DevOps)?
- Como é feito o deployment de uma aplicação monilítica e de um microsserviço?

### [Link: Microsserviços - Martin Fowler](https://www.martinfowler.com/articles/microservices.html)

### Perguntas
- O que significa um microsserviço rodar em seu próprio processo?
- Como pode ser feita a escalabilidade horizontal de uma aplicação monolítica?
- Qual situação que uma mudança no código de um monolito pode ocasionar?
- Em qual situação seria necessário atualizar diversos microsserviços ao mesmo tempo?
- Como devem ser organizadas as equipes que vão construir os microsserviços?
- Qual a relação de responsabilidade das equipes sobre o ciclo de vida dos microsserviços?
- O que são os Enterprise Service Bus e qual sua relação com o padrão SOA?
- Qual o impacto da mudança entre da técnica de comunicação in-process dos monolitos para o padrão de Remote Procedure Call dos microsserviços?
- O que é o conceito de ["paved road"](https://netflixtechblog.com/how-we-build-code-at-netflix-c5d9bd727f15) usado pelo Netflix?
- O que é o padrão de contratos de comunicação [Tolerant Reader](https://www.martinfowler.com/bliki/TolerantReader.html)?
- Microsserviços devem compartilhar uma única instância de banco de dados?
- O que é Continuous Delivery e Continuous Integration?
- Por que a tolerância a falhas é um requisito fundamental para microsserviços?