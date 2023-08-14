# Detecção de veículos

### UFMG <br> 2023.1 <br> Machine Learning
***
Trabalho Final<br>
Diego Tomaz<br>

Este trabalho visa criar um **`sistema de detecção de veículos`** (**traseira e lateral** de veículos). Em um contexto da vida real, imaginemos que há uma rua em que o trafego de veículos é proibido e, portanto, há necessidade de se fiscalizar se tal regra é respeitada e aplicar as medidas cabíveis. 

Nesse sentido, podemos exemplificar esse trecho da `Rua Rio de Janeiro`, no centro de Belo Horizonte, em que habitualmente há fluxo apenas de pedestres mas que, em um cenário hipotético, poderia haver fiscalização automática do trânsito de veículos.

![image](https://github.com/diego-tomaz/ml_deteccao_veiculos/assets/54359164/4509c8b6-5efa-49af-9993-e38d41bd1499)
<a href="https://joaodiniz.wordpress.com/2009/12/26/rua-rio-de-janeiro-praca-sete-de-setembro/">Fonte da imagem</a>

Para tal, utilizei o dataset disponibilizado pela Universidade Politécnica de Madrid (https://www.gti.ssr.upm.es/data/Vehicle_database.html). O algoritmo escolhido para atingir o objetivo desse projeto é baseado em deep learning e, mais especificamente, emprega uma arquitetura de **`Rede Neural Convolucional`**.

As Redes Neurais Convolucionais são um subconjunto dos algoritmos de aprendizado de máquina que se mostram particularmente eficientes para tarefas de processamento de imagem e reconhecimento de padrões, o que é o caso.

Sua eficácia é explicada pela capacidade de aprender automaticamente hierarquias de características abstratas a partir dos dados de entrada. As camadas inferiores das CNNs geralmente aprendem a detectar recursos de baixo nível, como bordas e cores, enquanto as camadas superiores combinam esses recursos para identificar padrões mais complexos, como formas ou objetos.

