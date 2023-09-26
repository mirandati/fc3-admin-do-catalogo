Revisão criação de classes fazendo os testes 
primeiro pelo TDD  
 * Criação de classes modelos DDD sem ser anemicas
    
 * Resumo para finalizar para que a gente possa voltar para o próximo módulo, que é criar os casos de uso. 
 * Então, bom, esse módulo, a gente criou a nossa entidade, seguindo tudo, o DBD, então a gente fez sempre...
  apresou pelos testes primeiro, e depois a gente tentou seguir a nossa entidade, seguindo o que o TDD fala,
  o Domain Driven Design, que é apresado pelos agregados, apresado pelos Value Objects, 
  apresado pelo Gateway, aqui separado, nomenclatura mais expressiva, então a gente focou muito nisso,
  reparem que a gente conseguiu, junto do DDB com o CleanArt, construir toda a nossa modelagem aqui de categoria
  sem precisar nos preocupar com informações como o banco de dados, informações como o que vai vir de uma Web Request ou não,
  esse tipo de informação são detalhes que a gente não precisa se preocupar agora no começo do projeto, e nem quando a gente
  implementar os casos de uso, a gente vai criar o nosso domínio com as interfaces, nosso caso de uso com as interfaces,
  e por último, a gente se preocupa com os detalhes, e é, por exemplo, se vai usar MySQL, se vai usar um Postgres, 
  se vai usar um KDS, um Cassandra, então esses caras a gente vai se preocupar por último, digamos que eu penso agora,
  isso é um poder, isso é uma arquitetura poderosa, que permite que 
  a gente deixe essas decisões complicadas como detalhes de banco, para depois, que a gente foque na regra de negócio 
  e foque no nosso domínio,
