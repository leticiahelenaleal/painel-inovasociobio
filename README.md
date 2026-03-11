# painel-inovasociobio
O Painel Inova Sociobio integra bases de dados públicas e institucionais sobre o contexto da sociobiodiversidade. As informações apoiam análises e decisões sobre políticas e iniciativas, sendo organizadas e tratadas para visualização integrada e comparabilidade de indicadores.

## Consultas realizadas para análise dos dados
### Consulta de CNPJ

O script `scripts/consulta_cnpj.py` consultou informações das entidades utilizando a API da BrasilAPI.

Dados retornados:
- CNPJ
- Data de abertura
- Porte da empresa
- Capital social

API utilizada:
https://brasilapi.com.br/api/cnpj/v1/{cnpj}
