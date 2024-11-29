# Erros do código:
1. Não há quase nenhuma documentação no código, sem a explicação do que ele faz cria-se uma dificuldade de sua interpretação e leitura.
2. As variáveis não possuem boas nomenclaturas, com nomes vagos e genéricos que podem criar confusão.
3. Não há muita legibilidade ou organização no código, sem um padrão muito claro, quebras de linha inconsitentes e métodos não organizados.
4. Os NullPoints não foram tratados devidamente, podendo criar pontos de NullPointerExceptions.
5. A arquitetura está pouco respeitada, contendo lógica de conexão e consulta misturada sem separação clara entre camadas.
6. Há uma conexão com o banco de dados não fechada após o uso (conn).  
