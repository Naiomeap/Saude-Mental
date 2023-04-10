# Saude-Mental

### Descrição

#### O objetivo desse trabalho busca descobrir se quanto mais ações de promoção a saúde e mais profissionais relacionados a saúde mental melhor será a saúde mental da população.

Um tema que vem sendo muito discutido no Brasil e no mundo, é a saúde mental. Após a pandemia do Covid 19 esse problema se tornou cada vez mais recorrentes e muitos estudos andam abordando as consequências ocasionadas por problemas mentais na vida do indivíduo como sua vida profissional, social, amorosa etc (Machado et al, 2022: doi 10.47626/1679-4435-2022-680; Pinho et al, 2021: doi 10.2196/24298).

O contexto escolhido para a analise de dados foi um estado que fica na região sul do Brasil. O Paraná é um estado que possui 399 municipíos e é a 4º maior econômia do país. Com os dados disponibilizados pelo governo federal iremos analisar se há diferença entre esses municipios, se é possivel medir a saúde mental de uma determinada população e se ações de promoção a saúde, um conjunto de politicas, programas e plano de saúde pública que visa melhorar o bem estar e a qualidade de vida da população, podendo ser realizadas por individuos, coletivamente ou por organizações.


# **Estrutura do Repositório**

- [README.md](https://github.com/Naiomeap/Saude-Mental/blob/main/README.md): Este arquivo.
- [Trabalho_Individual_Entrega_Final.ipynb](https://github.com/Naiomeap/Saude-Mental/blob/main/Trabalho_Individual_Entrega_Final.ipynb): Notebook produzido em Google Colab com as análises.
- [Tabela_Dados](https://github.com/Naiomeap/Saude-Mental/blob/main/Tabela_dados.csv): Base de dados, contendo as variáveis demográficas a serem incluídas no modelo.
- [Suícidio 2017](https://github.com/Naiomeap/Saude-Mental/blob/main/Suicidio%202017.csv): Base de dados, contendo as variáveis sobre tentativas de suícidio em 2017.
- [Suícidio 2018](https://github.com/Naiomeap/Saude-Mental/blob/main/Suicidio%202018.csv):Base de dados, contendo as variáveis sobre tentativas de suícidio em 2018.
- [Suícidio 2019](https://github.com/Naiomeap/Saude-Mental/blob/main/Suicidio%202019.csv): Base de dados, contendo as variáveis sobre tentativas de suícidio em 2019.
- [Suícidio 2020](https://github.com/Naiomeap/Saude-Mental/blob/main/Suicidio%202020.csv): Base de dados, contendo as variáveis sobre tentativas de suícidio em 2020.
- [Suícidio 2021](https://github.com/Naiomeap/Saude-Mental/blob/main/Suicidio%202021.csv): Base de dados, contendo as variáveis sobre tentativas de suícidio em 2021.

### Dicionário de Dados

O *dataset* final conta com os seguintes atributos:

MUN - Município - object

AS_SOC - Quantidade de Assistente Social - float64

PSICO - Quantidade de Psicólogo - float64

PSIQ - Quantidade de Psiquiatra - float64

Acoes_prom - Quantidade de Ações de Promoções e Prevenção da saúde - int64

Acoes_comp - Ações Complementares de Atenção a Saúde - int64

2017 - Quantidade de Ações Complementares de Atenção a Saúde 2017 - int64

2018 - Quantidade de Ações Complementares de Atenção a Saúde 2018 - int64

2019 - Quantidade de Ações Complementares de Atenção a Saúde 2019 - int64

2020 - Quantidade de Ações Complementares de Atenção a Saúde 2020 - int64

2021 - Quantidade de Ações Complementares de Atenção a Saúde 2021 - int64

AR_TER_km2 - Área Territorial em Km² - float64

POP_EST – Quantidade da população Estimada - int64

PIB_P_CAP - Produto Interno Bruto Per Capta (valores nominais) - float64

IDHM - Índice de Desenvolvimento Humano (escala) - float64

CODUFMUN - Código do Município - int64

MUN - Nome dos Município - object

REC - Recorrência de tentativa de suícidio 2017 - float64

TENT_y – Tentativa de Suícidio 2017 - int64

REC_21 - Recorrência de tentativa de suícidio 2021 - float64

TENT_21 – Tentativa de Suícidio 2021- int64

Soma_Acoes - Somatório das Ações Complementares da Saúde de 2017-2021 - int64

Dif_Suc - Subtração das colunas de tentativa de suícidio 2017-2021 - float64


### Autora

- Naiome Alves Pereira

### Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE.md para mais detalhes.
