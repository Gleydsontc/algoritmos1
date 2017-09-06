

```python
l = []
```


```python
l = [1,2,3]
```


```python
l
```




    [1, 2, 3]




```python
print(l[0])
```

    1



```python
l[2]
```




    3




```python
print(l[1:3])
```

    [2, 3]



```python
print(l[:-1])
```

    [1, 2]



```python
print("Tamanho da lista: %d" % len(l))
```

    Tamanho da lista: 3



```python
z = []
```


```python
# z[0] = 'a'
z.append('a')
```


```python
z
```




    ['a']




```python
z.append('b')
```


```python
z
```




    ['a', 'b']




```python
z[0]
```




    'a'




```python
z[0] = 'c'
```


```python
z
```




    ['c', 'b']




```python
y = [1, 'a', 3.4]
```


```python
y
```




    [1, 'a', 3.4]




```python
cliente1 = ['lúcio', 50.400, 2]
```


```python
cliente2 = ['joao', 649.00, 5]
```


```python
c = []
```


```python
c.append(cliente1)
```


```python
c.append(cliente2)
```


```python
c
```




    [['lúcio', 50.4, 2], ['joao', 649.0, 5]]




```python
notas = [5, 7, 8, 9, 1]
```


```python
i = 0
while i < len(notas):
    print(notas[i])
    i = i + 1
```

    5
    7
    8
    9
    1



```python
for i in notas:
    print(i)
```

    5
    7
    8
    9
    1



```python
y
```




    [1, 'a', 3.4]




```python
y[1] = ''
```


```python
y
```




    [1, '', 3.4]




```python
y[1] = None
```


```python
y
```




    [1, None, 3.4]




```python
del y[1]
```


```python
y
```




    [1, 3.4]




```python
i = 0
while i < 10:
    print(i)
    i = i + 1
```

    0
    1
    2
    3
    4
    5
    6
    7
    8
    9



```python
x = [1,2,3,4,5,6,7,8,9,10]
for i in x:
    print(i)
```

    1
    2
    3
    4
    5
    6
    7
    8
    9
    10



```python
for i in range(1,11):
    print(i)
```

    1
    2
    3
    4
    5
    6
    7
    8
    9
    10



```python
a = []
```


```python
a.append(1)
```


```python
a
```




    [1]




```python
a[0]
```




    1




```python
del a
```


```python
cliente1 = {"Nome": "Lúcio",
           "Salario": 50.500,
           "Filhos": 2,
           "Nomes_Filhos": ['Valentina','Miguel']}
```


```python
cliente1
```




    {'Filhos': 2, 'Nome': 'Lúcio', 'Salario': 50.5}




```python
cliente1["Nome"]
```




    'Lúcio'




```python
clientes = []
clientes.append(cliente1)
```


```python
clientes
```




    [{'Filhos': 2, 'Nome': 'Lúcio', 'Salario': 50.5}]




```python
cliente2 = {"Nome": "Joao",
           "Salario": 543,
           "Filhos": 6,
           "Nomes_Filhos": ['Ana', 'Maria', 'Carla', 'Bruna', 'Francisca', 'Serafina']}
```


```python
clientes.append(cliente2)
```


```python
clientes
```




    [{'Filhos': 2,
      'Nome': 'Lúcio',
      'Nomes_Filhos': ['Valentina', 'Miguel'],
      'Salario': 50.5},
     {'Filhos': 6,
      'Nome': 'Joao',
      'Nomes_Filhos': ['Ana', 'Maria', 'Carla', 'Bruna', 'Francisca', 'Serafina'],
      'Salario': 543}]




```python
clientes[0]
```




    {'Filhos': 2,
     'Nome': 'Lúcio',
     'Nomes_Filhos': ['Valentina', 'Miguel'],
     'Salario': 50.5}




```python
for x in clientes:
    print("Nome: %s" % x["Nome"])
    print("Salário: %.2f" % x["Salario"])
    print("Quantidade de filhos: %d" % x["Filhos"])
    print("Nome dos filhos:")
    for y in x["Nomes_Filhos"]:
        print("\t\t%s" % y)
    print("*"*30)
```

    Nome: Lúcio
    Salário: 50.50
    Quantidade de filhos: 2
    Nome dos filhos:
    		Valentina
    		Miguel
    ******************************
    Nome: Joao
    Salário: 543.00
    Quantidade de filhos: 6
    Nome dos filhos:
    		Ana
    		Maria
    		Carla
    		Bruna
    		Francisca
    		Serafina
    ******************************



```python
menu = ["Ligar para o 190", "Chamar o 191", "Mandar um zap para o mano"]
```


```python
menu.append("Lançar notas")
```


```python
for indice,valor in enumerate(menu):
    print(indice,valor)
```

    0 Ligar para o 190
    1 Chamar o 191
    2 Mandar um zap para o mano
    3 Lançar notas



```python

```
