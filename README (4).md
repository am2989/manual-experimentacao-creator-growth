# Manual de Experimentação e Plano de Teste com Critério | Creator Growth System

Projeto do **Desafio Criativo DIO: Construção de Hipótese e Planejamento de Teste com Critério**.

O objetivo é substituir o "achismo" da pauta por um método de experimentação: testar **uma variável por vez**, fixar **antes da publicação** o número que valida ou invalida a hipótese e extrair aprendizado acionável, quer a hipótese seja confirmada ou refutada.

> **Nota:** o contexto (perfil de contabilista que cria conteúdo no LinkedIn) e todos os números deste repositório são **fictícios**, assumidos como tal para fins de exercício.

## Documento de entrega

- Manual completo (Google Docs, acesso público): **[COLAR AQUI O LINK PÚBLICO]**
- Versão em Markdown neste repositório: [`MANUAL.md`](MANUAL.md)

## Estrutura do repositório

```text
.
├── README.md                      # Esta página
├── MANUAL.md                      # Manual completo (Partes 1, 2 e 3)
└── registro_aprendizado.md        # Ficha reutilizável de registo de aprendizado
```

## Resumo do projeto

| Campo | Valor |
|---|---|
| Projeto | Creator Growth System: conteúdo de contabilidade e análise de dados no LinkedIn |
| Oferta | Diagnóstico de Dados Financeiros para PMEs (sessão de 1h), ticket médio R$ 350 |
| Gargalo | Intenção → Ação: muitas impressões e salvamentos, poucos cliques e pedidos de contacto |
| Formato | Carrossel (PDF) |
| Baseline | Taxa de Intenção de 0,8% |

## Parte 1: Hipótese de crescimento

**Variável única:** apenas o CTA do último slide do carrossel.

- **Ação:** substituir o CTA genérico ("Gostou? Siga-me") por uma oferta concreta (checklist em troca de um comentário), sem alterar mais nada.
- **Expectativa:** um CTA com benefício imediato e passo único reduz o atrito entre ler e agir.
- **Métrica:** Taxa de Intenção = (comentários com a palavra-chave + cliques no perfil) ÷ impressões do carrossel.

**Força da hipótese:** média, ajustada para **forte** (métrica com fórmula fechada, 3 peças para diluir ruído, baseline definido e régua fixada antes de publicar).

## Parte 2: Plano de teste com critério

- **Janela:** 21 dias, com 3 carrosséis (1 por semana) e mínimo de 2.000 impressões por peça.

| Resultado (média dos 3 carrosséis) | Variação sobre o baseline | Decisão |
|---|---|---|
| ≥ 1,2% (e 2 de 3 peças acima de 1,0%) | ≥ +50% | Confirmada |
| 0,89% a 1,19% | +11% a +49% | Inconclusivo |
| ≤ 0,88% | ≤ +10% | Invalidada |

- **Paragem antecipada:** se os 2 primeiros carrosséis ficarem abaixo do baseline, o teste termina.
- **Variáveis de distorção monitorizadas:** sazonalidade e prazos fiscais; mudanças de distribuição orgânica do algoritmo.

## Parte 3: Matriz de decisão pós-teste

1. **Confirmada:** o CTA passa a padrão definitivo; a próxima variável a testar é o gancho do slide 1.
2. **Refutada:** reverter ao CTA antigo; o foco gira para a oferta do CTA.
3. **Inconclusiva:** prolongar uma única vez com um 4.º carrossel; se persistir, registar como "sem efeito detetável" e escolher uma variável de contraste mais forte.

Cada ciclo termina com uma ficha de registo de aprendizado ([`registro_aprendizado.md`](registro_aprendizado.md)).

## Como reutilizar este método

1. Escolher o gargalo principal e isolar **uma** variável.
2. Escrever a hipótese no formato **Ação + Expectativa + Métrica**.
3. Definir baseline, janela e réguas numéricas **antes** de publicar.
4. Executar o teste sem alterar mais nada.
5. Decidir pela árvore de decisão e preencher a ficha de aprendizado.

## Tecnologias e ferramentas

- LLM (Claude) como parceiro de refinamento e auditoria do plano
- Google Docs para o documento de entrega
- Markdown e GitHub para documentação e versionamento

## Autoria

Alda Marlene Anjo Benta, desafio criativo do bootcamp DIO.
