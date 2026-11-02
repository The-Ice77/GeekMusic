# Wireframe do Projeto GeekMusic

Este documento descreve a estrutura visual e a disposição das seções da landing page do **GeekMusic**, baseando-se no planejamento inicial e na organização de layout com Flexbox.

---

## Estrutura Geral (Esquema Visual)

```text
+-------------------------------------------------------------+
| Navbar: [Logo] GeekMusic | Início | Músicas | Autores | Sobre | [Entrar] |
+-------------------------------------------------------------+
| Hero:                                                       |
|   Título & Texto de Apresentação                            |
|   [Saber Mais]  [Participar]                                |
|   [Imagem Principal / Destaque]                             |
+-------------------------------------------------------------+
| Músicas Mais Ouvidas:                                       |
|                                                             |
|   [Card]                 [Card]                 [Card]      |
|   Música #1              Música #2              Música #3   |
|   Badge: Ranking         Badge: Ranking         Badge: Ranking |
|   [Ouvir]                [Ouvir]                [Ouvir]     |
+-------------------------------------------------------------+
| Músicas Recentes:                                           |
|                                                             |
|   [Card]                 [Card]                 [Card]      |
|   Imagem                 Imagem                 Imagem      |
|   Título                 Título                 Título      |
|   Descrição              Descrição              Descrição   |
|   [Saiba Mais]           [Saiba Mais]           [Saiba Mais]|
+-------------------------------------------------------------+
| Autores em Destaque:                                        |
|                                                             |
|   [Card]           [Card]           [Card]           [Card] |
|   Autor 1          Autor 2          Autor 3          Autor 4|
|   Badge: Ranking   Badge: Ranking   Badge: Ranking   Badge: Ranking |
|   Badge: Cidade    Badge: Cidade    Badge: Cidade    Badge: Cidade  |
|   [Seguir]         [Seguir]         [Seguir]         [Seguir]       |
+-------------------------------------------------------------+
| Formulário de Inscrição:                                    |
|                                                             |
|   Nome:      [___________________________________________]  |
|   Username:  [___________________________________________]  |
|   E-mail:    [___________________________________________]  |
|   Senha:     [___________________________________________]  |
|   Número:    [___________________________________________]  |
|                                                             |
|   [Enviar]  [Cancelar]                                      |
+-------------------------------------------------------------+
| Rodapé:                                                     |
|   Logo | Links de Navegação | Redes Sociais | Copyright     |
+-------------------------------------------------------------+
```

---

## Detalhamento das Seções e Componentes

### 1. Barra de Navegação (Navbar)
- **Tipo:** Componente Composto (`.navbar`)
- **Elementos:** 
  - Logotipo e nome da marca (`.navbar__logo`)
  - Links de navegação: Início, Músicas, Autores, Sobre (`.navbar__links`, `.navbar__link`)
  - Botão de ação: Entrar (`.btn`, `.btn--primary`)
- **Layout Flexbox:** Alinhamento horizontal com `display: flex; justify-content: space-between; align-items: center;`.

### 2. Cabeçalho Inicial (Hero)
- **Tipo:** Seção de destaque com Flexbox
- **Elementos:**
  - Título principal (`.hero__title`)
  - Texto introdutório / proposta de valor (`.hero__subtitle` / `.hero__text`)
  - Grupo de botões de ação: "Saber Mais" e "Participar" (`.hero__actions`)
  - Imagem ou ilustração principal (`.hero__image`)
- **Layout Flexbox:** Distribuição em duas colunas (texto e mídia) com quebra responsiva.

### 3. Músicas Mais Ouvidas
- **Tipo:** Grade/Lista Flexbox de Cards
- **Elementos:**
  - Cards de música (`.card`, `.card--ranking`)
  - Badges de ranking/sucesso (`.badge`, `.badge--ranking`)
  - Botão de reprodução/ação ("Ouvir")
- **Layout Flexbox:** Container flex com `display: flex; gap: 24px; flex-wrap: wrap;`.

### 4. Músicas Recentes (Lançamentos)
- **Tipo:** Grade/Lista Flexbox de Cards
- **Elementos:**
  - Card com imagem da capa, título e descrição da faixa
  - Botão de ação secundária ("Saiba Mais")
- **Layout Flexbox:** Distribuição uniforme dos cards com alinhamento flexível.

### 5. Autores em Destaque
- **Tipo:** Seção com Cards de Perfil
- **Elementos:**
  - Foto do autor / avatar
  - Nome do autor e descrição
  - Badges: Ranking e Cidade
  - Botão de interação ("Seguir")
- **Layout Flexbox:** Flexbox horizontal com espaçamento consistente (`gap`).

### 6. Formulário de Inscrição
- **Tipo:** Componente Composto de Formulário (`.form`)
- **Elementos:**
  - Campos de entrada: Nome, Username, E-mail, Senha e Telefone (`.form__group`, `.form__input`)
  - Ações do formulário: Botão "Enviar" (destaque) e "Cancelar" (neutro/secundário)
- **Layout Flexbox:** Direção em coluna (`flex-direction: column`) para os campos e linha horizontal para os botões.

### 7. Rodapé (Footer)
- **Tipo:** Componente Composto (`.footer`)
- **Elementos:**
  - Marca/Logo
  - Links rápidos
  - Ícones de redes sociais
  - Informações de direitos autorais
- **Layout Flexbox:** Alinhamento e distribuição espaçada entre os blocos informativos.

