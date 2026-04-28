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

### Delineamento de Látices (Quadrado, Retangular e Alpha Látices)

---

- Para fins de exemplo, foi utilizada a avaliação de 49 tratamentos de uma espécie vegetal em dois experimentos quanto à severidade de crestamento bacteriano (SCB).

---

<p align="justify">
A figura a seguir mostra onde está localizado o procedimento de análise conjunta de experimentos em delineamento de Látices no software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a62a2eb4-7e66-4a5a-bc12-1dcc27fd6088"  alt="Image">
</p>

<p align="justify">
A primeira etapa consiste em montar uma planilha em formato ".csv". Essa planilha deve conter a identificação dos experimentos na primeira coluna (Amb), das repetições (REP) na segunda coluna, dos blocos na terceira repetição (Blocos) e dos Tratamentos (Trat) na quarta coluna. As demais colunas correspondem às características avaliadas, podendo haver uma ou mais. A figura a seguir apresenta o procedimento de análise utilizando o arquivo de exemplo do software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cc5f0b7a-24ec-4537-b685-297e2438d05e" alt="Image">
</p>

<p align="justify">
Após carregar o arquivo, o usuário deve acessar a aba de procedimentos e definir a natureza dos efeitos do modelo estatístico. Na aba procedimentos ainda é possível definir se a análise considerará as variâncias residuais e a de blocos como homogêneas ou heterogêneas. Além disso, caso o efeito de tratamento seja considerado fixo, é possível selecionar um teste de médias (aba Médias) a ser realizado juntamente com a análise. 
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ac42f32f-1b6c-4b62-8652-f5d04ec5bf4c" alt="Image">
</p>

<p align="justify">
Após definir as configurações da análise, o usuário deve clicar no ícone azul de PLAY no canto superior esquerdo para executar a análise. Os resultados serão gerados nos formatos ".txt" e/ou ".xlsx".
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a0014728-edbb-4630-a2a1-90dfd982631a" alt="Image">
</p>

<p align="justify">
O arquivo de saída em formato ".txt" contém diversas informações, com destaque para os testes de efeitos fixos e/ou aleatórios. A seguir é apresentada a parte inicial desse arquivo.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/35d19606-281b-4fc2-b81a-9a9db24b895b"  alt="Image">
</p>

<p align="justify">
Os resultados dos testes de efeitos fixos e aleatórios são apresentados a seguir:
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b48ddf9e-18d6-4e82-b922-b68853a038ad" alt="Image">
</p>

<p align="justify">
A análise individual permitiu observar efeito significativo de tratamentos e ambientes. Entretanto, não foi observado efeito significativo da interação tratamentos por ambientes para o caráter SCB. O arquivo de resultados também apresenta a média do experimento (6.0510), herdabilidade (0.5938) e acurácia (0.7627).
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a98ed9d3-5c81-47fc-9ffc-07ba9ac8cbd1" alt="Image">
</p>



