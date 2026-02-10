# Tríade CIA na prática (Linux)

Este exercício tem como objetivo demonstrar, de forma simples e prática, os três pilares da Segurança da Informação — Confidencialidade, Integridade e Disponibilidade — utilizando apenas conceitos básicos do sistema Linux.

A ideia aqui não é complicar, mas mostrar que segurança começa no fundamento.

## Confidencialidade

Neste ponto, o foco é garantir que a informação só possa ser acessada por quem tem permissão.

A proposta é criar um arquivo que contenha uma informação sensível e restringir o acesso para que apenas o usuário dono consiga ler esse conteúdo. Dessa forma, fica evidente que outros usuários do sistema não teriam acesso ao arquivo, protegendo os dados contra leitura não autorizada.

Isso representa a confidencialidade na prática: informação visível apenas para quem deve vê-la.

## Integridade

Aqui o objetivo é garantir que a informação não seja alterada sem que o dono perceba.

A ideia é trabalhar com um arquivo importante, onde qualquer modificação fique evidente. Assim, é possível demonstrar que alterações não autorizadas comprometem a confiabilidade do dado e que mecanismos de controle são essenciais para preservar sua integridade.

Ou seja, o dado continua correto, confiável e protegido contra mudanças indevidas.

## Disponibilidade

Neste pilar, o foco não é quem acessa ou quem modifica, mas se a informação está acessível quando é necessária.

Mesmo que um dado seja confidencial e íntegro, ele perde seu valor se não estiver disponível no momento certo. Aqui entra a importância de acesso adequado, permissões corretas e práticas como backup, que garantem que a informação continue utilizável mesmo diante de falhas ou problemas.

## Conclusão

A Tríade CIA mostra que segurança da informação não depende de um único fator. Confidencialidade, Integridade e Disponibilidade precisam existir juntas. Se uma falha, todo o sistema fica vulnerável. Na prática, segurança é equilíbrio: proteger o dado, garantir sua confiabilidade e assegurar que ele esteja disponível quando realmente importa.
