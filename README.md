# 📘 TP2 - Trabalho Prático 2
# Tópicos Especiais em Algoritmos — Problema de Sequenciamento em Máquina Única com Atraso Total (SMTTP)
🧠 Sobre o Projeto

Este trabalho prático tem como objetivo implementar e testar uma meta-heurística de busca local para resolver o Problema de Sequenciamento em Máquina Única com Atraso Total (SMTTP), um problema clássico de otimização combinatória.

A ideia central é minimizar o somatório dos atrasos das tarefas, onde cada tarefa possui um tempo de processamento e uma data de entrega. A ordem em que as tarefas são executadas influencia diretamente o resultado final.

🧩 O que foi implementado

✅ Estrutura de dados
Classe Tarefa, que representa cada tarefa com ID, tempo de processamento (pj) e data de entrega (dj).

✅ Função objetivo

Função calcular_atraso_total(), responsável por calcular o total de atraso de uma sequência de tarefas.

✅ Geração de vizinhos

Swap: troca duas tarefas de posição.

Insertion: remove uma tarefa e a insere em outro ponto da sequência.

✅ Meta-heurística genérica (busca local)

Implementação de uma estratégia simples de busca local iterativa, testando vizinhos e buscando sempre a melhor solução encontrada.

Opções de escolha entre os movimentos: swap ou insert.

✅ Geração de dados sintéticos

Um conjunto fixo de tarefas foi criado para simular diferentes execuções e testar o desempenho do algoritmo.

✅ Comparação com heurística EDD

Heurística construtiva baseada em Earliest Due Date (data de entrega mais próxima).

🧪 Como executar

Abra o notebook no Google Colab.

Rode todas as células a partir do topo.

Observe as sequências de tarefas geradas, o valor do atraso inicial e os resultados após aplicação da meta-heurística com os dois movimentos (swap e insertion).

Ao final, é exibido também o resultado da heurística EDD para comparação.

⚙️ Requisitos

Python 3 (Google Colab já oferece)

Nenhuma biblioteca externa além de random, copy e time, já incluídas por padrão.
