#### primeiros-códigos-python
#### first code in python
Primeiros passos no python
#### First Steps in Python
#### What are Strings? (o que são strings)
name = "Michael Jackson"
#### or single marks (podemos usar áspas duplas("a") ou áspas simples ('a')
name= 'Michael Jackson'
#### A string can be a combination of spaces and digits ( Uma string pode ser uma combinação de espaços e digitos, caracteres e caracteres especiais)
'1 2 3 4 5 6 '
#### A string can be a combination of special characters
'!@@#$%¨%¨&"
#### We can print our using the print statement (nós podemos imprimir a mensagem na tela usando o comando print)
print ("hello!")
#### Indexing
It is helpfull to think of a string as an ordered sequence. Each element in the sequence can be accessed using an index represented by array of numbers. (isto é muito útil para pensar de uma string como uma sequecia ordenada, cada elemento na sequencia pode ser acessado usando uma representação index por matrix de numeros)

#### Name= Michael Jackson
#### M i c h a e l   J a c  k  s  o  n
#### 0  1  2  3  4  5  6 7 8 9 10 11 12 13 14
#### print(name[0])
#### M
#### print(name[6])
#### l
#### negative index
#### Michael Jackson
#### -14 -13 -12 -11 -10 -9 -8 -7 -6 -5 -4 -3 -2 -1
#### print (name [-1])
#### n
#### print (name [-14]
#### M
#### We can find the number of characters in a string (nós podemos encontrar o numero  de string )
len ("michael jacskson")
#### 15  caracters
#### Slicing
 we can obtain multiple characteres from a string using slicing, we can obtain the 0 to 4th and 8th to the 12th element
#### name="Michael Jackson"
#### MICHAEL JACKSON
NAME[O:4] = MICH NAME[8:12]= JACK
#### stride
We can also input a stride value as follow, with '2' indicating that we are selecting every seconf variable:
#### Name "michael jackson"
name[::2]: "mcaljcsn"
#### Concatenate
We can concatenate or comine strings by using the addition symbols, and the result is a new string that is a combination of both;
#### concatenate two strings
statement= name + 'is the best'
michael jackson is the best
#### print the string for 3 times
#### 3*"michael jackson"
michael jackson michael jackson michael jackson
#### name= "michael jackson"
name = name + "is the best"
#### name
Michael jackson is the best
#### Escape Sequences (mudar de linha)
back slashes represent the geginning of escape sequences. Escape sequences represent strings that may be difficult to input.
For example, bac slash "n" is encountered
#### print ("michael jackson" \n is the best")
Michael jackson 
is the best
#### similarly, bach slash "t represent a tab
#### print ("michael jackson \t is the best")
Michael Jackson        is the best
#### include back slash in string, if you want to place a backslash in your string, use double backslash
print("Michael Jackson \\ is the best
#### Michael Jackson 
#### \ is the best
#### We can also place an "r" before the string to display the backslash:
print (r"Michael Jackson \is the best")
#### Michael jackson 
#### \ is the best

#### String Operations
There are many string operation methods in Python that can be used to manipulate the data. We are going to use some basic string operations on the date.
Lets thry with the method:
#### upper (convert all the characters in string to upper case)
a= "triller is the sixth studio album"
#### print("before upper:",a)
#### print("after upper:",b)
#### before upper: triller is the sixth studio album
#### after upper: "THE TRILLER IS THE SIXTH STUDIO ALBUM"
##### The method "replace" replaces a segment of the string, a sbstring a new strin, We input the part of the string we would like change . the second argument is what we would like to exchange the segment with, and the result a new string with the segment changed:
#### a= Michael jackson is the best"
#### a= a.replace ("Michael", "janet")
#### Janet Jacksons is the best




