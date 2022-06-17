---

layout: ../../../layouts/BlogLayout.astro
title: 'I love (neo)vim'
date: '2021-12-25'
description: "I've fallen in love with neovim. Take a look at my new editor/IDE!"
image: 'nvim.png'
tags: ['neovim','nvim']
---

## TL;DR: Neovim is awesome

I've recently used some of my spare time to finally actually configure [Neovim](https://neovim.io/).

Here's an image of the result so far:
![Screenshot of my Neovim setup](https://the.owo.foundation/71fJyaK.png)
The configuration file itself is pretty dirty, ~~but it works~~.

## Plugins
Vim already has lots of good plugins. 

Neovim, being *much* newer than vim, has fewer plugins made specifically for it. 

Fortunately for us, most Vim plugins are compatible with Vim (Neovim *is* a Vim fork, afterall).

I'm using the following plugins, and a few more:
* [coq.nvim](https://github.com/ms-jpq/coq_nvim) for completion (super awesome)
* [nvim-dap](https://github.com/mfussenegger/nvim-dap) for debugging 
* [tokyonight.nvim](https://github.com/folke/tokyonight.nvim) as the theme
* [lightline.vim](https://github.com/itchyny/lightline.vim) as the statusline

If you want to see the (dirty) file, see the full configuration [here](https://gist.github.com/JcdeA/d5d4e09329092f654081b644d07ac866).

Thanks for reading!