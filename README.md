# rubythejourney
a jornada daquele rubi la
<img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExaG12Mzl6a3Fib3Rnbnc0Z3cwYTBoNngzYTByeW52MjVjNW9ieTdkYyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/j5DBja43qtLDH8Np1m/giphy.gif" >



```rb
#Operação Normal
nice = 17;
flash = 15;

resultado = nice + flash;

puts resultado
```

```rb
#Nil
_*Nil representa o nada absoluto*_
```
```rb
# Operadores
5+5 // 10
5-5 // 0
5*5 // 25
5**3 // 125
5 / 5 // 1
```


```rb
# Sintaxe If Else
puts "Digite:"
a = gets.chomp
if a == "Ney"
    print "NEEEEEEEEEEEEEEEEEEEEEEEEEEEEY"
else
    print "mrm tu digitou #{a}"
end
```


```rb
# Classes
10.class /Interger = inteiro
10.0.class /  Float = decimal


```
```rb
# Conversão de classes
No ruby também tem a conversão de classes
tipo integer pra float usando to(classe)
tipo a = 1
interger = a.to_i // transforma a variável em um
exemplo: a= "1.4"
 b = "1.5"
 c = a.to_f + b.to_f
 print c 
 ```



```rb
# Exemplo de convite
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


```rb
# While sintaxe
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

```
puts "Digite um número limite para a tabuada:"
n = gets.chomp.to_i
i = 1

while i <= 10

resultado = n * i
puts "A tabuada deu #{resultado}"
i += 1
end
```


```
puts "Digite um número limite para a tabuada:"
n = gets.chomp.to_i
i = 1

while i <= 10

resultado = n * i
puts "A tabuada deu #{resultado}"
i += 1
end
```


```rb
# ARRAYYYYYY
i  = 0
nome_convidado =  []
while i<3
    puts "digite o nome de um convidado"
    nome_convidado.push(gets.chomp)
    i = i + 1
end
puts "Listaa"
puts nome_convidado
```
```rb
# Interações de array 
Clientes = ["Alisson", "Cássio", "Leonardo"]
Clientes.push "Mauricio"
Clientes.shift "Alisson"
puts Clientes.inspect


Use `push` ou `<<` para adicionar no final do array (ex: `array.push("nova_coisa")`).
`pop`: Remove o último item do array (como tirar o último livro de uma pilha).
`shift`: Remove o primeiro item do array (como tirar o primeiro da fila).
Ambos retornam o elemento removido.
Útil para manter arrays dinâmicos.

```

```rb

# HASH
 Sintaxe moderna (preferencial para chaves de símbolo)
pessoa = {
  nome: "Alisson",
  idade: 30,
  cidade: "Recife"
puts pessoa[:nome]   # Saída: Alisson
puts carro["modelo"] # Saída: Corolla
}

USANDO EACH
pessoa = { nome:"Almeida", idade: 27, cidade: "Recife"}
pessoa.each do |chave, valor|
    puts "#{chave}: #{valor}"
end
```
```rb
# Exemplo de each e each dentro do each
produto = { nome: "Controle LG", preco: 185 , cor: " preto"}

    puts "Veja as informações do produto: "
    produto.each do |chave, valor|
        
    puts "#{chave}: #{valor}"
end




Livros = [{Título: "Pequeno Príncipe", Autor: "The Rock", Preço: 70 }, {Título: "Diário de um banana", Autor: "Maurício Pantera", Preço: 65  }, {Título: "A arte de meter o fodase", Autor: "Big pedro", Preço: 85  }]
Livros.each do  |valor|
    valor.each do |chave, propriedade|
    
    puts " #{chave}: #{propriedade}"
    end    
end
```



```rb
Criação de Objeto

class Gato
end
    
class Cachorro
end
    
Frajola = Gato.new
CoronelRuffs = Cachorro.new

puts Frajola == CoronelRuffs
```
