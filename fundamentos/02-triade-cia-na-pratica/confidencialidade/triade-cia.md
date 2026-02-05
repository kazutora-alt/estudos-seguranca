## Confidencialidade

Foi criado um arquivo chamado `segredo.txt` contendo uma informação sensível.

Inicialmente, o arquivo possuía permissões que permitiam leitura por outros usuários do sistema, o que representa um risco de acesso não autorizado.

Para aplicar o princípio da confidencialidade, as permissões do arquivo foram ajustadas para permitir acesso apenas ao usuário dono do arquivo, utilizando permissões restritivas no sistema Linux.

Após a alteração, somente o proprietário do arquivo consegue ler ou modificar o conteúdo, impedindo que outros usuários tenham acesso à informação.

Esse controle demonstra, de forma prática, o pilar da Confidencialidade da Tríade CIA, garantindo que a informação seja acessível apenas por quem tem autorização.
