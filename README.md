# python-basic
#string and type

A = "Michael Jackson ", "wrong turn" , "Johan whick"

print(A)

('Michael Jackson ', 'wrong turn', 'Johan whick')

print(len(A))

3

print(A[::])

('Michael Jackson ', 'wrong turn', 'Johan whick')

print(A[0])

Michael Jackson 

print(len(A[0]))

16

print(A[1][::-1])

nrut gnorw

print(A[0][:2])

Mi

print(A[0][::2])

McalJcsn

B = (1, 2, 3, 2, 4.4,5.6 )

print(B)

(1, 2, 3, 2, 4.4, 5.6)

type(B)

tuple

type(B[0])

int

type(B[4])

float

C = set(B)

print(C)

{1, 2, 3, 4.4, 5.6}

D = {

    "key1" : 1}

print(D)

{'key1': 1}

type(D)

dict

thisdict = {

  "brand": "Ford",

  "model": "Mustang",

  "year": 1964

}

print(thisdict)

{'brand': 'Ford', 'model': 'Mustang', 'year': 1964}

E = {"t": 2}

print(E)

{'t': 2}

type(E)

dict

E.update({"F": 1})

print(E)

{'t': 2, 'F': 1}

#calculator

print("Your first number: ")

inp = input()

print("Your second number: ")

inp2 = input()

print("Your result is: ", int(inp) + int(inp2))

Your first number: 

 2

Your second number: 

 3

Your result is:  5

print("your name: ")

p = input( )

print("your negative name:", p[::-1] )

​

your name: 

 rony

your negative name: ynor

a = (1,2,3,4,5,6,7,8,9,0)

​

print(int(input()) in a)

​

​

 1

True

r = "nobody"

u = r.upper()

print(u)

NOBODY

print(r)

nobody

v = r.replace('n','N')

print(v)

Nobody

print(v.isalnum())

True

print(v.isalpha())

True

print(v.endswith(u))

False

print(v.count(v))

1

h = "hello world"

print(h.capitalize())

Hello world

print(h.find("wo"))

6

print(h.replace('hello','hi'))

hi world
