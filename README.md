
# Análise de Dados e Dashboard — Oficina Mecânica

![Dashboard](https://github.com/Aline-Silva-ADS/analise-oficina-power-bi/raw/main/imagens/Pagina-1.png)

Projeto acadêmico desenvolvido em grupo durante o curso de Gestão da Tecnologia da Informação, utilizando **Power BI** para analisar dados de uma oficina mecânica.

O objetivo foi utilizar os dados de Ordens de Serviço (OS) para analisar aspectos como faturamento, custos, lucro, utilização da capacidade e desempenho dos serviços.

## Sobre o projeto

A oficina estava avaliando a possibilidade de ampliar sua estrutura física. A partir dos dados disponíveis, o grupo buscou entender se o espaço realmente era o principal fator limitante para o crescimento da operação.

Para isso, os dados foram tratados e organizados no Power BI e utilizados na criação de indicadores e visualizações.

## Tratamento e modelagem

Os dados foram fornecidos pelo professor em arquivos Excel.

No **Power Query**, foram realizadas etapas de:

* Limpeza dos dados;
* Ajuste dos tipos de dados;
* Tratamento de valores nulos;
* Tratamento de registros duplicados.

A modelagem utilizada no projeto conta com as seguintes tabelas:

* `Fato_OS`
* `Dim_Cliente`
* `Dim_Servico`
* `Dim_Mecanico`
* `Calendario`

## Indicadores

Foram utilizadas medidas em **DAX** para realizar os cálculos apresentados no dashboard.

Entre os indicadores trabalhados estão:

* Receita;
* Custo;
* Lucro;
* Ticket Médio;
* Quantidade Total;
* Taxa de Crescimento;
* Rentabilidade;
* Ocupação da oficina;
* Receita por hora trabalhada.

## Resultados da análise

Um dos principais pontos identificados foi uma **taxa média de ocupação de 52,2%**, indicando que parte da capacidade da oficina permanecia disponível.

Também foram encontradas diferenças na receita por hora entre os serviços, principalmente entre serviços de menor e maior duração.

Na análise dos clientes, o lucro apresentou uma distribuição relativamente pulverizada, sem concentração excessiva em poucos clientes.

A partir dessas análises, foram levantados pontos para avaliação, como:

* Ocupação nos períodos de menor demanda;
* Revisão da tabela de preços;
* Rentabilidade dos serviços;
* Fidelização dos clientes;
* Manutenção preventiva.

## Minha participação

O projeto foi desenvolvido em grupo. Minha participação foi principalmente nas etapas de tratamento dos dados, modelagem, criação de medidas e desenvolvimento da primeira página do dashboard.

### Power Query

* Limpeza dos dados;
* Ajuste dos tipos de dados;
* Tratamento de valores nulos;
* Tratamento de registros duplicados.

### Modelagem

* Desenvolvimento da modelagem dos dados no Power BI.

### DAX

Criei as seguintes medidas:

* Custo;
* Lucro;
* Ticket Médio;
* Taxa de Crescimento;
* Quantidade Total;
* Receita.

### Dashboard

* Desenvolvimento da Página 1;
* Organização dos visuais da página.

As demais páginas e etapas foram desenvolvidas pelos outros integrantes do grupo.

## Dashboard

### Página 1 — Minha participação

![Página 1 do Dashboard](https://github.com/Aline-Silva-ADS/analise-oficina-power-bi/blob/main/Imagens/Pagina-1.png)

### Página 2

![Página 2 do Dashboard](https://github.com/Aline-Silva-ADS/analise-oficina-power-bi/blob/main/Imagens/Pagina-2.png)

## Ferramentas

* Power BI
* Power Query
* DAX
* Excel

## Estrutura

```text
projeto-power-bi/
├── imagens/
│   ├── pagina-1.png
│   └── pagina-2.png
└── README.md
```

## Contexto acadêmico

Projeto desenvolvido como atividade acadêmica do curso de **Gestão da Tecnologia da Informação**.
