# iago_force-directed

# MATA53 - Force-directed graph drawing
Esse trabalho foi feito como uma das avaliações da disciplina de Teoria dos Grafos - MATA53, ministrada por Tiago Januário, pela Universidade Federal da Bahia (UFBA), feito pelo aluno Iago Pinto do Espirito Santo com a matrícula 201523035

### [**Link da apresentação do vídeo**](https://www.youtube.com/watch?v=Szaz4wSl50g)

# Force-directed graph drawing

Os algoritmos de Force-directed graph drawing servem para a visualização de grafos de uma forma fácil e interativa, através de uma representação espacial bidimensional ou tridimensional das posições dos vértices e das arestas de um grafo, de forma que suas arestas possuam o tamanho o mais uniforme possível e que evitando ao máximo quaisquer sobreposições de vértices.
Essa representação só é possível através de uma simulação de forças entre o conjunto de arestas e o de vértices, onde são consideradas as suas posições relativas para rearranjar o grafo na simulação para alcançar um arranjo distribuído e estável.
É válido dizer que esses algoritmos não requerem conhecimentos avançados sobre a Teoria dos Grafos.

A simulação de forças que são buscadas nesses algoritmos são baseadas na lei de Hooke, usada para atrair as extremidades das arestas dos grafos, e na lei de Coulomb, que busca repulsar pares de vértices nos grafos, com o objetivo de formar um sistema de forças que combinem atrações das arestas e repulsões dos vértices.

Em uma simulação com a aplicação desses algoritmos, a visualização dessas interações ficam melhores a serem observadas. Algumas das principais vantagens é a visualização com boa qualidade para uma quantidade razoável de vértices e interações; a flexibilidade, pois esses algoritmos podem ser adaptados à necessidade do problema, com a possibilidade de adicionar bibliotecas e outras extensões compatíveis e disponíveis gratuitamente, como a biblioteca D3.js, ou conhecida também como Data-Driver Documents.

### D3.js
D3.js é uma biblioteca de JavaScript que permite a manipulação de documentos que são baseados em informações que podem ser convertidas em HTML, SVG e CSS, normalmente voltado para aplicações WEB com o objetivo de melhor visualização de elementos e informações DOM (Document Object Model) dessas informações.

# Execução do Programa
Para poder acessar o algoritmo implementado, basta clonar o repositório e abrir o documento HTML [index.html](https://github.com/iagoesp/force-directed/blob/main/index.html) em um navegador, com acesso a internet.

Após o clone e abrir a página, o usuário pode criar os vértices e arestas seguindo as orientações das instruções para cada função. Ao final, é possível visualizar o grafo a partir do input definido e baixar uma cópia da visualização em PDF.

Para a visualização do algoritmo, você deverá acessar o outro arquivo em [JavaScript](https://github.com/iagoesp/force-directed/blob/main/scripts.js).

