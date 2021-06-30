# HTML5
**HTML5**, sigla para Hypertext Markup Language, é uma linguagem de marcação de hipertexto para apresentar e estruturar o conteúdo na web.

## Estrutura básica

```html
<!DOCTYPE  html>
<html  lang="en">
	<head>
		<meta  charset="UTF-8">
		<meta  http-equiv="X-UA-Compatible"  content="IE=edge">
		<meta  name="viewport"  content="width=device-width, initial-scale=1.0">
		<title>Document</title>
	</head>
	<body>
	</body>
</html>
```
## Tags
**Tags** são estruturas do HTML contendo instruções, tendo uma marca de início e outra de fim para que o navegador possa desenhar o conteúdo uma página.

### Estrutura de uma tag HTML
1. As tags html possuem **nome**, **atributo**, **valor do atributo** e **conteúdo**.
2. As tags html podem fechar com uma tag de fechamento `<title>conteúdo</title>` ou fechar a si mesmas `<img src="..."/>`
3. As tags html devem com exceção das **tags** dentro do head quase todas as tags dentro da tag **body** devem fechar a si mesmas.


- `<head>` Dentro da tag head nós definimos configurações da página atravéz do outros elementos filhos.
- `<meta>` As tags metas são tags genéricas que podem aplicar alterações dependendo dos seus atributos, por exemplo a tag **meta** com o atributo **charset** `<meta  charset="UTF-8">` define a codificação do arquivo atual, por exemplo **UTF-8** a qual diz a página para entender especiais como **ç** e acentuações, etc.
- `<title>Título</title>` A tag **title** define o **título da janera** **ou título da aba** esta recebe o título em seu conteúdo
- `<body>....</body>` A tag **body** recebe dentro de seu conteúdo em maioria todos os elementos vísiveis na página ela pode receber atributos como id e class.
