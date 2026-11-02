# 📓 Diário de Bordo — GeekMusic

## 📌 Informações Gerais do Projeto
* **Projeto:** GeekMusic — Página de Divulgação de Músicas Geek
* **Disciplina:** Design Web 1M
* **Integrantes do Grupo:**
  * Davi Gomes Suassuna
  * Luis Felipe Torres Josue
  * Jusdfran Medeiros Do Nascimento
  * João Victor Sales de Azevedo Silva
* **Repositório:** [https://github.com/The-Ice77/GeekMusic.git](https://github.com/The-Ice77/GeekMusic.git)

---

## 📋 Registro de Atividades e Uso de IA (Modelo Oficial)

| Data | Integrantes envolvidos | O que foi feito | Uso de IA | Decisão do grupo |
| :---: | :--- | :--- | :--- | :--- |
| **10/10** | Todos os integrantes | Detalhamento inicial do projeto (`Planejamento de Projeto.pdf`). Definição de tema, público-alvo, seções da página, componentes simples e compostos. | Consulta sobre boas práticas de organização de requisitos para landing pages musicais. | Escolhemos focar na comunidade de rap geek e anime, estruturando 7 seções principais e os componentes BEM necessários. |
| **13/10** | Todos os integrantes | Criação das estruturas padrões em HTML. Esboço das marcações da página principal (`index.html`) e catálogo (`componentes.html`). | Pedimos sugestões de estrutura semântica para cards e navegação. | Adotamos tags semânticas (`<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) e preparamos os containers. |
| **17/10** | Todos os integrantes | Discussão da identidade visual, definição da paleta de cores (foco em tons roxos) e especificações do wireframe (`docs/wireframe.md`). | Consulta sobre contraste e harmonização de paleta roxa com fundo claro. | Optamos por manter o modo claro com tons roxos (`#7c3aed`, `#2e1065`, `#f8f7ff`) e cantos arredondados, evitando estética escura genérica. |
| **20/10** | Todos os integrantes | Início da implementação do CSS (`css/style.css`), valores padrões e configuração de variáveis globais (`:root`). | Apoio na estruturação inicial de variáveis CSS e sintaxe da metodologia BEM. | O grupo definiu as variáveis de cores e espaçamentos, iniciando a codificação dos componentes simples. |
| **24/10** | Todos os integrantes | Conclusão da base do CSS: estilização com Flexbox dos componentes compostos (Navbar, Formulário de Inscrição e Rodapé). | Dúvidas pontuais sobre alinhamento com `justify-content` e `flex-wrap`. | Ajustamos a Navbar e o Rodapé para ocuparem 100% da largura da tela, com conteúdo interno centralizado em container. |
| **27/10** | Todos os integrantes | Curadoria e seleção de cantores, músicas geek reais e refinamento dos cards e badges. | Nenhum. | Escolhemos artistas conhecidos da cena nacional (Tauz, 7 Minutoz, VMZ) para tornar a página viva, realista e autoral. |
| **31/10** | Todos os integrantes | Criação do repositório oficial no GitHub (`Initial commit`) e preparação da unificação dos arquivos. | Nenhum. | Centralizamos o código trabalhado separadamente durante o mês no repositório final. |
| **01/11** | Todos os integrantes | Organização das pastas, subida dos PDFs de planejamento e documentação do wireframe no repositório. | Formatação do wireframe em representação textual/markdown. | Mantivemos a árvore de diretórios rigorosamente alinhada com as recomendações da disciplina (`css/`, `docs/`, `imagens/`). |
| **02/11** | Todos os integrantes | Mutirão de refinamento: ajuste das logos recortadas, unificação dos arquivos, README e diário de bordo atualizados. | Revisão de código, ajuste de referências de variáveis no CSS e estruturação da documentação. | O grupo refinou manualmente os estilos e finalizou a entrega. |

---

## 💡 Detalhamento do Uso de IA (Conforme Diretrizes do Manual)

1. **Ferramentas utilizadas:** Assistentes de inteligência artificial generativa (Google Antigravity / Gemini).
2. **Perguntas e solicitações feitas:**
   * Ajuda na aplicação da metodologia BEM em CSS.
   * Ajuda na aplicação de propriedades de alinhamento com Flexbox.
   * Sugestão de escala cromática em variáveis CSS (`:root`) baseada na cor roxa.
3. **Respostas aproveitadas:**
   * O molde da estrutura de arquivos (`index.html`, `componentes.html`, `style.css`, `docs/`).
   * A padronização da nomenclatura BEM (`.card__title`, `.btn--primary`, `.navbar__container`).
4. **Decisão final adotada:**
   * O uso de IA atuou estritamente como suporte técnico e consultivo de aprendizagem. Toda a decisão estética, organização de layout e autoria do projeto reflete as escolhas conscientes dos integrantes do grupo.

---

## 📝 Observação sobre o Versionamento no GitHub
*Durante as primeiras semanas (10/10 a 27/10), os integrantes trabalharam localmente e de forma descentralizada em rascunhos de HTML e CSS, aguardando a abertura formal da atividade de envio no Google Sala de Aula (GSA). Assim que o repositório foi criado em 31/10, os códigos foram unificados, passando pelas etapas incrementais de commits, documentação e refinamentos finais.*

---

## 🗓️ Histórico de Commits no Repositório

### 📅 Outubro 31, 2026
* **`8613547`** — **Initial commit**: Criação do repositório oficial com README inicial.

### 📅 Novembro 1, 2026
* **`3b9c67f`** — **Estrutura inicial do projeto e organizacao de pastas**: Criação das pastas `css/`, `docs/`, `imagens/` e arquivos base.
* **`34e9b15`** — **docs: adiciona wireframe e detalhamento das secoes da pagina**: Documentação do layout e arquitetura no `wireframe.md`.

### 📅 Novembro 2, 2026
* **`22b974b`** — **feat: constroi biblioteca de componentes, pagina principal e estilizacao com flexbox**: Implementação da biblioteca, página principal e estilos.
* **`e8077b2`** — **docs: atualiza titulos da documentacao do wireframe**: Limpeza e padronização dos títulos da documentação.
* **`a10dd33`** — **style: ajusta variaveis de border-radius para badges e imagens de autor**: Refinamento das variáveis de arredondamento no CSS.
* **`309334d`** — **style: atualiza referencias das variaveis de border-radius no css**: Aplicação consistente de `var(--radius-...)` em todo o CSS.
* **`3a61792`** — **style: restaura object-fit contain na logo do rodape e limpa .gitkeep**: Ajuste visual da logo no rodapé e limpeza de arquivos temporários.
* **`70470bc`** — **style: altera tipografia principal para fonte Verdana**: Definição da fonte Verdana como tipografia padrão do projeto.
* **`83088ec`** — **chore: ignora pasta GeekMusic-main no gitignore**: Configuração do `.gitignore` para proteção do repositório.
