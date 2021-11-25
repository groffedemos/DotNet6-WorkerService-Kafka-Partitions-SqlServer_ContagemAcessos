# DotNet6-WorkerService-Kafka-Partitions-SqlServer_ContagemAcessos
Exemplo de consumo de mensagens de um tópico do Apache Kafka com dados de contagens de acesso em um Worker Service criado com .NET 6, utilizando ainda SQL Server + Dapper.Contrib para gravação dos dados (registrando inclusive as partições de origem) e um Dockerfile para geração de imagens Docker em Linux.

API REST para geração das mensagens consumidas por este projeto:

https://github.com/renatogroffe/ASPNETCore6-REST_API-Kafka-Partitions_ContagemAcessos