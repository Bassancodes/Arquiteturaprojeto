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

Ao digitar a senha certa você recebera a mensagem liberado

![image](https://github.com/user-attachments/assets/86e806fc-d67b-410d-b6b0-9eef04ade99b)

Caso contrario a mensagem que ira aparecer no visor sera Erro

![image](https://github.com/user-attachments/assets/65340745-85ac-4b19-9d9b-5fe250269ee3)

Aqui esta um diagrama/fluxograma do projeto 

![image](https://github.com/user-attachments/assets/74144315-6fde-48e6-8dc7-b54a6d5cd3fb)

Por fim, o desenho esquemático do edsim51

![image](https://github.com/user-attachments/assets/c123b222-75a6-421b-8cc1-743981985ef5)


