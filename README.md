 # validacoes-github
 ## Descrição:
 Olá, me chamo Felipe André de Freitas e vou apresentar um projeto que tem a de validar **Cpf**.
Validação de CPF

Este projeto consiste em uma página HTML simples que permite a validação de números de CPF brasileiros. O código é dividido em três arquivos:
<br> 

![miau.gif](https://steemitimages.com/DQmZCo76MUSeg8WNYUqr9UMGig3kufJWfENY337KfSbpoJC/miau.gif)

**index.html:** Arquivo principal que contém a estrutura HTML da página.
cpf.css: Arquivo CSS para estilização opcional (não incluído nesse exemplo).
cpf.js: Arquivo JavaScript responsável pela lógica de validação do CPF.
Estrutura do Código:

 # index.html:

<!DOCTYPE html>: Declara o tipo de documento como HTML5.
<html></html>: Elemento raiz do documento HTML.
<head></head>: Contém metadados sobre o documento.
<meta charset='utf-8'>: Define o conjunto de caracteres utilizado como UTF-8.
<meta http-equiv='X-UA-Compatible' content='IE=edge'>: Garante compatibilidade com versões mais recentes do Internet Explorer.
<title>Validação de cpf</title>: Define o título da página.
<meta name='viewport' content='width=device-width, initial-scale=1'>: Configura a viewport para dispositivos móveis.
<link rel='stylesheet' type='text/css' media='screen' href='cpf.css'>: Inclui o arquivo CSS para estilização (opcional).
<body></body>: Contém o conteúdo visível da página.
<form action="" id="cpfForm"></form>: Cria um formulário para entrada do CPF.
<label for="">Cpf:</label>: Rótulo para o campo de entrada do CPF.
<input type="text" id="cpf" name="cpf" maxlength="14">: Campo de entrada para o CPF, limitado a 14 caracteres.
<button type="submit">Validar</button>: Botão para enviar o formulário e validar o CPF.
<p id="message"></p>: Elemento parágrafo para exibir a mensagem de resultado da validação.
<script src='cpf.js'></script>: Inclui o arquivo JavaScript com a lógica de validação

# cpf.js:
Este arquivo deve conter a função JavaScript responsável por validar o CPF digitado. A lógica de validação não está incluída neste exemplo, mas geralmente envolve cálculos matemáticos sobre os dígitos do CPF.

# Uso:
Crie os arquivos index.html, cpf.css (opcional) e cpf.js.
Preencha o arquivo cpf.js com a lógica de validação do CPF.
Abra o arquivo index.html em um navegador web.
Digite um número de CPF no campo de entrada e clique no botão "Validar".
A mensagem de resultado da validação será exibida abaixo do formulário.
Observações:

![miau.gif](https://steemitimages.com/DQmZCo76MUSeg8WNYUqr9UMGig3kufJWfENY337KfSbpoJC/miau.gif)

Este é um exemplo básico e pode ser expandido com funcionalidades adicionais, como formatação do CPF, verificação de campos obrigatórios, entre outras.
A validação do CPF deve ser implementada corretamente no arquivo cpf.js para garantir a precisão dos resultados.



 ![Vídeo de demonstração](gravacao.gif)



# Necessidades:
Um navegador web para abrir o arquivo index.html.
* [<code><img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" alt="HTML5"/></code>](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
* [<code><img height="32" src="https://www.malwarebytes.com/wp-content/uploads/sites/2/2023/01/asset_upload_file97293_255583.jpg" alt="Git"/></code>](https://git-scm.com/)
* [<code><img height="32" src="https://blog.netscandigital.com/wp-content/uploads/2023/07/O-que-e-o-Google-Bard.png" alt="Bard"/></code>](https://bard.google.com/chat?hl=pt)
* [<code><img height="32" src="https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" alt="VisualStudio"/></code>](https://code.visualstudio.com/)
* [<code><img height="32" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></code>](https://github.com/)
* [<code><img height="32" src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/CSS3_logo_and_wordmark.svg/1200px-CSS3_logo_and_wordmark.svg.png" alt="Css3"/></code>](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
* [<code><img height="32" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/1200px-Unofficial_JavaScript_logo_2.svg.png" alt="javascript"/></code>](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
* [<code><img height="32" src="https://i.pcmag.com/imagery/reviews/05GF8sMpHfawiyKgGnrgf7X-8..v1665503374.jpg" alt="canva"/></code>](https://www.techtudo.com.br/tudo-sobre/canva/)

![miau.gif](https://steemitimages.com/DQmZCo76MUSeg8WNYUqr9UMGig3kufJWfENY337KfSbpoJC/miau.gif)

# Readme de email.js

## Descrição
Este código contém uma função JavaScript chamada checarEmail() que valida um endereço de email inserido em um formulário HTML.

## Funcionalidade
A função verifica se o campo de email do primeiro formulário da página está vazio ou se não contém o caractere "@" ou ".". Se qualquer uma dessas condições for verdadeira, exibe uma mensagem de alerta informando que o email é inválido e retorna false. Caso contrário, exibe uma mensagem de alerta indicando que o email foi informado e insere o valor do email em um elemento HTML com o ID "email".

## Uso
Inclusão do código: Copie o código da função checarEmail() e cole-o em um arquivo JavaScript vinculado à sua página HTML.
Criar formulário: Crie um formulário HTML com um campo de entrada para o email.
Associar função ao formulário: Adicione um evento onsubmit ao formulário, chamando a função checarEmail().
Exemplo HTML
HTML

![miau.gif](https://steemitimages.com/DQmZCo76MUSeg8WNYUqr9UMGig3kufJWfENY337KfSbpoJC/miau.gif)

<!DOCTYPE html>
<html>
<head>
  <title>Validação de Email</title>
  <script src="script.js"></script> </head>
<body>
  <form onsubmit="return checarEmail()">
    <label for="email">Email:</label>
    <input type="email" id="email" name="email">
    <button type="submit">Enviar</button>
  </form>
  <p id="email"></p>
</body>
</html>

![miau.gif](https://steemitimages.com/DQmZCo76MUSeg8WNYUqr9UMGig3kufJWfENY337KfSbpoJC/miau.gif)

## Observações
A função assume que existe um elemento HTML com o ID "email" na página para exibir o email informado.
A função utiliza alert para exibir mensagens, o que pode ser substituído por outras formas de feedback ao usuário.
A função pode ser expandida para realizar validações mais complexas de endereços de email.
Potenciais melhorias
Implementar uma validação de email mais robusta utilizando expressões regulares.
Substituir alert por mensagens de erro mais amigáveis.
Adicionar feedback visual para indicar erros de validação.
Nota: Este código é um exemplo básico de validação de email e pode ser adaptado para atender a necessidades específicas.

# Autor
Nome: Felipe Freitas Loução