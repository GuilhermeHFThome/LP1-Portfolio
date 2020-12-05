# LP1-Portfolio
Listas python tiago

#########################
#lista pratica de sintaxe
#########################

#numero 1
print('declare os valores')

a = 44 + 1
b = 6 + 20 - 23
c = 3.0 + 5.0 + 1
d = 1/4 + 2
e = 29/7 + 4
f = 3/6.0 - 7
g = 2/2
h = 2//2
i = 4%2
j = (100//5)%5

print('A=',a,)
print('B=',b,)
print('C=',c,)
print('D=',d,)
print('E=',e,)
print('F=',f,)
print('G=',g,)
print('H=',h,)
print('I=',i,)
print('J=',j,)

#numero 2
def main():
  x = int(input('Digite o primeiro número: '))
  y = int(input('Digite o segundo número: '))

  mult(x, y)
def mult(x, y):
  print(x * y)

main()

#numero 3
def main():
  x = int(input('Digite um número: '))

  raiz_qua(x)
  raiz_cub(x)

def raiz_qua(x):
  print(x**(1/2))
  print('Índice: ', 2)

def raiz_cub(x):
  print(x**(1/3))
  print('Índice: ', 3)

main()

#numero 4
def main():
  l = int(input('Digite valor para lado: '))
  h = int(input('Digite valor para altura: '))
  b = int(input('Digite valor para base: '))

  Quadrado(l)
  Triangulo(b,h)
  Retangulo(l,h)

def Quadrado(l):
  print(l**2)
def Triangulo(b,h):
  print(b*h/2)
def Retangulo(l,h):
  print(l*h)

main()

#numero 6
#letra a:

n = int(input('Digite um numero: '))

A = n**2

print('Resultado A: ', A)

#letra b:

x = int(input('Digite um valor: '))
y = int(input('Digite um valor: '))

B = x/y

print('Resultado B: ', B)

#letra c:

x = int(input('Digite um valor: '))

C = x % 2

print('Resultado C: ', C)




#letra d:
x = int(input('Digite o primeiro número: '))
y = int(input('Digite o segundo número: '))

media = (x+y)/2

print(media)


#letra e:
raio = int(input('Digite o valor do raio: '))

diametro = raio * 2

pi = 3.14
#comp = comprimento da circunferência
comp = 2 * pi * raio

area = pi * (raio**2)

print('O comprimento da circunferência é: ', comp)
print('A área da circunferência é: ', area)

#numero 7

'''
a = Verdadeiro
b = Falso ou Falso
c = Falso e Falso
e = 2<3(Verdadeiro)

'''

######################
#lista 1 python tiago
######################

'''
Num. 1 (Feito)
'''
# A
x = int(input('Declare um valor: '))

print(x**2)

# C
x = int(input('Declare um valor: '))
y = int(input('Declare um valor: '))

print(x/2)

# C
x = int(input('Declare um valor: '))

print(x%2)

# D
raio = int(input('Digite o valor do raio: '))

diametro = raio * 2

pi = 3.14
#comp = comprimento da circunferência
comp = 2 * pi * raio

area = pi * (raio**2)

print('O comprimento da circunferência é: ', comp)
print('A área da circunferência é: ', area)

'''
Num. 2 (Feito)
'''
print('declare os valores')

a = 44 + 1
b = 6 + 20 - 23
c = 3.0 + 5.0 + 1
d = 1/4 + 2
e = 29/7 + 4
f = 3/6.0 - 7
g = 2/2
h = 2//2
i = 4%2
j = (100//5)%5

print('A=',a,)
print('B=',b,)
print('C=',c,)
print('D=',d,)
print('E=',e,)
print('F=',f,)
print('G=',g,)
print('H=',h,)
print('I=',i,)
print('J=',j,)

'''
Num. 3 (feito)
'''
a = 2 < 3
b = ( 6 < 3 ) or ( 10 > 11 )
c = ((( 6 // 3 ) % 2 ) > 5 ) and ( 2 < ( 3 % 2 ) )
d = !( 2 < 3 )

print('a= True, b= False e False, c= False e False, d= True')

'''
Num. 4 (Feito)
'''
# A
a=10
b=3
c=3
d=4
e=4
f=2

X = (a-((b*2)/c))/(d+(e/f))

print('X vale: ',X)

# B
x = 4

Y = (((2)+(x)-(((2)*(x)**2)**(x+2)))-(((x+1)**1/2)/x))/(3**x)

print('Y vale: ',Y)

'''
Num. 5 (Feito)
'''
Nome = input('Digite seu nome: ')

print('Olá',Nome)

'''
Num. 6 (Feito)
'''
x = int(input('Digite um valor: '))
y = int(input('Digite um valor: '))
z = int(input('Digite um valor: '))

Mylist = [x,y,z]
Mylist.sort()
print(Mylist)

'''
Num. 7 (Feito)
'''
x = int(input('Digite um valor: '))

if x==0:
  print('Positivo')
elif x>0:
  print('Positivo')
else:
  print('Negativo')

'''
Num. 8 (Feito)
'''
C = int(input('Digite um valor de temperatura em Celsius: '))
K = C + 273
F = (1.8*C) + 32

print(C,'graus Celsius em Kelvin vale: ',K)
print(C,'graus Celsius em Fahrenheit vale: ',F)

'''
Num. 9 (Feito)
'''
x = input('Digite um valor para X: ')
y = input('Digite um valor para Y: ')

if x==y:
  print('X e Y são iguais.')
elif x>y:
  print('X é maior que Y.')
else:
  print('Y é maior que X.')

'''
Num. 10 (Feito)
'''
N = int(input('Digite um numero < ou = 10: '))

if N < 2:
  print('N é primo')
elif N==2 or N==3 or N==5 or N==7:
  print('É primo')
elif N % 2 == 0:
  print('N é primo')

'''
Num. 11 (Feito)
'''
x = int(input('Digite um valor para X: '))
y = int(input('Digite um valor para y: '))
z = int(input('Digite um valor para z: '))

if ((x+y)>z)and ((x+z)>y)and ((y+z)>x):
  print('Um triangulo pode ser formado.')
else:
  print('Nao pode ser feito um triangulo.')

'''
Num. 12 (Feito)
'''
b = int(input('Digite um valor para base '))
h = int(input('Digite um valor para altura '))
A = (b*h)/2

print('A area do triagulo vale: ',A)

'''
Num. 13 (Feito)
'''
x = int(input('Digite um valor para X: '))
y = int(input('Digite um valor para y: '))
z = int(input('Digite um valor para z: '))

if ((x+y)>z)and ((x+z)>y)and ((y+z)>x):
  if x==y==z:
    print('Ira formar um triangulo equilátero.')
  if x==y or x==z or y==z:
    print('Ira formar um triangulo isósceles.')
  if x!=y!=z:
    print('Ira formar um triangulo escaleno.')
else:
  print('Nao pode ser feito um triangulo.')

'''
Num. 14 (Feito)
'''
x = int(input('Digite um valor para angulo X: '))
y = int(input('Digite um valor para angulo y: '))
z = int(input('Digite um valor para angulo z: '))

if (x+y+z)==90:
  print('Triângulo Retângulo.')
if (x+y+z)>90:
  print('Triângulo Obtusângulo.')
if (x+y+z)<90:
  print('Triângulo Acutângulo.')

'''
Num. 15 (solucao 1)(Feito)
'''
def main():
 L = int(input('Digite um valor para largura :'))
 C = int(input('Digite um valor para comprimento :'))
 Pw = int(input('Digite um valor para potencia da lampada :'))  # 18 Pw = 1 metro^2
 Nl = 0

 n_lampadas(Nl,L,C,Pw)

def n_lampadas(Nl,L,C,Pw):
  Nl = ((18*(L*C))//Pw)+1
  print('O numero de lampadas é: ',Nl)

main()

'''
Numero 15 (solucao 2)(feito)
'''

L = int(input('Digite um valor para largura :'))
C = int(input('Digite um valor para comprimento :'))
Pw = int(input('Digite um valor para potencia da lampada :'))  # 18 Pw = 1 metro^2

print('Numeros de lampadas :',(((L*C)*18)//Pw)+1 ) # +1 para caso a divisao do numero de lampadas nao tenha resto = 0

'''
Num. 16 (Feito)
'''
#cozinha retangular, 4 paredes, 2 pares de paredes iguais.
'''
2*P1 = L * H
2*P2 = C * H
Area total = ((2*P1)+(2*P2)//Aa)+1
'''

L = int(input('Digite um valor para largura :'))
C = int(input('Digite um valor para comprimento :'))
H = int(input('Digite um valor para altura :'))
Aa = 1.5

print('Vai precisar de',(((2*(L*H))+(2*(C*H))//Aa)+1),'azulejos.')

'''
Nume. 17 (Feito) (solucao 1)
'''
def main():
 Oi = int(input('Digite a marcação(Km) no início do dia:'))
 Of = int(input('Digite a marcação(Km) no final do dia:'))
 Li = int(input('Digite quantos litros de combustivel foi gasto:'))
 Vt = int(input('Digite o valor total recebido dos passageiros:'))
 C = 1.90 #O litro
 Vg = C*Li
 Vl = Vt - Vg
 M = (Of-Oi)/(Li)

 consumo(M,Of,Oi,Li)
 lucro(Vg,Vl,C,Vt)

def consumo(M,Of,Oi,Li):
  M = (Of - Oi)/(Li)
  print('Media do consumo: ',M)
def lucro(Vg,Vl,C,Vt):
  Vl = Vt - Vg
  print('Lucro liquido: ',Vl)
  
main()

'''
Nume. 17 (Feito) (solucao 2)
'''
Oi = int(input('Digite a marcação(Km) no início do dia:'))
Of = int(input('Digite a marcação(Km) no final do dia:'))
Li = int(input('Digite quantos litros de combustivel foi gasto:'))
Vt = int(input('Digite o valor total recebido dos passageiros:'))
C = 1.90 #O litro
Vg = C*Li
Vl = Vt - Vg
M = (Of-Oi)/(Li)

print('Media do consumo: ',M)
print('Lucro liquido: ',Vl)

'''
Nume. 18 (Feito)
'''
av1 = int(input('Digite um valor para avaliação 1: '))
av2 = int(input('Digite um valor para avaliação 2: '))
avo = int(input('Digite um valor para avaliação optativa: '))

if av1>av2>avo:
  x1=av1
  x2=av2
elif av2>av1>avo:
  x1=av2
  x2=av1
elif avo>av2>av1:
  x1=avo
  x2=av2
elif avo>av1>av2:
  x1=avo
  x2=av1
elif av2>avo>av1:
  x1=av2
  x2=avo
elif av1>avo>av2:
  x1=av1
  x2=avo

M = (x1+x2)/2

if M>=6:
  print('Aprovado')
elif 6>M>=3:
  print('Exame')
elif M<3:
  print('Reprovado')

'''
Nume. 19 (Feito)
'''
h1 = int(input('Digite um valor para idade h1: '))
h2 = int(input('Digite um valor para idade h2: '))
m1 = int(input('Digite um valor para idade m1: '))
m2 = int(input('Digite um valor para idade m2: '))

if h1>h2:
  x2=h1
  x1=h2
else:
  x2=h2
  x1=h1
if m1>m2:
  y2=m1
  y1=m2
else:
  y1=m1
  y2=m2

print('Soma da idade do homem + velho com mulher + nova: ',(x2 + y1))
print('Produto da idade do homem + novo com mulher + velha: ',(x1 * y2))

'''
Nume. 20 (feito)
'''

S1 = input('Digite algo: ')
S2 = input('Digite algo: ')

if S1==S2:
  print('True')
else:
  print('False')

#####################
#lista 2 python tiago
#####################

'''
Num. 1 (feito)
'''
raio = int(input('Digite o valor do raio: '))

diametro = raio * 2

pi = 3.14
#comp = comprimento da circunferência
comp = 2 * pi * raio

area = pi * (raio**2)

print('O comprimento da circunferência é: ', comp)
print('A área da circunferência é: ', area)

'''
Num. 2 (feito)
'''
a = 2 < 3
b = ( 6 < 3 ) or ( 10 > 11 )
c = ((( 6 // 3 ) % 2 ) > 5 ) and ( 2 < ( 3 % 2 ) )
d = !( 2 < 3 )

print('a= True, b= False e False, c= False e False, d= True')

'''
Num. 3 (feito)
'''
n1=int(input('Digite um numero :'))
n2=int(input('Digite outro numero :'))
n3=int(input('Digite outro numero :'))

Mylist=[n1,n2,n3]

print('Lista: ',Mylist.sort())
print(Mylist)

'''
Num. 4 (feito)
'''
N = int(input('Digite um numero: '))

if N < 2:
  print('N é primo')
elif N == 2:
  print('É primo')
elif N % 2 == 0:
  print('N é primo')
else:
  for x in range(3, N//2, 2):  #x = divisor
    if N % x == 0:
      print('N é primo')
      break
  else:
    print('É primo')

'''
Num. 5 (solucao 1)(Feito)
'''
def main():
 L = int(input('Digite um valor para largura :'))
 C = int(input('Digite um valor para comprimento :'))
 Pw = int(input('Digite um valor para potencia da lampada :'))  # 18 Pw = 1 metro^2
 Nl = 0

 n_lampadas(Nl,L,C,Pw)

def n_lampadas(Nl,L,C,Pw):
  Nl = ((18*(L*C))//Pw)+1
  print('O numero de lampadas é: ',Nl)

main()

'''
Numero 5 (solucao 2)(feito)
'''

L = int(input('Digite um valor para largura :'))
C = int(input('Digite um valor para comprimento :'))
Pw = int(input('Digite um valor para potencia da lampada :'))  # 18 Pw = 1 metro^2

print('Numeros de lampadas :',(((L*C)*18)//Pw)+1 ) # +1 para caso a divisao do numero de lampadas nao tenha resto = 0

'''
Num. 6 (Feito)
'''
#cozinha retangular, 4 paredes, 2 pares de paredes iguais.
'''
2*P1 = L * H
2*P2 = C * H
Area total = ((2*P1)+(2*P2)//Aa)+1
'''

L = int(input('Digite um valor para largura :'))
C = int(input('Digite um valor para comprimento :'))
H = int(input('Digite um valor para altura :'))
Aa = 1.5

print('Vai precisar de',(((2*(L*H))+(2*(C*H))//Aa)+1),'azulejos.')

'''
Nume. 7 (Feito)
'''
def main():

 Oi = int(input('Digite a marcação(Km) no início do dia:'))
 Of = int(input('Digite a marcação(Km) no final do dia:'))
 Li = int(input('Digite quantos litros de combustivel foi gasto:'))
 Vt = int(input('Digite o valor total recebido dos passageiros:'))
 C = 1.90 #O litro
 Vg = C*Li
 Vl = Vt - Vg
 M = (Of-Oi)/(Li)

 consumo(M,Of,Oi,Li)
 lucro(Vg,Vl,C,Vt)

def consumo(M,Of,Oi,Li):
  M = (Of - Oi)/(Li)
  print('Media do consumo: ',M)
def lucro(Vg,Vl,C,Vt):
  Vl = Vt - Vg
  print('Lucro liquido: ',Vl)
  
main()

'''
Nume. 8 (Feito)
'''
av1 = int(input('Digite um valor para avaliação 1: '))
av2 = int(input('Digite um valor para avaliação 2: '))
avo = int(input('Digite um valor para avaliação optativa: '))

if av1>av2>avo:
  x1=av1
  x2=av2
elif av2>av1>avo:
  x1=av2
  x2=av1
elif avo>av2>av1:
  x1=avo
  x2=av2
elif avo>av1>av2:
  x1=avo
  x2=av1
elif av2>avo>av1:
  x1=av2
  x2=avo
elif av1>avo>av2:
  x1=av1
  x2=avo

M = (x1+x2)/2

if M>=6:
  print('Aprovado')
elif 6>M>=3:
  print('Exame')
elif M<3:
  print('Reprovado')

'''
Nume. 9 (Feito)
'''
h1 = int(input('Digite um valor para idade h1: '))
h2 = int(input('Digite um valor para idade h2: '))
m1 = int(input('Digite um valor para idade m1: '))
m2 = int(input('Digite um valor para idade m2: '))

if h1>h2:
  x2=h1
  x1=h2
else:
  x2=h2
  x1=h1
if m1>m2:
  y2=m1
  y1=m2
else:
  y1=m1
  y2=m2

print('Soma da idade do homem + velho com mulher + nova: ',(x2 + y1))
print('Produto da idade do homem + novo com mulher + velha: ',(x1 * y2))

'''
Nume. 10 (feito)
'''

S1 = input('Digite algo: ')
S2 = input('Digite algo: ')

if S1==S2:
  print('True')
else:
  print('False')

'''
Nume. 11 (feito)
'''
P = input('Digite algo: ')
P2 = P[::-1]

if P==P2:
 print('True')
else:
  print('False')

print('Normal: ',P)
print('Invertido: ',P2)

'''
Nume. 12 (feito)
'''
p1 = input('digite uma palavra ')
p2 = input('digite uma palavra ')

if p1==p2:
  print('False.')
else: 
  if len(p1)==len(p2):
    if (sorted(s1)== sorted(s2)): 
      print('True.')
  else:
    print('False.')

'''
Nume. 13 (feito)
'''
m1 = [[0,1,1],[3,2,1],[4,3,1]]
m2 = [[1,2,1],[1,3,2],[1,6,3]]

def M_p(m1,m2):
  if len(m1)==len(m2):
    M=[['','',''],['','',''],['','','']]
    for i in range(len(m1)):
      for j in range(len(m1)):
        aux=0
        for k in range(len(m1)):
          aux +=m1[i][k] * m2[k][j]
        M[i][j] = aux
  
  return M

print(M_p(m1,m2))

'''
Nume. 14 (feito)
'''
m1 = [[0,1,1],[3,2,1],[4,3,1]]
m2 = [[1,2,1],[1,3,2],[1,6,3]]
 
#Multiplicação
 
def M_p(m1,m2):
  if len(m1)==len(m2):
    M=[['','',''],['','',''],['','','']]
    for i in range(len(m1)):
      for j in range(len(m1)):
        aux=0
        for k in range(len(m1)):
          aux +=m1[i][k] * m2[k][j]
        M[i][j] = aux
  
  return M
 
print('Multiplicação de matrizes: ',M_p(m1,m2))
 
#________________
#Soma (Solução 1)
 
def Som1(m1,m2):
    if len(m1) == len(m2):
      S= []
      for i in range(len(m1)):   
        S.append([])
        for j in range(len(m1)):
            S[i].append(m1[i][j] + m2[i][j])
    return S
 
print('Soma de matrizes: ',Som1(m1,m2))
#________________
#Soma (Solução 2)
 
def Som2(m1,m2):
  if len(m1)==len(m2):
    M=[['','',''],['','',''],['','','']]
    for i in range(len(m1)):
      aux=0
      for j in range(len(m1)):
        aux =m1[i][j] + m2[i][j]
        M[i][j] = aux
  
  return M
 
print('Soma de matrizes: ',Som2(m1,m2))
 
#Subtração
 
def Sub(m1,m2):
  if len(m1)==len(m2):
    M=[['','',''],['','',''],['','','']]
    for i in range(len(m1)):
      aux=0
      for j in range(len(m1)):
        aux =m1[i][j] - m2[i][j]
        M[i][j] = aux
  
  return M
 
print('Subtração de matrizes: ',Sub(m1,m2))

'''
Nume. 15 (feito)
'''
#Um número perfeito é aquele que a soma dos seus divisores naturais retorna o próprio numero
#Exemplo: 28: 1 + 2 + 4 + 7 + 14 = 28
 
x = int(input('Digite valor inicial: '))
y = int(input('Digite valor final: '))
 
#div_nat: Lista dos divisores naturais de um número.
div_nat = []
#num_per: Lista que contém os números perfeitos verificados.
num_per = []
 
 
#Verifica se um número dentro do intervalo acima é perfeito e coloca-o numa lista.
for i in range(x, y+1):
    for j in range(1, i):
        if i % j == 0:
            div_nat.append(j)
    if sum(div_nat) == i:
        num_per.append(i)
    div_nat = []
 
print(num_per)
