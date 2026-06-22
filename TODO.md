# TODO - ImobCRM (cadastro de unidades e residencial)

- [ ] Entender o schema esperado (campos atuais de `residencias` e `unidades` no Supabase) e ajustar o front se houver divergência.
- [ ] Corrigir o fluxo de criação de `residencias` para abrir imediatamente o “cadastro do residencial” (nome + unidades).
- [ ] Corrigir o fluxo de “Unidades e Vendas” para que `resSel` e `residencia_id` sejam tratados com o mesmo tipo (string/number) e nunca falhem.
- [ ] Garantir que ao criar/selecionar um residencial o usuário consiga:
  - [ ] Adicionar múltiplas unidades
  - [ ] Marcar unidade como **Vendido**/**Disponível**
  - [ ] Quando vendido, selecionar comprador (lead)
  - [ ] Preencher preço, metragem e detalhes
- [ ] Se necessário, adicionar campos de “informações do residencial” (ex: endereço/obs) na UI (dependente do schema real).
- [ ] Ajustar persistência (insert/update) para `unidades` e manter estado sincronizado.
- [ ] Validar carregamento após refresh (dados continuam aparecendo corretamente).
- [ ] Testar no navegador (criar residencial -> criar unidades -> vender -> atualizar -> recarregar página).

