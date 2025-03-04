# Medidas e Funções DAX
Reservo neste repositório algumas funções em DAX (Power BI) que são úteis e bastante utilizadas.

### <a href="https://github.com/ramoncampos/medidas-uteis-dax/blob/main/VendasDataAnterior">Vendas na data anterior não sequencial</a> 
Se você já tentou usar a DATEADD com uma tabela de datas não-sequenciais, sabe que a medida vai retornar um valor nulo. Nesse método, utilizo a função MAXX para retornar o maior valor anterior à data atual.

---

### <a href="https://github.com/ramoncampos/medidas-uteis-dax/blob/main/dCalendario">dCalendario</a>
O objetivo é criar uma tabela dimensão para calendário, essencial para análises temporais sem distorções. Foram adicionadas as colunas: Ano, Mês, Dia da Semana, Semestre, Bimestre, Trimestre etc.

---

### <a href="https://github.com/ramoncampos/medidas-uteis-dax/blob/main/PorcentagemAcumuladaPareto">Porcentagem acumulada Pareto</a>
Aqui é feito um cálculo da porcentagem acumulada por categoria para análise com base no Princípio de Pareto.
