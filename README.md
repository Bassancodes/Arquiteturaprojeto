Este projeto tem como objetivo criar uma simulação de uma fechadura digital utilizando o simulador edSim51 e um microcontrolador 8051. A fechadura digital permite ao usuário definir e verificar senhas por meio de um teclado matricial, além de oferecer controle visual do status da fechadura através de LEDs.

Ao iniciar o sistema, uma senha padrão "0000" é definida. O usuário pode inserir uma nova senha utilizando o teclado e escolher entre duas ações principais:

Redefinir Senha: Pressionando o botão hashtag (#), o usuário entra no modo de redefinição, onde pode definir uma nova senha personalizada.
Verificar Senha: Pressionando o botão asterisco (*), o sistema verifica se a senha inserida está correta. Se a senha for correta, o sistema exibe a mensagem "ABERTO" no display LCD e acende um LED verde para indicar que a fechadura foi aberta.
O sistema oferece uma experiência prática e flexível, permitindo ao usuário alterar a senha sempre que necessário, mantendo a segurança e simplificando o gerenciamento de acessos.

Funcionalidades
Senha Padrão: O sistema inicia com a senha "0000".

Inserção de Senha: O usuário pode digitar uma senha de quatro dígitos utilizando o teclado matricial.

Redefinição de Senha: Ao pressionar #, o sistema permite a redefinição da senha para uma nova sequência de quatro dígitos.

Verificação de Senha: Ao pressionar *, o sistema verifica a senha inserida.

Se a senha estiver correta, o sistema exibe "ABERTO" no LCD e acende o LED verde, simulando a abertura da fechadura.

Se a senha estiver incorreta, uma mensagem de "ERRO" é exibida e o LED vermelho permanece aceso, indicando que a fechadura está fechada.

Controle de LEDs: Indicação visual do status da fechadura.

LED Verde: Indica que a fechadura está aberta.
LED Vermelho: Indica que a fechadura está fechada.

Proteção de Memória: O sistema entra em um modo de espera (função FULL) quando a memória está cheia, aguardando que o usuário pressione # ou * para redefinir ou verificar a senha.

Como Usar
Inicialização: Ao iniciar o sistema, a senha padrão "0000" estará ativa.
Inserção de Senha:
Utilize o teclado para digitar uma senha de quatro dígitos.
Ações Disponíveis:
Pressione # para redefinir a senha. Digite a nova senha e confirme para armazená-la.
Pressione * para verificar a senha digitada.
Senha Correta: O display exibirá "ABERTO" e o LED verde acenderá.
Senha Incorreta: O display exibirá "ERRO" e o LED vermelho permanecerá aceso.
Modo de Memória Cheia:
Quando a memória estiver cheia, o sistema entrará no modo FULL, onde aguardará que o usuário pressione # ou * para redefinir ou verificar a senha.

Aqui você pode ver o painel inicial, nesse painel aparece o texto "digite a senha"

![image](https://github.com/user-attachments/assets/71ed673d-d8e0-4bec-882c-85e186c48646) 

Ao digitar a senha certa você recebera a mensagem aberto

![image](https://github.com/user-attachments/assets/06e8287c-eff3-4248-ae3b-b16b83b71049)



Caso contrario a mensagem que ira aparecer no visor sera Errado

![image](https://github.com/user-attachments/assets/50b785e3-de32-474c-82b1-166b152c9413)


Aqui esta um diagrama/fluxograma do projeto 

![image](https://github.com/user-attachments/assets/29f4eec3-457c-4cc6-bb7f-63183db952e8)


Por fim, o desenho esquemático do edsim51

![image](https://github.com/user-attachments/assets/27acdfce-081d-4c6d-b87f-91e3f9ce7802)



