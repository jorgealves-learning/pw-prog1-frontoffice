# Feature: Carrinho de Compras

Este módulo implementa a funcionalidade de um carrinho de compras simples, permitindo que usuários selecionem pratos de restaurantes, vejam o resumo do pedido (ticket) e realizem o pagamento.

## 📋 Descrição

A funcionalidade permite que o usuário:
1. Valide se o prato está no menu do restaurante.
2. Calcule o preço do pedido com base na quantidade de pratos selecionados.
3. Exiba o ticket do pedido para conferência.
4. Finalize a compra, se assim desejar.

## 🚀 Funcionalidade Principal

### Função `ticket(prato, restaurante, user, quantidade)`

Essa função realiza as seguintes etapas:
- **Validação**: Verifica se o prato escolhido está no menu do restaurante.
- **Criação do Ticket**: Gera um ticket com os itens do pedido e a quantidade.
- **Interação com o Usuário**: Solicita confirmação para finalizar o pedido.
- **Pagamento**: Finaliza o processo de compra se o usuário optar por prosseguir.
- **Exibição de Menus**: Após a operação, exibe o menu atualizado.

## 📚 Exemplos de Uso

### Fluxo de Pedido
1 - O usuário seleciona um prato, restaurante, quantidade e fornece suas credenciais.
2 - A função ticket valida o prato.
3 - O sistema gera e exibe o ticket do pedido.
4 - O usuário confirma o pedido.
5 - O sistema processa o pagamento e exibe o menu atualizado.

### `ticket(prato="Pizza", restaurante="Restaurante X", user="Usuario123", quantidade=2)`

## 🔧 Melhorias Futuras

- Suporte para múltiplos itens no ticket.
- Implementar tratamento de erros mais robusto.
- Adicionar cálculo automático de preços baseados em quantidade.
- Integração com sistemas de desconto e promoções.