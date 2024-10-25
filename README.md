# FECHADURA DIGITAL
## Projeto Henrique e Edson

Este projeto tem como objetivo criar uma simulação de uma fechadura digital utilizando o simulador edSim51 e um microcontrolador 8051. A fechadura digital permite ao usuário definir e verificar senhas por meio de um teclado matricial, além de oferecer controle visual do status da fechadura através de LEDs.

Ao iniciar o sistema, uma senha padrão "0000" é definida. O usuário pode inserir uma nova senha utilizando o teclado e escolher entre duas ações principais:

*Redefinir Senha: Pressionando o botão hashtag (#), o usuário entra no modo de redefinição, onde pode definir uma nova senha personalizada.
*Verificar Senha: Pressionando o botão asterisco (*), o sistema verifica se a senha inserida está correta. Se a senha for correta, o sistema exibe a mensagem "ABERTO" no display LCD e acende um LED verde para indicar que a fechadura foi aberta.
O sistema oferece uma experiência prática e flexível, permitindo ao usuário alterar a senha sempre que necessário, mantendo a segurança e simplificando o gerenciamento de acessos.

Funcionalidades
*Senha Padrão: O sistema inicia com a senha "0000".
*Inserção de Senha: O usuário pode digitar uma senha de quatro dígitos utilizando o teclado matricial.
*Redefinição de Senha: Ao pressionar #, o sistema permite a redefinição da senha para uma nova sequência de quatro dígitos.
*Verificação de Senha: Ao pressionar *, o sistema verifica a senha inserida.
*Se a senha estiver correta, o sistema exibe "ABERTO" no LCD e acende o LED verde, simulando a abertura da fechadura.
*Se a senha estiver incorreta, uma mensagem de "ERRO" é exibida e o LED vermelho permanece aceso, indicando que a fechadura está fechada.
*Controle de LEDs: Indicação visual do status da fechadura.
*LED Verde: Indica que a fechadura está aberta.
*LED Vermelho: Indica que a fechadura está fechada.
*Proteção de Memória: O sistema entra em um modo de espera (função FULL) quando a memória está cheia, aguardando que o usuário pressione # ou * para redefinir ou verificar a senha.
