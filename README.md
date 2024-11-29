# Critérios da Caixa Branca
1. Identificação dos Pontos, Nodos e Arestas
- Quantidade de pontos: 14
- Nodos:

N1: Início da execução do código "public class User {".

N2: Chamada para o método conectarBD() " public Connection conectarBD() {".

N3: Carregamento do driver MySQL " Class.forName("com.mysql.Drive.Manager").newInstance();".

N4: Definição da URL de conexão "String url = "jdbc:mysql://127.0.0.1/test?user=lopes$password=123";".

N5: Tentativa de conexão com o banco de dados "conn = DriveManager.getConnection(url);".

N6: Tratamento de exceção "}catch (Exception e) { }".

N7: Retorno da conexão.

N8: Execução do método verificarUsuario().

N9: Construção da consulta SQL.

N10: Criação do Statement.

N11: Execução da consulta SQL.

N12: Verificação do resultado da consulta.

N13: Atribuição de valor para result.

N14: Retorno do resultado de result.

Arestas:

A1: Da execução inicial (N1) para a chamada do método conectarBD() (N2).

A2: Do N2 para o carregamento do driver (N3).

A3: Do N3 para a definição da URL de conexão (N4).

A4: Do N4 para a tentativa de conexão (N5).

A5: Do N5 para o tratamento de exceção (N6).

A6: Do N6 para o retorno da conexão (N7).

A7: Do N7 para a execução do método verificarUsuario() (N8).

A8: Do N8 para a construção da consulta SQL (N9).

A9: Do N9 para a criação do Statement (N10).

A10: Do N10 para a execução da consulta SQL (N11).

A11: Do N11 para a verificação do resultado da consulta (N12).

A12: Do N12 para a atribuição de valor a result (N13).

A13: Do N13 para o retorno do valor de result (N14).
