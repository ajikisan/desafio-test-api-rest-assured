#### Explorando o Rest Assured para Automação de Testes de API
GFT Quality Assurance Para Mulheres
<p>Aluna: Mirian Ajiki Molicawa </p>
<p>Digital Innovation One </p>
<p>Data: 29/12/2022 </p>
<p>Instrutora: Carolina Santana Louzada </p>

### Desafio
Explorar o framework RestAssured + JUnit e geração de reports com o Allure Framework.

### Tecnologias
[x] Postman
[x] IntelliJ 
[x] Java 
[x] Allure Framework
[x] Json Server
[x] RestAssured

### Postman
É um Application Programming Interface (API Client) que facilita aos desenvolvedores criar, compartilhar, testar e documentar APIs. Isso é feito, permitindo aos usuários criar e salvar solicitações HTTP e HTTPs simples e complexas, bem como ler suas respostas.
API base: Restful booker https://restful-booker.herokuapp.com/apidoc/index.html#api-Auth-CreateToken


### Testes Unitários
São testes que verificam se uma parte específica do código, costumeiramente a nível de função, está funcionando corretamente. Em um ambiente orientado a objetos é usualmente a nível de classes e a mínima unidade de testes inclui construtores e destrutores.


### Allure Report
É uma biblioteca open-source, disponível em Java e pode ser utilizada através de um dos gerenciadores de dependência, o Maven.

Configuração
- Allure  https://docs.qameta.io/allure/ - no arquivo pom.xml


Execução de todos os testes pelo terminal do IntelliJ:
- Comando mvn test.


Geração do relatório de teste através de linhas de comando pelo terminal. 
- comando mvn allure:serve para abrir o relatório HTML no navegador; e
- comando mvn allure:report para gerar a porta HTML na pasta target/site/allure-maven-plugin

### URL´s
Edge
http://172.19.160.1:50185/index.html#packages/1c15894741bfa879f562ae91a543fc11/f098339e7a2101b3/retries

Google Chrome
http://localhost:63342/desafio-test-api-rest-assured/target/site/allure-maven-plugin/index.html?_ijt=drja5d482h8vajm27bk4f8geuj&_ij_reload=RELOAD_ON_SAVE#behaviors/b1a8273437954620fa374b796ffaacdd/826910031d9d6fac/retries
