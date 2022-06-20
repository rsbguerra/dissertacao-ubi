Modelo para a escrita em LaTeX de teses N�O OFICIAL da Universidade da Beira Interior, seguindo o despacho Reitoral n� 49/R/2010.
Revogado pelo despacho Reitoral n� 2019/R/630

Vers�o 3.0 - 2020/01/31
Esta Vers�o � um update � vers�o oficial Vers�o 2.2 .
Esta � uma Vers�o N�O OFICIAL do modelo de Teses da UBI. Segue o despacho Reitoral n� 2019/R/630 quase na integra. Sem garantias algumas.
Aguns erros que a UBI forneceu no ficheiro WORD foram corrigidos no LaTeX.

Vers�o 2.2 - 2016/06/01

Em rela��o � Vers�o 2.1 na Vers�o 2.2 existem duas op��es para as Listas, Lista de Figuras e Lista de Tabelas, podem aparecer as palavras "Figura" e "Tabela" nas respectivas listas. Como exemplo:
2.1 Correspond�ncia entre as cores das riscas das resist�ncias e o seu valor �hmico. .3
ou
Tabela 2.1 Correspond�ncia entre as cores das riscas das resist�ncias e o seu valor�hmico. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .
3

Em rela��o � Vers�o 2.0 na Vers�o 2.1 passa-se a deixar de compilar em PDFLaTeX para se passar a compilar em XeLaTeX.
� necessa?io passar a compilar em XeLaTeX para utilizar o tipo de letra Trebuchet.

Para utilizar o XeLaTeX a codifica��o dos ficheiros tem que ser em UTF-8.

Utilizadores de Linux com gestor de pacotes DEB t�m que ter o pacote "ttf-mscorefonts-installer" instalado
para utilizar o tipo de letra Georgia. N�o foram testados outros gestores de pacotes.

O modelo foi compilado em XeLaTeX e sem erros num sistema Debian 10 Gnome 64-bit 64-bit (N�o foram testadas outras distribui��es),
com Texmaker 5.0.3 e com texlive-full. Inclu�dos no .zip:

-   Tese.tex, o ficheiro principal do documento;
-   PaginaRosto.tex, que gera a p�gina de rosto;
-   Intro.tex e Exemplos.tex, exemplos de cap�tulos com tabela, figura e refer�ncias;
-   formatacaoUBI.tex e estiloUBI.sty, definem a formata��o da tese, n�o � recomend�vel
    editar estes ficheiros;
-   estilo-biblio.bst, define o estilo da bibliografia, pode ser trocado por qualquer
    outro ficheiro de acordo com a norma a utilizar (deixada em aberto pelo despacho);
-   bibliografia.bib, onde se inserem as refer�ncias da tese em formato bibTeX;
-   direct�rio imagens, onde por defeito dever�o ser colocadas as imagens a utilizar.
