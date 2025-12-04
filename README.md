# rc

Repositório com código para radiocontrole dos robôs da equipe usando esp-now como protocolo de comunicação.
Outros modos de comunicação (bluetooth clássico, ble, wifi, ir, via receptor de rádio) são planejados.

Eventualmente talvez se separe em projetos distintos para comunicação, robôs e controle.

## ressalvas

Se tiver usando um esp8266, os imports relativos não funcionam.
Tem que mover as headers comuns pra dentro da pasta do projeto específico quando for compilar.
