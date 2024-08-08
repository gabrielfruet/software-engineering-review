# MÓDULO 2 – Processos Prescritivos

## Questões

1. **Elenque as características relevantes de um projeto de software que podem interferir na escolha de um processo de desenvolvimento.**  
   Resposta: Tempo de entrega, risco aceitável, custos, capacidade de mudança dos requisitos. 

2. **Discuta a complexidade do gerenciamento da comunicação em projetos de software relativamente ao número de participantes do desenvolvimento.**  
   Resposta: Quanto mais participantes no desenvolvimento, mais é necessário uma estrutura coesa de comunicação, de tal forma que a informação não seja perdida ou descartada. 

3. **A qualidade de um processo garante a qualidade do produto? Discuta a sua resposta.**  
   Resposta: Se o produto for de má qualidade inicialmente(não resolve nenhuma dor plausível, não tem nenhum tipo de visão) o processo ajudará a desenvolver com qualidade na medida do possível, mas não ira superar a má qualidade intrínseca da ideia. No entanto, se for de boa qualidade, o processo ira ajudar a concretizar e implementar o produto de forma correta, tendendo a ter um produto de boa qualidade.

4. **Quais são as principais críticas relacionadas ao desenvolvimento sequencial na abordagem conhecida como cascata (ou waterfall)?**  
   Resposta: A necessidade de retrabalho quando há erros em uma das camadas e o aumento exponencial do risco ao longo das etapas. A falta de previsão de falhas também, já que não há nada previsto caso haja problema em alguma delas.

5. **Todos os softwares construídos segundo a abordagem sequencial apresentaram problemas? Explique.**  
   Resposta: No geral, são softwares que são mais caros e engessados, já que qualquer tipo de mudança vai ser necessário corrigir de uma forma não prescrita pelo projeto, que custaria caro. Além disso não estão abertos a mudança de requisitos. Isso tudo contribui para que esses softwares apresentem problemas. 

6. **O que é desenvolvimento iterativo? O que é desenvolvimento incremental? É possível fazermos um sem o outro? Discuta a sua resposta.**  
   Resposta: Desenvolvimento iterativo é definir uma quantidade de atividades N menores que o processo inteiro, que serão realizadas repetidas vezes, ou seja, quando acabar as N atividades, eu integro e retomo a atividade inicial e continuo o desenvolvimento. No dev. iterativo, o risco costuma ser maior no início do projeto, pois há mais incertezas, mas ao longo das iterações, as incertezas vão sendo postas e resolvidas ao longo das atividades, já que a iteração seguinte tem informação privilegiada sobre o reusultado da iteração anterior. Atividades aqui não são demandas específicas, mas coisas mais abstratas, como design, implementação, requisitios e etc...

   Desenvolvimento incremental tem como objetivo entregar o produto de maneira incremental, ou seja, entrega-se um produto menor que o final, com menos funcionalidades a cada iteração até que chegue no produto final, de tal modo que cada iteração incrementa algo no produto atual.

   Podemos fazer dev. iterativo sem incremental, mas o contrário não, pois o dev. incremental é iterativo por natureza, já que cada iteração tem como objetivo um entregável. No entanto, o iterativo não tem como objetivo um entregável em cada iteração por definição, mas simplesmente o desenvolvimento em si

7. **Quais as vantagens trazidas pelo desenvolvimento iterativo e incremental? Discuta os eventuais custos consequentes desta abordagem (apesar de suas claras vantagens!) quando comparada ao desenvolvimento sequencial.**  
   Resposta: A vantagem é que há diminuição de incertezas no início do projeto, como há iterações, o projeto e o produto vão ficando mais desenvolvidos a cada etapa do projeto, que diminui as incertezas, diminuindo os riscos. É preciso sempre ter "pessoal" disponível para participar de cada atividade da iteração, mesmo nos momentos do projeto que certas atividades são menos requisitas, como no ínicio que não há o que testar, ou no final, que há poucas coisas para definir em escopo.

8. **Explique a razão pela qual a curva que define a intensidade dos riscos em um projeto pode cair mais rapidamente ao longo do tempo de projeto quando usamos abordagens iterativas.**  
   Resposta: Pois as incertezas e riscos vão diminuindo nas primeiras iterações, já que o projeto vai se tornando mais concreto e as ideias que o rondeiam vão sendo colocadas em prática. 

