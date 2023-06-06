Projeto DB1 - README
Infelizmente, certas coisas não saíram como planejado neste projeto.enfreitei diversos problemas que afetaram o funcionamento correto do sistema. quero desculpas pelos inconvenientes causados, e gostaríamos de fornecer algumas orientações para executar o projeto em sua máquina.

Executando o Projeto
Para iniciar o projeto no terminal, você pode usar o comando docker-compose up. No entanto, lamentavelmente, os arquivos Dockerfile do backend e frontend não funcionaram corretamente. Portanto, ao clicar na porta do Docker, os servidores não serão abertos.

Para rodar o backend, digite no terminal da pasta "back" o comando php artisan serve. Isso iniciará o servidor PHP para o backend.

Para rodar o frontend, digite o comando npm start no terminal da pasta "front". Isso iniciará o servidor de desenvolvimento para o frontend.

Configurando o Banco de Dados
Para criar o banco de dados, digite o seguinte comando no terminal: php artisan migrate:fresh --seed. Isso criará o banco de dados com as migrações e populará as tabelas com dados de teste.

Limitações e Problemas Conhecidos
Lamentamos informar que não conseguimos estabelecer a conexão adequada entre o frontend e o backend. Estávamos enfrentando erros de Axios e, posteriormente, erros de CORS. Esses problemas afetaram a funcionalidade correta do sistema.

Além disso, algumas funcionalidades não estão implementadas corretamente. Por exemplo, a lógica do carrinho de compras apresenta problemas, onde ao tentar excluir um item, todos os itens do carrinho são apagados. Essa é uma falha que ainda não conseguimos resolver.

Também não conseguimos fazer com que o redirecionamento para a outra página após a finalização da compra funcione corretamente.


Gostaria de expressar minha sincera gratidão por eu fazer este projeto. Embora não tenha conseguido atender todas as expectativas, essa experiência foi incrível para mim como profissional. Estive empenhado e dedicado, vivendo e respirando esse projeto. Fazia tempo que não me sentia tão animado e motivado.

Reconheci minhas limitações ao longo do processo e identifiquei áreas em que posso melhorar. Essa jornada de autoconhecimento foi realmente incrível para mim. Mesmo que este README não seja o espaço apropriado, gostaria de expressar o quão grato estou por essa oportunidade.

Mais uma vez, muito obrigado por tudo!


