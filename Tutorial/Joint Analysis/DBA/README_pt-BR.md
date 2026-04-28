---

![Image](https://github.com/user-attachments/assets/762d2f59-8eb0-40eb-913f-c98ffc2f9c34)

---

🌎 Idioma:
- 🇺🇸 [English](README.md)
  
---

- GBS é um software gratuito voltado à realização de análises estatísticas aplicadas à genética quantitativa e ao melhoramento vegetal.
- A seguir apresentamos o manual e um estudo de caso de um dos procedimentos de análise de dados realizados no software GBS.

---

## Análise Conjunta de Experimentos

---

### Delineamento de Blocos Aumentados

---

- Para fins de exemplo, foi utilizada a avaliação de 493 tratamentos de uma espécie vegetal em três experimentos quanto à gravidade específica (GE).

---

<p align="justify">
A figura a seguir mostra onde está localizado o procedimento de análise conjunta de experimentos em delineamento de blocos aumentados no software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/4980f9ff-72cf-4c97-8f61-1fb34a4680e7"  alt="Image">
</p>

<p align="justify">
A primeira etapa consiste em montar uma planilha em formato ".csv". Essa planilha deve conter a identificação dos experimentos na primeira coluna (S1), dos blocos (Blocos) na segunda coluna e dos Tratamentos (Trat) na segunda coluna. As demais colunas correspondem às características avaliadas, podendo haver uma ou mais. A figura a seguir apresenta o procedimento de análise utilizando o arquivo de exemplo do software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cf8e5535-1b71-4ffd-a774-6e101bea255d" alt="Image">
</p>

<p align="justify">
Após carregar o arquivo, o usuário deve acessar a aba de procedimentos e definir a natureza dos efeitos do modelo estatístico. Na aba procedimentos ainda é possível definir se a análise considerará as variâncias residuais e a de blocos como homogêneas ou heterogêneas. Além disso, caso o efeito de tratamento seja considerado fixo, é possível selecionar um teste de médias (aba Médias) a ser realizado juntamente com a análise. 
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/25e14ba4-ec88-4d42-ab3e-741693fd2115" alt="Image">
</p>

<p align="justify">
Após definir as configurações da análise, o usuário deve clicar no ícone azul de PLAY no canto superior esquerdo para executar a análise. Os resultados serão gerados nos formatos ".txt" e/ou ".xlsx".
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e75dab11-d170-494e-84af-f9506c75418d" alt="Image">
</p>

<p align="justify">
O arquivo de saída em formato ".txt" contém diversas informações, com destaque para os testes de efeitos fixos e/ou aleatórios. A seguir é apresentada a parte inicial desse arquivo.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/30925c9c-b1e6-4eef-af45-4e878cca52e1"  alt="Image">
</p>

<p align="justify">
Os resultados dos testes de efeitos fixos e aleatórios são apresentados a seguir:
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/9679de13-b458-458a-b03a-37b125b4a2b9" alt="Image">
</p>

<p align="justify">
A análise individual permitiu observar efeito significativo de tratamentos, ambientes e interação tratamentos por ambientes para o caráter M100G. O arquivo de resultados também apresenta a média do experimento (1071.0711) e o desvio padrão médio das variâncias entre tratamentos (5.7084).
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/bf518578-d96d-434c-ac25-ce866e4292bf" alt="Image">
</p>



