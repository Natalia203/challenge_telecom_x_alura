Telecom X — Análise de Evasão de Clientes (Churn)

Este projeto foi desenvolvido para o ONE | TECH FOUNDATION - Especialização Data Science da Alura e tem como objetivo analisar o comportamento dos clientes da empresa fictícia **Telecom X**, com foco na **evasão de clientes (churn)**. Através de uma análise exploratória de dados, foram identificados padrões e variáveis que podem ajudar a empresa a **compreender os motivos da saída de clientes e propor ações para reduzir o churn**.

---

## Objetivo

O principal objetivo foi entender:

* Como a evasão está distribuída entre diferentes perfis de clientes.
* Quais características estão mais associadas a clientes que cancelaram seus serviços.
* Quais estratégias podem ser adotadas com base nos dados para aumentar a retenção.

---

## Estrutura do Projeto

```
Telecom_X_Churn_Analysis/

│
├── notebook/
│   └──  analise_de_evasão_de_clientes_telecomX_br.ipynb
│
├── README.md        
```

---

## Exemplos de Análises

Alguns dos gráficos e insights gerados incluem:

* **Distribuição de Evasão por Gênero**
  Clientes de ambos os gêneros possuem taxas de evasão semelhantes.

* **Idosos tendem a evadir mais**
  Clientes idosos têm uma taxa de evasão de 42%, significativamente maior que os não idosos (24%).

* **Tipo de contrato influencia fortemente**
  Clientes com contrato mensal têm 43% de evasão, enquanto contratos anuais ou de dois anos têm taxas abaixo de 12%.

* **Clientes com serviços adicionais como segurança online ou suporte técnico têm menor chance de evasão**
  Ex: 85% dos que possuem suporte técnico permaneceram, contra 61% dos que não possuem.

---

## Como Executar

Para executar este projeto localmente:

1. **Clone este repositório**:

   ```bash
   git clone https://github.com/Natalia203/challenge_telecom_x_alura
   cd analise_de_evasão_de_clientes_telecomX_br
   ```

2. **Instale as dependências** (recomenda-se usar um ambiente virtual):

   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```

3. **Execute o notebook**:

   ```bash
   jupyter notebook analise_de_evasão_de_clientes_telecomX_br.ipynb
   ```

---

## Requisitos

* Python 3.7+
* Jupyter Notebook
* Bibliotecas:

  * pandas
  * matplotlib
  * seaborn

---

## Conclusões

A análise mostrou que a evasão está relacionada com diversos fatores, como:

* Tipo de contrato
* Presença de serviços adicionais
* Idade (idoso ou não)
* Forma de pagamento

Esses insights são fundamentais para **criar estratégias direcionadas**, como oferecer descontos para contratos longos, incentivar o uso de serviços extras e melhorar a experiência de clientes mais propensos à evasão.
