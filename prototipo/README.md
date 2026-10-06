# Protótipo — Atto Pedidos Online

Site de demonstração, em um único arquivo (`index.html`, sem build), em que clientes fictícios entram no portal, configuram caixas de papelão, veem a estimativa e acompanham cotações e pedidos.

Abrir: dê dois cliques em `index.html` ou rode `npx serve prototipo`.

## O que dá para fazer
- Entrar como um de 4 clientes fictícios (alimentos, autopeças, têxtil, e-commerce) ou clicar em **Assistir simulação** para ver o cliente fazendo o pedido sozinho.
- Configurador de 7 passos com prévia da caixa em 3D e estimativa de preço em faixa.
- Regras de cotação personalizada: modelo fora do catálogo, medida fora do limite, mais de 3 cores, acabamento especial, quantidade fora da faixa e pedido técnico nas observações.
- Carrinho, solicitação de cotação, proposta firme, aceite, aprovação de prova de arte e linha do tempo do pedido (os botões marcados como "Simulação" fazem o papel da equipe da Atto).
- Minhas embalagens e repetir pedido, sem cobrar clichê e faca de novo.

## Limites
- Empresas, preços, prazos e catálogo são **fictícios**. Os valores reais da Atto não foram informados (ver lacunas em `docs/especificacao-sistema-pedidos-atto.md`).
- Nada é enviado nem salvo: ao recarregar a página, o estado volta ao início.
