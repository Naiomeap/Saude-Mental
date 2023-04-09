# Saude-Mental

### Descrição

#### O objetivo desse trabalho busca descobrir se quanto mais ações de promoção a saúde e mais profissionais relacionados a saúde mental melhor será a saúde mental da população.

Um tema que vem sendo muito discutido no Brasil e no mundo, é a saúde mental. Após a pandemia do Covid 19 esse problema se tornou cada vez mais recorrentes e muitos estudos andam abordando as consequências ocasionadas por problemas mentais na vida do indivíduo como sua vida profissional, social, amorosa etc (Machado et al, 2022: doi 10.47626/1679-4435-2022-680; Pinho et al, 2021: doi 10.2196/24298).

O contexto escolhido para a analise de dados foi um estado que fica na região sul do Brasil. O Paraná é um estado que possui 399 municipíos e é a 4º maior econômia do país. Com os dados disponibilizados pelo governo federal iremos analisar se há diferença entre esses municipios, se é possivel medir a saúde mental de uma determinada população e se ações de promoção a saúde, um conjunto de politicas, programas e plano de saúde pública que visa melhorar o bem estar e a qualidade de vida da população, podendo ser realizadas por individuos, coletivamente ou por organizações.


# **Estrutura do Repositório**

- [README.md](https://github.com/Naiomeap/Trabalho_em_Grupo_Saude/blob/main/README.md): Este arquivo.
- [Trabalho_em_Grupo_Analise_Saude.ipynb](https://github.com/Naiomeap/Trabalho_em_Grupo_Saude/blob/main/Entrega_Final_Trabalho_em_Grupo_Analise_Saude.ipynb): Notebook produzido em Google Colab com as análises.
- [Tabela_Compilada](https://github.com/Naiomeap/Trabalho_em_Grupo_Saude/blob/main/Tabela_Compilada.csv): Base de dados, contendo as variáveis demográficas a serem incluídas no modelo.

### Dicionário de Dados

O *dataset* final conta com os seguintes atributos:

MUN - Município	- object 
AS_SOC -	Quantidade de Assistente Social	- float64
PSICO -	Quantidade de Psicólogo -	float64
PSIQ -	Quantidade de Psiquiatra	- float64
Acoes_prom -	Ações de promoção e prevenção a saúde -	int64 
Acoes_comp -	Ações complementares de atenção a saúde -	int64 
2017 -	Quantidade de ações complementares de atenção a saúde em 2017 -	int64 
2018 -	Quantidade de ações complementares de atenção a saúde em 2018 -	int64 
2019 -	Quantidade de ações complementares de atenção a saúde em 2019 -	int64 
2020 -	Quantidade de ações complementares de atenção a saúde em 2020 -	int64 
2021 -	Quantidade de ações complementares de atenção a saúde em 2021 -	int64 
AR_TER_km2 - Área Territorial em Km² - float64
POP_EST	-  Quantidade da população Estimada -	int64 
PIB_P_CAP -	Produto Interno Bruto Per Capta (valores nominais) - float64
IDHM -	Índice de Desenvolvimento Humano (escala) -	float64


### Autora

- Naiome Alves Pereira

### Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE.md para mais detalhes.
