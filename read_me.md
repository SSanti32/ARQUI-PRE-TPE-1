mateo:
1).
alias dcom='docker run -v ~/arqui/pre_tpe/RowDaBoat:/root --security-opt seccomp:unconfined -ti -w /root agodio/itba-so:1.0 ${1}';
2).
alias dcom2='docker run -v  ~/arqui/ARQUI-PRE-TPE/pre_tpe/RowDaBoat:/root --security-opt seccomp:unconfined -ti -w /root agodio/itba-so:1.0 ${1}';

santi:
1) el posta:

alias dcom='sudo docker run -v ~/ARQUI/ARQUI-PRE-TPE/pre_tpe/RowDaBoat:/root -ti -w /root agodio/itba-so:1.0 ${1}';

2)Back up

alias dcom_BU='sudo docker run -v ~/ARQUI/PRE_TPE_BACK_UP/RowDaBoat:/root -ti -w /root agodio/itba-so:1.0 ${1}';

hola
