# Projeto Prático - Software

Este projeto prático tem como objetivo introduzir os futuros novos membros da equipe a algumas das tecnologias utilizadas dentro da área, com destaque no código usado para controlar o drone e com interações com o ambiente possíveis maneiras de obter informação dele. O intuito desse projeto é que os candidatos tenham a oportunidade de conhecer e ganhar experiência com essas tecnologias essenciais para a área de software da equipe EDRA.

## Material de estudo

Para o início do projeto, será fornecido um conjunto de materiais de estudo para auxiliar no desenvolvimento e no entendimento do funcionamento de cada parte do projeto. Este material será essencial para a explicação técnica do projeto durante a apresentação final.

*   **Opção 1: Visão Computacional**
    *   OpenCV para processamento de imagens e interface de usuário.
    *   Conceitos de filtros de imagem, morfologia matemática e segmentação por cor.

*   **Opção 2: Simulação ROS2 e PX4**
    *   Docker da PX4 para ambiente de simulação.
    *   ROS2 para comunicação e controle de robôs.
    *   PX4 e Gazebo para simulação de drones.
    *   MAVLINK e PX4_msgs para troca de mensagens com o drone simulado.

*   **Opção 3: Planejamento de Missão e Lógica de Decisão**
    *   Bibliotecas Python para Máquinas de Estados Finitos ou Árvores de Comportamento (e.g., python-statemachine, py\_trees).
    *   Conceitos de planejamento de missão, lógica de decisão e requisitos de missão.

## Escopo

O projeto prático será individual e os candidatos deverão escolher **uma** dentre as três opções a seguir:

*   **Opção 1: Visão Computacional para Detecção de Formas Geométricas Coloridas**
    *   Desenvolver um programa capaz de detectar formas geométricas específicas (círculos, quadrados, triângulos, ou formas compostas) com cores predefinidas em imagens ou vídeos, utilizando OpenCV.

*   **Opção 2: Criação de Missões Paramétricas em Simulação ROS2/PX4**
    *   Implementar missões de navegação autônoma paramétricas em ambiente de simulação ROS2/PX4. O foco será na compreensão do ROS2, PX4 e Gazebo, criando missões configuráveis por parâmetros (trajetória, controle, etc.) e monitorando dados via terminal (requisito opcional de dashboard para visualização gráfica).

*   **Opção 3: Planejamento de Missão com Máquina de Estados ou Árvore de Comportamento**
    *   Desenvolver um sistema de planejamento de missão baseado em Máquina de Estados Finita ou Árvore de Comportamento para um drone simulado (sem Gazebo, podendo incluir testes automatizados com cadeias de Markov). A missão consistirá em seguir uma linha até uma base de pouso identificada, justificando as escolhas de design e implementação.

Os requisitos exatos e funcionalidades de cada opção, incluindo requisitos obrigatórios e opcionais, serão detalhados em um manual específico para cada projeto, juntamente com o material de estudos organizado e exemplos de código.

## Avaliação

Os candidatos deverão apresentar o projeto escolhido, demonstrando o cumprimento dos requisitos especificados e a compreensão das tecnologias envolvidas. A avaliação será baseada na apresentação final do projeto, na explicação do processo de desenvolvimento e na capacidade de responder a dúvidas técnicas. Não será obrigatório um relatório escrito, mas a clareza na explicação e a qualidade do código serão criteriosamente avaliadas.