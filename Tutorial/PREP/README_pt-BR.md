---

![Image](https://github.com/user-attachments/assets/762d2f59-8eb0-40eb-913f-c98ffc2f9c34)

---

🌎 Idioma:
- 🇺🇸 [English](README.md)
  
---

- GBS é um software gratuito voltado à realização de análises estatísticas aplicadas à genética quantitativa e ao melhoramento vegetal.
- A seguir apresentamos o manual e um estudo de caso de um dos procedimentos de análise de dados realizados no software GBS.

---

## Análises Individuais de Experimentos

---

### Delineamento Parcialmente Repetido

---

- Para fins de exemplo, foi utilizada a avaliação de 49 tratamentos de uma espécie vegetal quanto à severidade de crestamento bacteriano (SCB) e produtividade de grãos (PRODUTIVIDADE).

---

<p align="justify">
A figura a seguir mostra onde está localizado o procedimento de análise individual de experimentos em delineamento de Látices no software. Este procedimento está preparado para analisar dados oriundos de experimentos em látices quadrado, retangular e alpha látices.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a0faeb35-ca3f-45b3-9d94-1700bf56f2e0" alt="Image">
</p>

<p align="justify">
A primeira etapa consiste em montar uma planilha em formato ".csv". Essa planilha deve conter, obrigatoriamente, a identificação das repetições (REP) na primeira coluna, dos blocos na segunda coluna e a dos Tratamentos na terceira coluna. As demais colunas correspondem às características avaliadas, podendo haver uma ou mais. A figura a seguir apresenta o procedimento de análise utilizando o arquivo de exemplo do software. Nessa aba você poderá escolher para qual variável você deseja realizar a análise. Nesse estudo de caso, será realizada a análise para SCB. Ressalta-se que as análises no software GBS são realizadas para cada variável separadamente.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ab5e1152-9db0-4d92-ac26-85ce3bf0294d" alt="Image">
</p>

<p align="justify">
Após carregar o arquivo, o usuário deve acessar a aba de procedimentos e definir a natureza dos efeitos do modelo estatístico. Caso o efeito de tratamento seja considerado fixo, é possível selecionar um teste de médias a ser realizado juntamente com a análise.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ffac9103-161c-430b-8172-7d5aad1dcff5" alt="Image">
</p>

<p align="justify">
Após definir as configurações da análise, o usuário deve clicar no ícone azul de PLAY no canto superior esquerdo para executar a análise. Os resultados serão gerados nos formatos ".txt" e/ou ".xlsx".
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ad88f8c4-fe9c-4b4b-929e-8c1d9828b648" alt="Image">
</p>

<p align="justify">
O arquivo de saída em formato ".txt" contém diversas informações, com destaque para os testes de efeitos fixos e/ou aleatórios. A seguir é apresentada a parte inicial desse arquivo.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cbb6fe12-5b02-4f30-ac83-9f0e4d420e4f" alt="Image">
</p>

<p align="justify">
Os resultados dos testes de efeitos fixos e aleatórios são apresentados a seguir:
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/bd767844-f833-4d0e-8767-f3f15f01bd8e" alt="Image">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c7de40d8-cef7-455f-a93c-bf7d65e4eb90" alt="Image">
</p>

<p align="justify">
A análise individual permitiu observar efeito significativo de tratamentos para o caráter SCB. O arquivo de resultados também apresenta a média do experimento (6.6122), o coeficiente de variação (16.6097%) e o desvio padrão médio das variâncias entre tratamentos (0.8967).
</p>

