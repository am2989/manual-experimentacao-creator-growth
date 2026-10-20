# Manual de Experimentação e Plano de Teste com Critério | Creator Growth System

**Aluna:** Alda Marlene Anjo Benta · **Projeto:** Creator Growth System (perfil simulado de contabilista no LinkedIn) · **Desafio:** Construção de Hipótese e Planejamento de Teste com Critério

*Nota: o contexto e todos os números deste documento são fictícios, assumidos como tal para fins de exercício.*

## Parte 1: Construção de Hipótese de Crescimento (Base do System)

### Contexto da operação

| Campo | Valor |
|---|---|
| Projeto | Creator Growth System: conteúdo de contabilidade e análise de dados no LinkedIn |
| Oferta principal | Diagnóstico de Dados Financeiros para PMEs (sessão de 1h), ticket médio R$ 350 |
| Gargalo atual | Intenção → Ação: muitas impressões e salvamentos, mas poucos cliques no link e poucos pedidos de contacto |
| Formato atual | Carrossel (PDF) |
| Baseline fictício | Taxa de clique (CTR) no CTA do último slide: 0,8% |

### 1. Isolamento da variável única

**Variável alterada: apenas o CTA do último slide do carrossel.**

- **Antes:** "Gostou? Siga-me para mais conteúdo."
- **Depois:** "Comente DIAGNÓSTICO e envio-lhe o checklist de 5 erros nos seus números."

**Mantém-se inalterado:**

- tema e estrutura dos slides 1 a 9
- gancho do slide 1
- horário e dia de publicação
- frequência (1 carrossel por semana)
- público e hashtags

### 2. Declaração da hipótese estruturada

- **AÇÃO:** Substituir o CTA genérico do último slide por um CTA com oferta concreta (checklist em troca de um comentário), sem alterar mais nada no carrossel.
- **EXPECTATIVA:** Um CTA com benefício imediato e passo único reduz o atrito entre ler e agir. Os leitores que já salvam o conteúdo passam a dar o primeiro passo em direção à oferta.
- **MÉTRICA:** Taxa de Intenção = (comentários com a palavra-chave + cliques no perfil) ÷ impressões do carrossel, comparada com o baseline de 0,8%.

**Enunciado formal:** *Se eu trocar o CTA do último slide por uma oferta de checklist por comentário, então a taxa de Intenção sobe, medida por (comentários-chave + cliques no perfil) ÷ impressões.*

### 3. Classificação de força da hipótese: MÉDIA, ajustada para FORTE

**Falhas da versão inicial:**

- A métrica estava solta e sem régua.
- Com poucas publicações, um só carrossel não separa sinal de ruído.
- Faltava o número que valida ou invalida o teste.

**Ajustes feitos:**

1. A métrica é única e tem fórmula fechada.
2. O teste usa 3 carrosséis no mesmo formato e com o mesmo CTA novo (um por semana), para diluir o ruído de algoritmo.
3. O baseline vem das últimas 3 publicações com o CTA antigo.
4. A régua será fixada antes de publicar (Etapa 2 do desafio).

**Veredicto: FORTE.** Uma só variável, métrica mensurável, ação cirúrgica e resultado interpretável, quer a hipótese seja confirmada ou refutada.

## Parte 2: Planejamento de Teste com Critério (Base do System)

### Parâmetros do teste

| Parâmetro | Valor |
|---|---|
| Métrica | Taxa de Intenção = (comentários-chave + cliques no perfil) ÷ impressões do carrossel |
| Baseline (média das últimas 3 publicações com o CTA antigo) | 0,8% |
| Janela do teste | 21 dias |
| Peças testadas | 3 carrosséis (1 por semana), todos com o CTA novo e a mesma estrutura |
| Mínimo de validade por peça | 2.000 impressões; abaixo disso a peça não conta e é repetida |

### 1. Régua de Validação (Critério de Sucesso)

A hipótese é **CONFIRMADA** quando as duas condições se verificam em simultâneo:

1. A média da Taxa de Intenção dos 3 carrosséis é **igual ou superior a 1,2%** (variação de **+50%** sobre o baseline de 0,8%).
2. **Pelo menos 2 dos 3 carrosséis** ficam individualmente acima de 1,0% (+25%), para evitar que uma única peça viral decida o resultado.

### 2. Régua de Invalidação (Critério de Descarte)

