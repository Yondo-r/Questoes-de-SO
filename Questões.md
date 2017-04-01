# Questoes-de-SO

1) Quais são as diferenças essenciais entre um aplicativocomum (por exemplo, o Microsoft Word) e um sistema operacional?

R: O Sistema operacional fica entre o Hardware e os programas/aplicativos. Já o Word é um programa ou aplicativo que necessita de um sistema operacional para funcionar.


2) Por que um sistema operacional é necessário?

R:Para permitir o compartilhamento dos recursos de
hardware por diversas aplicações.
Para facilitar o desenvolvimento de novas aplicações,
deixando o gerenciamento dos recursos de hardware a cargo do sistema operacional.


3) Que nome é dado às chamadas realizadas pelas aplicações aos serviços disponibilizados pelo sistema operacional? Mencione como exemplo duas destas chamadas.

R: Chamadas de sistemas (System Calls).
Create file
Ready file


4) O que é um processo?

R: é um trabalho em execução em um sistema computacional


5) Um processador com um único núcleo executa vários processos simultaneamente? Explique sua resposta.

R: Sim pois cada processo recebe uma parcela do tempo de execução no processador.


6) O que ocorre quando o sistema operacional faz o chaveamento entre processos?

R: O sistema operacional salva todo o estado do processo que está em execução e carrega o estado do processo que entrará em execução.


7) Qual é a diferença entre thread e processo?
R: O Thread é uma linha de execução de um processo
E um processo pode ter várias Threads


8) Qual é a diferença entre escalonamento preemptivo e não-preemptivo.

R: Preemptivo: É quando um processo que está em “execução” muda para “pronto” ou quando ele está em “espera” e muda para “pronto”

Não-preemptivo: é quando o processo que está em “execução” muda para “espera” ou quando um processo “encerra”.


9) Cite 2 algoritmos de escalonamento de processos e explique o funcionamento de cada um.

R: Escalonamento First-come, First-served - consiste em simplesmente atender as tarefas em sequência, à medida em que elas se tornam prontas

R: Escalonamento Shortest job First (SJF) – Consiste em
atender as tarefas que terminaram primeiro


10) Cite 2 recursos disponibilizados pelo sistema operacional para ajudar o programador a implementar programas concorrentes sem interferência entre threads, e diga em qual situação é mais conveniente utilizar cada recurso.

R: Semáforo – Mecanismo que garante que somente “N” processos podem acessar um certo recurso em um dado momento.
É conveniente usar quando um processo depende do outro 

Passagem de mensagens – Combinação de transferência de dados com exclusão Mútua e sincronização.
