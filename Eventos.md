# Eventos do Body

Os eventos de body são escritos desta forma:

	<body evento="myFunction()">

`onafterprint`

Inicia após o documento ser impresso.

`onbeforeprint`

Inicia antes de o documento ser impresso.

`onbeforeunload`

Inicia quando o documento estiver prestes a ser descarregado.

`onerror`

Inicia quando ocorrer um erro.

`onhashchange`

Inicia quando houver mudanças na parte âncora de um URL.

`onload`

Inicia depois que a página termina de carregar.

`onmessage`

Inicia quando a mensagem for Iniciada.

`onoffline`

Inicia quando o navegador começar a funcionar offline.

`ononline`

Inicia quando o navegador começar a funcionar online.

`onpagehide`

Inicia quando a pagina estiver oculta.

`onpageshow`

Inicia quando um usuário navegar para uma página.

`onpopstate`

Inicia quando o histórico da janela mudar.

`onresize`

Inicia quando a janela do navegador é redimensionada.

`onstorage`

Inicia quando o storege do navegador for atualizado.

`onunload`

Inicia quando uma página é descarregada (ou a janela do navegador é fechada).


# Eventos de Forms

Os eventos de forms podem ser escritos dentro da tag forms:

	<form evento="myFunction()"></form>

Ou, dentro da tag input:

	<input type="" name="" id="" evento="myFunction()">

`onblur`

Inicia no momento em que o elemento perde o foco.

`onchange`

Inicia o momento em que o valor do elemento é alterado.

`oncontextmenu`

Inicia quando um menu de contexto é acionado.

`onfocus`

Aciona o momento em que o elemento obtém o foco.

`oninput`

Inicia quando um elemento obtém a entrada do usuário.

`oninvalid`

Inicia quando um elemento for inválido.

`onreset`

Inicia quando o botão Redefinir em um formulário é clicado.

`onsearch`

Inicia quando o usuário escreve algo em um campo de pesquisa (para <input = "search">).

`onselect`

Inicia após algum texto ter sido selecionado em um elemento.

`onsubmit`

Inicia quando um formulário é enviado.

# Eventos do Teclado
`onkeydown`

Inicia quando um usuário pressiona uma tecla.

	<input type="text" onkeydown="myFunction())">


`onkeypress`

Inicia quando um usuário pressiona uma tecla.

	<input type="text" onkeypress="displayResult()">


`onkeyup`

Inicia quando um usuário libera uma tecla.

	<input type="text" onkeyup="myFunction())">

# Eventos do Mouse
Os eventos de arrastar são escritos dentro de uma tag, desta forma:

	<tag evento="myFunction()></tag>
	
`onclick`

Inicia com um clique do mouse no elemento.

`ondblclick`

Inicia com um clique duplo do mouse no elemento.

`onmousedown`

Inicia quando um botão do mouse é pressionado em um elemento.

`onmousemove`

Inicia quando o ponteiro do mouse está se movendo enquanto está sobre um elemento.

`onmouseout`

Inicia quando o ponteiro do mouse sai de um elemento.

`onmouseover`

Dispara quando o ponteiro do mouse se move sobre um elemento.

`onmouseup`

Dispara quando um botão do mouse é liberado sobre um elemento.

`onwheel`

Dispara quando a roda do mouse rola para cima ou para baixo sobre um elemento.
 
# Eventos de Arrastar
Os eventos de arrastar são escritos dentro de uma tag, desta forma:

	<tag evento="myFunction()></tag>

`ondrag`

Inicia quando um elemento é arrastado.

`ondragend`

Inicia no final de uma operação de arrastar.

`ondragenter`

Inicia quando um elemento for arrastado para um destino de soltar válido.

`ondragleave`

Inicia quando um elemento deixa um destino de descarte válido.

`ondragover`

Inicia quando um elemento está sendo arrastado sobre um destino de soltar válido.

