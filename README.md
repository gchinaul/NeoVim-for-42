# 🧠 NeoVim-for-42

Configuration Neovim optimisée pour les étudiants de l'école 42.  
Inclut support complet pour C, C++, Python, Java, la Norminette, Copilot, Treesitter, LSP, autocomplétion intelligente, et bien plus.

---

## 🚀 Fonctionnalités principales

- ✅ **Norminette** à la sauvegarde (`.c`, `.h`, `.cpp`, `.hpp`)
- ✅ **Header 42** automatique à la création de fichier
- 💬 **GitHub Copilot + Copilot Chat**
- 🧠 **nvim-cmp** pour l’autocomplétion
- 🧩 **LSP** intégré : C, C++, Java, Python
- 🌈 **Treesitter** pour une coloration syntaxique avancée
- 📁 **nvim-tree** pour explorer vos fichiers
- 📌 **gitsigns** pour visualiser les changements Git
- 📊 **lualine** pour une ligne de statut stylée
- 💡 Optimisé pour la vitesse et la simplicité

---

## 🛠️ Installation

### Prérequis

- [Neovim](https://neovim.io/) **v0.8+**
- `curl`, `git`, et un compilateur (`gcc`, `clang`, etc.)

### 1. Cloner la config

```bash
git clone https://github.com/gchinaul/NeoVim-for-42.git ~/.config/nvim

| Plugin                       | Rôle                                       |
| ---------------------------- | ------------------------------------------ |
| `vim-plug`                   | Gestionnaire de plugins                    |
| `copilot.lua`, `copilot-cmp` | Suggestions Copilot + intégration nvim-cmp |
| `CopilotChat.nvim`           | Interface de chat avec Copilot             |
| `42header`, `norminette`     | Plugins officiels de l’école 42            |
| `nvim-cmp` + extensions      | Moteur d’autocomplétion intelligent        |
| `nvim-lspconfig`             | Intégration LSP                            |
| `nvim-tree`                  | Arborescence de fichiers                   |
| `gitsigns.nvim`              | Intégration Git visuelle                   |
| `lualine.nvim`               | Ligne de statut moderne                    |
| `nvim-treesitter`            | Coloration et parsing avancés              |

| Raccourci clavier | Action                     |
| ----------------- | -------------------------- |
| `<C-n>`           | Ouvrir/fermer `nvim-tree`  |
| `<C-h>`           | Split horizontal           |
| `<C-v>`           | Split vertical             |
| `:W`, `:Q`, `:WQ` | Alias de `:w`, `:q`, `:wq` |
