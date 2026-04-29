1 - Entradas e saídas do sistema:
As entradas são os botões e o potenciômetro. 
A saída será o LED RGB.

2 - Componentes do sistema:
LED RGB indica os diferentes modos de uma máquina industrial, onde a cor verde sinaliza (operação normal), a cor amarela (modo de atenção) e a cor vermelha (modo crítico).  Para cada uma dessas, tem um  que controla qual das cores será do LED. O potenciômetro controla a intensidade da luz, com valores de 0 a 1023, podendo deixar ela mais forte ou mais fraca.

3 - Regras de funcionamento:
Se dois botões forem pressionados ao mesmo tempo, o LED não deve fazer misturas de cores  mantendo apenas a que o botão determinar, o mesmo vale para o potenciômetro que apenas irá mudar a intensidade da cor, sem fazer misturas entre elas. 

4 - Estruturas do if:
A estrutura de if será utilizada para determinar qual cor cada botão deve acionar, se o primeiro botão for pressionado, a luz verde acenderá indicando “operação normal”. Se o segundo botão for pressionado, a luz amarela acenderá indicando “modo de atenção”. Se o terceiro botão for pressionado,a luz vermelha acenderá indicando “modo crítico”. Por fim, quando o botão de desligamento for pressionado, o LED voltará ao seu estado inicial.
