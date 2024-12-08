REGEX="^(\*.*\sde)(\s[0-9]{2}\/[0-9]{2}\/[0-9]{4})(\s\*)$"
SUBSTITUTION="## Data da publicação:${2}"
---
# DIÁRIO OFICIAL DE BUGSLÂNDIA


## Data da publicação: 12/11/2024

- Região Sem Bugs
1 - Pedidos de Licença Recusados
Nome: Maria Lima
Cargo: Professor
RE: 12345-A
Nome: Maria José
Cargo: Professor
RE: 12345-B
_____
2 - Pedidos  de Licença Aprovados
Nome: Maria Lima
Cargo: Professor
RE: 12345-C
Nome: Maria José
Cargo: Professor
RE: 12345-B
Nome: Outro Sobrenome
Cargo: Diretor
RE: 12345-D
_____
- Região Com Bugs
1 - Pedidos de Licença Aprovados
Nome: Maria Lima
Cargo: Professor
RE: 12345-C
Nome: Maria José
Cargo: Professor
RE: 12345-B
Nome: Outro Sobrenome
Cargo: Diretor
RE: 12345-D
_____
2 - Pedidos de Licença Recusados
Nome: Maria Lima
Cargo: Professor
RE: 12345-C
Nome: Maria José
Cargo: Professor
RE: 12345-B
Nome: Outro Sobrenome
Cargo: Diretor
RE: 12345-D
_____

## Data da publicação: 13/11/2024

- Região Com Alguns Bugs
1 - Pedidos de Licença Recusados
Nome: Maria Lima
Cargo: Professor
RE: 12345-C
Nome: Maria José
Cargo: Professor
RE: 12345-B
Nome: Outro Sobrenome
Cargo: Diretor
RE: 12345-D
_____
2 - Pedidos de Licença Aprovados
Nome: Maria Lima
Cargo: Professor
RE: 12345-C
Nome: Maria José
Cargo: Professor
RE: 12345-B
Nome: Outro Sobrenome
Cargo: Diretor
RE: 12345-D
_____

## Data da publicação: 14/11/2024

- Região Tudo Funciona
1 - Pedidos de Licença Aprovados
Nome: Jean Grey
Cargo: Professor
RE: 12345-C
Nome: Scott Summers
Cargo: Professor
RE: 12345-B
Nome: Charles Xavier
Cargo: Diretor
RE: 12345-D
_____
2 - Pedidos de  Licença Recusados
Nome: Magneto
Cargo: Diretor da outra escola
RE: 12345-C
Nome: Mística
Cargo: Professor
RE: 12345-B
Nome: Fanático
Cargo: Pau pra toda obra
RE: 12345-D
_____
