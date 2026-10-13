# CA PDV

PDV (ponto de venda) simples para a CA Café & Doceria: calcula o total do pedido, o troco, cadastra produtos e registra o histórico de vendas.

- **Front-end:** um único `index.html` (HTML/CSS/JS puro), mobile-first e responsivo.
- **Banco:** Supabase (projeto `pdv`). As tabelas ficam fechadas; o app só acessa o banco por funções (RPC) protegidas por PIN.
- **Hospedagem:** Vercel, projeto `ca-pdv` → https://ca-pdv.vercel.app

## Telas
PDV · Produtos (cadastro) · Vendas (histórico). Menu lateral, tela cheia e teclado numérico próprio.

## Atualizar
Edite `index.html`, faça commit e publique na Vercel.
