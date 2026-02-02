# Persistência Contextual em Arquitetura de Software

Este repositório acompanha o artigo **“Nem todo sistema precisa de um banco de dados: uma decisão arquitetural contextual”**.

O objetivo não é propor substituição de bancos de dados tradicionais, mas discutir **quando eles são excesso** e quando soluções de persistência mais simples podem ser adequadas ao problema real.

## A tese central

Nem todo sistema precisa nascer com um banco de dados transacional tradicional.

Em determinados cenários — como MVPs, automações e sistemas internos — o requisito real pode ser apenas persistência tabular acessível por API, com baixo custo operacional e possibilidade de inspeção humana.

Nesses casos, soluções como Google Sheets + Google Apps Script **podem ser uma decisão arquitetural consciente**, desde que seus limites sejam explícitos e assumidos.

## O que este repositório contém

- O artigo completo em formato `.docx` / `.pdf`
- Diagramas conceituais da arquitetura
- Um script em Python que gera o artigo formatado automaticamente em Word
- Exemplos didáticos (não produtivos)

## O que este repositório NÃO é

- Não é uma recomendação genérica
- Não é uma solução escalável
- Não é adequado para sistemas críticos ou financeiros

## Quando faz sentido

- Baixa concorrência
- Baixa taxa de escrita
- Dados pouco críticos
- Necessidade de inspeção humana
- Foco em agilidade e baixo custo operacional

## Quando evitar

- Transações complexas
- Concorrência elevada
- Requisitos fortes de consistência
- SLA rigoroso

## Licença

Uso educacional e técnico. Use com responsabilidade arquitetural.
