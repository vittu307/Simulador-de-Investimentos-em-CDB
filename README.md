# Simulador de Investimentos em CDB

Um simulador desenvolvido em Python para estimar a evolução do patrimônio investido em um Certificado de Depósito Bancário (CDB), considerando aportes periódicos, juros compostos, Imposto de Renda e inflação.

## Objetivo

Este projeto foi desenvolvido com o objetivo de praticar conceitos de programação em Python por meio de uma aplicação financeira, utilizando funções, estruturas de repetição, validação de dados, cálculos matemáticos e visualização gráfica.

## Funcionalidades

- Definição de aporte inicial e aportes mensais.
- Simulação de investimentos com juros compostos.
- Estimativa da rentabilidade de um CDB em função do CDI.
- Escolha entre aportes realizados no início ou no final do mês.
- Estimativa do Imposto de Renda conforme o prazo da aplicação.
- Cálculo do rendimento bruto e líquido.
- Estimativa do patrimônio futuro em valores de hoje, considerando a inflação.
- Exibição de gráfico com a evolução do patrimônio.
- Validação de entradas e tratamento de erros.
- Formatação de valores monetários no padrão brasileiro.

## Tecnologias utilizadas

- **Python** — lógica e cálculos da simulação.
- **Matplotlib** — geração do gráfico de evolução patrimonial.
- **Google Colab** — ambiente utilizado para desenvolver e executar o projeto.

## Como executar

1. Acesse o notebook do projeto no Google Colab.
2. Execute as células do código.
3. Informe os valores solicitados pelo programa, como aporte inicial, aporte mensal, CDI anual, percentual do CDI, prazo e inflação estimada.
4. Escolha se os aportes mensais serão realizados no início ou no final do mês.
5. Consulte os resultados apresentados no terminal e o gráfico gerado.

## Limitações

Os resultados são estimativas para fins educacionais e não representam uma previsão garantida de rentabilidade.

- A rentabilidade do CDB é estimada a partir do CDI anual informado e do percentual contratado.
- A capitalização é mensal, simplificando o funcionamento real de investimentos atrelados ao CDI.
- Os prazos das aplicações utilizados na estimativa do Imposto de Renda são aproximados.
- O IOF não está incluído nos cálculos.
- A simulação não considera todas as particularidades tributárias e operacionais de um investimento real.

Os resultados podem diferir dos valores efetivamente obtidos em uma aplicação financeira.

## Aprendizados

O desenvolvimento deste projeto permitiu praticar:

- Criação e reutilização de funções.
- Validação de entradas e tratamento de exceções.
- Manipulação de listas e dicionários.
- Laços de repetição e estruturas condicionais.
- Cálculos com juros compostos e inflação.
- Visualização de dados com Matplotlib.
- Organização e documentação de código.

## Exemplo de execução

Abaixo, um exemplo visual do resultado gerado pelo simulador.

![Exemplo do gráfico de evolução do patrimônio](<img width="989" height="490" alt="exemplo" src="https://github.com/user-attachments/assets/b5464593-fa28-403c-82b6-1a999d243f95" />
)
## Aviso

Este projeto possui finalidade exclusivamente educacional. Não constitui recomendação de investimento.

## Autor

Victor Augusto Pires Ferreira
