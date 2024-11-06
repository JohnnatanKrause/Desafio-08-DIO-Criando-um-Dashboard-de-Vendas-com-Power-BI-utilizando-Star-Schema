# Desafio 08: Criando um Diagrama Dimensional com Power BI

👋 Olá, eu sou Johnnatan Krause! Este é o meu projeto para o **Desafio 08** do módulo de Power BI no bootcamp de **Engenharia de Dados com Python**.

## Descrição do Desafio

Neste desafio, o objetivo foi criar um diagrama dimensional (star schema) focado na análise dos dados de professores, utilizando o diagrama relacional disponibilizado como base.

### Objetivos

O modelo de dados contém as seguintes tabelas:

1. **F_Professores**: Tabela fato que inclui informações relevantes sobre os professores, como ID do professor, cursos ministrados, departamento e outras métricas associadas.
2. **D_Cursos**: Tabela dimensão que contém detalhes sobre os cursos, como ID do curso, nome do curso, carga horária e descrição.
3. **D_Departamentos**: Tabela dimensão que abrange informações sobre os departamentos, incluindo ID do departamento, nome e localização.
4. **D_Datas**: Tabela dimensão de datas, criada para incluir dados como data de oferta das disciplinas e data de início dos cursos. Os campos foram definidos para diferentes níveis de granularidade.

### Processo de Construção

- **Definição da Tabela Fato**: A tabela fato foi criada para refletir as métricas e informações chave sobre os professores e suas interações com os cursos.
- **Criação das Tabelas Dimensão**: As tabelas dimensão foram montadas com informações relevantes que complementam a análise da tabela fato.
- **Construção da Tabela de Datas**: Para suprir a falta de dados de datas no modelo relacional, foi criada a tabela dimensão de datas, utilizando uma granularidade que atende às necessidades de análise.

### Visualização do Modelo

Abaixo está uma imagem do esquema em estrela criado durante o projeto:

![Esquema em Estrela](link-para-a-imagem-do-esquema)

## Links para Dados Utilizados

- **Dados Utilizados**: [Diagrama Relacional no GitHub](link-para-o-diagrama)

## Dicas e Recursos para Aprofundamento

- **Cursos e Tutoriais**: Explore plataformas como DIO, Coursera, Udemy e YouTube para cursos de modelagem de dados e Power BI.
- **Comunidades**: Participe de grupos no LinkedIn e fóruns como o Power BI Community para trocar experiências.
- **Documentação Oficial**: Consulte a [documentação do Power BI](https://docs.microsoft.com/pt-br/power-bi/) para aprofundar seu conhecimento.

## Conclusão

Este desafio foi uma excelente oportunidade para aplicar conhecimentos de modelagem dimensional e construção de esquemas em estrela. Estou animado para aplicar essas habilidades em projetos futuros!

## Conecte-se comigo

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/johnnatankrause/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JohnnatanKrause) 
[![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/channels/@johnnatankrause/)
[![DIO](https://img.shields.io/badge/DIO-0000FF?style=for-the-badge&logo=digitalocean&logoColor=white)](https://www.dio.me/users/johnnatankrause)

## Habilidades

![Power BI](https://img.shields.io/badge/Power%20BI-F2C94C?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

JK
