# Guia estelar de HTML

### Títulos e parágrafos

**&lt;p>** - A tag p é usado para agrupar conteúdos relacionados como imagens, textos ou formulários.

**&lt;th…>** - A tag h é usada como título do conteúdo que está por vir, geralmente uma página irá conter até 3 tags hs, sendo **&lt;h1>**, **&lt;h2>** e **&lt;h3>**. 

### Listas

**&lt;ol>** - Usado para criar listas ordenadas. 

**&lt;ul>** - Semelhante a tag ol entretando um linha desordenada. 

**&lt;li>** - Cria uma linha dentro da lista criada com um das tags anteriores. 

A tag **&lt;a>** pode ser colocada dentro da **&lt;li>** para criar textos com hyperlink e criar um menu, por exemplo.

**&lt;dl>** - Criar uma lista com definições, mais usado para criar glossários.

**&lt;dt>** - Adiciona uma linha da lista dl.

**&lt;dd>** - Cria a expecificação do que foi adicionado no dt.

### Outras tags semânticas

**&lt;abbr title=””>** - Usado em abreviações para mostrar seu significado. 

**&lt;addres>** - Tag usada para criar uma área de contato.

**&lt;pre>** e **&lt;code>** - Usados para adicionar código à pagina HTML, entretanto os caractereres reservados ainda precisam ser substituídos com o &;

Tags de citação: 

**&lt;blockquote cite=””>**

**&lt;cite>** 

**&lt;q cite=””>**

### Links

A tag **&lt;a>**, usada para criar links com HTML, aceita algumas possibiliades de redirecionamento dentro do href, entre elas temos o “**mailto:{email}**”, “**tel:[nº do telefone}**”, “**http://{link}**” ou somente o **caminho do arquivo HTML**.

<aside>
💡 É possível também adicionar #{id} para posicionar a pagina em cima do id de algum elemento da página.

</aside>

### Tabelas

**&lt;thead>**, **&lt;tbody>** e **&lt;tfoot>** - Tag semântica usada para separar o cabeçario, o corpo e rodapé da tabela criada.

**&lt;tr>** e **&lt;td>** - Cria respesctivamente uma fileira e uma coluna na tabela que pertencem.

**&lt;th>** - Cria o cabeçalho da tabela.

**&lt;colgroup>** + **&lt;col>** - Usadas para adicionar cor e outros estilos as colunas da tabela com o parametro style, além dele é possível usar o span para englobar uma coluna.

<aside>
💡 Usar o parametro scope para definir a função daquela tag ajuda na acessibilidade da página.

</aside>
