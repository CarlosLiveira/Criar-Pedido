# Concluir um Pedido LML

## 1 - Filtrar os pedidos LML  
Caminho: Monitorar / Entregas TMS / Filtro

1 - Filtrar Tipo Operação = LML  
2 - Selecionar um pedido com status Planejada  
3 - Filtrar pelo código interno do pedido escolhido selecionado  

![image](https://github.com/CarlosLiveira/Criar-Pedido/assets/89557656/2468421f-5c99-42c8-ae1b-5392c0b951e9)

## 2 - Concluindo as Etapas  

1 - Clicar no hiperlink código interno  
2 - Selecionar a aba Etapas  
3 - Clicar na linha 1  

![image](https://github.com/CarlosLiveira/Criar-Pedido/assets/89557656/db5d40b6-22f2-467e-b03c-0ed66af8ede8)

4 - Clicar no botão Concluir etapa  

![image](https://github.com/CarlosLiveira/Criar-Pedido/assets/89557656/d451d42f-c373-4122-ae68-10f8432f4dd3)

5 - Aguardar, demora bastante para processar local  
6 - Escolher um motorista em Realizado por  
7 - Verificar se a data não é superior a data ddo dia em que está realizando a opreação, caso seja alterar  
8 - Clicar em Concluir etapa  

![image](https://github.com/CarlosLiveira/Criar-Pedido/assets/89557656/9bce6967-c983-40e3-b58e-a3e1f57a7ed0)

9 - Repitir esses passos para todas as linhas  

![image](https://github.com/CarlosLiveira/Criar-Pedido/assets/89557656/966a7ad4-3ba9-43eb-99de-e3f339befc92)

Obs: Se quiser ver o status alterado, atualize a página  
No exemplo mudou de Planejada para Em last mile

![image](https://github.com/CarlosLiveira/Criar-Pedido/assets/89557656/4209c775-6f1d-4cb1-b6e2-37e3df60041f)  

10 - Última etapa  
   * Selecionar um nome em Realizado por
   * Preencher todos os campos
   * Em ocorrência selecioanr Entregue
   * Importar uma foto em Selecionar o comprovante de entrega (opcional)
   * Clicar em Concluir etapa

![image](https://github.com/CarlosLiveira/Criar-Pedido/assets/89557656/0bb23f88-aa77-4659-9900-2cb8f30e087c)  

![image](https://github.com/CarlosLiveira/Criar-Pedido/assets/89557656/b65cceec-f855-4326-8a98-86f582a43898)  

* Atualizar a página para ver o status Entregue  

![image](https://github.com/CarlosLiveira/Criar-Pedido/assets/89557656/31815f4c-0d3c-4ea3-994c-186dcc3c5f39)

11 - Só quando concluir a última etapa, o pedido aparecerá em Monitorar Ocorrências enviadas  

# Monitorar Ocorrências enviadas

Caminho: Monitorar / Ocorrências enviadas

1 - Atualizar a página  
2 - Filtrar por código interno o pedido que acabou de concluir  

![image](https://github.com/CarlosLiveira/Criar-Pedido/assets/89557656/7d8b01af-5a1d-4026-aa4c-afd4a3cef5de)  

3 - Clicar na engrenagem e Visualizar payload  

![image](https://github.com/CarlosLiveira/Criar-Pedido/assets/89557656/61e2f7a0-280b-4b5f-b8fc-d179c0f4c7dc)  

4 - O mais recente (segunda linha) se refere a ocorrência: PEDIDO_RECEBIDO_TRANSPORTADORA

![image](https://github.com/CarlosLiveira/Criar-Pedido/assets/89557656/a21a94e4-c3c1-4a91-9f80-ae288daa7f05)

5 - O mais antigo (primeira linha) e refere a ocorrência: ENTREGUE  

![image](https://github.com/CarlosLiveira/Criar-Pedido/assets/89557656/b7d7827e-79d2-4fc8-8f2e-ceb5ca9313a9)


# FIM




















