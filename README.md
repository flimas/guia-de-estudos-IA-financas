# 📈 Miniguia de Estudos: Inteligência Financeira e Investimentos com IA

## 🎯 Contexto e Objetivos

O assunto de interesse deste caderno temático é a organização das finanças pessoais alinhada à análise fundamentalista de investimentos, utilizando o poder da Inteligência Artificial e da automação para a tomada de decisões.

O objetivo principal deste estudo é criar um sistema automatizado para gerenciar um orçamento pessoal baseado na regra do **50/30/20** e, a partir das sobras financeiras, construir uma carteira de investimentos sólida.

Para a escolha dos ativos, o projeto une duas das maiores escolas de investimento:

- **Benjamin Graham:** busca por margem de segurança e valor intrínseco (*Value Investing*).
- **Luiz Barsi:** estratégia de geração de renda passiva através de dividendos.

---

# 📚 Curadoria de Fontes

As principais referências utilizadas neste caderno foram:

## 📘 Livro: Análise de Investimentos (CVM/APIMEC Brasil)

Material educacional oficial que aborda:

- Histórico do mercado financeiro
- Análise Fundamentalista
- Método Top-Down
- Método Bottom-Up
- Avaliação por Múltiplos
- Valuation

## 📘 Livro: Planejamento Financeiro Pessoal (CVM/Planejar)

Guia focado em:

- Organização financeira
- Orçamento
- Fluxo de caixa
- Fundo de emergência
- Vieses comportamentais do investidor

## 📘 E-book InfoMoney — Como Analisar Balanços

Material prático que ensina a interpretar:

- DRE
- Balanço Patrimonial
- Indicadores financeiros
- Múltiplos de mercado

## 📘 Artigo Investidor10 — Luiz Barsi

Fonte dedicada à metodologia do maior investidor pessoa física do Brasil, focando em:

- Empresas perenes
- Dividendos
- Acúmulo patrimonial

## 📘 O Investidor Inteligente — Benjamin Graham

O clássico do Value Investing, ensinando:

- Valor intrínseco
- Margem de segurança
- Psicologia do investidor
- Senhor Mercado

---

# 📖 Miniguia de Estudo

## 1. Organização Financeira

### Regra 50/30/20

A renda líquida é dividida em:

| Categoria | Percentual |
|------------|-----------:|
| Necessidades | 50% |
| Qualidade de vida | 30% |
| Investimentos | 20% |

Antes de investir em renda variável, deve-se construir um **Fundo de Emergência** equivalente a **6 a 12 meses** do custo de vida.

Os ativos mais indicados são:

- Tesouro Selic
- CDB com liquidez diária

---

## 2. Análise Fundamentalista 

A estratégia combina Graham e Barsi.

### Benjamin Graham

Objetivo:

Comprar empresas abaixo do seu valor.

Filtros:

- P/L < 15
- P/VPA < 1,5

---

### Luiz Barsi

Objetivo:

Gerar renda passiva recorrente.

Busca empresas:

- Bancos
- Energia
- Saneamento
- Outros setores perenes

Filtro principal:

- Dividend Yield > 6%

---

## 3. Custo Médio em Dólares (DCA)

Ao invés de tentar prever o mercado, realiza-se um aporte fixo todos os meses.

Benefícios:

- reduz impacto emocional;
- compra mais ações em momentos de queda;
- compra menos ações em momentos de alta;
- diminui o preço médio ao longo do tempo.

---

# 📚 Glossário

## P/L (Preço/Lucro)

Indica quantos anos seriam necessários para recuperar o investimento através dos lucros da empresa.

Quanto menor, mais barata tende a ser a ação.

---

## P/VPA (Preço/Valor Patrimonial)

Compara o valor de mercado da empresa com seu patrimônio líquido.

Valores inferiores a **1** indicam negociação abaixo do patrimônio.

---

## Dividend Yield (DY)

Representa o percentual pago em dividendos em relação ao preço da ação.

---

## ROE (Return on Equity)

Mede a eficiência da administração em gerar lucro utilizando o patrimônio dos acionistas.

---

## ETFs

Fundos negociados em bolsa que replicam índices como:

- Ibovespa
- S&P 500

Principais vantagens:

- Diversificação
- Baixo custo
- Gestão passiva

---

# 🛠 Engenharia de Prompts (Troubleshooting)

# 🤖 Prompts Reutilizáveis

## Diagnóstico Financeiro Mensal

```text
Atue como um planejador financeiro certificado (CFP).

Minha renda líquida este mês foi de R$ [INSIRA VALOR].

Meus gastos essenciais somaram R$ [INSIRA VALOR].

Meus gastos variáveis/lazer somaram R$ [INSIRA VALOR].

Calcule a distribuição percentual do meu orçamento.

Depois, utilizando a regra do 50/30/20, identifique onde estou fora da proporção ideal e monte um plano de redução de gastos focado nas despesas variáveis para que eu consiga atingir a meta de investir 20% da renda no próximo mês.
```

---

## Análise Fundamentalista

```text
Atue como um analista fundamentalista sênior.

Faça uma análise comparativa entre as empresas [AÇÃO 1] e [AÇÃO 2] pertencentes ao mesmo setor.

Compare:

- P/L
- P/VPA
- ROE
- Margem Líquida
- Dívida Líquida/EBITDA

Utilizando os princípios de Benjamin Graham (margem de segurança) e Luiz Barsi (dividendos e perenidade), indique qual empresa representa a melhor oportunidade de compra atualmente e explique detalhadamente os motivos.
```