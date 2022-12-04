## Respostas da atividade
1. Qual problema percebeu ao realizar tais alterações?
```
  A mensagem "Dados obtidos do servidor!" apareciam primeiro do que os dados obtidos.
```
2. Explique porque o problema ocorreu e o qual a relação com chamadas assíncronas?
```
  Este problema ocorre devido ao interpretador Javascript executar as chamadas assíncronas em segundo plano, passando imediatamente para a próxima instrução, de modo que a inserção da mensagem "Dados obtidos do servidor!" fosse finalizada primeiramente que a requisição ao servidor.
```
3. Altere o código para resolver o problema.