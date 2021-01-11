# Aplicando design patters na prática com C#

## Design Patters

Design Patters são soluções reutilizáveis para problemas comumente ocorridos (no contexto do design de software). Estes padrões foram iniciados como melhores práticas que foram aplicadas repetidamente a problemas semelhantes encontrados em diferentes contextos. Eles se tornaram populares depois que foram apresentados, de forma estrutura no livro "Design Patters - Elements of Reusable Object-Oriented Software" (Gang of four) em 1994

***O "Gang of Four" representa apenas uma de muitas coleções de design patters***

![livro design patters](./img/livro.jpg)



## Porque devo usar os padrão de projeto?

- Produtividade

  Estes padrões são modelos de resolução de problemas que já foram utilizados e testados inúmeras vezes.

- Manutenção

  Os padrões são baseados em soluções de baixo acoplamento e padronização de soluções.

- Termos Universais

  Os projetos são amplamente conhecidos desta forma as discussões técnicas são facilitadas.



## Desuso

Alguns padrões surgiram para contornar as limitações de um determinada linguagem de programação e neste caso os padrões criados eram como gambiarras que possibilitavam implementação de mecanismo não suportado nativamente.



## Soluções "Prontas"

Os padrões não são soluções prontas.



## A "bala de prata"

Um martelo é ótimo para colocar um prego na parede, mas não funciona tão bem se você tiver um parafuso.



# S.O.L.I.D

- **Princípio da responsabilidade única**

  ma classe deve ter um , e somente um, motivo para mudar.

- **Princípio aberto fechado**

  Você deve ser capaz de estender um comportamento de uma classe, sem modificá-lo

- **Princípio da substituição de Liskov**

  As classes base devem ser substituíveis por suas classes derivadas

- **Princípio da segregação da interface**

  Muitas interfaces especificas são melhores do que uma interface única

- **Princípio da inversão da dependência**

  Dependa de uma abstração e não de uma implementação.