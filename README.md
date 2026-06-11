# Calculadora-FUST
Calculadora simples para inserção de valores e estimativas FUST

# Calculadora FUST 

Ferramenta para estimar a contribuição ao FUST e o potencial de financiamento disponível pelo programa BNDES FUST Automático, com base na receita do provedor de internet.

---

## Acesso

Acesse diretamente pelo navegador, sem instalar nada:

**https://bakuhhh.github.io/calculadora-fust**

Compatível com Chrome, Edge, Firefox e Safari.

---

## Como usar

### 1. Informe o regime tributário

| Opção | Quando usar |
|---|---|
| Lucro presumido / real | Maioria dos provedores |
| Simples Nacional | Provedor optante pelo Simples — **isento do FUST**, a ferramenta informa automaticamente |

---

### 2. Selecione o período de referência

- **Mensal** → informe os valores de um mês. A ferramenta projeta o FUST anual automaticamente.
- **Anual** → informe os valores acumulados do ano.

---

### 3. Preencha os campos

| Campo | O que informar |
|---|---|
| **Receita bruta de telecom** | Faturamento bruto do período com serviços de telecomunicações |
| **ICMS** | Valor do ICMS incidente sobre a receita de telecom |
| **PIS** | Valor do PIS incidente sobre a receita de telecom |
| **COFINS** | Valor da COFINS incidente sobre a receita de telecom |
| **Cancelamentos / descontos** | Vendas canceladas e descontos concedidos (deixe 0 se não houver) |

> Os valores são formatados automaticamente enquanto você digita — não é necessário digitar ponto ou vírgula.

---

### 4. Clique em **Calcular →**

Os resultados aparecem automaticamente na parte inferior da tela.

---

## O que a ferramenta calcula

### Contribuição FUST

| Resultado | Descrição |
|---|---|
| **ROB-Telecom** | Receita bruta menos ICMS, PIS, COFINS e cancelamentos — base de cálculo legal |
| **FUST a recolher** | 1% sobre a ROB-Telecom (Lei 9.998/2000) |
| **FUST anual estimado** | Projeção anual com base no período informado |

### Financiamento disponível — BNDES FUST Automático

| Modalidade | Teto | Prazo | Para que serve |
|---|---|---|---|
| **FUST Equipamentos** | R$ 10.000.000 | até 120 meses | Compra de equipamentos (NCM 85.17, fibra óptica 8544.70) e capital de giro associado (até 30%) |
| **FUST Crédito Conectividade** | R$ 2.000.000 | até 60 meses | Capital de giro para provedores que ampliaram acessos recentemente |
| **FUST Emergencial** | R$ 5.000.000 | até 90 meses | Capital de giro para provedores em áreas de calamidade pública |

> Todas as modalidades têm carência de até 24 meses e participação de até 100% do valor do projeto.

---

## Avisos da ferramenta

| Aviso | O que significa |
|---|---|
| Faixa amarela | As deduções informadas superam a receita — verifique os valores digitados |
| Faixa verde | Provedor optante pelo Simples Nacional — isento do FUST |

---

## Fontes e legislação

- Lei nº 9.998/2000 — institui o FUST e define a alíquota de 1%
- Resolução Anatel nº 729/2020 — regulamento de arrecadação (isenção Simples Nacional: art. 31)
- Portaria Anatel nº 2817/2024 — procedimento de fiscalização e base de cálculo
- Circular BNDES SUP/ADIG nº 12/2025 (atualizada pela Circular 92/2025) — parâmetros das modalidades de financiamento

---
