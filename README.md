# Testes Unitários da Classe AnaliseDeDados

Este repositório contém os testes unitários para a classe `AnaliseDeDados`, que realiza várias operações estatísticas sobre um conjunto de dados numéricos.

## Resumo dos Testes Realizados

O arquivo `analiseDeDados.test.js` contém testes que validam os cálculos estatísticos, manipulação de dados e a análise da correlação entre dois conjuntos de dados.

### Funcionalidades Testadas

1. **Adicionar Dados**:
   - Teste que valida a adição de novos dados ao conjunto existente.
   
2. **Limpar Dados**:
   - Teste que valida a remoção de todos os dados do conjunto.
   
3. **Ordenação de Dados**:
   - Teste que verifica se os dados estão sendo corretamente ordenados em ordem crescente.

4. **Cálculos Estatísticos**:
   - **Média**: Validação do cálculo correto da média dos dados.
   - **Mediana**: Validação do cálculo da mediana.
   - **Moda**: Teste que verifica se a moda (valor mais frequente) está sendo corretamente calculada.
   - **Variância**: Teste de precisão para o cálculo da variância.
   - **Desvio Padrão**: Validação do cálculo do desvio padrão.
   - **Coeficiente de Variação**: Teste que valida o cálculo do coeficiente de variação.
   
5. **Normalização dos Dados**:
   - Teste que valida a normalização dos dados entre 0 e 1, com base nos valores mínimo e máximo.

6. **Percentis**:
   - Teste para calcular o percentil dos dados.

7. **Soma e Produto**:
   - Verifica se a soma e o produto dos dados estão corretos.

8. **Amplitude**:
   - Validação do cálculo da amplitude (diferança entre o valor máximo e mínimo).

9. **Remoção de Outliers**:
   - Teste para validar a remoção de outliers com base no critério de IQR (Intervalo Interquartílico).

10. **Correlação**:
    - **Correlação Perfeita**: Teste de correlação entre dois conjuntos de dados idênticos (esperado: `1`).
    - **Correlação Nula**: Teste para verificar a correlação entre dois conjuntos de dados sem relação (esperado: `null`).
    - **Correlação Positiva**: Teste de correlação positiva entre dois conjuntos de dados (esperado: valor próximo de `1`).
    - **Correlação Negativa**: Teste de correlação negativa entre dois conjuntos de dados (esperado: valor próximo de `-1`).

### Execução dos Testes

Os testes são executados usando o framework **Jest**. Para rodar os testes, utilize o seguinte comando:

```bash
npm test
