# SD-SincronizacaoThreadsJava

## Análise da execução:
Os dois códigos simulam um cenário em que duas threads, chamadas produtor e consumidor, trabalham juntas.

No primeiro código, não há controle de sincronização, o que pode fazer com que as duas threads acessem os recursos ao mesmo tempo, causando erros. Já no segundo código, a sincronização é feita usando "monitores", garantindo que o produtor só coloque um número quando o consumidor tiver pegado o número anterior, evitando conflitos e garantindo que as tarefas sejam feitas na ordem certa.

## Analise do log:

``MeuDadoThreadsJava`` -> Em duas execuçoes realizadas os arquivos de logs apresentaram pequenas diferenças

``MeuDadoMonitorJava`` -> A principal diferença entre as execuções é como a sincronização com o monitor melhora o controle sobre a ordem de acesso aos dados, evitando que ambos tentem acessar os dados simultaneamente

``MeuDadoEventJava`` -> Não foi possivel executar por causa de erros no código.

