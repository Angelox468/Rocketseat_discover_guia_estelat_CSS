podemos inserir o css na tag style direto no documento do html, podemos támbem inserir a tag style dentro de um elemnto no HTML tipo em algum h1 ou alguma outra tag ou podemos chamar o arquivo style de fora.

## HTML

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="style.css"> /* o link está chamando o arquivo css para fazer as auterações */
</head>
<body>
  <h1>
    Título
    <strong>alo</strong>
  </h1>
</body>
</html>

## CSS

@import 'https://fonts.googleapis.com/css2?family=Ranchers&display=swap';

h1{
  color: blue;
  font-family: 'Ranchers', cursive;
}
strong{
  color: red;
}