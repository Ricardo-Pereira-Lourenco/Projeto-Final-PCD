![image](https://github.com/Lorena881/PCD_Analise_Espectroscopia/assets/172424739/e6ca9dbf-861e-4b91-91fe-0691270a5773)

# <h1 align="center"> Analise De Sistemas Lineares

## Projeto de final de semestre da disciplina praticas em ciências de dados

**Instituição: Ilum Escola de Ciência**

**Aluno: Ricardo Pereira Lourenço de Carvalho**

**Docentes: Daniel R. Cassar, James M. de Almeida, Leandro N. Lemos**

# 📄 Descrição do projeto
**Este projeto automatiza o processo da resolução de sistemas lineares 3x3 e 2x2 e da classificação destes**

# 📄 Detalhamento do código
**Este programa em python busca solucionar sistemas lineares 3x3 e 2x2, covertendo os em matrizes 3X4 e matrizes 2x3 respectivamente. Assim, os metodos de calculo utilizados neste código se baseiam em matrizes triangulares como o método de eliminação de Gauss.**

**O sistema linear:**
 
        1 x + 2 y + 3 z = 11

        3 x + 2 y + 1 z = 9

        2 x + 3 y + 1 z = 10

**Tem como representação matricial:**

$$
M =
\begin{bmatrix}
1 & 2 & 3 & 11 \\
3 & 2 & 1 & 9 \\
2 & 3 & 1 & 10
\end{bmatrix}
$$

**E o código tem o objetivo de inicialmente converter a matriz reduzida (3x3) deste sistema em uma matriz triangular**

**O processo de transformar a matriz em uma matriz triangular é essencial, pois facilita o calculo computacional.
Neste sentido matrizes triangulares são aquelas que seguem o seguinte formato:**

$$
M =
\begin{bmatrix}
a & b & c \\
0 & d & e \\
0 & 0 & f
\end{bmatrix}
$$

**Ao final das seções Sistemas Lineares 2x2 e 3x3 existem seus respectivos sumários contendo informações da matriz inicial, tipo do sistema, determinantes e suas soluções caso existam:**
```python
"""
Exibe um resumo final do sistema.

Mostra:
sistema original
determinante
classificação
soluções (caso existam)
"""

print(f"Seu sistema inicial é:\n{M_3x3}")
print("")
print(f"A determinante da matriz é {determinante_3x3(matriz_copia_3x3)}")
print("")
print(tipo_sistema_3x3(matriz_copia_3x3))
print("")

if respostas_sistema_3x3(matriz_copia_3x3) is not None:

    print(f"Suas variáveis x, y e z são respectivamente:")
    print(f"x = {respostas_sistema_3x3(matriz_copia_3x3)['x']}") 
    print(f"y = {respostas_sistema_3x3(matriz_copia_3x3)['y']}")
    print(f"z = {respostas_sistema_3x3(matriz_copia_3x3)['z']}")
else:
    print("Não foram encontradas soluções ao seu sistema")
```

# 🖥️ Ferramentas Utilizadas
- **Jupyter Notebook para desenvolvimento do código**
- **Bibliotecas para aplicabilidade das funções expostas:**
    - **Numpy**
<img src="https://github.com/GabrielMartinsSousa/Projeto_PCD_Climogramas/assets/172425313/314dcd00-784b-4f40-b361-a46329aad30e" alt="Texto Alternativo" width="145">

# 📁 Acesso e Utilização

**O acesso do código pode ser dado pelo arquivo *Projeto final-Ricardo.ipynb***

# 🔎 Referências 
* OPENAI. ChatGPT . Disponível em: <https://chatgpt.com/>.

<img loading="lazy" src="https://github.com/Lorena881/PCD_Analise_Espectroscopia/assets/172424739/c930826b-3189-41d5-b4cc-a33dbf3ee611">
