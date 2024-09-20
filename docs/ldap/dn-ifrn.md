
## Compreensão do DN

O DN (Distinguished Name) é uma representação única que identifica uma entrada na árvore LDAP, e sua estrutura é composta por diferentes componentes que fornecem informações essenciais sobre a organização e a localização do objeto. A lista abaixo resume os principais componentes do DN, detalhando seu significado e descrição:

- CN(Common Name) Nome comum ou identificador único do objeto (neste caso, a matrícula do aluno).
- OU(Organizational Unit) Unidades organizacionais que categorizam o objeto, indicando subgrupos ou departamentos.
- DC(Domain Component) Componentes de domínio que especificam o domínio da organização (ex: ifrn.local).

### DN (Distinguished Name) 

O DN é o identificador único de uma entrada na árvore LDAP, composto por uma série de RDNs (Relative Distinguished Names) que descrevem a trajetória até a entrada. Por exemplo:

| CN           | OU   | OU  | OU    | OU     | DC   | DC   |
|--------------|-------|------|--------|---------|-------|-------|
| 20221148060005 | Alunos | DG-PAR | RE | IFRN | ifrn  | local |

Este é o DN completo da entrada em questão.

### RDN (Relative Distinguished Name) 

O RDN é a parte do DN que se refere à entrada em relação ao seu pai imediato na árvore. É o identificador que representa a entrada em um nível específico do LDAP. No exemplo, o RDN mais específico é:

| CN            |
|---------------|
| 20221148060005| 

Aqui, "CN" (Common Name) é o atributo e "20221148060005" é o valor correspondente.

### DC (Domain Component) 

O DC representa os componentes de um domínio DNS e é utilizado para identificar o domínio ao qual a entrada pertence. No exemplo:

| DC    | DC    |
|-------|-------|
| ifrn  | local |


Isso indica que a entrada pertence ao domínio "ifrn.local".

### OU (Organizational Unit) 

A OU é uma Unidade Organizacional, utilizada para categorizar entradas em subgrupos dentro da árvore LDAP. No exemplo, temos várias OUs:

| OU     | OU     | OU  | OU   |
|------- |--------|-----|-------
| Alunos | DG-PAR | RE  | IFRN |

Cada uma dessas OUs representa uma categoria dentro da hierarquia organizacional.

### CN (Common Name) 

O CN é o nome comum associado à entrada, frequentemente utilizado para identificar indivíduos ou objetos. No exemplo:

| CN            |
|---------------|
| 20221148060005| 

Aqui, "20221148060005" é um identificador exclusivo, que pode corresponder a um código de aluno.

### Conclusão 

O DN completo (CN=20221148060005,OU=Alunos,OU=DG-PAR,OU=RE,OU=IFRN,DC=ifrn,DC=local) define a posição de um aluno na árvore LDAP, organizando-o em uma hierarquia clara por meio de unidades organizacionais e componentes de domínio. Essa estrutura permite uma gestão eficiente e facilita a localização de informações dentro do contexto do IFRN.

##  Explicação do DN em Manuscrito

Você pode acessar a explicação completa do _Distinguished Name (DN)_ em formato PDF através do link abaixo:

> [Clique aqui para baixar o PDF](./juranda2024.pdf)
> (Explicação detalhada do DN em manuscrito)