REGEX="^([0-9]\s-.*Aprovados)$"
SUBSTITUTION="#### Aprovados\n\n| Nome | Cargo | RE"
---
# DIÁRIO OFICIAL DE BUGSLÂNDIA


## Data da publicação: 12/11/2024

### Área: Sem Bugs
#### Recusados

| Nome | Cargo | RE
Nome: Maria Lima
Cargo: Professor
RE: 12345-A
Nome: Maria José
Cargo: Professor
RE: 12345-B
_____
#### Aprovados

| Nome | Cargo | RE
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
### Área: Com Bugs
#### Aprovados

| Nome | Cargo | RE
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
#### Recusados

| Nome | Cargo | RE
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

### Área: Com Alguns Bugs
#### Recusados

| Nome | Cargo | RE
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
#### Aprovados

| Nome | Cargo | RE
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

### Área: Tudo Funciona
#### Aprovados

| Nome | Cargo | RE
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
#### Recusados

| Nome | Cargo | RE
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