# 🧠 Brainstorm Canvas

> Canvas de brainstorm e diagramação minimalista — roda direto no browser, sem instalação.

**[→ Abrir ferramenta](https://nomeerrado.github.io/brainstorm-canvas/)**

---

## ✨ Funcionalidades

| Ferramenta | Atalho | Descrição |
|---|---|---|
| Selecionar | `V` | Clica para selecionar, arrasta para mover |
| Texto | `T` | Clique em qualquer ponto para criar caixa de texto |
| Retângulo | `R` | Arraste para desenhar |
| Elipse | `E` | Arraste para desenhar |
| Seta | `A` | Arraste para criar seta com ponta |
| Livre | `F` | Desenho à mão livre |
| Grupo | `G` | Retângulo tracejado para agrupar ideias |

**Outras interações:**
- **Duplo clique** num texto para editar
- **Cor ativa** — clique na paleta para trocar (também recolore o elemento selecionado)
- **Espessura** — 4 opções de traço na toolbar
- `DEL` / `Backspace` — deleta elemento selecionado
- `ESC` — deseleciona tudo

**Exportar:**
- **↓ JSON** — salva o estado completo do canvas (para continuar depois)
- **↓ PNG** — exporta como imagem
- **⌫ Limpar** — apaga tudo (pede confirmação)

---
 
## 🛠 Como funciona

Um único `index.html` com:

- **React 18** via CDN (`unpkg.com`)
- **Babel Standalone** para compilar JSX no browser
- **SVG nativo** para renderização do canvas

Sem bundler, sem `node_modules`, sem build step. O Babel compila o JSX na primeira visita (~2s) e o browser faz cache automaticamente.

---

## 📁 Estrutura

```
brainstorm-canvas/
└── index.html    ← tudo aqui
└── README.md
```
