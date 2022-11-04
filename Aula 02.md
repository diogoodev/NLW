# Css fornece o estilo ao HTML
 
Css funciona por declaração, que é um pedaço de codigo que irá ditar propriedades e valores a serem aplicados a um elemento HTML

Exemplo de uma declaração
```css
body{
  background: red;
}
```
- Cascata

Temos que a ultima será mais relevante

Exemplo
```css
body{
  background: red;
}
body{
  background: blue;
}
```
Nesse o fundo da pagina será azul

- Especifidade

Cada seletor tem um peso e a soma será leavada em conta para que determinada declaração seja mais especifica

Exemplos

```css
#id{
 peso: 100;
}

.class{
 peso: 10;
}

element{
 peso: 1;
}
```
## Box model

- Em css tudo é caixa

Todos os elementos HTML serão considerados um caixa, assim como uma caixa de papelão

- Caixas possuem determinadas propriedades

Conteúdo, largura, altura, borda, preenchimento ( espaço externo)

No header como tem um display block, que ocupa toda a linha por natural, e utiliza todo o espço disponivel do body

```css
header{
  border: 1px solid red;
  padding: 60px;
}
``` 
Já no h1 seguimos o mesmo principio do header, porem usando o que sobra de espaço apos o header

```css
h1{
  border: 1px solid green
  height: 60px;
}
```
Unando a propridade margin espaçamos o elemento p dos outros elementos
```css
p{
  margin: 20px ;
  border: 1px solid purple;
}
```
Já no span temos uma visualização do tipo inline, isso que dizer que ele ficara aomlado dos outros elementos.
```css
span{
  border: 1px solid pink;
}
```