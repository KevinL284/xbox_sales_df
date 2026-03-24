# Xbox Game Pass Subscriptions Dashboard

## Objetivo

Analisar dados de assinaturas com foco em receita, comportamento de usuários e retenção.

---

## Dados

Principais colunas:

* Subscriber ID
* Plan
* Subscription Type
* Start Date
* Auto Renewal
* Subscription Price
* EA Play Season Pass e preço
* Minecraft Season Pass e preço
* Coupon Value
* Total Value

---

## Análises

### Receita de Add-ons

Soma total de:

* EA Play Season Pass
* Minecraft Season Pass

Exibido como KPI.

---

### Ticket Médio por Plano

Média de Total Value por tipo de plano:

* Monthly
* Quarterly
* Annual

Resultado: o plano Quarterly apresentou maior ticket médio.

---

### Auto Renewal Rate

Cálculo:
Quantidade de "Yes" / Total de usuários

Implementação com tabela dinâmica exibindo % do total.

Resultado aproximado: 50%

---

## Visualização

* KPIs de receita (EA e Minecraft)
* KPI de Auto Renewal Rate
* Gráfico de ticket médio por plano

---

## Observações

* Quarterly gera maior valor por usuário
* Taxa de renovação em torno de 50% indica retenção moderada
* Add-ons impactam o valor total

---

## Estrutura

* Base de dados original
* Aba de cálculos auxiliares
* Dashboard final
