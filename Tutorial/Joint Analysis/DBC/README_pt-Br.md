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

### Delineamento Inteiramente Casulizado

---

- Para fins de exemplo, foi utilizada a avaliação de 9 tratamentos de uma espécie vegetal em dois experimentos quanto à massa seca total (MST).

---

<p align="justify">
A figura a seguir mostra onde está localizado o procedimento de análise conjunta de experimentos em delineamento inteiramente casualizado no software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b2e0f0ed-6fe8-4dec-9581-f8070f704e0a" alt="Image">
</p>

<p align="justify">
A primeira etapa consiste em montar uma planilha em formato ".csv". Essa planilha deve conter a identificação dos experimentos na primeira coluna (Exp) e dos Tratamentos (Trat) na segunda coluna. As demais colunas correspondem às características avaliadas, podendo haver uma ou mais. A figura a seguir apresenta o procedimento de análise utilizando o arquivo de exemplo do software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/6abbb264-db41-4465-b4c2-7de02d7ea5c2" alt="Image">
</p>

<p align="justify">
Após carregar o arquivo, o usuário deve acessar a aba de procedimentos e definir a natureza dos efeitos do modelo estatístico. Na aba procedimentos ainda é possível definir se a análise considerará as variâncias residuais e a de blocos como homogêneas ou heterogêneas. Além disso, caso o efeito de tratamento seja considerado fixo, é possível selecionar um teste de médias (aba Médias) a ser realizado juntamente com a análise. 
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/316fa090-bd9c-40f9-873f-531d98558ba7" alt="Image">
</p>

<p align="justify">
Após definir as configurações da análise, o usuário deve clicar no ícone azul de PLAY no canto superior esquerdo para executar a análise. Os resultados serão gerados nos formatos ".txt" e/ou ".xlsx".
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c7a6815e-069c-4804-989b-d60090b065a9" alt="Image">
</p>

<p align="justify">
O arquivo de saída em formato ".txt" contém diversas informações, com destaque para os testes de efeitos fixos e/ou aleatórios. A seguir é apresentada a parte inicial desse arquivo.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/535f7702-d5d0-4768-ab9d-6ab6534e3186"  alt="Image">
</p>

<p align="justify">
Os resultados dos testes de efeitos fixos e aleatórios são apresentados a seguir:
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/4f507754-f585-4ff8-9b97-fc62020733c9" alt="Image">
</p>

<p align="justify">
A análise individual permitiu observar efeito não significativo de tratamentos para o caráter MST. O arquivo de resultados também apresenta a média do experimento (43.5907) e o desvio padrão médio das variâncias entre tratamentos (3.6587).
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/3863aad1-d91d-45f1-84e7-1f83c6fda328" alt="Image">
</p>


