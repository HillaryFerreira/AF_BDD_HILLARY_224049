# BDD - Hillary Ferreira - 224049
<h1>Enunciado Exercício</h1>
<p>EXERCÍCIO INDIVIDUAL CONTA_TESTE
REPRODUZA O EXEMPLO DADO CONFORME EXPLICADO EM AULA;CRIE UM REPOSITÓRIO REMOTO DO PROJETO, ESCREVA O README.MD CONFORME O EXEMPLO DADO NO CONTEÚDO DA AULA;ESCREVA O CÓDIGO DA CLASSE CONTA UTILIZANDO OS MÉTODOS QUE O CUCUMBER INDICOU;AO TÉRMINO, EXECUTE O PROJETO E VERIFIQUE AS INFORMAÇÕES DADAS NO CONSOLE, TIRE PRINT DESTAS INFORMAÇÕES E UTILIZE NA CONSTRUÇÃO DO README.MD DO REPOSITÓRIO REMOTO DO PROJETO;
APÓS TER TODAS AS ETAPAS CRIADAS, CRIE A DOCUMENTAÇÃO DA CLASSE CONTA E DO ARQUIVO DE TESTE
CUCUMBER (USE O EXEMPLO QUE A BIBLIOTECA GERA NO ARQUIVO), GERE UM JAVA DOC DO PROJETO;
O EXERCÍCIO FAZ PARTE DAS ATIVIDADES FINAIS E DEVE SER ENTREGUE NO 28/11 ATÉ ÁS 23:59, ESTE PRAZO
NÃO SERÁ PRORROGADO;
O EXERCÍCIO É INDIVIDUAL E EM CASO DE CÓPIA AMBOS OS ALUNOS RECEBERAM ZERO;
ENVIE O LINK DO SEU REPOSITÓRIO REMOTO NO EXERCÍCIO;
UTILIZE À AULA PARA TIRAR DÚVIDAS E REALIZAR O EXERCÍCIO.
</p>
<h1>Gherkin</h1>
<h2>Funcionalidade: Sistema de Locação de Carros</h2>
<ul>
<li>Como um cliente preciso alugar um carro para viajar</li>
</ul>
<h2>Cenário: Reserva antecipada de um carro de luxo</h2>
<ul>
 <li> Dado que o cliente deseja alugar um carro de luxo E o cliente realiza a reserva com antecedência de pelo menos uma semana Quando o sistema processa a reserva Então o sistema deve oferecer um desconto especial no valor total da locação</li>
</ul>
<h2>Cenário: Locação de última hora de um carro utilitário</h2>
<ul>
  <li>Dado que o cliente necessita alugar um carro de última hora e o cliente não tem qualquer reserva prévia, quando o sistema processa a locação então o sistema deve encontrar um veículo disponível</li>
  <li>O sistema deve processar a locação rapidamente</li>
  <li>O o sistema deve informar que o custo será um pouco mais elevado devido à demanda urgente e não ter uma reserva.</li>
</ul>
