# conexus-drivers-xiaomi

Catálogo e módulos de driver da marca **xiaomi** para o [Conexus Mobile OS](https://github.com/conexus-systems/conexus-mobile-os).

89 aparelhos com build oficial do LineageOS 23.2, 25 deles com kernel ≥ 5.10.

## O que este repositório é, e o que não é

- **É** um catálogo (`devices.json`, `CATALOG.md`) e o lugar onde ficam os módulos de driver da marca.
- **Não contém drivers.** Para os aparelhos com LineageOS oficial, o kernel, o device tree e os blobs já vêm nos repositórios do LineageOS, e a imagem oficial já os inclui. Aqui só se referencia o nome desses repositórios.
- **Não contém blobs de fabricante** (ADR-014). O `.gitignore` bloqueia os tipos binários.
- **Nada aqui está verificado em aparelho.** O estado é `unverified` em `brand-module.json`; só passa a `verified` com C1–C5 aprovados, cada um com fonte e data (ADR-010).

Dados de 2026-10-22 (LineageOS 23.2). Veja SOURCES.md.
