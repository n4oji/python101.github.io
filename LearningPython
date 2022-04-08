COMENTÁRIOS:
Para fazer comentários no python, temos duas maneiras:

#Podemos usar a hashtag antes da frase

ou

"""
Três aspas duplas ou simples para escrever em multiplas linhas
Como estou fazendo agora
Entendeu?
"""

-----------------------------------------------------------------------------------------------
VARIÁVEL:
No python não é necessário escrever o tipo da variável, mas se você quiser, pode usar:

x = str(3) # aqui o x é considerado uma string '3'
x = int(3) # aqui o x é considerado um numero inteiro 3
x = float(3) # aqui o x é considerado um numero com casa decimal 3.0

Se você quer declarar uma variável como string, pode usar aspas simples ou duplas:
x = "Antonio" ou x = 'Antonio'

É importante saber que no python, o uso da letra maiúscula é considerado uma variável diferente da minúscula:
a = 4
A = "Santos"

Regras para criar uma variável:
. Ela deve começar com uma letra ou _
. Não pode começar com numero
. Só podemos usar letras, numeros e _ nas variáveis
. Variáveis são sensíveis ao maiúsculo: Ator, ator e ATOR são variáveis diferentes

Você pode atribuir diversos valores em diversas variáveis usando virgula:
x, y, z = "Maça", "Banana", "Laranja"

Se você define o valor de uma variável e depois, dentro de uma função, atribui outro valor pra mesma variável, você terá resultados diferentes quando for printar. Isso acontece porque o valor da variável dentro da função é somente local.

x = "awesome"

def myfunc():
  x = "fantastic"
  print("Python is " + x)

myfunc()

print("Python is " + x)

Agora se você utiliza a função global, você terá o mesmo valor da variável dentro e fora da função:

def myfunc():
  global x
  x = "fantastic"

myfunc()

print("Python is " + x)

-----------------------------------------------------------------------------------------------
TIPOS DE DADOS:
No python temos os seguintes tipos de dados:
x = "Hello World"	#string
x = 20			#int
x = 20.5		#float
x = 1j			#complex
x = ["maça", "banana", "laranja"] #lista
x = ("maça", "banana", "laranja") #tupla
x = {"nome" : "joão", "idade" : 35} #dicionario
x = {"maça", "banana", "laranja"} #conjunto ou set
x = range(6) #define um range que começa no 0 e para no 6, então vai até o 5
x = True #bool

-----------------------------------------------------------------------------------------------
STRINGS:
É possível pegar a posição de uma frase usando o número em um colchetes:
a = "Olá, time"
print(a[1]) -> a = l

#lembrar que a primeira posição é o numero 0, não o numero 1

Você pode saber qual o tamanho da string com a função len:
a = "Hello, World!"
print(len(a)) -> a = 13 #lembrando que ele conta o espaço também

Você pode checar se uma palavra realmente está naquela frase com o seguinte comando:
txt = "The best things in life are free!"
print("free" in txt) -> True

É possível achar um range de caracter usando o slice, ou seja, definir qual a posição inicial e final a gente quer pegar:
b = "Hello, World"
print(b[2:5]) -> llo

#Se você somente colocar print(b[:5]), ele vai pegar da primeira posição até a quinta.
#A mesma coisa acontece ao contrário se você colocar print(b[2:]), ele vai começar da segunda posição até a frase final.
#Se você colocar os numeros negativos, você começa do final da frase, ou seja:
b = "Olá, mundo"
print(b[-4:-2]) -> und

Para deixar a frase toda em maiúsculo:
a = "Teste"
print(a.upper()) -> "TESTE"

Para deixar a frase toda em minúsculo:
a = "TEstE"
print(a.lower()) -> "teste"

Para apagar os espaços no começo e final da frase:
a = " Amigo é coisa para se guardar "
print(a.strip()) -> "Amigo é coisa para se guardar"

Para trocar um caracter por outro:
a = "Esse é um teste"
print(a.replace("U","O") -> "Esse é om teste"

Para criar um dicionário baseado nas vírgulas das frases:
a = "Olá, mundo"
print(a.split(",")) -> ['Olá', 'mundo']

Para referenciar um numero em uma string, podemos usar o format:
quantity = 3
itemno = 567
price = 49.95
myorder = "I want {} pieces of item {} for {} dollars."
print(myorder.format(quantity, itemno, price)) -> I want 3 pieces of item 567 for 49.95 dollars.

Se quisermos escrever aspas dentro de uma string, precisamos usar o escape character:
txt = "We are the so-called \"Vikings\" from the north."
print(txt) -> We are the so-called "Vikings" from the north.

-----------------------------------------------------------------------------------------------

