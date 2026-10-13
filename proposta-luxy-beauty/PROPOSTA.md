# Proposta Comercial – Luxy Beauty Imports

**Projeto:** Correção da loja WooCommerce, integração Olist + APPMAX, NF-e/etiquetas em 1 clique, atendimento por WhatsApp com IA e automações de venda
**Site:** www.luxybeutyimports.com.br
**Plataforma:** 99 Freelas
**Validade da proposta:** 15 dias

---

## 1. Entendimento do projeto

A loja precisa de três frentes de trabalho:

1. **Corrigir a loja.** Hoje há bugs, loops, elementos que não carregam, imagens fora de proporção e problemas no mobile.
2. **Integrar a operação.** WooCommerce, Olist (ERP, estoque, NF-e e logística) e APPMAX (pagamento) devem trocar dados sozinhos, desde o pedido até o rastreio.
3. **Automatizar o atendimento e as vendas.** Um agente de IA no WhatsApp, mensagens automáticas de status, recuperação de carrinho e integração com redes sociais.

O objetivo é que o pedido entre pelo site e passe por pagamento, ERP, nota fiscal, etiqueta, envio e aviso ao cliente sem digitação manual. A única exceção é a separação física, que termina com **1 clique**.

---

## 2. Escopo e valores por serviço

| # | Serviço | Horas estimadas | Valor |
|---|---------|:---------------:|------:|
| 1 | WooCommerce: correções, responsividade e reestilização | 18 h | **R$ 350,00** |
| 2 | Integração WooCommerce + Olist + APPMAX | 32 h | **R$ 600,00** |
| 3 | NF-e, etiquetas e envio (fluxo de 1 clique) | 14 h | **R$ 250,00** |
| 4 | WhatsApp + IA (n8n + Evolution API + OpenAI) | 30 h | **R$ 550,00** |
| 5 | Automações adicionais | 14 h | **R$ 250,00** |
| 6 | Testes completos e treinamento (2 h online) | 6 h | **R$ 100,00** |
| 7 | Suporte: 3 h/mês durante 2 meses (6 h) | 6 h | **R$ 200,00** |
| | **Soma dos serviços** | **120 h** | **R$ 2.300,00** |
| | **Pacote completo (desconto de ~9%)** | | **R$ 2.100,00** |

> Os itens podem ser contratados separadamente pelos valores da tabela. Fechando o pacote completo, o valor cai para **R$ 2.100,00**.

---

## 3. Detalhamento do escopo

### 3.1 WooCommerce / site (R$ 350)
- Diagnóstico técnico: tema, plugins, conflitos, console de erros, cache e performance.
- Correção dos bugs atuais, dos loops de produtos e dos elementos que não carregam (sliders, vitrines, AJAX, carrinho lateral etc.).
- Padronização das imagens de produto (proporção, recorte, tamanhos de miniatura e regeneração) e otimização com WebP/lazy load.
- Correção de posicionamentos e responsividade em celular, tablet e desktop.
- Reestilização e organização visual das páginas necessárias: home, categoria, produto, carrinho, checkout e minha conta.
- Revisão geral da loja: cadastro, busca, filtros, cupons, e-mails do WooCommerce, fluxo de compra e SEO básico.
- Backup completo antes de qualquer alteração. O trabalho é feito em ambiente de homologação quando possível.

### 3.2 Integração WooCommerce + Olist + APPMAX (R$ 600)
- Sincronização de produtos por **SKU**, incluindo **variações** (cor, tamanho, volume etc.).
- **Estoque centralizado no Olist**, atualizado automaticamente no site.
- Sincronização de **preços** e promoções.
- **Pedidos do WooCommerce enviados ao Olist** com cliente, endereço, CPF/CNPJ, itens, frete e forma de pagamento.
- Cadastro e atualização de **clientes** no Olist.
- Configuração do **checkout APPMAX** (cartão, Pix e boleto, conforme o contrato da loja) e dos retornos de pagamento.
- Sincronização de **status e cancelamentos** nos dois sentidos: pago, em separação, faturado, enviado, entregue e cancelado.
- **Frete:** cálculo no checkout, transportadoras e regras (frete grátis, prazos, CEP).
- **Retorno do Olist para o WooCommerce:** número da NF, código de rastreio e status de envio.
- Uso das integrações nativas quando forem suficientes e webhooks/n8n quando for preciso complementar.

### 3.3 NF-e, etiquetas e envio (R$ 250)
- Fluxo de **1 clique** após a separação do pedido:
  1. emissão/autorização da **NF-e**;
  2. geração da **etiqueta** da transportadora/Correios;
  3. atualização do pedido no Olist e no WooCommerce;
  4. envio do **código de rastreio** ao cliente por e-mail e WhatsApp.
- Configuração das regras fiscais básicas no Olist (natureza de operação, CFOP padrão). A parte tributária é validada pelo contador da loja.
- Documentação do passo a passo da expedição.

