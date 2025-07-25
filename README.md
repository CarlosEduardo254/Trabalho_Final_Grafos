# Trabalho Final - Algoritmo de Christofides para o Problema do Caixeiro Viajante

Este projeto implementa uma solução aproximada para o **Problema do Caixeiro Viajante (TSP)** em grafos completos, utilizando o **Algoritmo de Christofides**. O algoritmo garante uma solução com custo no máximo 1,5 vezes o custo da solução ótima.

---

### **Tecnologias e Bibliotecas**

- **Python 3**
- **NetworkX** para manipulação de grafos e emparelhamento de custo mínimo.
- **Matplotlib** para a visualização gráfica dos resultados.
- **Heapq** para otimização do algoritmo de Prim com uma fila de prioridade.

---

### **Execução**

O projeto pode ser executado em um ambiente local (com Python instalado na sua máquina) ou em um ambiente online como o Google Colab.

#### **1. Ambiente Local**

**Instalação:**
Para executar o projeto localmente, é necessário ter o **Python 3**, o seu gerenciador de pacotes **`pip`** e o Jupyter Notebook (ou outra ferramenta compatível) instalados. As bibliotecas podem ser instaladas via `pip`.

```bash
pip install networkx matplotlib jupyter
```

**Como rodar:**
1.  Clone ou baixe o repositório e certifique-se de que o notebook `Trabalho_Final_de_Grafos.ipynb` e os arquivos de entrada (`bayg29.tsp.txt` e `si175.tsp.txt`) estão no mesmo diretório.
2.  Abra o terminal, navegue até o diretório do projeto e inicie o Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
3.  No seu navegador, abra o arquivo `Trabalho_Final_de_Grafos.ipynb`.
4.  Localize a célula principal e altere o nome do arquivo de entrada conforme desejado:
    ```python
    # Altere o nome do arquivo para 'bayg29.tsp.txt' ou 'si175.tsp.txt'
    arquivo = 'bayg29.tsp.txt'
    ```
5.  Execute todas as células do notebook.

#### **2. Ambiente Online (Google Colab)**

**Instalação:**
O Google Colab já vem com a maioria das bibliotecas pré-instaladas. Caso alguma não esteja disponível, você pode instalá-la executando o seguinte comando em uma célula do notebook:

```python
!pip install networkx matplotlib
```

**Como rodar:**
1.  Abra o notebook diretamente no Google Colab através do seguinte link: [Abrir no Colab](https://colab.research.google.com/github/CarlosEduardo254/Trabalho_Final_Grafos/blob/main/Trabalho_Final_de_Grafos.ipynb).
2.  No painel lateral esquerdo, clique no ícone de pasta para abrir a aba "Arquivos". Faça o upload dos arquivos de entrada necessários para o ambiente:
    - `bayg29.tsp.txt`
    - `si175.tsp.txt`
3.  Localize a célula principal e altere o nome do arquivo de entrada conforme desejado:
    ```python
    # Altere o nome do arquivo para 'bayg29.tsp.txt' ou 'si175.tsp.txt'
    arquivo = 'bayg29.tsp.txt'
    ```
4.  Execute todas as células do notebook (`Ambiente de execução > Executar tudo`).

---

A saída para ambos os ambientes incluirá os passos do algoritmo, o caminho hamiltoniano aproximado, o custo total da solução e a visualização gráfica do resultado.
