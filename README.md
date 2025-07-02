# rubythejoruney
a jornada daquele rubi la




```
#Operação Normal
nice = 17;
flash = 15;

resultado = nice + flash;

puts resultado
```

```
###Nil
_*Nil representa o nada absoluto*_
```
```
###Operadores
5+5 // 10
5-5 // 0
5*5 // 25
5**3 // 125
5 / 5 // 1
```


```
###Sintaxe If Else
puts "Digite:"
a = gets.chomp
if a == "Ney"
    print "NEEEEEEEEEEEEEEEEEEEEEEEEEEEEY"
else
    print "mrm tu digitou #{a}"
end
```


```
Classes
10.class /Interger = inteiro
10.0.class /  Float = decimal


```
```
No ruby também tem a conversão de classes
tipo integer pra float usando to(classe)
tipo a = 1
interger = a.to_i // transforma a variável em um
exemplo: a= "1.4"
 b = "1.5"
 c = a.to_f + b.to_f
 print c 
 ```



```
Exemplo de convite
puts "Bem-vindo(a) festa!, por favor, responda as perguntas do nosso porteiro eletrônico. Diga sua idade"
 puts " Diga sua idade"
 idade = gets.chomp.to_i
 
 puts "Tem convite? (sim ou não)"
 convite = gets.chomp
 if idade >= 18 && convite == "sim"
      puts "Entrada permitida! Aproveite"
  else
      puts "ixi moiô
      "
     end
```


```
While sintaxe
senha = "345"
tsenha = 0

while tsenha != senha
    puts "Digite sua senha"
    tsenha = gets.chomp.to_s
    if tsenha != senha
        puts "Acesso negado"
    end
end

puts "Acesso garantido"
```




```
puts "Digite um número"
i = gets.chomp.to_i

if i >= 0
    while i > 0
    i = i - 1
    puts i
end
else
    puts "Esse número gera loop"
end
```
