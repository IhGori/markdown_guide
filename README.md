# Guia de uso para Markdown

Aqui um guia simplificado de como utilizar dos conceitos desta linguagem de marcação

## Cabeçalho 

Segue mesmo princípio dos elementos de cabeçalho do HTML: h1, h2, h3, h4, h5 e h6 para quantidade respectiva de #

# h1
## h2
### h3
#### h4
##### h5
###### h6

## Negrito

Para escrever em negrito pode-se utilizar dos comandos: ** texto ** ou __ texto __ =>  Sem o espaçamento com o texto

## Itálico 

Para escrever em itálico pode-se utilizar dos comandos: * texto * ou _ texto _ => Sem o espaçamento com o texto

# Combinação Negrito e Itálico

É possível utilizar uma **_combinação_** com: ** _ texto _ ** => Sem o espaçamento

## Listas 

Pode-se assumir como listas ordenadas ou não-ordenadas:

* Listas Ordenadas
    1. Item 1
    2. Item 2
* Listas Não-Ordenadas

## Adicionando Imagem

Imagem local:

![Logo Django](django-logo.png)
Imagem externa:

![Logo Python](https://www.python.org/static/community_logos/python-logo-master-v3-TM-flattened.png)

## Espaçamento de linhas

Utilizar comando shit+enter

# Links

Segue mesmo padrão de imagens:

[Link Google](https://www.google.com.br)

Para colocar o link como texto se repete o link no lugar do texto
[https://www.google.com.br](https://www.google.com.br)

Para inserir uma imagem com link dentro:

Só incluir dentro do padrão da imagem o link

[![Logo Google](https://www.logotipo.pt/wp-content/uploads/2016/10/Evolu%C3%A7%C3%A3o-do-log%C3%B3tipo-da-Google-2016.jpg)](https://www.google.com.br)

## Inserindo Código Fonte

Utilizando entre 3 aspas aparecerá como código:

Ex: Código de soma

```
def soma(){
    a = 2;
    b = 3;
    soma = a + b;
    print(soma);
} 
```

## Task List
- [ x ] Concluído
- [ ] Não-concluído
