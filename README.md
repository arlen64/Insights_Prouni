# Insights_Prouni

Este é um projeto simples de web scraping desenvolvido em Python para extrair as últimas notícias do site G1 (globo.com)<br />
Nesse projeto é realizado uma extração de até 8 notícias do site sendo elas as notícias atualizadas dando ao usuário a oportunidade de escolher quantas notícias quer exibir.<br />
Obs: O usuário não consiguirá exibir mais de 8 notícias <br />



## Bibliotecas necessárias:

- dash
- ploty
- pandas
- sqlalchemy

## 🧐 Objetivo

Extrair informções de uma base de dados do 'Prouni' que se retrata do detalhamento quantitaivo de bolsas concedidas pelo Prouni por ano . <br/>
Esse código pode ser usado como base para projetos mais avançados ou para entender os conceitos básicos de processos de ETL.

## Como Usar

Para utilizar este projeto, siga os passos abaixo:

### Instalação das Dependências:

Certifique-se de ter o Python instalado em seu ambiente. Este projeto foi desenvolvido usando Python 3.x.

Utilize o comando abaixo para instalar as dependências necessárias:

```bash
pip3 install -r requirements.txt
```

### Execução do Scraping:

Após a instalação das dependências, você pode executar o arquivo `WebScrapingG1.py` para iniciar o scraping das notícias.

```bash
python3 WebScrapingG1.py
```

### Resultado:

O código irá coletar as últimas notícias do G1, exibindo os títulos, subtítulos (se conter subtítulo) e links das notícias obtidas no console. <br />
Obtendo até 8 notícias do site.

## Estrutura de Pasta

A estrutura de pastas do projeto está organizada da seguinte maneira:

```bash
-   `README.md`: Documentação explicando o projeto, instruções de uso e informações gerais.
-   `WebScrapingG1.py`: Script que contém o código fonte do projeto.
-   `requirements.txt`: Lista todas as dependências do projeto para facilitar a instalação.
