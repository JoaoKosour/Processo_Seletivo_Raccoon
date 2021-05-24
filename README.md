# HTML/CSS - PROCESSO SELETIVO RACCOON
Nesse código encontra-se uma pagina em **HTML** e **CSS** criada pelo candidato **João Pedro Kosour Guimarães** no processo seletivo de estágio a desenvolvedor *front-end*. O projeto consiste em replicar uma foto da versão original de uma página em código, a fim de testar as habilidades do candidato na criação de páginas; assim como aprendizado, organização e engajamento.
A página criada não possui funcionalidade, sendo que os diversos elementos clicáveis contidos nela são de caráter plenamente demonstrativo e não redirecionam o usuário.
	
# PRÉ-REQUISITOS
Para a criação desta página foram fornecidos *assets*, como o logo da empresa e as fotos. Para que a página possa ser visualizada corretamente, é necessário que os arquivos de imagem estejam armazenados na pasta "assets".

# PECULIARIDADES/SOLUÇÕES
Para resolver o problema da responsividade, foram utilizadas dimensões em vw (*viewport width*) e em porcentagem, que, em conjunto com a função *calc(),* permitem que um elemento aumente e diminua de tamanho de acordo com a tela, mantendo-se um numero mínimo de pixels definidos na função (ex: `calc(12px + 1vw)`).
Por fim, foram utilizadas *media-queries*, as quais permitem que, dependendo da resolução da tela, diferentes propriedades sejam atribuídas ao *css* da página, podendo-se alternar entre os layouts *mobile* e *desktop* -- ao se atingir uma certa resolução, a página muda para o layout *handheld friendly* (apropriado para tablets e celulares).
Utilizando-se desses recursos, foi possível identificar e solucionar as ocorrências de quebras de *layout* na página de modo eficiente.