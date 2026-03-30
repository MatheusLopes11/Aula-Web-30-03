# Aula-Web-30-03

FINALMENTE AULA DE WEB OFICIAL (30/03/2026)

1) Linguagens Principais

HTML (HyperText Markup Language) - Linguagem de Marcação de Hipertexto. sem HTML, não há web. Títulos, parágrafos, imagens, links. O alicerce. Não possui lógica (loop,repetição, etc)

Exemplo:

<h1> Hello World! </h1>
<p> Minha Primeira Página</p>
<a href= “https://google.com”>
Ir para o Google
</a> 

<h1> - título grande
<p> - parágrafo
<href> - tag de endereçamento
<a> (âncora) - é usada para criar hiperlinks, conectando páginas, arquivos, e-mails ou locais específicos.

1.1)  Anatomia do Documento HTML

<!DOCTYPE html>
<html>
  <head>
	   <meta charset=”UTF-8”>
     <title> Minha Página </title>
  </head>
  <body>
    	<h1> Olá Mundo </h1>
  </body>
</html>

<!DOCTYPE> - declara que o documento usa HTML 5, ajuda o navegador a interpretar o arquivo corretamente.
<html> - é o elemento raiz, todo o conteúdo fica contido nele, contêiner principal do documento.
<head> - contém os metadados da página, informações que não aparecem na tela.
<body> - contém todo o conteúdo visível da página, tudo o que o usuário vê.


CSS -  Linguagem de estilo. Cores, fontes, tamanhos, espaçamentos, layouts

JS - Linguagem de Programação de fato. Linguagem WEB, permite que a página reaja a cliques, validar formulários, bloquear cópias

2) Internet/Web -  !!! Pergunta de Prova

Web - Lógica, Visual, protocolos http/https 

Internet - Físico, cabeamento, roteadores, protocolos de comunicação tcp/ip, rede elétrica

3) Ciclo requisição/resposta - como uma página web chega até nós

Digitar URL -> Enviar Requisição -> Processar Resposta -> Renderizar Página

Esse processo é chamado de modelo cliente-servidor. O navegador (cliente) sempre inicia a conversa; o servidor responde com o conteúdo solicitado

4) 
