# GUIA DETALHADO DE PROCESSOS INTERNOS DE COMPRAS
**Prefeitura Municipal de Fronteira/MG**

---

## 📋 ÍNDICE
1. [Resumo Executivo](#resumo-executivo)
2. [Configurações do Sistema](#configurações-do-sistema)
3. [Auxílio Financeiro - Pós Graduação](#auxílio-financeiro---pós-graduação)
4. [Empenho de Gás](#empenho-de-gás)
5. [Prestação de Serviço TEBAS](#prestação-de-serviço-tebas)
6. [Despesa de Viagem - Diárias](#despesa-de-viagem---diárias)
7. [Fluxo Geral de Empenho](#fluxo-geral-de-empenho)
8. [Contatos e Responsáveis](#contatos-e-responsáveis)

---

## RESUMO EXECUTIVO

O sistema de compras da Prefeitura Municipal de Fronteira segue procedimentos específicos para cada tipo de despesa. Este documento detalha os **4 principais processos**:

| PROCESSO | TIPO | VALOR | LEGISLAÇÃO |
|----------|------|-------|------------|
| Auxílio Financeiro - Pós Graduação | Empenho | R$ 379,50 | Lei 1.428/2009 |
| Empenho de Gás | Empenho | Varia | Pregão 40/2025 |
| Prestação de Serviço TEBAS | Empenho + Retenção | R$ 3.300,00 | Contrato 221 |
| Despesa de Viagem (Diárias) | Empenho | Varia | Lei 1.818/2018 |

---

## CONFIGURAÇÕES DO SISTEMA

### Dados da Prefeitura
- **CNPJ**: 18.449.140/0001-07
- **Responsável Assinante**: Carla Peixoto (Código 4318)

### Banco de Dados
- **Banco**: Banco do Brasil
- **Código**: 001
- **Agência**: 0422-7
- **Conta Corrente**: 101126-X
- **Tipo de Operação**: Somente depósito ou transferência

### Padrões Orçamentários
- **Fonte Principal de Recurso**: 1500
- **Centro de Custo - Materiais**: 0000
- **Centro de Custo - Auxílios/Diárias**: 1001
- **Unidade Padrão**: 002 - Secretaria da Educação

### Dotações Disponíveis (Projetos)
| Projeto | Descrição | Ficha | Subelemento |
|---------|-----------|-------|------------|
| 2034 | Diárias de Viagem | 340 | Diária de demais Servidores |
| 2038 | Auxílios Financeiros | 376 | 3390180000 |
| 2044 | Escolas | 402 | - |
| 2049 | Creches | 460 | - |
| 2050 | Pré-Escolas | 478 | - |

---

## AUXÍLIO FINANCEIRO - PÓS GRADUAÇÃO

### Objetivo
Conceder auxílio financeiro a profissionais de educação básica para formação e aperfeiçoamento, conforme Lei Municipal 1.428/2009.

### Valor e Competência
- **Valor Padrão**: R$ 379,50 (1/4 do salário mínimo)
- **Competência**: Mês referente ao auxílio

### Dados Orçamentários
```
Projeto/Atividade: 2038
Ficha: 376
Subelemento: 3390180000
Fonte de Recurso: 1500
Centro de Custo: 1001
Objeto de Despesa: 031
Item: 20025000101
```

### Fluxo Detalhado (14 etapas)

**ETAPA 1-5: Movimento e Dados Básicos**
1. Acessar: **Movimentação > Comunicações Internas > Movimentações de Comunicações Internas**
2. Incluir dados básicos (verificar data de empenho do grupo)
3. Preencher **Finalidade/Histórico**:
   > "REFERE-SE A CONCESSÃO DE AUXÍLIO FINANCEIRO A PROFISSIONAL DE EDUCAÇÃO BÁSICA ACIMA MENCIONADA, PARA FORMAÇÃO E APERFEIÇOAMENTO DE ACORDO COM A LEI 1.428 DE 10 DE MARÇO DE 2009, A QUAL SE COMPROMETE A PRESTAR CONTA POSTERIORMENTE. COMPETÊNCIA: [MÊS/ANO]."
4. **Incluir Ítem**: 20025000101 | Valor: R$ 379,50
5. Clicar **OK > OK > FECHAR DEPOIS**

**ETAPA 6-8: Aprovação e Dotação**
6. Acessar: **Movimentação > Comunicações Internas > Aprovação de Comunicações Internas**
7. Acessar pelo nome do beneficiário e preencher **Dotação**
   - Projeto: 2038
   - Ficha: 376
   - Subelemento: 3390180000
   - Fonte: 1500
   - CO: 1001
   - Obj. Despesa: 031
8. Clicar **OK / SIM** (documento ficará em amarelo para Controle Interno)

**ETAPA 9-14: Empenho e Finalização**
9. Clicar **Empenhar > SIM > Desconto (não)**
10. **Imprimir**: Empenho, Nota de Despesa e C.I.
11. Ordem dos documentos: Nota Despesa > Empenho > C.I. > Boleto
12. Entregar para **CARLA PEIXOTO** assinar
13. **Protocolar** e enviar à Contabilidade (NÃO BATER CARIMBO antes)
14. Reembolso: Banco do Brasil | AG: 0422-7 | CC: 101126-X

---

## EMPENHO DE GÁS

### Objetivo
Adquirir gás GLP (13kg e 45kg) com vasilhames para creches e escolas municipais.

### Informações Licitatórias
- **Pregão**: 40/2025
- **Licitação**: 0032586
- **Fornecedor Código**: 6609
- **Tipo de Fornecimento**: Ordinário

### Unidades Atendidas

#### CRECHES (Projeto 2049 | Ficha 460)
- CMEI Santo Antonio
- CMEI Dona Belinha
- CMEI Dona Mençora
- CMEI Dona Alice
- *Tamanho padrão: 13kg e 45kg | Período: 2 meses*

#### PRÉ-ESCOLAS (Projeto 2050 | Ficha 478)
- EMEI Maísa Ferreira Passuelo Vasconcelos (Av Brasil, 220 - Vila Residencial de Furnas)
- *Tamanho: 45kg | Período: 20 dias*

#### ESCOLAS (Projeto 2044 | Ficha 402)
- EM Marechal Castelo Branco (Rua Godofredo Antonio da Costa, 238)
- PEM Turma da Mônica (Rua Higino Florencio de Souza, 430 - Vila Residencial de Furnas)
- EM José Maria Bastos Garcia (Av Abdo Jauide Feres, 370 - Centro)
- EM Poliana Ziza Ferreira (Av Aurelio Luis Mistieri, 370 - Centro)
- *Tamanho: 45kg | Período: 20 dias cada*

### Dados Orçamentários Padrão
```
Fonte de Recurso: 1500
Centro de Custo: 0000
Material: Não Permanente
```

### Fluxo Detalhado (31 etapas)

**ETAPA 1-5: Acesso e Seleção**
1. **Movimentação > Processos de Compras > Pregão Eletrônico** (ano anterior, Licitação 0032586)
2. Selecionar **Fornecedor 6609**
3. Acessar **Manutenção > Registro de Preço**
4. Clicar **Empenhar > Incluir**
5. Selecionar **Material > Confirmar** (Não Permanente)

**ETAPA 6-8: Dotação por Tipo de Unidade**
6. **Creches**: Proj: 2049 | Ficha: 460 | Fonte/Det/Sub: 1500 | CO: 0000
7. **Pré-escolas**: Proj: 2050 | Ficha: 478 | Fonte/Det/Sub: 1500 | CO: 0000
8. **Escolas**: Proj: 2044 | Ficha: 402 | Fonte/Det/Sub: 1500 | CO: 0000

**ETAPA 9-17: Descrição Histórica por Unidade**
Preencher histórico específico para cada unidade:
- Creches: "Aquisição de gás GLP 13kg e 45kg para creches (Santo Antonio, Dona Belinha, Dona Mençora, Dona Alice) - 2 meses"
- Maísa: "Aquisição de gás GLP 45kg para EMEI Maísa Ferreira Passuelo Vasconcelos, AV BRASIL, N°220 - 20 dias"
- Marechal: "Aquisição de gás GLP 45kg para EM Marechal Castelo Branco, RUA GODOFREDO ANTONIO DA COSTA, N° 238 - 20 dias"
- Mônica: "Aquisição de gás GLP 45kg para PEM Turma da Mônica, RUA HIGINO FLORENCIO DE SOUZA, N°430 - 20 dias"
- José Maria: "Aquisição de gás GLP 45kg para EM José Maria Bastos Garcia, AV ABDO JAUIDE FERES, N° 370 - 20 dias"
- Poliana: "Aquisição de gás GLP 45kg para EM Poliana Ziza Ferreira, AV AURELIO LUIS MISTIERI, N°370 - 20 dias"
- Dona Belinha: "Aquisição de recargas de gás GLP 45kg para CMEI Dona Belinha, AV. LIBERDADE, Nº 1480 - 20 dias"
- Dona Alice: "Aquisição de gás GLP 45kg para CMEI Dona Alice, RUA JOSÉ MIGUEL MIZIARA, N°241 - 20 dias"
- Dona Mençora: "Aquisição de gás GLP 45kg para CMEI Dona Mençora, RUA CAMPO FLORIDO, N° 390 - 20 dias"

**ETAPA 18-20: Confirmação e Envio**
18. **Confirmar > SIM** (pré-empenho na data) | *Avisar no grupo da data de empenho*
19. **Empenhar > Confirmar > SIM > Desconto (não) > OK**
20. **Enviar A.F. para o fornecedor**

**ETAPA 21-25: Retenção e Descontos**
21. **Fornecedor 8468** (Francisca Sonia de Figueiredo Neves) - NÃO OPTANTE
22. **Desconto Orçamentário**: IR 0,24% (Fonte 1500)
23. **Incluir > Conta Tradutor: 17** | Detalhamento da Fonte: 000 000
24. **Natureza**: 17010 | **Base de Cálculo**: Valor do Empenho (Nota)
25. **Confirmar retenção e detalhamento** > OK > SIM > OK > OK

**ETAPA 26: Impressão**
26. **Imprimir Empenho Analítico e A.F.**

**ETAPA 27-31: Recebimento e Finalização**
27. **Movimentação > Almoxarifado > Recebimento de Notas Fiscais e Materiais**
28. **Unidade**: 002 - Secretaria da Educação
29. Procurar pelo valor da nota ou fornecedor
30. **Imprimir**: Autorização, Empenho Analítico e Recebimento
    - Data Empenho: conforme emissão da nota
    - Vencimento: 30 dias
31. **Bater carimbos > Entregar para CARLA assinar > Protocolar > Levar na Contabilidade**

---

## PRESTAÇÃO DE SERVIÇO TEBAS

### Objetivo
Formalizar prestação de serviço de consultoria/manutenção do fornecedor TEBAS com retenção de IR.

### Informações do Contrato
- **Fornecedor**: TEBAS (Código 20605)
- **Número Global do Contrato**: 221
- **Valor**: R$ 3.300,00
- **Situação**: Não Optante
- **Retenção IR**: 4,8% (R$ 158,40)

### Fluxo Detalhado (17 etapas)

**ETAPA 1-3: Liberação Parcial de Autorização**
1. **Movimentação > Liberação Parcial de Autorização de Serviços**
2. Procurar por **TEBAS ou N° Global 221**
3. **Abrir A.F.** - Data 9 (emissão da nota ou um dia antes)

**ETAPA 4-5: Liberação da Quantidade**
4. **Liberar > Quantidade: 01 > Valor: 3.300,00 > OK > OK**
5. **Finalidade/Histórico**: "FAZER AS ALTERAÇÕES PARA O MÊS COMPETENTE" (conforme mês da prestação)

**ETAPA 6: Confirmação Inicial**
6. **OK > SIM > SIM**

**ETAPA 7-12: Retenção de IR**
7. **Desconto Orçamentário**: IR 4,8% (R$ 158,40) *(descrito na nota)*
8. **Contribuinte**: 20605 - TEBAS
9. **Incluir Receita > Tradutor**: 17
10. **Valor do Desconto**: R$ 158,40
11. **Fonte de Recurso**: 1500 | **Centro de Custo (C.O.)**: 1001
12. **Natureza de Rendimento**: 17099 | **Base de Cálculo**: Valor Serviço (Nota)

**ETAPA 13: Confirmação de Desconto**
13. **OK > SIM > OK > OK**

**ETAPA 14: Impressão**
14. **Imprimir A.F. e Empenho**

**ETAPA 15-17: Liquidação de Serviços**
15. **Movimentação > Liquidação de Serviços > Procurar Empenho**
16. **Datas Liquidação**:
    - Data Entrada: do empenho ou nota
    - Emissão: da nota
    - Vencimento: 1ª semana do mês seguinte
17. **OK > SIM** *(Liquidação concluída)*

---

## DESPESA DE VIAGEM - DIÁRIAS

### Objetivo
Liberar adiantamentos de diária para viagens de servidores municipais e processar reembolsos de despesas com deslocamento e alimentação.

### Legislação Aplicável
- **Lei Municipal 1.818/2018**: Regulamenta despesas com viagem
- **Lei Municipal 1.897/2019**: Complementa disposições sobre diárias

### Dados Orçamentários Padrão
```
Projeto: 2034
Ficha: 340
Subelemento: Diária de demais Servidores
Fonte de Recurso: 1500
Centro de Custo: 1001
Objeto de Despesa: 02
Responsável: Carla Peixoto (Código 4318)
Unidade: 02.01.05.01 - Educação
```

### Itens de Despesa
| Item | Código | Descrição |
|------|--------|-----------|
| 1 | 170010019 | Diária Viagem Simples |
| 2 | 170010007 | Diária de Viagem |

*Observação: Verificar valor conforme local (Faixa II na tabela de referência)*

### Fluxo Detalhado - ADIANTAMENTO DE VIAGEM (14 etapas)

**ETAPA 1-5: Movimento e Dados Básicos**
1. **Mov. > Comunicação Interna > Mov. de Comum. Interna - Incluir** (Adiantamento de Viagem)
2. **Data**: Pode ser um dia antes ou na data de empenho
3. **Responsável**: Carla Peixoto (4318)
4. **Unidade**: 02.01.05.01 - Educação
5. **Fornecedor**: Funcionário | **Código Pagamento**: 12 (9 = À Vista)

**ETAPA 6-7: Finalidade e Itens**
6. **Finalidade/Histórico**: Descrever detalhadamente:
   > "REFERE-SE A LIBERAÇÃO DE DIÁRIA DE VIAGEM DA SERVIDORA [NOME], PARA CUSTEAR DESPESA COM VIAGEM ATÉ O MUNICÍPIO DE [DESTINO] NO DIA [DATA], PARA [MOTIVO/EVENTO], CONFORME PROSPECTO ANEXO E LEIS MUNICIPAIS AUTORIZATIVAS N°1.818/2018 E N°1.897/2019, A QUAL SE COMPROMETE A PRESTAR CONTAS POSTERIORMENTE."

7. **Incluir Itens**:
   - Item 1: 170010019 (Diária Viagem Simples)
   - Item 2: 170010007 (Diária de Viagem)
   - *Verificar valor conforme local (Faixa II)*

**ETAPA 8-10: Aprovação e Dotação**
8. **Mov. > Comunic. Interna > Aprovação de Comunic. Interna** (clicar no nome)
9. **Preencher Dotação**:
   - Projeto: 2034
   - Ficha: 340
   - Subelemento: Diária de demais Servidores
   - Fonte: 1500
   - CO: 1001
   - Obj. Desp: 02
10. **OK > SIM** (documento ficará em amarelo)

**ETAPA 11-14: Empenho e Finalização**
11. **Empenhar > OK > SIM**
12. **Imprimir**: Empenho, Nota de Despesa e C.I. juntamente com **Requerimento Anexo II preenchido**
13. **Levar na Contabilidade** com Requerimento de Viagem assinado
14. *Documentação completa*

### Fluxo Detalhado - RESTITUIÇÃO DE DESPESAS (Reembolso)

**Aplicável Para**:
- Despesas com alimentação já realizadas
- Despesas com hospedagem já realizadas
- Despesas com combustível/transporte já realizadas

**Procedimento**: Seguir as mesmas 14 etapas acima, porém:
- Na **Finalidade/Histórico**, mencionar:
  > "REFERE-SE A RESTITUIÇÃO DE VALOR, UTILIZADO PARA CUSTEAR DESPESAS COM [TIPO: ALIMENTAÇÃO/HOSPEDAGEM/ETC.], [LOCAL/EVENTO], NOS DIAS [DATAS], CONFORME DOCUMENTAÇÃO ANEXA E AUTORIZATIVAS N° 1.818/2018 E N°1.897/2019."
- Anexar comprovantes de despesa (notas fiscais, recibos)

---

## FLUXO GERAL DE EMPENHO

```
┌─────────────────────────────────────────────────────┐
│          INÍCIO DO PROCESSO DE EMPENHO              │
└─────────────────────────────────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────┐
    │ 1. MOVIMENTAÇÃO DE COMUNICAÇÃO  │
    │    (ou Processos de Compra)     │
    └─────────────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────┐
    │ 2. INCLUIR DADOS BÁSICOS        │
    │    - Data                       │
    │    - Responsável                │
    │    - Unidade                    │
    │    - Finalidade/Histórico       │
    └─────────────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────┐
    │ 3. INCLUIR ITENS                │
    │    (Códigos de Despesa)         │
    └─────────────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────┐
    │ 4. CONFIRMAÇÃO INICIAL          │
    │    OK > OK > FECHAR             │
    └─────────────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────┐
    │ 5. APROVAÇÃO DE COMUNICAÇÃO     │
    │    (por Responsável)            │
    └─────────────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────┐
    │ 6. PREENCHER DOTAÇÃO            │
    │    - Projeto                    │
    │    - Ficha                      │
    │    - Fonte                      │
    │    - CO (Centro de Custo)       │
    │    - Obj. Desp (Objeto)         │
    └─────────────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────┐
    │ 7. CONTROLE INTERNO (Se houver) │
    │    OK > SIM (fica amarelo)      │
    └─────────────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────┐
    │ 8. EMPENHO                      │
    │    Empenhar > SIM               │
    │    Desconto: SIM ou NÃO         │
    └─────────────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────┐
    │ 9. RETENÇÃO (Se necessário)     │
    │    - IR, INSS, ISS              │
    │    - Código Conta Tradutor      │
    │    - Valor de Desconto          │
    └─────────────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────┐
    │ 10. IMPRESSÃO                   │
    │     - Empenho                   │
    │     - Nota de Despesa           │
    │     - C.I.                      │
    │     - A.F. (se houver)          │
    └─────────────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────┐
    │ 11. ASSINATURA E PROTOCOLO      │
    │     (Responsável: CARLA)        │
    │     - Não bater carimbo antes   │
    └─────────────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────┐
    │ 12. ENTREGA À CONTABILIDADE     │
    │     (com documentação completa) │
    └─────────────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────┐
    │ 13. LIQUIDAÇÃO (Se necessário)  │
    │     - Recebimento de Nota       │
    │     - Liquidação de Serviço     │
    └─────────────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────┐
    │ 14. PAGAMENTO                   │
    │     Banco do Brasil             │
    │     AG: 0422-7                  │
    │     CC: 101126-X                │
    └─────────────────────────────────┘
                          │
                          ▼
┌─────────────────────────────────────────────────────┐
│            FIM DO PROCESSO DE EMPENHO               │
└─────────────────────────────────────────────────────┘
```

---

## CONTATOS E RESPONSÁVEIS

### Responsável Principal de Assinatura
- **Nome**: Carla Peixoto
- **Código**: 4318
- **Cargo**: [Especificar]
- **Funções**: Assinar empenhos, documentos de compra, autorizações

### Entidade Responsável
- **Prefeitura Municipal de Fronteira**
- **CNPJ**: 18.449.140/0001-07
- **Unidade**: 02 - Secretaria da Educação

### Banco Depositário
- **Nome**: Banco do Brasil S.A.
- **Código**: 001
- **Agência**: 0422-7
- **Conta Corrente**: 101126-X
- **Tipo de Operação**: Depósito ou Transferência

---

## OBSERVAÇÕES GERAIS IMPORTANTES

### Para Todos os Processos:
1. **Datas**: Verificar sempre a data de empenho conforme o grupo/departamento
2. **Assinatura**: CARLA PEIXOTO deve assinar todos os documentos
3. **Protocolização**: Não bater carimbo antes de entregar para assinatura
4. **Entrega**: Sempre levar à Contabilidade com documentação completa
5. **Banco**: Todas as transferências pelo Banco do Brasil 001 AG 0422-7 CC 101126-X

### Para Retenção de IR:
- Verificar se o fornecedor é **optante** ou **não optante**
- **Não optante**: Aplicar retenção (IR 4,8% para TEBAS; IR 0,24% para fornecedores)
- **Optante**: Não aplicar retenção
- Usar **Conta Tradutor: 17** para registrar a receita

### Para Material de Gás:
- Sempre especificar o tamanho (13kg ou 45kg)
- Indicar a unidade beneficiária (creche, pré-escola ou escola)
- Mencionar o período estimado de utilização

### Para Viagem:
- Anexar prospecto com informações do evento
- Verificar a tabela de valores de diária por local (Faixa II)
- Levar Requerimento de Viagem Anexo II assinado
- Para reembolso, anexar comprovantes de despesa

---

**Documento Atualizado**: 14 de Novembro de 2025
**Preparado por**: Análise de Codebase e Documentação Interna
**Status**: Documento Informativo para Referência
