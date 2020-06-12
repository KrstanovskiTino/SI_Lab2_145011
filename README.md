# Втора лабораториска вежба по Софтверско инженерство 
## Тино Крстановски, бр. на индекс 145011
### Група на код:
Група 6

### Control Flow Graph 
![CFG Diagram (1)](https://user-images.githubusercontent.com/37616613/84551486-1adc1600-ad0e-11ea-825c-07eb1fb3bb25.png)
### Цикломатска комплексност 
Цикломатската комплексност на овој код може да ја пресметаме со формулата: Е-N+2 <br/>
N - број на темиња = 15<br/>
E - број на ребра = 20<br/>
20-15+2 = 7<br/>
Цикломатската комплексност ќе биде 7.

### Тест случаи според критериумот Every branch 
Со Every Branch критериумот треба да ги поминеме сите можни услови во графот. 
Тест примери: 6
20 degrees 55 minutes 40 seconds (A-B, B-C, C-F, F-G, G-P, P-B)<br/>
360 degrees 0 minutes 0 seconds (A-B, B-C, C-J, J-K, K-L, L-N, N-P, P-B)<br/>
360 degrees 0 minutes 20 seconds (A-B, B-C, C-J, J-K, K-M, M-N, N-P, P-B)<br/>
420 degrees 15 minutes 15 seconds (A-B, B-C, C-O, O-P, P-B)<br/>
70 degrees 62 minutes 20 seconds (A-B, B-C, C-D, D-G, G-P, P-B)<br/>
92 degrees 40 minutes -8 seconds (A-B, B-C, C-E, E-G, G-P, P-Q)<br/>
A-B;
B-C;
C-D;
C-E;
C-F;
C-J;
C-O;
D-G;
E-G;
F-G;
J-K;
K-L;
K-M;
L-N;
M-N;
O-P;
G-P;
N-P;
P-B;
P-Q;

### Тест случаи според критериумот Every path
Со Every Path критериумот ги поминуваме сите можни патеки во графот.<br/>
1.ABCFGPB<br/>
2.ABCJKLNPB<br/>
3.ABCJKMNPB<br/>
4.ABCOPB<br/>
5.ABCDGPB<br/>
6.ABCEGPQ
