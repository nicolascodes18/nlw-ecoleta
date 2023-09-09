#### Back End ####
- __Rota__: Endereço completo da requisição
- __Recurso__: Qual entidade está sendo acessada do sistema

- __GET__: Busca uma ou mais informações do back-end
- __POST__: Cria uma nova informação no back-end
- __PUT__: Atualizar uma informação existente no back-end
- __DELETE__: Remover uma informação do back-end

- __Request Param__: Parametros que vem na propria rota que idenfiticam um recurso
- __Query Param__: Parametros que vem na propria rota geralmente opcionais para filtros, paginação...
- __Request Body__: Parametros para criação / atualizar uma informação

#### Banco de Dados ####
> #### Migrations
> - Neste contexto específico, migration é a definição que se dá ao gerenciamento de mudanças incrementais e reversíveis em esquemas (estrutura) de banco de dados. Isso permite que seja possível ter um controle "das versões" do banco de dados.
> - As migrations são executadas sempre que for necessário atualizar a estrutura do banco ou reverter as alterações para uma migration antiga.
> - Não necessariamente cada migration é uma atualização no banco de dados, a forma mais comum é uma atualização fazer uso de várias migrations.
> - É algo muito usado no desenvolvimento de software ágil, onde geralmente o desenvolvimento da aplicação é feito em conjunto com um banco de dados que está em construção. Assim, a estrutura da base de dados vai sendo alterada em conjunto com o desenvolvimento.

> #### Seeds
> - Como o próprio nome diz, um seeder é um semeador. Neste contexto específico serve para alimentar a base de dados com dados.
> - Geralmente é usado para popular a base com dados padrões, necessários pro funcionamento correto da aplicação.
> - Por exemplo: você desenvolve uma aplicação que só pode ser acessada por usuários autenticados, quando esta publicação for publicada pela primeira vez, a estrutura do banco de dados vai ser criada. Como será possível acessar a aplicação para criar o primeiro usuário? Bem, existem várias maneiras de se lidar com isso, o seeder é uma delas (ótima maneira, na minha opinião. Diga-se passagem).
