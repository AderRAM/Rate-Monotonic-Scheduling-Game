RM Scheduling Game

<img width="856" height="870" alt="image" src="https://github.com/user-attachments/assets/062f113b-868e-43bb-9069-f308c7162454" />

Simulador de escalonamento de tempo real para estudar RM, EDF e DM. Fiz para treinar e corrigir as questões da disciplina de Sistemas em Tempo Real, já que o Cheddar não funcionou aqui.

O arquivo principal é (rms_game.html). Abre no navegador, possui também uma imagem usada para background.

Como rodar

Baixe o arquivo e abra no navegador. Se quiser o fundo, coloque uma imagem chamada Astronaut.png na mesma pasta. Sem ela, funciona igual, só fica sem a imagem.

O que dá pra fazer

Você preenche a tabela com período, deadline, computação e prioridade de cada tarefa (até 8). Deadline vazio vale o período. O horizonte da simulação vai de 10 a 1000.

Alguns controles que valem explicar:

P=D: com ele ligado, todos os algoritmos usam o período como deadline. Desligado, usam o deadline da tabela.

Na aba de simulação, o botão Expandir mostra o resultado de cada algoritmo e o instante da primeira falha. Ali também ficam os botões N/V/F de cada algoritmo,
que filtram o gerador aleatório: N ignora, V exige que não falhe, F exige que falhe.
As outras abas são para praticar: prever se cada algoritmo funciona, montar o escalonamento na mão, ver a tabela de jobs e responder perguntas rápidas.
