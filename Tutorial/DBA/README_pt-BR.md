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

### Delineamento Inteiramente Casulizado

---

- Para fins de exemplo, foi utilizada a avaliação de 9 tratamentos de uma espécie vegetal quanto à massa seca total.

---

<p align="justify">
A figura a seguir mostra onde está localizado o procedimento de análise individual de experimentos em delineamento inteiramente casualizado no software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d861b898-7404-45aa-8621-ca39feefab6f" alt="Image">
</p>

<p align="justify">
A primeira etapa consiste em montar uma planilha em formato ".csv". Essa planilha deve conter os Tratamentos obrigatoriamente na primeira coluna. As demais colunas correspondem às características avaliadas, podendo haver uma ou mais. A figura a seguir apresenta o procedimento de análise utilizando o arquivo de exemplo do software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/2aa46b18-8789-477d-9d87-20a68d184537" alt="Image">
</p>

<p align="justify">
Após carregar o arquivo, o usuário deve acessar a aba de procedimentos e definir a natureza dos efeitos do modelo estatístico. Caso o efeito de tratamento seja considerado fixo, é possível selecionar um teste de médias a ser realizado juntamente com a análise.
</p>

<p align="center">
  <img src="https://github.com/VQCarneiro/GBS/issues/23#issue-4329357865" alt="Image">
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
  <img src="https://github.com/user-attachments/assets/6cea531f-63f8-48ff-9014-167e23417a85" alt="Image">
</p>

<p align="justify">
Os resultados dos testes de efeitos fixos e aleatórios são apresentados a seguir:
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/65f19297-774e-40a9-b62e-54b06bcc83fa" alt="Image">
</p>

<p align="justify">
A análise individual permitiu observar efeito não significativo de tratamentos para o caráter MST. O arquivo de resultados também apresenta a média do experimento (38.3925), o coeficiente de variação (14.8683%) e o desvio padrão médio das variâncias entre tratamentos (4.0364).
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/9d9b806c-6f06-49ab-b86c-cff822645d43" alt="Image">
</p>

