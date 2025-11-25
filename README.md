## 📄 Sobre o Projeto

Este repositório contém a implementação de um sistema de roteamento urbano que utiliza dados geográficos reais do **OpenStreetMap (OSM)** para encontrar o caminho mais curto entre dois pontos.

Diferente de abordagens cegas (como o Dijkstra padrão), este projeto utiliza o **Algoritmo A* (A-Star)** com uma heurística de distância Euclidiana, otimizando drasticamente o tempo de busca e a exploração do grafo.

O projeto foi desenvolvido como parte da disciplina de **Teoria dos Grafos** no **IFNMG (Instituto Federal do Norte de Minas Gerais)**.

---

## ✨ Funcionalidades

* **📍 Dados Reais:** Download automático da malha viária de Montes Claros via `OSMnx`.
* **🧠 Algoritmo A*:** Busca informada utilizando distância geodésica como heurística para otimização.
* **⌨️ Interatividade:** Interface que permite adicionar novos pontos de interesse (vértices) dinamicamente via terminal.
* **🎨 Visualização Rica:** Geração de mapas de rota, grafos completos e diagramas esquemáticos.

---

## 🚀 Como Executar

A maneira mais recomendada de testar este projeto é através do **Google Colab**, pois ele já gerencia as bibliotecas geoespaciais complexas.

### Opção 1: Google Colab (Recomendado)
1. Clique no botão **"Open in Colab"** no topo deste README.
2. No menu do Colab, vá em **Ambiente de Execução** > **Executar tudo** (ou `Ctrl+F9`).
3. O script irá baixar o mapa, calcular a rota e mostrar os resultados interativamente.

### Opção 2: Execução Local (Python)
Se preferir rodar na sua máquina:

1. Clone o repositório:
   ```bash
   git clone https://github.com/GabrielDavi7/A-Star_Search_Algorithm.git
   cd A-Star_Search_Algorithm
2. Instale as dependências:
    ```bash
   pip install osmnx networkx matplotlib
3. Execute o script:
