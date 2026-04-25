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

### Delineamento de Blocos Aumentados

---

- Para fins de exemplo, foi utilizada a avaliação de 493 tratamentos de uma espécie vegetal quanto à gravidade específica (GE).

---

<p align="justify">
A figura a seguir mostra onde está localizado o procedimento de análise individual de experimentos em delineamento de blocos aumentados no software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d861b898-7404-45aa-8621-ca39feefab6f" alt="Image">
</p>

<p align="justify">
A primeira etapa consiste em montar uma planilha em formato ".csv". Essa planilha deve conter, obrigatoriamente, a identificação dos blocos na primeira coluna e a dos Tratamentos na segunda coluna. As demais colunas correspondem às características avaliadas, podendo haver uma ou mais. A figura a seguir apresenta o procedimento de análise utilizando o arquivo de exemplo do software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/2aa46b18-8789-477d-9d87-20a68d184537" alt="Image">
</p>

<p align="justify">
Após carregar o arquivo, o usuário deve acessar a aba de procedimentos e definir a natureza dos efeitos do modelo estatístico. Caso o efeito de tratamento seja considerado fixo, é possível selecionar um teste de médias a ser realizado juntamente com a análise.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/5e29d069-062a-4ee6-a5cc-ffc3c131fb2d" alt="Image">
</p>

<p align="justify">
Após definir as configurações da análise, o usuário deve clicar no ícone azul de PLAY no canto superior esquerdo para executar a análise. Os resultados serão gerados nos formatos ".txt" e/ou ".xlsx".
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/6cea531f-63f8-48ff-9014-167e23417a85" alt="Image">
</p>

<p align="justify">
O arquivo de saída em formato ".txt" contém diversas informações, com destaque para os testes de efeitos fixos e/ou aleatórios. A seguir é apresentada a parte inicial desse arquivo.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/2f2582f8-262d-446c-8088-73726ef51bb3" alt="Image">
</p>

<p align="justify">
Os resultados dos testes de efeitos fixos e aleatórios são apresentados a seguir:
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/65f19297-774e-40a9-b62e-54b06bcc83fa" alt="Image">
</p>

<p align="justify">
A análise individual permitiu observar efeito significativo de tratamentos para o caráter GE. O arquivo de resultados também apresenta a média do experimento (1067.3823), o coeficiente de variação (0.5389%) e o desvio padrão médio das variâncias entre tratamentos (9.8463).
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a6887218-741b-48af-8ddf-09f303ea0a18" alt="Image">
</p>

