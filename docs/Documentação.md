# Documentação — GeekMusic

## 1. Visão Geral da Arquitetura CSS
O projeto adota uma abordagem inspirada na metodologia **BEM (Block, Element, Modifier)**, garantindo que as classes CSS sejam previsíveis, reutilizáveis e evitem conflitos com outros elementos.

* **Bloco (`.bloco`):** Entidade autônoma que representa um componente (ex: `.card`, `.btn`, `.navbar`).
* **Elemento (`.bloco__elemento`):** Parte de um bloco que não tem significado sem ele (ex: `.card__title`, `.navbar__logo`).
* **Modificador (`.bloco--modificador`):** Variante que altera a aparência ou comportamento de um bloco ou elemento (ex: `.btn--primary`, `.badge--ranking`).

---

## 2. Design Tokens & Variáveis (`:root`)
O sistema de desin utiliza variáveis nativas do CSS (`CSS Custom Properties`) definidas no arquivo `css/style.css`:

### Paleta de Cores (Tons de roxo)
* `--purple-100` até `--purple-900`: Escala de roxos utilizada para fundos, bordas e títulos principais.
* `--color-primary`: Cor principal de ação (`var(--purple-600)`).
* `--color-bg`: Fundo padrão da página (`#f8f7ff`).
* `--color-surface`: Superfície de cards e containers (`#ffffff`).

### Raios de Borda (`Border Radius`)
* `--radius-small`: `4px`
* `--radius-medium`: `8px`
* `--radius-large`: `12px`
* `--radius-pill`: `20px`

---

## 3. Catálogo de Componentes Reutilizáveis

### 🔘 Botões (`.btn`)
* **Variantes:**
  * `.btn--primary`: Fundo roxo sólido com texto branco.
  * `.btn--secondary`: Fundo roxo claro com texto em tom escuro.
  * `.btn--danger`: Fundo vermelho para ações críticas/cancelamento.

### 🏷️ Badges (`.badge`)
* Marcadores compactos em formato de pílula (`--radius-pill`) com letras maiúsculas e espaçamento de caracteres ajustado (`letter-spacing`).
* **Tipos:** `.badge--city`, `.badge--danger`, `.badge--success`, `.badge--ranking`, `.badge--warning`.

### 🃏 Cards (`.card`)
* Estrutura flexível contendo imagem (`.card__image`), título (`.card__title`), descrição (`.card__description`) e botões de ação (`.card__button`).
* **Variações de contexto:** `.card--music`, `.card--listen`, `.card--recent`, `.card--author`.

### 📝 Formulários (`.registration-form`)
* Agrupamento semântico através de `.form-field`, combinando `.form-field__label` e `.form-field__input` com estados de foco estilizados.
