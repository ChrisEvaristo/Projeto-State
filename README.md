# Projeto-State

Classificação :Padrão Comportamental




Intente -> Permitir  que um objeto  altere o seu comportamento  quando o seu estado  interno muda.




Motivação: motivado por aqueles objetos que, em seu estado atual, varia o seu comportamento devido as diferentes mensagens que possa receber.


Applicability->Está recomendado quando um determinado objeto tem estados e responsabilidades diferentes, dependendo de qual estado você está em determinado momento. Também pode ser usada para simplificar os casos em que há código complicado e extenso de decisão que depende do estado do objeto



Participantes:
Context -> Define a interface  com o cliente  e mantém  a instancia  de estado  concreto do qual define  o estado  atual do objeto.
State-> Interface que permite  encapsular as responsabilidades associadas ao estado particular de contexto.
ConcreteState->Um ou mais  estados concretos que implementam a interface estado.

