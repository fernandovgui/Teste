# Joia Gestão — Sistema de controle interno para joalherias

Protótipo funcional, em um único arquivo (`index.html`). Para usar, abra o arquivo no navegador; não precisa instalar nada.
Ele já vem com dados de demonstração. Tudo o que você cadastrar fica salvo no próprio navegador.

## Módulos
| Módulo | O que faz |
|---|---|
| Painel | Faturamento, margem, estoque, OS atrasadas, contas a vencer, aniversariantes |
| Ponto de Venda | Venda por clique ou código de barras, desconto, parcelas, abatimento de ouro, comissão, recibo |
| Estoque | Peças com código, metal/teor, peso, pedras, custo, preço, mínimo, local, movimentações e etiqueta |
| Ordens de Serviço | Kanban de consertos/encomendas (Recebido → Em produção → Pronto → Entregue), sinal e saldo |
| Produção (PCP) | Ordens de produção com roteiro por etapa (design, fundição, montagem, cravação, polimento, banho, qualidade). Em cada etapa registra o responsável (interno ou terceiro), o peso de entrada e de saída e o metal recuperado; a perda é calculada e gera alerta quando passa da tolerância. Inclui carga por setor, conta-corrente de metal e finalização integrada com estoque, custo e etiqueta. Modelo inspirado no PCP do CAPTA ERP |
| Compra de Ouro | Cálculo por peso × teor × cotação × % pago, com CPF e destino da peça |
| Consignação / Malinha | Saída de peças para clientes/representantes e acerto (vendido/devolvido) |
| Clientes (CRM) | Aro, aniversário, datas especiais, preferências, histórico de compras e serviços |
| Financeiro | Contas a pagar/receber, crediário, baixa, DRE simplificada |
| Calculadora de Preço | Metal + perda + mão de obra + pedras + acabamento × markup |
| Relatórios | Margem, giro, ranking de vendedores e comissões, mais vendidos, estoque parado |
| Benchmark | Comparativo com Jewel360, The Edge, Lightspeed, Adaptive Jewelry ERP e ERPs brasileiros |
| Configurações | Loja, cotações, vendedores, ourives, backup/restauração |

## Próximas fases (versão de produção)
Banco de dados em nuvem com login e permissões, NFC-e/NF-e, PIX/TEF integrados, cotação automática do ouro, WhatsApp, fotos e certificados, multi-loja.
