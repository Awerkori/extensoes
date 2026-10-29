# Project Nox · Extensões de Mangá

Repositório oficial de distribuição e catálogo compilado de extensões de mangá do **Project Nox** para **Mihon e forks**.

---

## 🎯 Para quem é este repositório?

Este repositório é voltado para **leitores e usuários finais** que desejam instalar, explorar e manter atualizadas as extensões de leitura de mangás, manhwas, manhuas e quadrinhos diretamente em seus aplicativos móveis compatíveis com o ecossistema **Mihon e forks**.

> [!NOTE]
> Se você é desenvolvedor e procura o **código-fonte em Kotlin** das extensões ou deseja contribuir tecnicamente com correções, acesse o repositório irmão de desenvolvimento:  
> ➡️ [**Project Nox · Código-fonte das Extensões de Mangá**](https://github.com/Awerkori/manga-fonte-extensoes)

---

## 📲 Como Adicionar ao Mihon e forks

### Método 1: Instalação Automática (Recomendado)
Toque no link abaixo diretamente pelo navegador do seu celular Android para registrar o repositório de forma automática no aplicativo:

👉 [**Adicionar Repositório Automaticamente**](tachiyomi://add-repo?url=https%3A%2F%2Fraw.githubusercontent.com%2FAwerkori%2Fmanga-extensoes%2Frepo%2Findex.min.json)

---

### Método 2: Instalação Manual

1. No seu aplicativo (**Mihon e forks**), acesse **Mais** (ou Configurações) → **Configurações** → **Navegar** → **Repositórios de extensões**.
2. Toque no botão de adicionar (`+`).
3. Insira a URL do catálogo moderno de alta performance (Protobuf):

```
https://raw.githubusercontent.com/Awerkori/manga-extensoes/repo/index.pb
```

*(Opcional: para versões antigas de leitores ou compatibilidade legada com JSON puro, você também pode utilizar `https://raw.githubusercontent.com/Awerkori/manga-extensoes/repo/index.min.json`).*

---

### Método 3: Download Direto de APKs
Caso prefira instalar uma extensão específica manualmente:
- Acesse a pasta [`apk/`](apk/) nesta branch ou verifique as [Releases](https://github.com/Awerkori/manga-extensoes/releases) para baixar o arquivo `.apk` desejado e instalá-lo no Android.

---

## ⚙️ Como Funciona este Repositório

- **Automação Completa:** Os arquivos desta branch (`repo`) são gerados e mantidos por pipelines automatizados acionados a partir de [`manga-fonte-extensoes`](https://github.com/Awerkori/manga-fonte-extensoes).
- **Catálogo Otimizado (Protobuf v2):** O arquivo binário `index.pb` provê leitura ultrarrápida, serialização compacta e baixo consumo de dados móveis no seu aplicativo.
- **Assinatura e Segurança:** Todos os APKs disponibilizados são assinados digitalmente com chaves criptográficas consistentes, garantindo integridade e atualizações transparentes.

---

## 🛠️ Suporte e Pedidos de Extensões

Encontrou uma fonte de mangá que parou de funcionar ou deseja sugerir uma nova scan/site?

- 🎫 **Abrir solicitação oficial:** [Project Nox · Central de Pedidos](https://github.com/Awerkori/project-nox-requests)
- 📊 **Acompanhar status em tempo real:** [Project Nox · Tracker](https://awerkori.github.io/project-nox-tracker/)
- 🌐 **Ler pelo navegador:** [Project Nox · Site](https://manga.project-nox-awerkori.workers.dev)

---

## 🔗 Projetos Relacionados

- 💻 [**Project Nox · Código-fonte das Extensões de Mangá**](https://github.com/Awerkori/manga-fonte-extensoes) — Código em Kotlin, automação e desenvolvimento.
- 🎬 [**Project Nox · Extensões de Anime**](https://github.com/Awerkori/anime-extensoes) — Catálogo de extensões de vídeo para Aniyomi e forks.
- 💻 [**Project Nox · Código-fonte das Extensões de Anime**](https://github.com/Awerkori/anime-fonte-extensoes) — Código-fonte e extractors de streaming.
- ⚙️ [**Project Nox · Importer**](https://github.com/Awerkori/project-nox-importer) — Ingestão contínua de catálogo para a plataforma web.
- 📊 [**Project Nox · Tracker**](https://awerkori.github.io/project-nox-tracker/) — Dashboard público de status.

---

## 🌟 Créditos e Reconhecimento

- **Felipe GFA** ([@FelipeGFA](https://github.com/FelipeGFA)): Responsável pela estruturação do ecossistema de compilação, engenharia dos scripts de catalogação em Protobuf v2 e suporte primordial às fontes brasileiras.
- **Keiyoushi** ([@keiyoushi](https://github.com/keiyoushi)): Especificação de arquitetura de catálogos v2 e ecossistema upstream de referência.
- Comunidade open-source de leitores e desenvolvedores independentes.

---

## ⚖️ Isenção de Responsabilidade

O **Project Nox** disponibiliza apenas ferramentas de software livre para integração e leitura. Não controlamos, não hospedamos e não comercializamos arquivos de imagem de terceiros. Todo o conteúdo carregado através das extensões é fornecido diretamente pelas fontes externas públicas.
