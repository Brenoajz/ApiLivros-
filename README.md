<h1>API de Livros</h1>
<h2>Projeto</h2>
<p>Este é um projeto de uma API de livros que permite operações como adicionar, editar, excluir e visualizar livros.</p>
<h2>Tecnologias Utilizadas</h2>
<ul>
  <li>Flask</li>
  <li>Python</li>
  <li>JSON</li>
</ul>
<h2>Funcionalidades</h2>
<ul>
  <li>
    <h3>Ver todos</h3>
    <ul>
      <li><strong>Rota:</strong> /livros</li>
      <li><strong>Método:</strong> GET</li>
      <li><strong>Descrição:</strong> Retorna uma lista de todos os livros cadastrados.</li>
    </ul>
  </li>
  <li>
    <h3>Ver por id</h3>
    <ul>
      <li><strong>Rota:</strong> /livros/&lt;int:id&gt;</li>
      <li><strong>Método:</strong> GET</li>
      <li><strong>Descrição:</strong> Retorna um livro específico pelo seu id.</li>
    </ul>
  </li>
  <li>
    <h3>Alterar</h3>
    <ul>
      <li><strong>Rota:</strong> /livros/&lt;int:id&gt;</li>
      <li><strong>Método:</strong> PUT</li>
      <li><strong>Descrição:</strong> Altera um livro existente pelo seu id.</li>
    </ul>
  </li>
  <li>
    <h3>Adicionar</h3>
    <ul>
      <li><strong>Rota:</strong> /livros</li>
      <li><strong>Método:</strong> POST</li>
      <li><strong>Descrição:</strong> Adiciona um novo livro.</li>
    </ul>
  </li>
  <li>
    <h3>Excluir</h3>
    <ul>
      <li><strong>Rota:</strong> /livros/&lt;int:id&gt;</li>
      <li><strong>Método:</strong> DELETE</li>
      <li><strong>Descrição:</strong> Exclui um livro existente pelo seu id.</li>
    </ul>
  </li>
</ul>
<h2>Como Rodar o Projeto</h2>
<ol>
  <li>Clone o repositório para sua máquina.</li>
  <li>Instale as dependências usando <code>pip install -r requirements.txt</code>.</li>
  <li>Execute o comando <code>python app.py</code>.</li>
  <li>Abra seu navegador em <a href="http://localhost:5000">http://localhost:5000</a> para visualizar a API.</li>
</ol>
