# Bug Reports - Urban Routes

## Bug 01 - Cálculo de rota não atualizado após alteração do transporte

### Título
Sistema não atualiza corretamente tempo e custo ao trocar o tipo de transporte.

### Ambiente
Aplicação web Urban Routes

### Pré-condição
Origem e destino preenchidos corretamente.

### Passos para reproduzir
1. Inserir um endereço no campo "De"
2. Inserir um endereço no campo "Para"
3. Selecionar um tipo de transporte
4. Observar tempo e custo exibidos
5. Alterar para outro tipo de transporte

### Resultado atual
O sistema não atualiza corretamente as informações de tempo e custo após a troca do transporte.

### Resultado esperado
O sistema deve recalcular e exibir corretamente tempo e custo para o transporte selecionado.

### Prioridade
Grande

---

## Bug 02 - Elemento da interface não exibido corretamente

### Título
Ícone ou opção de transporte não é exibido corretamente na interface.

### Ambiente
Aplicação web Urban Routes

### Pré-condição
Aplicação aberta e carregada no navegador.

### Passos para reproduzir
1. Abrir a aplicação
2. Informar origem e destino
3. Observar a seção de opções de transporte

### Resultado atual
Um ou mais elementos visuais da interface não são exibidos corretamente ou apresentam inconsistência.

### Resultado esperado
Todos os elementos da interface devem ser exibidos corretamente e sem falhas visuais.

### Prioridade
Pequeno

---

## Bug 03 - Comportamento divergente no envio das rotas

### Título
Sistema apresenta comportamento divergente após envio dos endereços.

### Ambiente
Aplicação web Urban Routes

### Pré-condição
Campos "De" e "Para" disponíveis para preenchimento.

### Passos para reproduzir
1. Inserir endereço de origem
2. Inserir endereço de destino
3. Enviar os dados para cálculo de rota

### Resultado atual
O sistema apresenta comportamento diferente do esperado ao processar as informações inseridas.

### Resultado esperado
O sistema deve processar os dados corretamente e apresentar as opções de rota sem erro.

### Prioridade
Grande
