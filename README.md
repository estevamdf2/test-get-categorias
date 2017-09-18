# test-get-categorias
Objetivo. Testar uma requisição GET para categorias do projeto algamoney-api para testar o funcionamento do CORS.
Além disso há uma página para testar a obtenção do acess token após a criação da classe CorsFilter no projeto algamoney-api

## Servidor python

Caso queira testar a requisição e tenha o python instalado em sua máquina você pode entrar no diretório dos arquivos e executar o seguinte
comando:
 - python -m SimpleHTTPServer <porta>
 
 Após isto é só chamar a página em seu browser e clicar no botão para realizar a requisição ao serviço RestFull.
 
 ## Arquivos
 - index.html: Faz o teste de uma requisição get para listar as categorias
 - teste-get-acess-token.html: Faz uma requisição para obter o access token.
