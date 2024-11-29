
# Feature: Order

Esta feature permite aos usuários escolher um restaurante, selecionar pratos de seu menu, e adicionar os itens ao carrinho.


## 📄 Descrição

A funcionalidade implementa um fluxo simples para que o usuário possa:
1. Visualizar os restaurantes disponíveis.
2. Escolher um restaurante e visualizar seu menu.
3. Selecionar um prato e a quantidade desejada.
4. Validar e adicionar o pedido ao carrinho.

## 🔑 Função Principal

### `escolhe_menu(user)`
Gerencia todo o fluxo de escolha do restaurante e do prato. 

#### Processo:
1. **Loop Principal**:
   - Lista os restaurantes disponíveis usando `Restaurante.Mostar_Restaurantes()`.
   - Coleta a entrada do usuário para selecionar o restaurante e o prato.
   - Valida os itens escolhidos.
2. **Adicionar ao Carrinho**:
   - Chama `Carrinho.ticket()` para salvar o pedido se o usuário confirmar.
  
   Diogo Lopes
