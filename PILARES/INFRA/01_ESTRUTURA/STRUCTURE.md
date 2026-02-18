# STRUCTURE

## Base fisica e logica

A infraestrutura local esta centralizada no Mac Studio, com organizacao principal sob `~/srv`:

- `~/srv/angones-core`: politicas oficiais, arquitetura e validacoes da base.
- `~/srv/docker/stacks`: stacks de servicos versionaveis.
- `~/srv/docker/volumes`: dados persistentes de runtime.
- `~/srv/vm`: area dedicada para virtualizacao (futuro).
- `~/srv/ai`: area dedicada para IA local (futuro).
- `~/srv/backups`: armazenamento de backups.
- `~/srv/projects`: repositorios de trabalho e codigo.
- `~/srv/infra-docs`: documentacao complementar.

## Arquitetura do Mac Studio

- Host principal de operacao local.
- Runtime de containers via Docker Desktop (Apple Silicon).
- Exposicao controlada apenas para LAN e VPN.
- Organizacao orientada a separacao entre configuracao versionada e dados persistentes.
