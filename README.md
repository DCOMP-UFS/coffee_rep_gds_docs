### Repositório para Documentação do Projeto de Gestão de Salas do HU-UFS.

## Publicação no portal (intranet Ebserh)

A inclusão do **tile** ou atalho no portal institucional da Ebserh/intranet é um **processo da TI** da instituição: normalmente envolve cadastro da URL de produção (ex.: frontend no Vercel) e alinhamento de identidade visual/acessos. Este repositório não automatiza esse passo — apenas registre a URL final acordada com a equipe de infraestrutura.

## Dados de cadastro (ex.: 57 consultórios)

Critérios como número de consultórios por clínica são **dados operacionais**: podem ser cadastrados via telas de **Setores** e **Salas** ou, quando houver planilha oficial, via **script Flyway opcional** de seed ou instruções em runbook — não bloqueiam o desenvolvimento das funcionalidades de ausência/reserva.

## API (Postman)

A coleção `GDS_Backend.postman_collection.json` inclui os endpoints de **ausências do solicitante** (`/api/requester-absence`) e **health** (`/api/health`) para warm-up.
