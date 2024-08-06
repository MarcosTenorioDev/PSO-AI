# Otimização por Enxame de Partículas (PSO)

Este projeto é uma aplicação simples desenvolvida para introduzir o conceito de Otimização por Enxame de Partículas (PSO) e algoritmos de otimização baseados em enxames. O projeto foi desenvolvido como parte do curso de Inteligência Artificial na Universidade Católica de Pernambuco.

![image](https://github.com/user-attachments/assets/7ba244f7-4d8d-415e-a29f-bbf7ede37b50)


## Introdução ao PSO
A Otimização por Enxame de Partículas (PSO) é um algoritmo de otimização inspirado no comportamento social de aves e peixes. Ele é usado para encontrar soluções aproximadas para problemas de otimização, baseando-se no movimento e interação de partículas (candidatos a soluções) que se ajustam com base em sua experiência pessoal e a de seus vizinhos.
Objetivo da Aplicação

A aplicação visa proporcionar uma visualização interativa do algoritmo PSO, permitindo que usuários observem como as partículas se movem em direção a um alvo em um espaço bidimensional e compreendam os princípios fundamentais dessa técnica.
Funcionalidades

- Criação de Partículas: Gera partículas com posições e velocidades iniciais aleatórias.
- Execução do PSO: Atualiza as partículas com base nas equações PSO iterativamente, movendo-as em direção ao melhor local conhecido por elas mesmas e pelo grupo.
- Alteração da Posição do Alvo: Move o alvo para uma nova posição aleatória, alterando a meta das partículas.
- Limpeza da Solução: Reseta o canvas e os dados das partículas.
- Histórico: Exibe o histórico do movimento das partículas, especialmente a partícula verde, incluindo várias métricas relevantes.

Como Funciona

- Número de Partículas: O usuário define o número de partículas que serão simuladas.
- Constantes C1 e C2: O usuário pode ajustar os valores das constantes (C1) e (C2) que influenciam a atualização das velocidades das partículas.
- Criação e Execução: Ao criar partículas, cada partícula é posicionada aleatoriamente no canvas. A execução do PSO move as partículas iterativamente em direção ao alvo, considerando suas melhores posições conhecidas e a melhor posição global.
- Histórico e Visualização: O movimento e os cálculos envolvidos do ponto verde são registrados e exibidos numa tabela, permitindo um acompanhamento detalhado de cada passo do algoritmo.
- Alvo e Reset: O usuário pode mudar a posição do alvo ou limpar a simulação para reiniciar o processo.

Esta aplicação oferece uma forma interativa e visual de entender como o PSO funciona.

Feito com carinho ❤ por MarcosTenorio 🚀
