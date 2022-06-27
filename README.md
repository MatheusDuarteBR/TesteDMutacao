# Teste_De_Mutacao // Gerenciamento, Configuração e Processos de Software.

Aqui temos o nosso código que será testado, um código simples que verifica que o usuário já pode tirar a CNH ou não pela idade.

![alt text](https://github.com/MatheusDuarteBR/TesteDMutacao/blob/main/images/entrada.png)

A expressão condicional idade >= 18 será alterada para true e false;
O operador de idade >= será alterado para < e >;
O bloco => { return idade >= 18 } será alterado para => {}.

Executando esse teste com o STRYRKEOUT temos a seguinte saída de dados.

![alt text](https://github.com/MatheusDuarteBR/TesteDMutacao/blob/main/images/saida.png)

Porém com esse teste conseguimos verificar que temos somente 60% do teste concluído, então das 5 mutações que temos, 2 delas que "sobreviveram". Portanto para que as 5 mutações não sobrevivam rodados o seguinte código.

![alt text](https://github.com/MatheusDuarteBR/TesteDMutacao/blob/main/images/FixOfmutations.png)

Após essa correção de código temos zero sobreviventes em nosso código ou seja o teste foi concluído.
