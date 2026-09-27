# Comparação inicial: módulos ESM e CJS

![comparision-cjs-x-esm](images/comparacao-cjs-esm.png)


# Um pouco de história

A aula contou que, no passado, cada navegador implementava do seu jeito a mesma funcionalidade, e que isso levou à criação de um padrão mantido por um comitê. Daí saíram versões de especificação, como a de 2015. A recomendação atual, repetida em aula, é usar módulos padronizados — e você vai encontrar muitas bibliotecas nesse formato.


# Usando módulos padronizados

Ativa-se pelo campo de tipo no manifesto do projeto:

![using-esm-modules](images/ativando-modulos.png)

Comentário: o valor padrão desse campo é o formato antigo.



---

# Exportação padrão

![export default of ESM modules](images/exportacao-padrao.png)


# Importando módulos

![importing ESM modules](images/importando-modulos.png)

**Observação importante**: nesse formato é **obrigatório** informar a extensão do arquivo.

Comentário: dá para usar a extensão específica de módulo. Ela foi pensada justamente para guardar código destinado à exportação, e a escolha entre a extensão comum e a específica fica a seu critério.


# Exportando vários itens

![exporting several things](images/exportando-varios-itens.png)


# Importando vários itens

Dá para trazer tudo de uma vez usando o asterisco.

![importing several things](images/importando-varios-itens.png)


# Importando só um item quando vários foram exportados

Isso se chama desestruturação.

![destructuring~](images/desestruturacao.png)


# Importando tudo com apelido

![import * using an alias](images/importacao-com-apelido.png)


# Exportação direta

![direct export](images/exportacao-direta.png)


# Slides da aula

O material apresentado está publicado na plataforma do curso.


# Repositório da aula

O código usado está num repositório público da trilha.


# Documentação da Mozilla

A referência completa sobre módulos está no centro de documentação da fundação.

### Note

A ordem dos passos importa: nao pule a preparacao do ambiente.