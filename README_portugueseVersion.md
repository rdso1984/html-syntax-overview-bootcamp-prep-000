# Introdução à HTML

HTML é a linguagem que você deve ter gasto a maior parte do seu tempo como usuário da internet.  Isso porque HTML é a linguagem da web. Tudo mais que você tem ouvido ao redor de programação para web se resume a modificar a HTML e está próximo do seu irmão: CSS. Nós vamos entrar no CSS um pouco, mas por hora vamos investigar o HTML.

O bloco de construção fundamental do HTML é o que chamamos de _tag_. Tags permitem que desenvolvedores-web falem coisas ao browser como "faça desse texto um cabeçalho" ou "inclua essa imagem". Todas as tags seguem o mesmo formato, como esse:

```html
<tag-text>
```

Simplesmente é algum texto entre os caracteres '<' e '>'. A mais básica tag é a "break" tag. Isso é representado em HTML como `<br>` e fala ao browser para criar uma linha nova. Após essa lição e entrando em CSS nós vamos criar uma página de Perfil simples.

<iframe height='265' scrolling='no' title='intro br' src='//codepen.io/joemburgess/embed/MoJLVL/?height=265&theme-id=0&default-tab=html,result&embed-version=2&editable=true' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/joemburgess/pen/MoJLVL/'>intro br</a> by Joe Burgess (<a href='https://codepen.io/joemburgess'>@joemburgess</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Vá em frente e adicione mais `<br>` tags e veja o que acontece.

![Break it down](https://curriculum-content.s3.amazonaws.com/web-development/break-it-down.gif)

### Abra e Feche Tags

A 'break'tag é muito útil, mas e se nós precisarmos de um cabeçalho. Há uma tag para isso, é a `<h1>` tag. Isso fará o texto se tornar maior e negrito. Obviamente, nós não queremos todo nosso texto como o cabeçalho. Para falar ao browser qual texto deve ser um cabeçalho e qual não deve, nós usamos _closing tags_. Closing tags (tags de fechamento - tradução livre) são exatamente o mesmo que tags que você já viu antes, mas com prefixo `/`. A closing tag para `<h>`seria `</h1>`. Aqui está um exemplo.

<iframe height='265' scrolling='no' title='closing tags' src='//codepen.io/joemburgess/embed/BZpMPJ/?height=265&theme-id=0&default-tab=html,result&embed-version=2&editable=true' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/joemburgess/pen/BZpMPJ/'>closing tags</a> by Joe Burgess (<a href='https://codepen.io/joemburgess'>@joemburgess</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Qualquer texto que voê colocar entre `<h1>` e `</h1>` será um cabeçalho. Há muitas e muitas outras tags como essa. Outro grande exemplo é o paragraph tag que é representado com `<p>`. O paragraph tag fala ao browser que o texto inserido é um parágrafo e coloca duas linhas antes e abaixo do texto. Aqui está um exemplo:

<iframe height='265' scrolling='no' title='p tag' src='//codepen.io/joemburgess/embed/owBmQL/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/joemburgess/pen/owBmQL/'>p tag</a> by Joe Burgess (<a href='https://codepen.io/joemburgess'>@joemburgess</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

### Estrutura do Documento

Enquanto a maioria dos textos HTML está escrevendo tags como as acima, há algumas tags especiais que falam ao browser o que está por vir. Essas são tags que nunca são vistas pelos usuários, mas o browser as utiliza para entender recursos externos que a sua webpage precisa. Aqui está um exemplo completo de uma webpage

<iframe height='265' scrolling='no' title='Intro to HTML' src='//codepen.io/joemburgess/embed/jwydYp/?height=265&theme-id=0&default-tab=html,result&embed-version=2&editable=true' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/joemburgess/pen/jwydYp/'>Intro to HTML</a> by Joe Burgess (<a href='https://codepen.io/joemburgess'>@joemburgess</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Você notará que a web page aparecerá idêntica com a outra acima. Se você ver o código, perceberá três novas tags: `<html>`, `<head>`, e `<body>`. A `<html>` tag fala ao browser "hei, aqui está uma parte de código HTML". O `<head>` tag nós não usamos ele realmente agora, mas ele conterá nossas referências para partes de códigos externos, como CSS ou Javascript. Finalmente, o `<body>` tag conta ao browser "o que está aqui são as coisas que realmente quero que mostre ao usuário".

Em muitos exemplos futuros, nós omitiremos esses `html`, `body` and `head` tags para abreviar. Mas esteja certo de lembrar deles quando você criar seu próprio website!