9. **O modelo V define um processo de desenvolvimento sequencial ou iterativo? Explique.**  
   Resposta: Sequencial, pois, apesar de cada etapa estar atrelada a um tipo de teste, não há retorno ou iteração, é feito etapa -> teste -> etapa -> teste de maneira sequencial.

10. **Quais são os benefícios e limitações trazidos pelo modelo V?**  
    Resposta: Benefícios: Cada etapa é testada, diminuindo o risco, contribuição para o desenvolvimento de software
    Limitações: Retrabalho e realocação para cada etapa de teste, apesar da diminuição do risco, a incerteza continua a mesma pois é sequencial.

11. **Qual a contribuição original trazida pelo Modelo Espiral para a Engenharia de Software? Pode-se dizer que a participação do cliente neste processo é idêntica ao que ocorre no modelo cascata? Explique.**  
    Resposta: Principalmente a analise de riscos, pois cada ciclo do projeto tem etapas de analise de risco. Além de ser um modelo iterativo e incremental. Cada ciclo corresponde a um passeio no ciclo de vida do software. Não, pois no cascata só há contato com o cliente no inicio e no fim, já no espiral, cada ciclo tem contato com o cliente no início e no final, para feedback e entendimento do direcionamento do projeto.

12. **Dizemos que o Processo Unificado é um framework. O que isso significa?**  
    Resposta: Significa que é um arcabouço de metodologias, uma coleção de métodos e  boas práticas adaptáveis para inúmeros casos de uso.

13. **O Processo Unificado é dividido em fases. Podemos inferir desta afirmação que se trata de um processo sequencial como o cascata? Justifique a sua resposta.**  
    Resposta: Não, pois essas fases são realizadas de maneira iterativa e incremental.h

14. **Embora não tenhamos ainda discutido as formas de representação de requisitos (o modelo funcional), o que você entende por Caso de Uso?**  
    Resposta:Caso de uso é uma forma de estruturação de requisitos com base na interação entre atores e softwares.

15. **Quando se diz que o PU é orientado ou dirigido por Casos de Uso, o que isso significa?**  
    Resposta: Pois no UP a evolução do projeto se apoia na especifiação e desenvolvimento dos casos de uso. 

16. **O que o PU preconiza para ordenação do desenvolvimento de Casos de Uso? Explique.**  
    Resposta: A criticidade do caso de uso, primeiro os casos de uso mais críticos, depois os menos críticos.

17. **Como o PU propõe que se lide com a redução de riscos?**  
    Resposta: Antecipaçao de casos de uso mais críticos, uso de prototipação para reduzir incertezas, verificação de qualidade, controle de riscos desde o ínicio do projeto.

18. **No PU, é possível definir a arquitetura de software sem especificar Casos de Uso? Explique.**  
    Resposta: Não, pois o desenvolvimento se apoia nos casos de uso.

19. **É certo afirmar que em uma iteração do PU somente atividades concernentes a uma disciplina podem ser realizadas? Justifique.**  
    Resposta: Não, pois são realizadas diversas atividades e disciplinas diferentes, de uma maneira que incremente o que tinhamos antes no projeto.

20. **O ciclo construtivo do PU é desenvolvido em fases. No caso do RUP, as fases são denominadas Concepção, Elaboração, Construção e Transição. Isso faz desse um processo sequencial e traz ao modelo os mesmos problemas que encontramos no modelo cascata? Discuta a sua resposta.**  
    Resposta: Apesar de apresentar uma sequencialidade de fases, o modelo não é sequencial, pois cada fase é composta de várias iterações. As fases servem como norte para saber em que ponto o software esta no desenvolvimento. Fases mais no início possuem maior incerteza e risco, já fases no final possuem menor incerteza e risco.

21. **Que tipo de codificação pode-se mais facilmente encontrar na fase de “concepção” do PU, em que os requisitos são possivelmente ainda pouco amadurecidos?**  
    Resposta:

22. **A grande quantidade de papéis definida pelo RUP pode tornar a adoção desse modelo de processo impraticável? Justifique a sua resposta.**  
    Resposta:

23. **O que é um artefato no RUP? Qual a sua relação com as atividades?**  
    Resposta:

24. **Todos os artefatos no RUP devem ser submetidos ao controle de versão? Justifique a sua resposta.**  
    Resposta:
