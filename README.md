# pw-prog1-frontoffice
ETICEats Frontoffice

## Restaurante - Sistema de Pedidos

Este projeto simula o processo de realizar um pedido num restaurante, validando o prato escolhido, registando o pedido e permitindo o pagamento. Através de funções que interagem com diferentes módulos como 'Restaurante', 'Order' e 'pagar', o sistema oferece uma maneira simples de simular a experiência de fazer um pedido e pagar por ele.

## Estrutura do Projeto

O projeto é composto pelos seguintes módulos:

- **Restaurante**: Contém as funções relacionadas ao restaurante e ao seu menu.
- **Order**: Responsável por mostrar os menus e registar os pedidos.
- **Pagar**: Trata da parte de pagamento do pedido.

A função principal é 'ticket()', que processa o pedido, valida o prato escolhido e chama as funções de pagamento e exibição de menu.

## Fluxo do Sistema

1. **Validação do prato**: A função 'ticket()' valida se o prato escolhido está disponível no menu do restaurante.
2. **Registo do pedido**: Se o prato estiver disponível, é registado o pedido juntamente com a quantidade solicitada.
3. **Confirmação do pedido**: O sistema pergunta ao utilizador se deseja finalizar o pedido.
4. **Pagamento**: Se o utilizador confirmar a finalização, o sistema chama o módulo 'Pagar' para realizar o pagamento.
5. **Exibição do menu**: Após o pagamento ou cancelamento, o sistema exibe novamente o menu de opções.

## Exemplo de Execução

Exemplo simples:
1. O sistema recebe o menu de pratos selecionado e quantidade.
2. O sistema valida se o prato está no menu.
3. Se o prato for válido, o sistema pergunta se o utilizador deseja finalizar o pedido.
4. Caso o utilizador confirme, o sistema realiza o pagamento e exibe o recibo.
