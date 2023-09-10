![image](https://github.com/TatianaFlorentino/EngenhariaDados/assets/41309689/2f36c038-b210-4e6f-9923-2dd33989c934)

<hr>

### Tópicos Básicos
- [Desenvolvedores](#desenvolvedores)
- [Papel Engenheiro de Dados](#papel-engenheiro-de-dados)

### Tópicos Intermediário
- [Estudos Engenharia de Dados](#estudos-engenharia-de-dados)

### Tópicos Avançados

- [Desafios Arquitetura Mercado](#desafios-arquitetura-mercado)
- [Descrição do projeto](#descrição-do-projeto)
- [Tipos de Cenários](#tipos-de-cenários)
- [Desenho da Solução](#desenho-da-solução)
- [Soluções Implementadas](#soluçoes-implementadas)
- [Ferramentas utilizadas](#ferramentas-utilizadas)
- [Benefícios Obtidos](#benefícios-obtidos)
- [Skills de Palavra Chave](skill-de-palavra-chave)


### Desenvolvedores
| [<img src="https://avatars.githubusercontent.com/tatianaflorentino?v=4" width=115><br><sub>Tatiana Florentino</sub>](https://github.com/TatianaFlorentino) 

### Papel Engenheiro de Dados
Tem uma matéria da Alura falando do papel e responsabilidade desse profissional que acredito que vale a pena ler e assistir o conteúdo da página, [link](https://www.alura.com.br/artigos/engenharia-dados).
Links utéis para relebrar conceitos e simplemente estudar, [link](https://github.com/SartMorgs/data-engineer-roadmap)

### Estudos Engenharia de Dados

### Desafios Arquitetura Mercado

* Diversidade de Fontes de Dados: A organização recebe dados de várias fontes, cada uma com seu próprio formato e estrutura.

* Variedade de Casos de Uso: Existem sete casos de uso diferentes para a ingestão de dados, cada um com requisitos específicos de processamento e entrega.

* Streaming vs. Batch: Alguns casos de uso exigem processamento em tempo real (Streaming), enquanto outros são mais adequados para processamento em lote (Batch).

* Escalabilidade: A quantidade de dados a serem ingetados é massiva, exigindo uma infraestrutura escalável.


### Descrição do projeto

Case de estudo para planejamento da melhor solução, imagine uma organização que lida com uma enorme quantidade de dados de diferentes fontes, incluindo registros transacionais, logs de aplicativos, feeds de sensores, entre outros. Esses dados são cruciais para alimentar análises, inteligência de negócios e tomada de decisões. A organização decidiu centralizar e armazenar todos esses dados em um Data Lake para aproveitar ao máximo seu potencial.

Elabore um desenho de arquitetura de dados para "Jornada da Ingestão de Dados no Data Lake: Balanceando Streaming e Batch"

Nesse case não está contemplando uso de tecnologia para resolução final do problema, somente análise, planejamento, entendimento de conceitos de arquitetura, avaliar conceitos de dados.

Este case destaca a importância de uma abordagem flexível e bem planejada para a ingestão de dados em um Data Lake, permitindo que uma organização aproveite ao máximo seus ativos de dados e obtenha insights valiosos para impulsionar o sucesso dos negócios.

## Desenho da Solução

## Tipos de Cenários

:heavy_check_mark: `Case 1:` NRT

:heavy_check_mark: `Case 2:` Streaming de eventos

:heavy_check_mark: `Case 3:` Streaming de CDC

:heavy_check_mark: `Case 4:` Streaming de eventos períodicos

:heavy_check_mark: `Case 4:` Consumo de API interativa

:heavy_check_mark: `Case 5:` Consumo de bases - Batch

:heavy_check_mark: `Case 5:` Consumo de arquivos - Batch


### Soluções Implementadas

* Unificação de Dados:

Desenvolvimento de um modelo de metadados comum para mapear a estrutura de dados de todas as fontes.
Uso de ferramentas de ETL (Extração, Transformação e Carga) para padronizar e transformar os dados em um formato consistente antes da ingestão.

* Arquitetura Híbrida:

Implementação de uma arquitetura híbrida que suporta tanto a ingestão de dados em tempo real (Streaming) quanto em lote (Batch).
Utilização de tecnologias como Apache Kafka para streaming e Apache Spark para processamento em lote.

*  Orquestração:

Uso de ferramentas de orquestração, como Apache Airflow, para gerenciar e agendar tarefas de ingestão de dados.

* Monitoramento e Logging:

Implementação de um sistema de monitoramento em tempo real para acompanhar o desempenho da ingestão e identificar problemas rapidamente.
Criação de registros (logs) detalhados para rastrear cada etapa do processo de ingestão.


### Ferramentas utilizadas
Drawio
https://www.drawio.com/

### Benefícios Obtidos

Benefícios Obtidos

Eficiência Operacional: A padronização dos dados e a automação dos processos de ingestão reduziram significativamente o tempo e os recursos necessários.

Maior Agilidade: A arquitetura híbrida permite que a organização responda rapidamente às mudanças nos requisitos de ingestão de dados.

Tomada de Decisões Baseada em Dados: Com os dados centralizados e preparados na camada raw, a organização pode extrair insights valiosos para melhorar seus processos de negócios.

Escalabilidade: A infraestrutura escalável garante que a organização possa lidar com o aumento contínuo dos dados.



## Skills de Palavra Chave:
C, C++, SQL, JAVA , C#, Python , SPARK e PySpark. DataBricks | Cloud AWS | Cloud Azure | ELT | ETL | Delta Lake | Blob Storage | Data Lake | Data LakeHouse | Data Factory | Data Flow | Azure Synapse Studio | Dedicated SQL Pool | Serveless SQL Pool | Apache Spark Pool | Airflow | Crawler | Jenkins | Terraform | Cloudformation | Azure Devops | AWS Synapse | Kinesis | Data Store | Data Lake - S3 | AWS GLUE | AWS ATHENA | REDSHIFT | Docker | Kubernetes | API | Git | GitHub | Power BI (M e DAX) | Talend | SSIS | Orientação a Objeto OO | Entrega contínua | MVC | MTV | DDL | DQL | DML | DCL | TCL Gerenciamento de Recursos e Custo | Segurança | Governança de Dados

