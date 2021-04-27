Alunos:
Lucas Eduardo Batista Ferreira;
Gabriel Moreira Bini;
Douglas Borges.

# Trabalho SonarCloud
Neste artigo foi documentado todas as atividades executadas e experiências vivenciadas ao utilizar o SonarCloud em nosso projeto.
O projeto utilizado foi o mesmo que está sendo desenvolvido na matéria PAC, o qual foi feito utilizando o framework NextJS.

## Primeiro contato
Ninguém da equipe conhecia a ferramenta, então o primeiro passo foi todos pesquisarem como funciona e como utilizar.
Em seguida, foi implementada em nosso código e foi gerado uma dashboard indicando os possíveis bugs em nosso código. Mas o mais surpreendente foram as dicas e recomendações de melhorias para o código.

![Dashboard antes](https://i.imgur.com/mcmR0Kd.jpg)

Nesta imagem pode-se ver o quão completa e efetiva essa ferramenta é. Ela mostra a segurança do código, quantas melhorias podem ser feitas nela e as duplicações de código.

## Corrigindo e melhorando
Depois de termos acesso à toda essa informação, só restava uma coisa a fazer, botar a mão na massa...
O SonarCloud detalhava muito bem o que poderia ser evitado e melhorado no código. Então foi bem tranquilo zerar os Bugs e os Code Smells.
Passamos por apenas um contra-tempo, o SonarCloud considerava como um Code Smell uma abordagem que tomamos intensionalmente. Mas ela dá a opção de informar que aquilo não é algo ruim, mas sim um comportagento desejado do código.

![Adaptando Soundcloud](https://i.imgur.com/MjuHbLD.jpg)

## Finalizando as correções
A melhor parte de ter seguido as recomendações do SonarCloud foi, sem dúvidas, a experiência "gamificada" dele, onde a cada commit ele abaixava o número de smells e descia o gráfico.
Acabou que o tempo mensurado para as correções foi bem impreciso. Dizia que tudo seria feito em aproximadamente 54min, mas acabou sendo apenas uns 20min.

![Dashboard depois](https://i.imgur.com/VWciHGA.jpg)

## Conclusão
Tendo em vista todos o assuntos abordados, podemos concluir que a ferramenta é ótima, ajuda muito a escrever códigos melhores e facilita o processo de code review. Outro ponto muito positivo é que ela é gratuita para repositórios públicos, o que é excelente para fins didáticos.
Nossa experiência foi muito boa utilizando essa ferramenta. É fácil de usar, muito útil e, sinceramente, parece coisa de outro mundo.