`ondragstart`

Inicia no início de uma operação de arrastar.

`ondrop`

Inicia quando o elemento arrastado for solto.

`onscroll`

Script to be run when an element's scrollbar is being scrolled.

# Eventos de Área de Transferência
Os eventos de àrea de transferência são escritos desta forma:

	<input type="" evento="myFunction()" value="">

`oncopy`

Inicia quando o usuário copia o conteúdo de um elemento.

`oncut`

Inicia quando o usuário corta o conteúdo de um elemento.

`onpaste`

Inicia quando o usuário cola algum conteúdo em um elemento.

# Eventos de Mídia
`onabort`

Script a ser executado ao abortar.

`oncanplay`

Script a ser executado quando um arquivo estiver pronto para começar a ser reproduzido (quando tiver armazenado em buffer o suficiente para começar).

`oncanplaythrough`

Script a ser executado quando um arquivo puder ser reproduzido até o fim sem pausar para armazenamento em buffer.

`oncuechange`

Script a ser executado quando a sugestão muda em um elemento <track>.

`ondurationchange`

Script a ser executado quando o comprimento da mídia mudar.

`onemptied`

Script a ser executado quando algo de ruim acontecer e o arquivo ficar indisponível repentinamente (como uma desconexão inesperada).

`onended`

Script a ser executado quando a mídia chegar ao fim (um evento útil para mensagens como "obrigado por ouvir").

`onerror`

Script a ser executado quando ocorrer um erro durante o carregamento do arquivo.

`onloadeddata`

Script a ser executado quando os dados da mídia são carregados.

`onloadedmetadata`

Script a ser executado quando metadados (como dimensões e duração) são carregados.

`onloadstart`

O script deve ser executado assim que o arquivo começa a carregar, antes que qualquer coisa seja realmente carregada.

`onpause`

Script a ser executado quando a mídia for pausada pelo usuário ou programaticamente.

`onplay`

Script a ser executado quando a mídia estiver pronta para começar a tocar.

`onplaying`

Script a ser executado quando a mídia realmente começar a ser reproduzida.

`onprogress`

Script a ser executado quando o navegador estiver no processo de obtenção dos dados de mídia.

`onratechange`

Script a ser executado toda vez que a taxa de reprodução mudar (como quando um usuário muda para um modo de câmera lenta ou avanço rápido).

`onseeked`

Script a ser executado quando o atributo de busca for definido como falso, indicando que a busca terminou.

`onseeking`

Script a ser executado quando o atributo de busca for definido como verdadeiro, indicando que a busca está ativa.

`onstalled`

Script a ser executado quando o navegador não conseguir buscar os dados da mídia por qualquer motivo.

`onsuspend`

O script a ser executado ao buscar os dados da mídia é interrompido antes de ser completamente carregado por qualquer motivo.

`ontimeupdate`

Script a ser executado quando a posição de reprodução for alterada (como quando o usuário avança rapidamente para um ponto diferente na mídia).

`onvolumechange`

Script a ser executado cada vez que o volume for alterado (inclui definir o volume para "mudo").

`onwaiting`

Script a ser executado quando a mídia for pausada, mas espera-se que seja retomada (como quando a mídia faz uma pausa para armazenar mais dados em buffer).

# Outros Eventos
`ontoggle`

Inicia quando o usuário abre ou fecha o elemento <details>.

	<details ontoggle="myFunction()">

#### continue Estudando
- <a href="https://github.com/wesleybertipaglia/html-para-iniciantes/blob/main/1.%20Conceitos%20Basicos.md">Conceitos Básicos</a>
- <a href="https://github.com/wesleybertipaglia/html-para-iniciantes/blob/main/2.%20Primeiros%20Passos.md">Primeiros Passos</a>
- <a href="https://github.com/wesleybertipaglia/html-para-iniciantes/blob/main/Atributos%20Globais.md">Atributos Globais</a>
