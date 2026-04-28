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

### Delineamento de Blocos Completamente Casualizados

---

- Para fins de exemplo, foi utilizada a avaliação de 29 tratamentos de uma espécie vegetal em dois experimentos quanto à massa de 100 grãos (M100G).

---

<p align="justify">
A figura a seguir mostra onde está localizado o procedimento de análise conjunta de experimentos em delineamento de blocos completamente casualizados no software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/68888a5a-b0f6-4c64-a827-ea697dc4610a"  alt="Image">
</p>

<p align="justify">
A primeira etapa consiste em montar uma planilha em formato ".csv". Essa planilha deve conter a identificação dos experimentos na primeira coluna (Amb), das repetições (REP) na segunda coluna e dos Tratamentos (Trat) na segunda coluna. As demais colunas correspondem às características avaliadas, podendo haver uma ou mais. A figura a seguir apresenta o procedimento de análise utilizando o arquivo de exemplo do software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/1b00e7b1-60b4-4a2c-ba18-b3f5554c73c3" alt="Image">
</p>

<p align="justify">
Após carregar o arquivo, o usuário deve acessar a aba de procedimentos e definir a natureza dos efeitos do modelo estatístico. Na aba procedimentos ainda é possível definir se a análise considerará as variâncias residuais e a de blocos como homogêneas ou heterogêneas. Além disso, caso o efeito de tratamento seja considerado fixo, é possível selecionar um teste de médias (aba Médias) a ser realizado juntamente com a análise. 
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/558faaa9-87cb-445d-82c7-eeb136c93a1b" alt="Image">
</p>

<p align="justify">
Após definir as configurações da análise, o usuário deve clicar no ícone azul de PLAY no canto superior esquerdo para executar a análise. Os resultados serão gerados nos formatos ".txt" e/ou ".xlsx".
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/fc1570ef-4276-47cf-bc57-7e9cf738de86" alt="Image">
</p>

<p align="justify">
O arquivo de saída em formato ".txt" contém diversas informações, com destaque para os testes de efeitos fixos e/ou aleatórios. A seguir é apresentada a parte inicial desse arquivo.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/09242d6b-fce1-4651-af39-62fed93cbe72"  alt="Image">
</p>

<p align="justify">
Os resultados dos testes de efeitos fixos e aleatórios são apresentados a seguir:
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/31a0da96-0939-4b6b-9d22-d729c1dd2737" alt="Image">
</p>

<p align="justify">
A análise individual permitiu observar efeito significativo de tratamentos, ambientes e interação tratamentos por ambientes para o caráter M100G. O arquivo de resultados também apresenta a média do experimento (27.3064) e o desvio padrão médio das variâncias entre tratamentos (0.8424).
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/427271b0-8260-4b46-b579-205d9b383e8d" alt="Image">
</p>


