# Analise_de_credito_estatistica
Este projeto realiza uma análise exploratória de dados (EDA) para identificar padrões entre idade, renda e o impacto da inadimplência na concessão de limites de crédito. O objetivo é demonstrar como variáveis comportamentais podem ser mais decisivas para o risco de crédito do que o salário bruto.

# Visão Estratégica
A análise foca em duas hipóteses principais:

Correlação Idade vs. Salário: Verificação da teoria de que a experiência profissional (refletida pela idade) impulsiona a senioridade salarial.

O "Teto" da Inadimplência: Demonstração visual de que o histórico de pagamento é um limitador crítico, agindo como um teto para o crédito mesmo em faixas salariais elevadas.

# Tecnologias Utilizadas
Python 3.x

Pandas: Manipulação, limpeza e tipagem de dados (conversão de strings para float/int).

Matplotlib: Visualização de dados estática e anotações estratégicas.

# Insights Extraídos
Limitação de Crédito: Através do gráfico de dispersão, observou-se que indivíduos inadimplentes (marcados com 'X' vermelho) possuem limites drasticamente reduzidos. Mesmo o perfil com o maior salário da amostra (R$ 15.000) não consegue romper a barreira do crédito baixo devido ao seu histórico financeiro.

Segmentação de Dados: O código utiliza filtragem lógica para separar clientes "Em dia" de "Inadimplentes", permitindo uma comparação visual direta das distribuições.
