# :checkered_flag: Biblioteca Digital Comunitária

A Biblioteca Digital Comunitária é uma plataforma que reúne livros e materiais de estudos, permitindo que usuários tenham acesso a informações, reservem livros e baixem materiais de domínio público.

## :technologist: Membros da equipe

554679 - José Witalo - Ciência da Computação.

## :bulb: Objetivo Geral
Ampliar o acesso à leitura e promover a educação, facilitando o acesso a materiais de estudo e livros através de uma plataforma digital acessível.

## :eyes: Público-Alvo
Alunos, professores e comunidades locais.

## :star2: Impacto Esperado
Facilitar o acesso de mais pessoas ao conhecimento, principalmente em lugares com poucas opções de biblioteca, promovendo ainda mais a ação de leitura e apoiando a educação.

## :people_holding_hands: Papéis ou tipos de usuário da aplicação

Usuário não logado.
Administrador.
Usuário comum(que esteja logado).

> Tenha em mente que obrigatoriamente a aplicação deve possuir funcionalidades acessíveis a todos os tipos de usuário e outra funcionalidades restritas a certos tipos de usuários.

## :triangular_flag_on_post:	 Principais funcionalidades da aplicação

Vizualizar o catálogo de livros e materiais disponíveis(Todos os usuários).
Filtrar os livros por categoria e os materias por determinado assunto ou matéria(Todos os usuários).
Realizar reservas de livros físicos(Apenas usuários que estejam logados).
Realizar download de materiais PDF de domínio público(Apenas usuários que estejam logados).
Gerenciar o catálogo(Administrador).
Monitorar as reservas feitas no sistema(Administrador).

## :spiral_calendar: Entidades ou tabelas do sistema

Usuário(ID_user, nome, email, senha, tipo (administrador ou comum)).
Livro(ID_livro, nome, autor, categoria, descrição, disponibilidade).
Reserva(ID_user, ID_livro, ID_reserva, data).
PDF(ID_pdf, título, assunto, descrição, link_download).


----

:warning::warning::warning: As informações a seguir devem ser enviadas juntamente com a versão final do projeto. :warning::warning::warning:


----

## :desktop_computer: Tecnologias e frameworks utilizados

**Frontend:**

Lista as tecnologias, frameworks e bibliotecas utilizados.

**Backend:**

Lista as tecnologias, frameworks e bibliotecas utilizados.


## :shipit: Operações implementadas para cada entidade da aplicação


| Entidade| Criação | Leitura | Atualização | Remoção |
| --- | --- | --- | --- | --- |
| Entidade 1 | X |  X  |  | X |
| Entidade 2 | X |    |  X | X |
| Entidade 3 | X |    |  |  |

> Lembre-se que é necessário implementar o CRUD de pelo menos duas entidades.

## :neckbeard: Rotas da API REST utilizadas

| Método HTTP | URL |
| --- | --- |
| GET | api/entidade1/|
| POST | api/entidade2 |
