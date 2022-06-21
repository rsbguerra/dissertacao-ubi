# Modelo Dissertação/Tese UBI adaptado para LaTeX

_**Modelo para a escrita em LaTeX de teses ***NÃO OFICIAL*** da Universidade da Beira Interior, seguindo o despacho Reitoral n° 49/R/2010. Revogado pelo despacho Reitoral n° 2019/R/630**_

### Organização do template:
- `/src` contém todos os ficheiros relativos à formatação do documento e o ficheiro principal. Nesta pasta encontram-se:
  - `main.tex`, o ficheiro principal do documento;
  - `PaginaRosto.tex`, gera a página de rosto;
  - `formatacaoUBI.tex` e `estiloUBI.cls`, definem a formatação a ser usada em teses apresentadadas na Universidade da Beira Interior, seguindo as normas do despacho previamente mensionadas. ***Não se aconselha a edição destes dois documentos***.
  - `preamble.tex` contém todos os pacotes ou comandos que o autor pode precisar para além dos importados ou comandos definidos em `formatacaoUBI.tex`
- `/bibtex`, onde se inserem as referências da tese em formato bibTeX. Para teses com uma lista de referências considerável é aconselhado dividi-las por vários ficheiros, organizados por capítulo ou tópico. Esta pasta também contém:
  - `estilo-biblio.bst`, define o estilo da bibliografia, pode ser trocado por qualquer outro ficheiro de acordo com a norma a utilizar (deixada em aberto pelo despacho);
- O corpo principal da tese esterá contido em `/chapters`:
  - Cada capítulo terá o seu próprio ficheiro `.tex`. Para capítulos maiores, espera-se que o autor crie uma pasta separada contendo um ficheiro por secção (a pasta `/state-art` exemplifica a organização mencionada)
  - **Para além do corpo do documento, aqui encontra-se o **fichiero `preliminary.tex`**, onde é definido, por esta ordem**:
    1. Dedicatória;
    2. Agradecimentos;
    3. Prefácio;
    4. Resumo (português);
    5. Palavras-chave (português);
    6. Absctract (inglês, neste caso localizado em `/chapters/abstract.tex`);
    7. Keywords (inglês);
    8. Lista de figuras;
    9. Lista de tabelas;
    10. Acrónimos (definidos em `/chapters/acro.tex`).
- Por fim, as imagens serão colocadas em `/images`.

Download da última versão edisponível na área reservada da Universidade da Beira Interior: http://www.UBI.pt.

Uso e distribuição de acordo com a licenca GNU GPL.

Este programa é um software livre: pode redistribui-lo e/ou modificá-lo dentro dos termos da Licença Pública Geral GNU como publicada pela Free Software Foundation, na versão 3 da Licença, ou (na sua opinião) qualquer versão.

Este programa é distribuido na esperança que possa ser útil, mas **SEM NENHUMA GARANTIA**; **sem uma garantia implícita de ADEQUAÇÃO a qualquer MERCADO ou APLICAÇÃO EM PARTICULAR**. 

Em caso de dúvidas, consulte a Licença Pública Geral GNU incluída neste repositório, tembém disponível em <http://www.gnu.org/licenses/>.
