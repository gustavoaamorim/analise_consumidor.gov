# Análise Exploratória de Dados - Consumidor.gov
Esta análise busca identificar padrões e extrair informações e insights a respeito das reclamações finalizadas no portal Consumidor.gov no primeiro trimestre de 2024. 

Foram consideras as reclamações finalizadas no período de 01/01/2024 a 31/03/2024. 

As empresas cadastradas possuem 10 dias para responder os consumidores e caso não respondam dentro deste prazo a reclamação é finalizada. Já os consumidores possuem 20 dias para avaliar a resposta da empresa e caso não avaliem dentro deste prazo a reclamação é finalizada sem a nota do consumidor. 

#### Fonte dos dados: https://www.consumidor.gov.br/pages/conteudo/publico/1

## Perguntas a serem respondidas

- Como é a distribuição das reclamações pelo país?
- Quais os segmentos com maior número de reclamações?
- Qual o perfil dos consumidores?
- Qual o tempo médio de resposta por segmento?
- Quais as empresas com mais reclamações e sua nota média de avaliação dos clientes?
- Há relação entre a nota de avaliação e o tempo de resposta?

### Para acessar o ETL dos dados [clique aqui](etl.ipynb).

### Para acessar a análise dos dados [clique aqui](eda_consumidorgov.ipynb).


## Principais Conclusões

São Paulo é a cidade com maior concentração de reclamações com cerca de 79000 reclamações.

Sobre os consumidores:

- 82% tem menos de 50 anos;
- 36% está na faixa de 31 a 40 anos;
- 59% é do sexo masculino;
- 53% fizeram aquisição do produto/serviço da empresa pela internet;
- 88% procuraram as empresas antes de registrar a reclamação no Consumidor.gov.

As empresas com mais reclamações são:

- Vivo - Telefônica com 10924 registros;
- Google com 10484 registros;
- Hurb - Hotel Hurbano com 10174 registros;

Os segmentos de mercado com mais reclamações são:

- Bancos, Financeiras e Administradoras de Cartão com 90133 registros;
- Operadoras de Telecomunicações com 41873 registros;
- Comércio Eletrônico com 23775 registros;


### Bibliotecas utilizadas

Para este trabalho foram utilizadas as seguintes bibliotecas Python para ETL e análise:

- Pandas
- Unidecode
- Matplotlib


