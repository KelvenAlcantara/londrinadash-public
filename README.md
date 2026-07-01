# LondrinaDash

Painel aberto sobre o orçamento municipal de Londrina/PR: como ele é
planejado, autorizado e (quando os dados de execução estiverem
integrados) efetivamente gasto, ano a ano.

Cobertura atual: **QDD 2018–2026** (9 anos), com cada valor anual
reconciliado contra o Art. 2º da respectiva Lei Orçamentária Anual (LOA)
— nada entra no painel sem bater com um número publicado oficialmente.

## Acessar o painel

Publicado via GitHub Pages a partir da pasta [`docs/`](docs/) deste
repositório. Também funciona offline, com duplo clique em qualquer
arquivo — os dados já vêm embutidos:

| Arquivo | Conteúdo |
|---|---|
| `docs/index.html` | Página inicial / navegação |
| `docs/dashboard.html` | Painel principal |
| `docs/explorador.html` | Explorador dos dados linha a linha |
| `docs/analise.html` | Análises e comparações |
| `docs/verificacao.html` | Verificação de integridade dos dados |
| `docs/construtor.html` | Construtor de visualizações |

## Fonte dos dados

Documentos oficiais da Prefeitura de Londrina (Quadro Detalhado de
Despesa e Lei Orçamentária Anual). Cada valor é rastreável até o
documento de origem — sem estimativas, sem dados de terceiros.

## Metodologia e limitações

Este painel reflete o **orçado e autorizado**. A etapa de **execução**
(quanto foi de fato gasto) depende de uma âncora externa do Portal da
Transparência, ainda em integração — acompanhe o andamento no
repositório de desenvolvimento.

Este projeto busca apresentar dados de forma isenta e verificável. Erros
ou inconsistências podem ser reportados abrindo uma *issue* neste
repositório.

## Licença

O **código** deste repositório (HTML/CSS/JS em `docs/`) está sob
[licença MIT](LICENSE) — uso e adaptação livres, inclusive para outros
municípios.

Os **dados** orçamentários embutidos são de fontes públicas oficiais e
estão sob **CC BY 4.0** — uso livre, desde que citada a fonte
(LondrinaDash + documento oficial de origem).
