# BACKUP STRATEGY

## Politica atual

A base inicial contempla separacao clara de dados persistentes e estrutura documental, com area dedicada de backup em `~/srv/backups`.

## Politica futura

A estrategia de backup evoluira para incluir:

- janelas de backup por criticidade de ativo;
- politica de retencao por horizonte temporal;
- validacao de integridade por checksum;
- testes periodicos de restauracao;
- definicao formal de RPO/RTO por servico.
