---

![Image](https://github.com/user-attachments/assets/762d2f59-8eb0-40eb-913f-c98ffc2f9c34)

---

🌎 Idioma:
- 🇺🇸 [English](README.md)
  
---

- GBS é um software gratuito voltado à realização de análises estatísticas aplicadas à genética quantitativa e ao melhoramento vegetal.
- A seguir apresentamos o manual e um estudo de caso de um dos procedimentos de análise de dados realizados no software GBS.

---

## Análises Conjuntas de Experimentos

---

### Delineamento Inteiramente Casulizado

---

- Para fins de exemplo, foi utilizada a avaliação de 9 tratamentos de uma espécie vegetal em dois experimentos quanto à massa seca total.

---

<p align="justify">
A figura a seguir mostra onde está localizado o procedimento de análise conjunta de experimentos em delineamento inteiramente casualizado no software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b2e0f0ed-6fe8-4dec-9581-f8070f704e0a" alt="Image">
</p>

<p align="justify">
A primeira etapa consiste em montar uma planilha em formato ".csv". Essa planilha deve conter os Tratamentos obrigatoriamente na primeira coluna. As demais colunas correspondem às características avaliadas, podendo haver uma ou mais. A figura a seguir apresenta o procedimento de análise utilizando o arquivo de exemplo do software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/4033571b-fa59-402f-b229-c0fdc7c5fa95" alt="Image">
</p>

<p align="justify">
Após carregar o arquivo, o usuário deve acessar a aba de procedimentos e definir a natureza dos efeitos do modelo estatístico. Caso o efeito de tratamento seja considerado fixo, é possível selecionar um teste de médias a ser realizado juntamente com a análise.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/f75e282b-8bd0-4aa2-8f8d-d1d4cd8fe9ba" alt="Image">
</p>

<p align="justify">
Após definir as configurações da análise, o usuário deve clicar no ícone azul de PLAY no canto superior esquerdo para executar a análise. Os resultados serão gerados nos formatos ".txt" e/ou ".xlsx".
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/1d284c6a-e39e-4ebf-8e5b-53259e2096f6" alt="Image">
</p>

<p align="justify">
O arquivo de saída em formato ".txt" contém diversas informações, com destaque para os testes de efeitos fixos e/ou aleatórios. A seguir é apresentada a parte inicial desse arquivo.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/61f4588c-b17a-4399-bfcd-0102aefc49ac" alt="Image">
</p>

<p align="justify">
Os resultados dos testes de efeitos fixos e aleatórios são apresentados a seguir:
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/57c7867d-a252-4b33-9234-37a401bcdb17" alt="Image">
</p>

<p align="justify">
A análise individual permitiu observar efeito não significativo de tratamentos para o caráter MST. O arquivo de resultados também apresenta a média do experimento (38.3925), o coeficiente de variação (14.8683%) e o desvio padrão médio das variâncias entre tratamentos (4.0364).
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/9d9b806c-6f06-49ab-b86c-cff822645d43" alt="Image">
</p>

