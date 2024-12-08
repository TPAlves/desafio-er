## Storytelling

Na cidade de Bugslândia é publicado semanalmente um Diário Oficial contendo, em
uma determinada parte do documento, informações sobre licenças aprovadas
ou recusadas para funcionários públicos. Esse documento contém os seguintes dados:

- Região de trabalho
- Data de publicação
- Pedidos de Licença Aprovados/recusados
- Nome
- Cargo
- RE/RF

Você foi contratado urgentemente para formatar os textos para a diretoria da empresa
poder utilizar em uma campanha de divulgação de um dos seus serviços prestados. A diretoria
deseja que esse trabalho seja realizado apenas utilizando expressões regulares. Ouve-se nos corredores que
isso é apenas para testar o profissional que assumirá o posto com um salário muito bom, algo em torno de bitbugs ($BB).

O arquivo [diario-oficial.txt](https://gist.github.com/oliveiraxavier/fadf8f27abca9be276c25c37c8b84b21) possui o conteúdo fictício das publicações.

É importante salientar que no contéudo do Diário Oficial pode ocorrer erros de digitação como por exemplo:
* palavras que deveriam ter acento aparecerem no arquivo sem acento;
* c no lugar de ç;
* Datas estarem no formato dd/mm/YYYY ou dd/mm/YY;

## O desafio

1 - Para esse desafio ser dado como válido você deverá:
* Utilizar somente expressões regulares;
* Utilizar o mínimo possível de expressões regulares;
* Para cada expressão regular aplicada criar um arquivo .md com o conteúdo da expressão regular utilizada na primeira linha
desse arquivo, seguido pelo conteúdo gerado pelo replace dessa expressão regular. O nome  do arquivo deve seguir o padrão
er-N.md. Exemplo:
* Na primeira expressão regular utilizada para substituir o texto, o arquivo será er-1.md, na segunda ER er-2.md e assim;
consecutivamente. Se você construir 3 expressões regulares, deverão existir 3 arquivos.

## O resultado esperado

O texto final deverá estar igual ou mais similar possível do arquivo [modelo-saida.md](https://gist.github.com/oliveiraxavier/4f228b1b7d099615a74b0d5356aa2444)

## Links úteis
* https://www.regular-expressions.info/quickstart.html
* https://regex101.com/
* https://aurelio.net/regex/guia/

