# Projeto2-Spring-Boot-3
Aprendendo boas práticas na API
<br>
<br>
<b>Instrutor do curso: </b>
<p>Luan Alves</p>
<br>
<b>Assuntos que serão abordados no curso: </b>

<ul>
  <li>Padronize os retornos dos controllers da API</li>
  <li>Utilize os códigos HTTP corretamente</li>
  <li>Adicione o módulo Spring Security no projeto</li>
  <li>Implemente um mecanismo de autenticação na API</li>
  <li>Realize o controle de acesso na API</li>
  <li>Utilize Json Web Token para controlar o acesso na API</li>
</ul>

<br>
<b>Aulas: </b>
<ul>
  <li><b><i>Boas práticas na API</i></b></li>
  <ul>
  <li>Utilizar a classe ResponseEntity, do Spring, para personalizar os retornos dos métodos de uma classe Controller;</li>
  <li>Modificar o código HTTP devolvido nas respostas da API;</li>
  <li>Adicionar cabeçalhos nas respostas da API;</li>
  <li>Utilizar os códigos HTTP mais apropriados para cada operação realizada na API.</li>
  </ul>
  <br>
  <li><b><i>Lidando com erros</i></b></li>
  <ul>
  <li>Criar uma classe para isolar o tratamento de exceptions da API, com a utilização da anotação @RestControllerAdvice;</li>
  <li>Utilizar a anotação @ExceptionHandler, do Spring, para indicar qual exception um determinado método da classe de tratamento de erros deve capturar;</li>
  <li>Tratar erros do tipo 404 (Not Found) na classe de tratamento de erros;</li>
  <li>Tratar erros do tipo 400 (Bad Request), para erros de validação do Bean Validation, na classe de tratamento de erros;</li>
  <li>Simplificar o JSON devolvido pela API em casos de erro de validação do Bean Validation.</li>
  </ul>
  <br>
  <li><b><i>Spring Security</i></b></li>
  <ul>
  <li>Funciona o processo de autenticação e autorização em uma API Rest;</li>
  <li>Adicionar o Spring Security ao projeto;</li>
  <li>Funciona o comportamento padrão do Spring Security em uma aplicação;</li>
  <li>Implementar o processo de autenticação na API, de maneira Stateless, utilizando as classes e configurações do Spring Security.</li>
  </ul>
  <br>
  <li><b><i>JSON Web Token</i></b></li>
  <ul>
  <li>Adicionar a biblioteca Auth0 java-jwt como dependência do projeto;</li>
  <li>Utilizar essa biblioteca para realizar a geração de um token na API;</li>
  <li>Injetar uma propriedade do arquivo application.properties em uma classe gerenciada pelo Spring, utilizando a anotação @Value;</li>
  <li>Devolver um token gerado na API quando um usuário se autenticar nela.</li>
  </ul>
  <br>
  <li><b><i>Controle de Acesso</i></b></li>
  <ul>
  <li>Funcionam os Filters em uma requisição;</li>
  <li>Implementar um filter criando uma classe que herda da classe OncePerRequestFilter, do Spring;</li>
  <li>Utilizar a biblioteca Auth0 java-jwt para realizar a validação dos tokens recebidos na API;</li>
  <li>Realizar o processo de autenticação da requisição, utilizando a classe SecurityContextHolder, do Spring;</li>
  <li>Liberar e restringir requisições, de acordo com a URL e o verbo do protocolo HTTP.</li>
  </ul>
</ul>

