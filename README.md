# projectWSE

Dawid Sznajder, Informatyka Stosowana I rok:

https://wokwi.com/projects/321677895528350291

Projekt przedstawia mikrokontroler Arduino MEGA z programem sterującym
w symulatorze WOKWI. 

Za przyjetą metodę działania można uznać zamianę liczb w systemie binarnym
na system dziesiętny. 4 diody symbolizują wagi bitów w zapisie dwójkowym.
W momencie gdy LED jest zapalony utożsamiamy go z cyfrą "1" natomiast zgaszony
z cyfrą "0".

Przekręcając wskazówkę potencjometru możemy regulować napięcie. 
Ustawiając niskie napięcie zwiększamy szybkość wykonywania się petli; zwiększając
napięcie pętla przebiega wolniej.

Wadą projektu jest to, że trzeba na starcie przestawić napięcie 
na potencjometrze przekręcając wskazówkę w prawą stronę po to,
aby pętla przebiegała wolniej i można było zobaczyć 
działanie projektu. Najpierw należy uruchomić symulację, następnie
zwiększyć napięcie.
