# Aaron's Neovim Config

## Presets
Number Line\
Relative Number Line\
Sync OS and Neovim clipboard\
Case-insensitive search\
Show preview of search and substitute\
Min 10 lines above and below cursor\
Ask to save unsaved changes\
Yank Highlighting\
Color: catppuccin-frappe\
background: transparent

## Keymaps
Leader ' '\
\<Esc\> clear search highlights\
\<leader\>ga [g]it [a]dd\
\<leader\>gc [g]it [c]ommit\
\<leader\>gm [g]it commit --a[m]end
\<leader\>gp [g]it [p]ull\
\<leader\>gP [g]it [P]ush\
\<leader\>gPl [g]it [P]ush force-with-[l]ease\
]c Jump to next git [c]hange\
\<leader\>gs [g]it[s]tage hunk\
\<leader\>gr [g]it [r]evert hunk\
\<leader\>gS [g]it [S]tage buffer\
\<leader\>gR [g]it [R]eset buffer\
\<leader\>gh [g]it preview [h]unk\
\<leader\>gi [g]it preview hunk [i]nline\
\<leader\>gb [g]it [b]lame line\
\<leader\>gd [g]it [d]iff against index\
\<leader\>gD [g]it [D]iff against last commit\
\<leader\>gQ [g]it [Q]uickfix list (all files in repo)\
\<leader\>gq [g]it hunk [q]uickfix list (all changes in this file)\
\<leader\>tb [t]oggle git show [b]lame line\
\<leader\>tw [t]oggle git intra-line [w]ord diff\
ih text object [i]inside [h]unk

## Packages
Package manager: vim.pack\
guess-indent\
gitsigns\
which-key\
todo-comments\
mini: icons, ai, surround, pairs, statusline\
telescope\
fidget\
nvim-lspconfig\
mason\
mason-lspconfig\
manson-tool-installer

## LSPs
asm-lsp - assembly \
basedpyright - Python\
clangd - c and c++\
css-lsp - css\
csskit - css\
gopls - golang\
html-lsp -- HTML\
jdtls - java\
lua-language-server - lua\
ruff - python\
rust_analyzer - rust\
stylua - lua\
typescript-language-server - typescript and javascript

## Formatters
csskit\
prettier\
prettierd\
ruff\
stylua

## Linters
csskit\
htmlhint\
ruff\
typos\
write-good\
yamllint

## Plans
Add a \<leader\>gs [g]it [s]tatus\
Add a \<leader\>gPl [g]it [P]ush --force-with-[l]ease
