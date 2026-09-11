| Cenário | Exchange escolhida | Justificativa |
|---|---|---|
| **1** | **Fanout** | Envia a notificação para **todas as filas conectadas** ao exchange. |
| **2** | **Direct** | Envia a mensagem **apenas para a fila de erro crítico**, usando uma chave de roteamento específica. |
| **3** | **Topic** | Permite encaminhar eventos como `pedido.criado` e `pedido.cancelado` para filas conforme **categorias/padrões de roteamento**. |