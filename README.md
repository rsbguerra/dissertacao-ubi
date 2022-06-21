>  Modelo para a escrita em LaTeX de teses ***NÃO OFICIAL*** da Universidade da Beira Interior, seguindo o despacho Reitoral n° 49/R/2010. Revogado pelo despacho Reitoral n° 2019/R/630

### Organização do template:
- `/src` contém todos os ficheiros relativos à formatação do documento e o ficheiro principal. Nesta pasta encontram-se:
  - `main.tex`, o ficheiro principal do documento;
  - `PaginaRosto.tex`, que gera a página de rosto;
  - `formatacaoUBI.tex` e `estiloUBI.cls`, definem a formatação a ser usada em teses apresentadadas na Universidade da Beira Interior, seguindo as normas do despacho préviamente mensionado. ***Não se aconselha a edição destes dois documentos***.
  - `preamble.tex` contém todos os pacotes ou comandos que o autor pode precisar para além dos importados ou definidos em `formatacaoUBI.tex`
- `\bibtex`, onde se inserem as referências da tese em formato bibTeX. Para teses com uma lista de referências considerável é aconselhado dividi-las por vários ficheiros, organizados por capítulo ou tópico. Esta pasta também contém:
  - `estilo-biblio.bst`, define o estilo da bibliografia, pode ser trocado por qualquer outro ficheiro de acordo com a norma a utilizar (deixada em aberto pelo despacho);
- O corpo principal da tese esterá contido em `\chapters`
- directório imagens, onde por defeito deverão ser colocadas as imagens a utilizar.

Download da última versão em área reservada: http://www.UBI.pt.

Uso e distribuição de acordo com a licenca GNU GPL.

Este programa é um software livre: você pode redistribui-lo e/ou modificá-lo dentro dos termos da Licença Pública Geral GNU como publicada pela Free Software Foundation, na versão 3 da Licença, ou (na sua opinião) qualquer versão.

Este programa é distribuido na esperança que possa ser útil, mas SEM NENHUMA GARANTIA; sem uma garantia implícita de ADEQUAÇÃO a qualquer MERCADO ou APLICAÇÃO EM PARTICULAR. Veja a Licença Pública Geral GNU para maiores detalhes.Você deve ter recebido uma cópia da Licença Pública Geral GNU junto com este programa, se não, veja <http://www.gnu.org/licenses/>.
