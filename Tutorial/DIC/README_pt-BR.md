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

### Delineamento de Blocos Completos Casualizados

---

- Para fins de exemplo, foi utilizada a avaliação de 30 tratamentos de uma espécie vegetal quanto à massa de 100 grãos.

---

<p align="justify">
A figura a seguir mostra onde está localizado o procedimento de análise individual de experimentos em delineamento de blocos completos casualizados no software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/bdd54d8c-800d-4920-af12-880056d720a2" alt="Image">
</p>

<p align="justify">
A primeira etapa consiste em montar uma planilha em formato ".csv". Essa planilha deve conter obrigatoriamente as colunas Repetição e Tratamentos, nessa ordem. As demais colunas correspondem às características avaliadas, podendo haver uma ou mais. A figura a seguir apresenta o procedimento de análise utilizando o arquivo de exemplo do software.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/4c8fe6fb-d5f7-4a80-b8d8-fb1ac2b8eec0" alt="Image">
</p>

<p align="justify">
Após carregar o arquivo, o usuário deve acessar a aba de procedimentos e definir a natureza dos efeitos do modelo estatístico. Caso o efeito de tratamento seja considerado fixo, é possível selecionar um teste de médias a ser realizado juntamente com a análise.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/67ed1667-5449-4ce9-83aa-c1c4934a30d9" alt="Image">
</p>

<p align="justify">
Após definir as configurações da análise, o usuário deve clicar no ícone azul de PLAY no canto superior esquerdo para executar a análise. Os resultados serão gerados nos formatos ".txt" e/ou ".xlsx".
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c708a766-dbc8-4189-be38-2d23b1255be2" alt="Image">
</p>

<p align="justify">
O arquivo de saída em formato ".txt" contém diversas informações, com destaque para os testes de efeitos fixos e/ou aleatórios. A seguir é apresentada a parte inicial desse arquivo.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/efc46175-6e48-4d55-98d9-bfc733308197" alt="Image">
</p>

<p align="justify">
Os resultados dos testes de efeitos fixos e aleatórios são apresentados a seguir:
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/40cfcea2-03e5-42c1-b741-74982c61347e" alt="Image">
</p>

<p align="justify">
A análise individual permitiu observar efeito significativo de tratamentos para o caráter M100G. Verificou-se que 97,07% da variação total foi atribuída ao efeito de tratamentos. O arquivo de resultados também apresenta a média do experimento (28,7301 g), o coeficiente de variação (3,4161%) e o desvio padrão médio das variâncias entre tratamentos (0,8085).
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a2017004-1780-4172-8e82-040aaf36533b" alt="Image">
</p>

