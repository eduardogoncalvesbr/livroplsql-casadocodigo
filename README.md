livroplsql-casadocodigo
=======================

Olá, galera!!! Tudo bom? Fico muito feliz por você ter despendido um tempo para ler meu livro e o mais bacana, se você chegou até aqui, é sinal que ficou interessado em ver como tal da PLSQL funciona e deseja testar os conhecimentos adquiridos. Fique a vontade, abaixo, te explico como montar a base para testar os PLSQLs do livro e também utilizá-los em suas práticas. Conte comigo para qualquer coisa. Forte abraço e aproveite o material.

Qualquer coisa me contate pelo email: eduardogoncalves.br@gmail.com

Vamos lá…

Para praticar melhor os conceitos do livro, sugiro que você crie esta base de dados e execute os exemplos mostrados em cada capítulo. Ainda está valendo aquela máxima que “A prática leva a perfeição”. Então não perca tempo e comece a treinar!!! ;-)
	ATENÇÃO: Não utilize ambientes de produção para estes testes. Utilize sempre bancos de dados de teste, principalmente, se estiverem utilizando usuários com privilégio de DBA, muito menos se você tiver pouca experiência para manipulá-los.




	Obs.: Para a base HR, pode acontecer de alguns erros surgirem logo no início da execução do script. Isto porque antes de criar os objetos, tabelas e views, ele tenta excluí-las para o caso de você já tenha executado este script, anteriormente. Neste caso, ele apagará todos os objetos e recriará todos novamente. Na base SCOTT, tem um arquivo específico para isto (DEMODROP.SQL), que está dentro da pasta que você descompactou, que serve para apagar os objetos criados. Ao contrário da base HR, na criação da base SCOTT este arquivo não chamado. Caso você queria excluir todos os objetos execute o arquivo que esta na pasta. Eu deixei desta forma, para não mexer nos script padrões distribuídos pela Oracle.