### 3.4 WhatsApp + IA, "MEU MOUSE" (R$ 550)
- Instalação de **n8n + Evolution API** em **VPS Hostinger** com Docker, SSL, domínio/subdomínio e backup.
- Conexão do número de WhatsApp da loja.
- Integração com a **OpenAI**.
- **Agente de IA** que responde dúvidas (frete, prazos, trocas, formas de pagamento), consulta produtos e estoque e **recomenda produtos** com link de compra.
- Transferência para atendimento humano quando necessário.
- **Mensagens automáticas** de pedido recebido, pagamento aprovado/recusado, em preparação, enviado (com rastreio), entregue e pós-venda (avaliação/recompra).
- Base de conhecimento editável pela loja (políticas, FAQ, tom de voz).

### 3.5 Automações adicionais (R$ 250)
- **Recuperação de carrinho abandonado** por WhatsApp e/ou e-mail, com sequência de lembretes e cupom opcional.
- **Pop-ups promocionais**: captura de e-mail/WhatsApp, cupom de primeira compra e saída da página.
- **Integração com Instagram e TikTok**: catálogo de produtos, Instagram Shopping, TikTok Shop/catálogo e pixels.
- **Automação de e-mails** de status do pedido com layout padronizado da marca.

### 3.6 Testes e treinamento (R$ 100)
- Testes completos de ponta a ponta com pedidos reais/simulados: compra, pagamento, envio ao Olist, NF-e, etiqueta, rastreio, mensagens no WhatsApp e cancelamento.
- **2 horas de treinamento online** gravado para a equipe.
- Checklist de validação assinado ao final.

### 3.7 Suporte (R$ 200)
- **3 horas técnicas por mês durante 2 meses** (6 h no total) para suporte, correção de bugs e ajustes relacionados ao projeto.
- Atendimento por WhatsApp/chat da plataforma em horário comercial.
- Horas extras ou novas demandas: **R$ 50,00/hora**.

---

## 4. Cronograma estimado

| Semana | Entregas |
|:------:|----------|
| 1 | Diagnóstico, backup e correções críticas do site |
| 2 | Responsividade, imagens e reestilização |
| 3–4 | Integração WooCommerce + Olist + APPMAX |
| 4–5 | Fluxo de NF-e / etiqueta / rastreio em 1 clique |
| 5–6 | VPS, n8n, Evolution API, agente de IA e mensagens automáticas |
| 6 | Automações adicionais (carrinho, pop-ups, redes sociais, e-mails) |
| 7 | Testes completos, ajustes e treinamento |
| 8–15 | Suporte (3 h/mês por 2 meses) |

**Prazo de implantação: cerca de 7 semanas**, contando a partir do recebimento dos acessos.

---

## 5. Forma de pagamento (marcos na 99 Freelas)

| Marco | Entrega | % | Valor (pacote) |
|-------|---------|:-:|--------------:|
| 1 | Site corrigido e reestilizado | 20% | R$ 420,00 |
| 2 | Integração Olist + APPMAX + NF-e/etiqueta funcionando | 40% | R$ 840,00 |
| 3 | WhatsApp + IA + automações adicionais | 30% | R$ 630,00 |
| 4 | Testes, treinamento e início do suporte | 10% | R$ 210,00 |
| | **Total** | **100%** | **R$ 2.100,00** |

---

## 6. Custos de terceiros (não inclusos)

Estes custos são pagos diretamente pela loja aos fornecedores:

- **VPS Hostinger** para n8n + Evolution API (plano KVM 2 ou superior).
- **API da OpenAI** (cobrança por uso; costuma ser baixa para atendimento de loja).
- **Plano do Olist** com os módulos de NF-e e logística.
- **Taxas da APPMAX** por transação.
- **Certificado digital A1** para emissão de NF-e.
- **Frete/etiquetas** das transportadoras e Correios.
- **Plugins premium**, se algum for necessário (ex.: pop-up ou recuperação de carrinho avançada). Todos serão informados antes da compra.

---

## 7. O que preciso da loja

- Acesso de administrador ao WordPress/WooCommerce e à hospedagem (cPanel/FTP).
- Acesso ao Olist, à APPMAX e ao painel da Hostinger.
- Número de WhatsApp dedicado à loja.
- Conta da OpenAI (ou cartão para criar uma).
- Contas Business do Instagram e TikTok e o Gerenciador de Negócios da Meta.
- Políticas da loja (trocas, frete, prazos) e informações para a base de conhecimento da IA.
- Contato do contador para validar as regras fiscais da NF-e.

---

## 8. Garantias

- Backup completo antes de qualquer alteração.
- Toda a infraestrutura (VPS, n8n, contas) fica **no nome e na propriedade da loja**.
- Entrega de documentação dos fluxos e acessos.
- **30 dias de garantia** para correção de falhas no que foi entregue, além das horas de suporte contratadas.
