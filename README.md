# 8-Febrero
Actividades de Matlab
%Script para resolver un sistema de ecuaciones
clc
clear

syms x a

Sol=2*x+a-5

solve(Sol,x)

%___________________________________


%Script para resolver un sistema de ecuaciones
clc
clear

syms x a b

Sol=x.^2+a*x+b

y=solve(Sol,x)

%_________________________


%Script para resolver un sistema de ecuaciones
clc
clear

syms x

Sol=2*exp(x)+3*cos(x)

y=solve(Sol,x)


%_______________________________________

%Script para resolver un sistema de ecuaciones
clc
clear

syms x y c

A=[2 -3*c; c 2];

B=[5; 7]

IA=inv(A)

Sol=IA*B

%_______________________________________

%Script para resolver un sistema de ecuaciones
clc
clear

syms x y

A=[3 -2; 0 1+y];
B=[7-y; 5];

IA=inv(A);

%Solucion
Sol=IA*B;
