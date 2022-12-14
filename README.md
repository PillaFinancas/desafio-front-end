# Desafio \<front>developer\</end>

Se deseja participar do nosso processo seletivo, siga as instruções deste desafio e execute os seguintes passos: 

* Nos mande sua resolução em um *pull request* neste repositório.

* Deixe a aplicação disponível publicamente em algum host ([GitHub Pages](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/),  [Firebase Hosting](https://firebase.google.com/docs/hosting), [Azure](https://azure.microsoft.com/pt-br/services/app-service/web/), ou qualquer um de sua preferência) para testes. 

* Por último, envie um email para [renatto.machado@pilla.tech](mailto:renatto.machado@pilla.tech) com seu CV anexado e o link da aplicação;



# O desafio

Você implementará uma aplicação web **responsiva** que consulta os dados de empresas em uma API, armazena no LocalStorage e mostra no mapa o endereço da empresa selecionada.



## Requisitos

1. Consulta de empresas pelo CNPJ;
   1. O número do CNPJ deve ser válido antes de executar a requisição na API;
   2. Caso o CNPJ não exista, o usuário deve ser informado;
   3. Os dados da empresa devem ser armazenados no LocalStorage do navegador, se o usuário sair da página e voltar a lista de empresas consultadas anteriormente deve ser recuperada do LocalStorage;
2. Mostrar uma lista em cards das empresas consultadas;
3. Mostrar os dados da empresa e a localização no mapa;



## Protótipos

[Neste link](https://invis.io/Q6T6JI44FTY#/376025753_pesquisa) você encontrará os protótipos *navegáveis* feitos no Invision e [aqui](https://invis.io/Q6T6JI44FTY#/376033742_style_Guide) você poderá ver o style guide.

O layout e a estilização devem seguir a risca os protótipos e o style guide, tirando isso, você tem oportunidade de mostrar todo seu talento e criatividade.



## Recomendações

* Utilize um destes três frameworks: VueJS, React ou Angular;
* Utilize SASS ou LESS;
* Utilize a UI Library que preferir. Sugestões: [Element](https://element.eleme.io/), [Bootstrap](https://getbootstrap.com/), [Material](https://material.io/design/);
* API de Consulta de CNPJs: https://receitaws.com.br/
* Utilize ECMAScript 5 ou 6;
* Linguagens: JavaScript ou TypeScript;
* Utilize boas práticas de codificação, isso será avaliado;
* Mostre que você manja dos paranauê do CSS3 (implemente animações, transições, efeitos, seja livre para voar!);
* Código limpo, organizado e documentado (quando necessário);
* Use e abuse de:
  * Usabilidade;
  * Criatividade;
  * Performance;
  * Manutenabilidade;
  * Testes Unitários (quando necessário)
  * ... pois avaliaremos tudo isso!
