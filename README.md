# financas_pessoais

com o objetivo de ajudar pessoas a se organizarem financeiramente.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
# FLUXO DO PROJETO:
O que o aplicativo deverá fazer?
    * CRUD DE CONTAS
    * REGISTRAR O PERÍODO (EX.: DIA 08/MAIO A 08/JUNHO)
    * REGISTRAR DESPESAS E RECEITAS DO PERÍODO MENSAL
    * CALCULAR QUANTO TEM DE SALDO LÍQUIDO EM CADA CONTA.
    * MOSTRAR O SALDO ATUAL PRESENTE E O QUANTO TERÁ NO FINAL DO MÊS
    * DEVERÁ REGISTRAR A ORIGEM DA DESPESA (QUAL CONTA FOI DEBITADA?) E NO CASO DA RECEITA (EM QUAL CONTA FOI APLICADO O DINHEIRO)
    
como fazer?
1- PESSOA FAZ LOGIN NO APP
2- CADASTRA CONTAS (receitas/despesas/banco)
    EX.: CONTA 1: BANCO DO BRASIL
         CONTA 2: BRADESCO
         CONTA 3: NUBANK
         CONTA ......
    EX.:
        DESPESAS{
         CONTA 4: MERCADO
         CONTA 5: VESTUÁRIO
        }
        RECEITA{
         CONTA 6: SALÁRIO
         CONTA 7: EMPRÉSTIMO
    }
REGISTRO DAS DESPESAS E RECEITAS
3- CADA CONTA PODERÁ SER CREDITADA (ENTRA DINHEIRO) OU DEBITADO (SAI DINHEIRO)
3.1 NO REGISTRO DA DESPESA DEVERÁ ESPECIFICAR COM O QUE GASTOU E SE JÁ PAGOU OU AINDA VAI PAGAR
    EX.: CONTA 04: MERCADO 
         DETALHE 05: FEIRA MENSAL
         STATUS: 02: DESPESA PAGA 
    O REGISTRO FICARÁ: 04.05.2
    DEPOIS ESPECIFICA A CONTA QUE SAIU O RECURSO (PELO NÚMERO)

3.2 NO REGISTRO DA RECEITA DEVERÁ ESPECIFICAR DE ONDE VEIO E SE JÁ RECEBEU OU AINDA VAI RECEBER:
    EX.: CONTA 06: SALÁRIO
         ESPECIFICAÇÃO: 08 PREFEITURA
         STATUS: 03: RECEITA RECEBIDA.
    O REGISTRO FICARÁ: 06.08.03
    DEPOIS ESPECIFICA A CONTA QUE SAIU O RECURSO (PELO NÚMERO)

RESULTADO:
===========================================================
COM ISSO TEREMOS 2 TABELAS:
1- TABELA: COM CONTAS DETALHADAS (DE ONDE VEIO O DINHEIRO, COM O QUE GASTOU E SE FOI PAGA OU NÃO) 
    DESPESA
1.1 SE FOI PAGA DEVE ENTRAR NO VALOR TOTAL
1.2 SE NÃO FOI PAGA SÓ ENTRA NO CALCULO DEPOIS QUE PAGAR
    RECEITA
1.3 SE JÁ RECEBEU DEVE ENTRAR NO VALOR TOTAL
1.4 SE AINDA NÃO RECEBER SÓ ENTRA QUANDO RECEBER.
OBJETIVO: IDENTIFCAR COM O QUE GASTOU E DE ONDE VEIO O DINHEIRO PARA PAGAR AS CONTAS DURANTE O MÊS E QUAL O MEU SALDO ATUAL.

2- TABELA:
2.1 DEVERÁ TER DUAS COLUNAS (AUMENTO E DIMINUIÇÃO) QUE REPRESENTAM QUAL AUMENTO OU DIMINUIÇÃO DO PATRIMÔNIO
nessa tela deverá aparecer todos os valores registrados (independente se foi pago ou não) com o número da CONTA se 
os valores das despesas deverão ficar no lado da "diminuição" junto com a conta que saiu o dinheiro.
os valores dar receitas deverão ficar no lado do "aumento" junto com a conta que recebeu o dinheiro.
OBJETIVO: IDENTIFICAR DE QUAL CONTA ENTROU OU SAIU DINHEIRO EM CADA TRANSAÇÃO E MOSTRAR QUANTO TEREI ATÉ O FINAL DO MÊS.
=====================



