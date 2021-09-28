### Processo de Testes de Software (Conceitos, Fases, Técnicas e Automação de Testes)

Conceitos Básicos 

Inicialmente, precisamos conhecer a diferença entre Defeitos, Erros e Falhas.

 **Defeito** É um ato inconsistente cometido por um indivíduo ao tentar entender uma determinada informação, resolver um problema ou utilizar um método ou uma ferramenta. Por exemplo, uma instrução ou comando incorreto. 

**Erro** É uma manifestação concreta de um defeito num artefato de software. Diferença entre o valor obtido e o valor esperado, ou seja, qualquer estado intermediário incorreto ou resultado inesperado na execução de um programa constitui um erro. 

**Falha**  É o comportamento operacional do software diferente do esperado pelo usuário. Uma falha pode ter sido causada por diversos erros e alguns erros podem nunca causar uma falha. 

**Defeitos** fazem parte do universo físico (a aplicação propriamente dita) e são causados por pessoas, por exemplo, através do mal uso de uma tecnologia. Defeitos podem ocasionar a manifestação de erros em um produto, ou seja, a construção de um software de forma diferente ao que foi especificado (universo de informação). Por fim, os erros geram falhas, que são comportamentos inesperados em um software que afetam diretamente o usuário final da aplicação (universo do usuário) e pode inviabilizar a utilização de um software. A imagem a seguir sumariza esse parágrafo: ![img](http://www.devmedia.com.br/imagens/engsoft/artigo7/image01.jpg)  

Fases do Processo de Testes 

Os testes devem estar presentes em todo o processo de desenvolvimento de software, e geralmente são divididos nas seguintes fases:

** Testes de Unidade** 

É a fase de testes onde cada unidade do sistema é testada individualmente. O objetivo é isolar cada parte do sistema e garantir que elas estão funcionando conforme especificado, porém não garante que a integração dessas partes irá funcionar corretamente. 

 Ex: no teste da função que valida CPF, o teste se resume apenas em checar se a função é capaz de “dizer” se o CPF é válido ou não.

 **Testes de Integração** 

Nesta fase as unidades do sistema são testadas de forma combinada, o objetivo é detectar falhas na interação entre as unidades integradas. Não faz parte desta fase os testes de integração com outros sistemas.  

Ex: Na integração do cadastro de clientes com a função que valida CPF, as duas unidades já foram testadas individualmente na fase de testes de unidade, porém é neste momento que a interação entre elas é validada.  

**Testes de Sistema** Nesta fase o sistema é testado completamente, ou seja, todas as funcionalidades do sistema são testadas, assim como as integrações com outros sistemas que possam existir. Os testes não se limitam apenas a requisitos funcionais, pois requisitos não funcionais também são testados nesta fase. 

**Testes de aceitação** 

Nesta fase serão testadas as funcionalidades requeridas pelo cliente durante o projeto. Deve ser feito, preferencialmente, pelo usuário final. 

**Teste de Regressão** 

Teste de regressão não corresponde a um nível de teste, mas é uma estratégia importante para redução de “efeitos colaterais”. Consiste em se aplicar, a cada nova versão do software ou a cada ciclo, todos os testes que já foram aplicados nas versões ou ciclos de teste anteriores do sistema. Pode ser aplicado em qualquer nível de teste. Com os testes sendo executados em todas as fases do desenvolvimento é possível detectar falhas com antecedência e entregar o sistema com mais qualidade. Além disso, quanto antes a falha é detectada mais barato é para corrigi-la, evitando aumento de custo desnecessário no projeto. A imagem a seguir mostra de maneira resumida a ordem dos testes: 

![fases_testes](http://404846152.r.upxcdn.net/br/wp-content/uploads/2013/07/fases_testes-171x180.png)

 Na imagem a seguir é possível ver o paralelismo entre as atividades relacionadas ao desenvolvimento e aos testes de software. ![img](http://www.devmedia.com.br/imagens/engsoft/artigo7/image03.jpg)  Técnicas de Teste de Software 

As principais técnicas existentes no que se refere a testes de software são: técnica funcional e estrutural. 

** Técnica Estrutural (ou teste caixa-branca)** 

Essa técnica trabalha diretamente sobre o código fonte do componente de software para avaliar aspectos tais como: teste de condição, teste de fluxo de dados, teste de ciclos e teste de caminhos lógicos. Este tipo de teste é desenvolvido analisando-se o código fonte e elaborando-se casos de teste que cubram todas as possibilidades do componente de software. Dessa maneira, todas as variações originadas por estruturas de condições são testadas. A técnica de teste de Estrutural é recomendada para os níveis de Teste da Unidade e Teste da Integração, cuja responsabilidade principal fica a cargo dos desenvolvedores do software, que são profissionais que conhecem bem o código-fonte desenvolvido e dessa forma conseguem planejar os casos de teste com maior facilidade. 

 ** Teste Funcional (ou teste caixa-preta)**

 Técnica de teste em que o componente de software a ser testado é abordado como se fosse uma caixa-preta, ou seja, não se considera o comportamento interno do mesmo. Dados de entrada são fornecidos, o teste é executado e o resultado obtido é comparado a um resultado esperado previamente conhecido. Haverá sucesso no teste se o resultado obtido for igual ao resultado esperado. O componente de software a ser testado pode ser um método, uma função interna, um programa, um componente, um conjunto de programas e/ou componentes ou mesmo uma funcionalidade. A técnica de teste funcional é aplicável a todos os níveis de teste. A seguir temos duas imagens que mostram o funcionamento da Técnica Estrutural (imagem à esquerda) e Teste Funcional (à direita): 

![img](http://www.devmedia.com.br/imagens/engsoft/artigo7/image04.jpg)  ![img](http://www.devmedia.com.br/imagens/engsoft/artigo7/image06.jpg)  

Automação de Testes Automação de teste é o uso de software para controlar a execução do teste de software. Há duas abordagens usadas na automação. 

No **teste de interface gráfica**, uma plataforma gera os eventos de entrada na interface de utilizador do sistema e observa as mudanças na saída. Várias ferramentas fornecem funcionalidades para gravar e reproduzir as ações do utilizador. Sendo aplicável a qualquer aplicação que use uma interface gráfica, esta técnica possui a vantagem de exigir menos codificação, mas implica dificuldades de manutenção do teste, como quando a interface gráfica é alterada. Já no teste **baseado em código**, a interface pública das classes, módulos ou bibliotecas são testadas com uma variedade de argumentos de entrada, observando-se a saída. Uma tendência atual no desenvolvimento de software é o uso de plataformas xUnit, que permitem realizar testes de unidade para determinar se as seções do código estão processando de forma esperada em diversas circunstâncias. O teste baseado em código é uma funcionalidade chave no desenvolvimento ágil de software.  



Fontes:http://www.devmedia.com.br/artigo-engenharia-de-software-introducao-a-teste-de-software/8035http://www.matera.com/br/2013/07/19/fases-de-testes-de-software/https://pt.wikipedia.org/wiki/Automação_de_teste