A hipótese é **INVALIDADA** quando a média da Taxa de Intenção dos 3 carrosséis fica **igual ou inferior a 0,88%** (variação de **+10%** ou menos sobre o baseline), valor que cabe na oscilação normal do canal.

**Regra de paragem antecipada:** se os 2 primeiros carrosséis ficarem ambos abaixo de 0,8% (abaixo do baseline), o teste é encerrado sem esperar pela 3.ª peça.

**Zona cinzenta (resultado inconclusivo):** média entre 0,89% e 1,19%. Não confirma nem invalida; segue o Caminho 3 da Parte 3.

| Resultado (média dos 3 carrosséis) | Variação sobre o baseline | Decisão |
|---|---|---|
| ≥ 1,2% (e 2 de 3 peças acima de 1,0%) | ≥ +50% | CONFIRMADA |
| 0,89% a 1,19% | +11% a +49% | INCONCLUSIVO |
| ≤ 0,88% | ≤ +10% | INVALIDADA |

### 3. Mapeamento de Variáveis de Distorção

1. **Sazonalidade e calendário:** feriados, pontes e semanas de prazos fiscais alteram o consumo de conteúdo contabilístico. Monitorizar o dia da semana e a proximidade de prazos; se uma peça sair numa semana atípica, assinalar no registo e comparar com o baseline da mesma semana quando possível.
2. **Mudança de distribuição orgânica do algoritmo:** picos ou quedas de alcance sem relação com o conteúdo (por exemplo, impressões 40% acima ou abaixo da média das últimas 3 peças). Como a métrica é uma taxa sobre impressões, o efeito é atenuado, mas uma peça com alcance atípico deve ser lida com cautela e repetida se necessário.

## Parte 3: Matriz de Decisão Pós-Teste e Giro de Iteração

### Árvore de decisão em 3 caminhos

**Caminho 1: Hipótese Confirmada (média ≥ 1,2%)**

1. Incorporar o CTA com oferta de checklist por comentário como **padrão definitivo** em todos os carrosséis, registando-o no guia de pauta.
2. Congelar esta variável: o CTA não volta a ser alterado durante o próximo ciclo.
3. **Próxima variável a testar sobre esta base:** o gancho do slide 1 (nova abertura focada num número ou erro concreto), mantendo o novo CTA inalterado. O novo baseline passa a ser a média confirmada neste teste.

**Caminho 2: Hipótese Refutada (média ≤ 0,88%, ou paragem antecipada)**

1. **Diagnóstico comportamental:** a audiência consome e guarda o conteúdo como referência, mas o atrito não está no pedido de ação. O problema provável está na oferta (o checklist não é percebido como valioso) ou na falta de confiança para dar o passo.
2. Reverter ao CTA antigo como padrão e arquivar a ficha de aprendizado.
3. **Girar o foco** para a oferta do CTA: testar um benefício diferente (por exemplo, mini-diagnóstico gratuito de 15 minutos em vez do checklist), mantendo o formato e o mecanismo de comentário.

**Caminho 3: Resultado Inconclusivo (média entre 0,89% e 1,19%)**

1. Não declarar vitória nem derrota, e não alterar o padrão.
2. Verificar primeiro se alguma variável de distorção contaminou alguma das 3 peças.
3. Prolongar o teste **uma única vez**, com mais 1 carrossel (semana 4) sob as mesmas condições, e recalcular a média das 4 peças contra a mesma régua.
4. Se continuar na zona cinzenta, registar como "sem efeito detetável", manter o CTA antigo (menor custo) e escolher uma variável de contraste mais forte para o ciclo seguinte.

### Modelo do Registro de Aprendizado

Preencher uma ficha por ciclo e guardá-la no histórico de inteligência do canal.

| Tópico | Preenchimento |
|---|---|
| **[Hipótese Testada]** | Se o CTA do último slide oferecer um checklist por comentário, a Taxa de Intenção sobe. |
| **[Resultado vs Baseline]** | Média dos 3 carrosséis: ___% vs baseline 0,8% (variação: ___%). Decisão: confirmada, invalidada ou inconclusiva. |
| **[Aprendizado Comportamental Extraído]** | O que a audiência mostrou sobre o que a move a agir (oferta, atrito, momento). |
| **[Próxima Ação]** | Variável do próximo ciclo, novo baseline e data de início. |
