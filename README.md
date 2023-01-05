# NasaLibraryBR
Biblioteca de Imagens e Videos da NASA pela API oficial

<strong>Descrição</strong>
<ul>
  <li>Imagens disponibilizadas pela NASA para efeitos de divulgação.</li>
  <li>As imagens possuem titulo e explicação e geralmente estão disponiveis em mais de uma resolução.</li>
  <li>Algumas imagens são protegidas por Copyright, neste caso elas são devidamente creditadas.</li>
  <li>Em algums resultados a media disponibilizada são videos, nessas datas, além de exibir o video, também é exibido thumbs-image.</li>
  <li>Os dados das imagens são disponibilizados pela agencia espacial americana em inglês, a ferramenta de tradução do goole está disponivel para o usuário que desejar.</li>
</ul>

<strong>Instrução</strong>
<ul>
  <li>Ao fazer uma pesquisa basica, o termo pesquisado é buscado em todos os dados das imagens.</li>
  <li>Na pesquisa avançada é possivel filtrar em qual campo os dados serão buscados.</li>
  <li>Nos dois casos as imagem são mostradas em miniaturas logo que a requisição é respondida.</li>
  <li>Ao se quicar na miniatura uma tela com a imagem em tamanho normal é aberta, com a possibilidade de alterar por toda a coleção disponivel.</li>
  <li>Se desejar ver os dados da imagem (em ingles) basta clicar no botão "dados da coleção"</li>
  <li>Se o usuário desejar traduzir as informações basta selecionar o idioma com a <a href="https://translate.google.com/" target="_blank">ferramenta de google translate.<a></li>
  <li>O usuário pode realizar o download da imagem clicando no link abaixo da imagem</li>
</ul>

<strong>API</strong></br>
<a href="https://api.nasa.gov/" target="_blank">A pagina consome a API publica da NASA disponibilizada em https://api.nasa.gov/</a><b/>
<p>A documentação completa para esta API pode ser encontrada em <a href="https://images.nasa.gov/docs/images.nasa.gov_api_docs.pdf" target="_blank">https://images.nasa.gov/docs/images.nasa.gov_api_docs.pdf</a></p></br>
<strong>Requicisão http basica</strong><br/>
<code>GET https://images-api.nasa.gov/search?q={<i>termo a ser pesquisado</i>}</code><br>
