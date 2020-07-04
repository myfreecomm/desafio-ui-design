Teste de UI Design Nexaas
=========================

Este teste é apresentado aos candidatos as vagas de UI Design e Product Design para avaliar os quesitos técnicos.

----------


O Desafio
-------------

Seu objetivo é otimizar a experiência de navegação do usuário na manipulação de um cadastro de produtos. Na primeira etapa é necessário listar todos os produtos e na segunda é apresentada a edição.

> **Notas:**

> - A ideia é avaliar a criatividade na concepção das telasl
> - Lembre-se de que usabilidade é importante, a navegação precisa ser fluída e intuítiva;


#### <i class="icon-file"></i> Telas
<table>
<tbody>
<tr><th>Listagem</th>
  <th>Detalhes</th>
</tr>
<tr>
<td><img src="https://github.com/myfreecomm/desafio-ui-design/blob/master/product-list.png?raw=true" style="height:300px"></td>
</tr>
</tbody>
</table>


#### <i class="icon-folder-open"></i> Consumindo Serviço

Para consumir o serviço da API Rest

**Como usar:**

> - **URL** https://raw.githubusercontent.com/myfreecomm/desafio-mobile-android/master/api/data.json
> - **Método**: GET

Exemplo de resposta
>  [{
        "name": "Pencil",
        "quantity": 1,
        "stock": 5,
        "image_url": "https://github.com/myfreecomm/desafio-mobile-android/blob/master/assets/pencil.png?raw=true",
        "price": 150,
        "tax": 162,
        "shipping": 50,
        "description": "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam nunc magna, gravida ut orci non, egestas venenatis libero. Sed luctus, turpis at porta commodo, ipsum orci volutpat sapien, ut scelerisque diam massa lobortis odioc."
    }]

#### <i class="icon-pencil"></i> Pré-requisitos

- Versão mínima do SDK: 21
- Tela deve ajustar em devices menores.
- Utilizar Kotlin

#### <i class="icon-folder-open"></i> O que esperamos
- Boa arquitetura, pode ser  (mvc, mvp, mvvm, clean etc)
- RxJava ou Coroutines
- Testes unitários
- Cache de imagens
- Tratamentos de erros
- Padrão de Projeto e boas práticas de Orientação a Objetos.
- Google AAC (Android Architecture Components) 

#### <i class="icon-hdd"></i> Plus
- Construir layouts com Constraints
- Trabalhar offline (cache dos dados)
- Injeção de dependência (dagger, koin, kodein)


Publicação
-------------

Crie um **Fork** do repositório para realizar o teste, e depois de finalizado envie um **Pull Request** para nossa equipe interna avaliar
