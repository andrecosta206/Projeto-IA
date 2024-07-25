# Otimização de Picking em Armazéns
Este projeto visa otimizar o processo de recolha de produtos (picking) em armazéns. 
Utilizando algoritmos genéticos e o algoritmo de busca A*, a aplicação distribui produtos entre agentes e define a ordem de recolha, com o objetivo de minimizar o tempo de entrega do último produto, a distância total percorrida e o número de colisões entre agentes.

## Funcionalidades
**Leitura de Problemas:** O utilizador pode escolher o problema a ser resolvido a partir de ficheiros de texto que contêm matrizes representando o layout do armazém. <br />
**Distribuição de Produtos:** Utilização de algoritmos genéticos para distribuir produtos de forma eficiente entre os agentes de recolha. <br />
**Otimização de Rotas:** Implementação do algoritmo A* para calcular o caminho mais eficiente entre a posição inicial dos agentes, os produtos a serem recolhidos e o ponto de entrega. <br />
**Minimização de Colisões:** Redução do número de colisões entre agentes durante o processo de recolha.

### Tecnologias Utilizadas
 - **Python**<br />
 - **Algoritmos Genéticos** <br />
 - **Algoritmo de Busca A***<br />
 - **Leitura e Manipulação de Matrizes**<br />
 
## Exemplo de data set


 
## Como Executar
**Escolha do Problema:** Selecione o ficheiro de texto que contém a matriz representando o armazém. <br />
**Configuração Inicial:** Defina os parâmetros dos algoritmos genéticos e do algoritmo A* conforme necessário. <br />
**Execução:** Execute a aplicação para calcular a distribuição de produtos e as rotas otimizadas. <br />
**Resultados:** Analise os resultados gerados, que incluem a ordem de recolha para cada agente e as rotas calculadas. <br />

