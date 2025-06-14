---
sidebar_position: 3
---

# ⌨️ Keymaps

**LazyVim** uses [which-key.nvim](https://github.com/folke/which-key.nvim) to help you remember your
keymaps. Just press any key like `<space>` and you'll see a popup with all
possible keymaps starting with `<space>`.

![image](https://user-images.githubusercontent.com/292349/211862473-1ff5ee7a-3bb9-4782-a9f6-014f0e5d4474.png)

- default `<leader>` is `<space>`
- default `<localleader>` is `\`

<!-- keymaps:start -->

## General

| Key                                               | Description                           | Mode                       |
| ------------------------------------------------- | ------------------------------------- | -------------------------- |
| <code>j</code>                                    | Down                                  | **n**, **x**               |
| <code>&lt;Down&gt;</code>                         | Down                                  | **n**, **x**               |
| <code>k</code>                                    | Up                                    | **n**, **x**               |
| <code>&lt;Up&gt;</code>                           | Up                                    | **n**, **x**               |
| <code>&lt;C-h&gt;</code>                          | Go to Left Window                     | **n**                      |
| <code>&lt;C-j&gt;</code>                          | Go to Lower Window                    | **n**                      |
| <code>&lt;C-k&gt;</code>                          | Go to Upper Window                    | **n**                      |
| <code>&lt;C-l&gt;</code>                          | Go to Right Window                    | **n**                      |
| <code>&lt;C-Up&gt;</code>                         | Increase Window Height                | **n**                      |
| <code>&lt;C-Down&gt;</code>                       | Decrease Window Height                | **n**                      |
| <code>&lt;C-Left&gt;</code>                       | Decrease Window Width                 | **n**                      |
| <code>&lt;C-Right&gt;</code>                      | Increase Window Width                 | **n**                      |
| <code>&lt;A-j&gt;</code>                          | Move Down                             | **n**, **i**, **v**        |
| <code>&lt;A-k&gt;</code>                          | Move Up                               | **n**, **i**, **v**        |
| <code>&lt;S-h&gt;</code>                          | Prev Buffer                           | **n**                      |
| <code>&lt;S-l&gt;</code>                          | Next Buffer                           | **n**                      |
| <code>[b</code>                                   | Prev Buffer                           | **n**                      |
| <code>]b</code>                                   | Next Buffer                           | **n**                      |
| <code>&lt;leader&gt;bb</code>                     | Switch to Other Buffer                | **n**                      |
| <code>&lt;leader&gt;`</code>                      | Switch to Other Buffer                | **n**                      |
| <code>&lt;leader&gt;bd</code>                     | Delete Buffer                         | **n**                      |
| <code>&lt;leader&gt;bo</code>                     | Delete Other Buffers                  | **n**                      |
| <code>&lt;leader&gt;bD</code>                     | Delete Buffer and Window              | **n**                      |
| <code>&lt;esc&gt;</code>                          | Escape and Clear hlsearch             | **i**, **n**, **s**        |
| <code>&lt;leader&gt;ur</code>                     | Redraw / Clear hlsearch / Diff Update | **n**                      |
| <code>n</code>                                    | Next Search Result                    | **n**, **x**, **o**        |
| <code>N</code>                                    | Prev Search Result                    | **n**, **x**, **o**        |
| <code>&lt;C-s&gt;</code>                          | Save File                             | **i**, **x**, **n**, **s** |
| <code>&lt;leader&gt;K</code>                      | Keywordprg                            | **n**                      |
| <code>gco</code>                                  | Add Comment Below                     | **n**                      |
| <code>gcO</code>                                  | Add Comment Above                     | **n**                      |
| <code>&lt;leader&gt;l</code>                      | Lazy                                  | **n**                      |
| <code>&lt;leader&gt;fn</code>                     | New File                              | **n**                      |
| <code>&lt;leader&gt;xl</code>                     | Location List                         | **n**                      |
| <code>&lt;leader&gt;xq</code>                     | Quickfix List                         | **n**                      |
| <code>[q</code>                                   | Previous Quickfix                     | **n**                      |
| <code>]q</code>                                   | Next Quickfix                         | **n**                      |
| <code>&lt;leader&gt;cf</code>                     | Format                                | **n**, **v**               |
| <code>&lt;leader&gt;cd</code>                     | Line Diagnostics                      | **n**                      |
| <code>]d</code>                                   | Next Diagnostic                       | **n**                      |
| <code>[d</code>                                   | Prev Diagnostic                       | **n**                      |
| <code>]e</code>                                   | Next Error                            | **n**                      |
| <code>[e</code>                                   | Prev Error                            | **n**                      |
| <code>]w</code>                                   | Next Warning                          | **n**                      |
| <code>[w</code>                                   | Prev Warning                          | **n**                      |
| <code>&lt;leader&gt;uf</code>                     | Toggle Auto Format (Global)           | **n**                      |
| <code>&lt;leader&gt;uF</code>                     | Toggle Auto Format (Buffer)           | **n**                      |
| <code>&lt;leader&gt;us</code>                     | Toggle Spelling                       | **n**                      |
| <code>&lt;leader&gt;uw</code>                     | Toggle Wrap                           | **n**                      |
| <code>&lt;leader&gt;uL</code>                     | Toggle Relative Number                | **n**                      |
| <code>&lt;leader&gt;ud</code>                     | Toggle Diagnostics                    | **n**                      |
| <code>&lt;leader&gt;ul</code>                     | Toggle Line Numbers                   | **n**                      |
| <code>&lt;leader&gt;uc</code>                     | Toggle Conceal Level                  | **n**                      |
| <code>&lt;leader&gt;uA</code>                     | Toggle Tabline                        | **n**                      |
| <code>&lt;leader&gt;uT</code>                     | Toggle Treesitter Highlight           | **n**                      |
| <code>&lt;leader&gt;ub</code>                     | Toggle Dark Background                | **n**                      |
| <code>&lt;leader&gt;uD</code>                     | Toggle Dimming                        | **n**                      |
| <code>&lt;leader&gt;ua</code>                     | Toggle Animations                     | **n**                      |
| <code>&lt;leader&gt;ug</code>                     | Toggle Indent Guides                  | **n**                      |
| <code>&lt;leader&gt;uS</code>                     | Toggle Smooth Scroll                  | **n**                      |
| <code>&lt;leader&gt;dpp</code>                    | Toggle Profiler                       | **n**                      |
| <code>&lt;leader&gt;dph</code>                    | Toggle Profiler Highlights            | **n**                      |
| <code>&lt;leader&gt;uh</code>                     | Toggle Inlay Hints                    | **n**                      |
| <code>&lt;leader&gt;gb</code>                     | Git Blame Line                        | **n**                      |
| <code>&lt;leader&gt;gB</code>                     | Git Browse (open)                     | **n**, **x**               |
| <code>&lt;leader&gt;gY</code>                     | Git Browse (copy)                     | **n**, **x**               |
| <code>&lt;leader&gt;qq</code>                     | Quit All                              | **n**                      |
| <code>&lt;leader&gt;ui</code>                     | Inspect Pos                           | **n**                      |
| <code>&lt;leader&gt;uI</code>                     | Inspect Tree                          | **n**                      |
| <code>&lt;leader&gt;L</code>                      | LazyVim Changelog                     | **n**                      |
| <code>&lt;leader&gt;fT</code>                     | Terminal (cwd)                        | **n**                      |
| <code>&lt;leader&gt;ft</code>                     | Terminal (Root Dir)                   | **n**                      |
| <code>&lt;c-/&gt;</code>                          | Terminal (Root Dir)                   | **n**                      |
| <code>&lt;c-\_&gt;</code>                         | which_key_ignore                      | **n**, **t**               |
| <code>&lt;C-/&gt;</code>                          | Hide Terminal                         | **t**                      |
| <code>&lt;leader&gt;-</code>                      | Split Window Below                    | **n**                      |
| <code>&lt;leader&gt;&vert;</code>                 | Split Window Right                    | **n**                      |
| <code>&lt;leader&gt;wd</code>                     | Delete Window                         | **n**                      |
| <code>&lt;leader&gt;wm</code>                     | Toggle Zoom Mode                      | **n**                      |
| <code>&lt;leader&gt;uZ</code>                     | Toggle Zoom Mode                      | **n**                      |
| <code>&lt;leader&gt;uz</code>                     | Toggle Zen Mode                       | **n**                      |
| <code>&lt;leader&gt;&lt;tab&gt;l</code>           | Last Tab                              | **n**                      |
| <code>&lt;leader&gt;&lt;tab&gt;o</code>           | Close Other Tabs                      | **n**                      |
| <code>&lt;leader&gt;&lt;tab&gt;f</code>           | First Tab                             | **n**                      |
| <code>&lt;leader&gt;&lt;tab&gt;&lt;tab&gt;</code> | New Tab                               | **n**                      |
| <code>&lt;leader&gt;&lt;tab&gt;]</code>           | Next Tab                              | **n**                      |
| <code>&lt;leader&gt;&lt;tab&gt;d</code>           | Close Tab                             | **n**                      |
| <code>&lt;leader&gt;&lt;tab&gt;[</code>           | Previous Tab                          | **n**                      |

## LSP

| Key                           | Description                | Mode         |
| ----------------------------- | -------------------------- | ------------ |
| <code>&lt;leader&gt;cl</code> | Lsp Info                   | **n**        |
| <code>gd</code>               | Goto Definition            | **n**        |
| <code>gr</code>               | References                 | **n**        |
| <code>gI</code>               | Goto Implementation        | **n**        |
| <code>gy</code>               | Goto T[y]pe Definition     | **n**        |
| <code>gD</code>               | Goto Declaration           | **n**        |
| <code>K</code>                | Hover                      | **n**        |
| <code>gK</code>               | Signature Help             | **n**        |
| <code>&lt;c-k&gt;</code>      | Signature Help             | **i**        |
| <code>&lt;leader&gt;ca</code> | Code Action                | **n**, **v** |
| <code>&lt;leader&gt;cc</code> | Run Codelens               | **n**, **v** |
| <code>&lt;leader&gt;cC</code> | Refresh & Display Codelens | **n**        |
| <code>&lt;leader&gt;cR</code> | Rename File                | **n**        |
| <code>&lt;leader&gt;cr</code> | Rename                     | **n**        |
| <code>&lt;leader&gt;cA</code> | Source Action              | **n**        |
| <code>]]</code>               | Next Reference             | **n**        |
| <code>[[</code>               | Prev Reference             | **n**        |
| <code>&lt;a-n&gt;</code>      | Next Reference             | **n**        |
| <code>&lt;a-p&gt;</code>      | Prev Reference             | **n**        |

## [bufferline.nvim](https://github.com/akinsho/bufferline.nvim.git)

| Key                           | Description                 | Mode  |
| ----------------------------- | --------------------------- | ----- |
| <code>&lt;leader&gt;bl</code> | Delete Buffers to the Left  | **n** |
| <code>&lt;leader&gt;bp</code> | Toggle Pin                  | **n** |
| <code>&lt;leader&gt;bP</code> | Delete Non-Pinned Buffers   | **n** |
| <code>&lt;leader&gt;br</code> | Delete Buffers to the Right | **n** |
| <code>[b</code>               | Prev Buffer                 | **n** |
| <code>[B</code>               | Move buffer prev            | **n** |
| <code>]b</code>               | Next Buffer                 | **n** |
| <code>]B</code>               | Move buffer next            | **n** |
| <code>&lt;S-h&gt;</code>      | Prev Buffer                 | **n** |
| <code>&lt;S-l&gt;</code>      | Next Buffer                 | **n** |

## [conform.nvim](https://github.com/stevearc/conform.nvim.git)

| Key                           | Description           | Mode         |
| ----------------------------- | --------------------- | ------------ |
| <code>&lt;leader&gt;cF</code> | Format Injected Langs | **n**, **v** |

## [flash.nvim](https://github.com/folke/flash.nvim.git)

| Key                      | Description         | Mode                |
| ------------------------ | ------------------- | ------------------- |
| <code>&lt;c-s&gt;</code> | Toggle Flash Search | **c**               |
| <code>r</code>           | Remote Flash        | **o**               |
| <code>R</code>           | Treesitter Search   | **o**, **x**        |
| <code>s</code>           | Flash               | **n**, **o**, **x** |
| <code>S</code>           | Flash Treesitter    | **n**, **o**, **x** |

## [grug-far.nvim](https://github.com/MagicDuck/grug-far.nvim.git)

| Key                           | Description        | Mode         |
| ----------------------------- | ------------------ | ------------ |
| <code>&lt;leader&gt;sr</code> | Search and Replace | **n**, **v** |

## [mason.nvim](https://github.com/mason-org/mason.nvim.git)

| Key                           | Description | Mode  |
| ----------------------------- | ----------- | ----- |
| <code>&lt;leader&gt;cm</code> | Mason       | **n** |

## [noice.nvim](https://github.com/folke/noice.nvim.git)

| Key                            | Description                     | Mode                |
| ------------------------------ | ------------------------------- | ------------------- |
| <code>&lt;c-b&gt;</code>       | Scroll Backward                 | **n**, **i**, **s** |
| <code>&lt;c-f&gt;</code>       | Scroll Forward                  | **n**, **i**, **s** |
| <code>&lt;leader&gt;sn</code>  | +noice                          | **n**               |
| <code>&lt;leader&gt;sna</code> | Noice All                       | **n**               |
| <code>&lt;leader&gt;snd</code> | Dismiss All                     | **n**               |
| <code>&lt;leader&gt;snh</code> | Noice History                   | **n**               |
| <code>&lt;leader&gt;snl</code> | Noice Last Message              | **n**               |
| <code>&lt;leader&gt;snt</code> | Noice Picker (Telescope/FzfLua) | **n**               |
| <code>&lt;S-Enter&gt;</code>   | Redirect Cmdline                | **c**               |

## [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter.git)

| Key                          | Description         | Mode  |
| ---------------------------- | ------------------- | ----- |
| <code>&lt;bs&gt;</code>      | Decrement Selection | **x** |
| <code>&lt;c-space&gt;</code> | Increment Selection | **n** |

## [persistence.nvim](https://github.com/folke/persistence.nvim.git)

| Key                           | Description                | Mode  |
| ----------------------------- | -------------------------- | ----- |
| <code>&lt;leader&gt;qd</code> | Don't Save Current Session | **n** |
| <code>&lt;leader&gt;ql</code> | Restore Last Session       | **n** |
| <code>&lt;leader&gt;qs</code> | Restore Session            | **n** |
| <code>&lt;leader&gt;qS</code> | Select Session             | **n** |

## [snacks.nvim](https://github.com/folke/snacks.nvim.git)

| Key                                      | Description                         | Mode         |
| ---------------------------------------- | ----------------------------------- | ------------ |
| <code>&lt;leader&gt;&lt;space&gt;</code> | Find Files (Root Dir)               | **n**        |
| <code>&lt;leader&gt;,</code>             | Buffers                             | **n**        |
| <code>&lt;leader&gt;.</code>             | Toggle Scratch Buffer               | **n**        |
| <code>&lt;leader&gt;/</code>             | Grep (Root Dir)                     | **n**        |
| <code>&lt;leader&gt;:</code>             | Command History                     | **n**        |
| <code>&lt;leader&gt;dps</code>           | Profiler Scratch Buffer             | **n**        |
| <code>&lt;leader&gt;e</code>             | Explorer Snacks (root dir)          | **n**        |
| <code>&lt;leader&gt;E</code>             | Explorer Snacks (cwd)               | **n**        |
| <code>&lt;leader&gt;fb</code>            | Buffers                             | **n**        |
| <code>&lt;leader&gt;fB</code>            | Buffers (all)                       | **n**        |
| <code>&lt;leader&gt;fc</code>            | Find Config File                    | **n**        |
| <code>&lt;leader&gt;fe</code>            | Explorer Snacks (root dir)          | **n**        |
| <code>&lt;leader&gt;fE</code>            | Explorer Snacks (cwd)               | **n**        |
| <code>&lt;leader&gt;ff</code>            | Find Files (Root Dir)               | **n**        |
| <code>&lt;leader&gt;fF</code>            | Find Files (cwd)                    | **n**        |
| <code>&lt;leader&gt;fg</code>            | Find Files (git-files)              | **n**        |
| <code>&lt;leader&gt;fp</code>            | Projects                            | **n**        |
| <code>&lt;leader&gt;fr</code>            | Recent                              | **n**        |
| <code>&lt;leader&gt;fR</code>            | Recent (cwd)                        | **n**        |
| <code>&lt;leader&gt;gd</code>            | Git Diff (hunks)                    | **n**        |
| <code>&lt;leader&gt;gs</code>            | Git Status                          | **n**        |
| <code>&lt;leader&gt;gS</code>            | Git Stash                           | **n**        |
| <code>&lt;leader&gt;n</code>             | Notification History                | **n**        |
| <code>&lt;leader&gt;S</code>             | Select Scratch Buffer               | **n**        |
| <code>&lt;leader&gt;s"</code>            | Registers                           | **n**        |
| <code>&lt;leader&gt;s/</code>            | Search History                      | **n**        |
| <code>&lt;leader&gt;sa</code>            | Autocmds                            | **n**        |
| <code>&lt;leader&gt;sb</code>            | Buffer Lines                        | **n**        |
| <code>&lt;leader&gt;sB</code>            | Grep Open Buffers                   | **n**        |
| <code>&lt;leader&gt;sc</code>            | Command History                     | **n**        |
| <code>&lt;leader&gt;sC</code>            | Commands                            | **n**        |
| <code>&lt;leader&gt;sd</code>            | Diagnostics                         | **n**        |
| <code>&lt;leader&gt;sD</code>            | Buffer Diagnostics                  | **n**        |
| <code>&lt;leader&gt;sg</code>            | Grep (Root Dir)                     | **n**        |
| <code>&lt;leader&gt;sG</code>            | Grep (cwd)                          | **n**        |
| <code>&lt;leader&gt;sh</code>            | Help Pages                          | **n**        |
| <code>&lt;leader&gt;sH</code>            | Highlights                          | **n**        |
| <code>&lt;leader&gt;si</code>            | Icons                               | **n**        |
| <code>&lt;leader&gt;sj</code>            | Jumps                               | **n**        |
| <code>&lt;leader&gt;sk</code>            | Keymaps                             | **n**        |
| <code>&lt;leader&gt;sl</code>            | Location List                       | **n**        |
| <code>&lt;leader&gt;sm</code>            | Marks                               | **n**        |
| <code>&lt;leader&gt;sM</code>            | Man Pages                           | **n**        |
| <code>&lt;leader&gt;sp</code>            | Search for Plugin Spec              | **n**        |
| <code>&lt;leader&gt;sq</code>            | Quickfix List                       | **n**        |
| <code>&lt;leader&gt;sR</code>            | Resume                              | **n**        |
| <code>&lt;leader&gt;su</code>            | Undotree                            | **n**        |
| <code>&lt;leader&gt;sw</code>            | Visual selection or word (Root Dir) | **n**, **x** |
| <code>&lt;leader&gt;sW</code>            | Visual selection or word (cwd)      | **n**, **x** |
| <code>&lt;leader&gt;uC</code>            | Colorschemes                        | **n**        |
| <code>&lt;leader&gt;un</code>            | Dismiss All Notifications           | **n**        |

## [todo-comments.nvim](https://github.com/folke/todo-comments.nvim.git)

| Key                           | Description              | Mode  |
| ----------------------------- | ------------------------ | ----- |
| <code>&lt;leader&gt;st</code> | Todo                     | **n** |
| <code>&lt;leader&gt;sT</code> | Todo/Fix/Fixme           | **n** |
| <code>&lt;leader&gt;xt</code> | Todo (Trouble)           | **n** |
| <code>&lt;leader&gt;xT</code> | Todo/Fix/Fixme (Trouble) | **n** |
| <code>[t</code>               | Previous Todo Comment    | **n** |
| <code>]t</code>               | Next Todo Comment        | **n** |

## [trouble.nvim](https://github.com/folke/trouble.nvim.git)

| Key                           | Description                              | Mode  |
| ----------------------------- | ---------------------------------------- | ----- |
| <code>&lt;leader&gt;cs</code> | Symbols (Trouble)                        | **n** |
| <code>&lt;leader&gt;cS</code> | LSP references/definitions/... (Trouble) | **n** |
| <code>&lt;leader&gt;xL</code> | Location List (Trouble)                  | **n** |
| <code>&lt;leader&gt;xQ</code> | Quickfix List (Trouble)                  | **n** |
| <code>&lt;leader&gt;xx</code> | Diagnostics (Trouble)                    | **n** |
| <code>&lt;leader&gt;xX</code> | Buffer Diagnostics (Trouble)             | **n** |
| <code>[q</code>               | Previous Trouble/Quickfix Item           | **n** |
| <code>]q</code>               | Next Trouble/Quickfix Item               | **n** |

## [which-key.nvim](https://github.com/folke/which-key.nvim.git)

| Key                                   | Description                   | Mode  |
| ------------------------------------- | ----------------------------- | ----- |
| <code>&lt;c-w&gt;&lt;space&gt;</code> | Window Hydra Mode (which-key) | **n** |
| <code>&lt;leader&gt;?</code>          | Buffer Keymaps (which-key)    | **n** |

## [CopilotChat.nvim](https://github.com/CopilotC-Nvim/CopilotChat.nvim.git)

Part of [lazyvim.plugins.extras.ai.copilot-chat](/extras/ai/copilot-chat)

| Key                           | Description                  | Mode         |
| ----------------------------- | ---------------------------- | ------------ |
| <code>&lt;c-s&gt;</code>      | Submit Prompt                | **n**        |
| <code>&lt;leader&gt;a</code>  | +ai                          | **n**, **v** |
| <code>&lt;leader&gt;aa</code> | Toggle (CopilotChat)         | **n**, **v** |
| <code>&lt;leader&gt;ap</code> | Prompt Actions (CopilotChat) | **n**, **v** |
| <code>&lt;leader&gt;aq</code> | Quick Chat (CopilotChat)     | **n**, **v** |
| <code>&lt;leader&gt;ax</code> | Clear (CopilotChat)          | **n**, **v** |

## [mini.surround](https://github.com/echasnovski/mini.surround.git)

Part of [lazyvim.plugins.extras.coding.mini-surround](/extras/coding/mini-surround)

| Key              | Description                          | Mode         |
| ---------------- | ------------------------------------ | ------------ |
| <code>gsa</code> | Add Surrounding                      | **n**, **v** |
| <code>gsd</code> | Delete Surrounding                   | **n**        |
| <code>gsf</code> | Find Right Surrounding               | **n**        |
| <code>gsF</code> | Find Left Surrounding                | **n**        |
| <code>gsh</code> | Highlight Surrounding                | **n**        |
| <code>gsn</code> | Update `MiniSurround.config.n_lines` | **n**        |
| <code>gsr</code> | Replace Surrounding                  | **n**        |

## [neogen](https://github.com/danymat/neogen.git)

Part of [lazyvim.plugins.extras.coding.neogen](/extras/coding/neogen)

| Key                           | Description                   | Mode  |
| ----------------------------- | ----------------------------- | ----- |
| <code>&lt;leader&gt;cn</code> | Generate Annotations (Neogen) | **n** |

## [nvim-dap](https://github.com/mfussenegger/nvim-dap.git)

Part of [lazyvim.plugins.extras.dap.core](/extras/dap/core)

| Key                           | Description             | Mode  |
| ----------------------------- | ----------------------- | ----- |
| <code>&lt;leader&gt;da</code> | Run with Args           | **n** |
| <code>&lt;leader&gt;db</code> | Toggle Breakpoint       | **n** |
| <code>&lt;leader&gt;dB</code> | Breakpoint Condition    | **n** |
| <code>&lt;leader&gt;dc</code> | Run/Continue            | **n** |
| <code>&lt;leader&gt;dC</code> | Run to Cursor           | **n** |
| <code>&lt;leader&gt;dg</code> | Go to Line (No Execute) | **n** |
| <code>&lt;leader&gt;di</code> | Step Into               | **n** |
| <code>&lt;leader&gt;dj</code> | Down                    | **n** |
| <code>&lt;leader&gt;dk</code> | Up                      | **n** |
| <code>&lt;leader&gt;dl</code> | Run Last                | **n** |
| <code>&lt;leader&gt;do</code> | Step Out                | **n** |
| <code>&lt;leader&gt;dO</code> | Step Over               | **n** |
| <code>&lt;leader&gt;dP</code> | Pause                   | **n** |
| <code>&lt;leader&gt;dr</code> | Toggle REPL             | **n** |
| <code>&lt;leader&gt;ds</code> | Session                 | **n** |
| <code>&lt;leader&gt;dt</code> | Terminate               | **n** |
| <code>&lt;leader&gt;dw</code> | Widgets                 | **n** |

## [harpoon](https://github.com/ThePrimeagen/harpoon.git)

Part of [lazyvim.plugins.extras.editor.harpoon2](/extras/editor/harpoon2)

| Key                          | Description        | Mode  |
| ---------------------------- | ------------------ | ----- |
| <code>&lt;leader&gt;1</code> | Harpoon to File 1  | **n** |
| <code>&lt;leader&gt;2</code> | Harpoon to File 2  | **n** |
| <code>&lt;leader&gt;3</code> | Harpoon to File 3  | **n** |
| <code>&lt;leader&gt;4</code> | Harpoon to File 4  | **n** |
| <code>&lt;leader&gt;5</code> | Harpoon to File 5  | **n** |
| <code>&lt;leader&gt;h</code> | Harpoon Quick Menu | **n** |
| <code>&lt;leader&gt;H</code> | Harpoon File       | **n** |

## [mini.surround](https://github.com/echasnovski/mini.surround.git)

Part of [lazyvim.plugins.extras.editor.leap](/extras/editor/leap)

| Key             | Description | Mode  |
| --------------- | ----------- | ----- |
| <code>gz</code> | +surround   | **n** |

## [refactoring.nvim](https://github.com/ThePrimeagen/refactoring.nvim.git)

Part of [lazyvim.plugins.extras.editor.refactoring](/extras/editor/refactoring)

| Key                           | Description              | Mode         |
| ----------------------------- | ------------------------ | ------------ |
| <code>&lt;leader&gt;r</code>  | +refactor                | **n**, **v** |
| <code>&lt;leader&gt;rb</code> | Extract Block            | **n**        |
| <code>&lt;leader&gt;rc</code> | Debug Cleanup            | **n**        |
| <code>&lt;leader&gt;rf</code> | Extract Block To File    | **n**        |
| <code>&lt;leader&gt;rf</code> | Extract Function         | **v**        |
| <code>&lt;leader&gt;rF</code> | Extract Function To File | **v**        |
| <code>&lt;leader&gt;ri</code> | Inline Variable          | **n**, **v** |
| <code>&lt;leader&gt;rp</code> | Debug Print Variable     | **n**, **v** |
| <code>&lt;leader&gt;rP</code> | Debug Print              | **n**        |
| <code>&lt;leader&gt;rs</code> | Refactor                 | **v**        |
| <code>&lt;leader&gt;rx</code> | Extract Variable         | **v**        |

## [snacks.nvim](https://github.com/folke/snacks.nvim.git)

Part of [lazyvim.plugins.extras.editor.snacks_explorer](/extras/editor/snacks_explorer)

| Key                           | Description                | Mode  |
| ----------------------------- | -------------------------- | ----- |
| <code>&lt;leader&gt;e</code>  | Explorer Snacks (root dir) | **n** |
| <code>&lt;leader&gt;E</code>  | Explorer Snacks (cwd)      | **n** |
| <code>&lt;leader&gt;fe</code> | Explorer Snacks (root dir) | **n** |
| <code>&lt;leader&gt;fE</code> | Explorer Snacks (cwd)      | **n** |

## [snacks.nvim](https://github.com/folke/snacks.nvim.git)

Part of [lazyvim.plugins.extras.editor.snacks_picker](/extras/editor/snacks_picker)

| Key                                      | Description                         | Mode         |
| ---------------------------------------- | ----------------------------------- | ------------ |
| <code>&lt;leader&gt;&lt;space&gt;</code> | Find Files (Root Dir)               | **n**        |
| <code>&lt;leader&gt;,</code>             | Buffers                             | **n**        |
| <code>&lt;leader&gt;/</code>             | Grep (Root Dir)                     | **n**        |
| <code>&lt;leader&gt;:</code>             | Command History                     | **n**        |
| <code>&lt;leader&gt;fb</code>            | Buffers                             | **n**        |
| <code>&lt;leader&gt;fB</code>            | Buffers (all)                       | **n**        |
| <code>&lt;leader&gt;fc</code>            | Find Config File                    | **n**        |
| <code>&lt;leader&gt;ff</code>            | Find Files (Root Dir)               | **n**        |
| <code>&lt;leader&gt;fF</code>            | Find Files (cwd)                    | **n**        |
| <code>&lt;leader&gt;fg</code>            | Find Files (git-files)              | **n**        |
| <code>&lt;leader&gt;fp</code>            | Projects                            | **n**        |
| <code>&lt;leader&gt;fr</code>            | Recent                              | **n**        |
| <code>&lt;leader&gt;fR</code>            | Recent (cwd)                        | **n**        |
| <code>&lt;leader&gt;gd</code>            | Git Diff (hunks)                    | **n**        |
| <code>&lt;leader&gt;gs</code>            | Git Status                          | **n**        |
| <code>&lt;leader&gt;gS</code>            | Git Stash                           | **n**        |
| <code>&lt;leader&gt;n</code>             | Notification History                | **n**        |
| <code>&lt;leader&gt;s"</code>            | Registers                           | **n**        |
| <code>&lt;leader&gt;s/</code>            | Search History                      | **n**        |
| <code>&lt;leader&gt;sa</code>            | Autocmds                            | **n**        |
| <code>&lt;leader&gt;sb</code>            | Buffer Lines                        | **n**        |
| <code>&lt;leader&gt;sB</code>            | Grep Open Buffers                   | **n**        |
| <code>&lt;leader&gt;sc</code>            | Command History                     | **n**        |
| <code>&lt;leader&gt;sC</code>            | Commands                            | **n**        |
| <code>&lt;leader&gt;sd</code>            | Diagnostics                         | **n**        |
| <code>&lt;leader&gt;sD</code>            | Buffer Diagnostics                  | **n**        |
| <code>&lt;leader&gt;sg</code>            | Grep (Root Dir)                     | **n**        |
| <code>&lt;leader&gt;sG</code>            | Grep (cwd)                          | **n**        |
| <code>&lt;leader&gt;sh</code>            | Help Pages                          | **n**        |
| <code>&lt;leader&gt;sH</code>            | Highlights                          | **n**        |
| <code>&lt;leader&gt;si</code>            | Icons                               | **n**        |
| <code>&lt;leader&gt;sj</code>            | Jumps                               | **n**        |
| <code>&lt;leader&gt;sk</code>            | Keymaps                             | **n**        |
| <code>&lt;leader&gt;sl</code>            | Location List                       | **n**        |
| <code>&lt;leader&gt;sm</code>            | Marks                               | **n**        |
| <code>&lt;leader&gt;sM</code>            | Man Pages                           | **n**        |
| <code>&lt;leader&gt;sp</code>            | Search for Plugin Spec              | **n**        |
| <code>&lt;leader&gt;sq</code>            | Quickfix List                       | **n**        |
| <code>&lt;leader&gt;sR</code>            | Resume                              | **n**        |
| <code>&lt;leader&gt;su</code>            | Undotree                            | **n**        |
| <code>&lt;leader&gt;sw</code>            | Visual selection or word (Root Dir) | **n**, **x** |
| <code>&lt;leader&gt;sW</code>            | Visual selection or word (cwd)      | **n**, **x** |
| <code>&lt;leader&gt;uC</code>            | Colorschemes                        | **n**        |

## [todo-comments.nvim](https://github.com/folke/todo-comments.nvim.git)

Part of [lazyvim.plugins.extras.editor.snacks_picker](/extras/editor/snacks_picker)

| Key                           | Description    | Mode  |
| ----------------------------- | -------------- | ----- |
| <code>&lt;leader&gt;st</code> | Todo           | **n** |
| <code>&lt;leader&gt;sT</code> | Todo/Fix/Fixme | **n** |

## [nvim-dap-python](https://github.com/mfussenegger/nvim-dap-python.git)

Part of [lazyvim.plugins.extras.lang.python](/extras/lang/python)

| Key                            | Description  | Mode  |
| ------------------------------ | ------------ | ----- |
| <code>&lt;leader&gt;dPc</code> | Debug Class  | **n** |
| <code>&lt;leader&gt;dPt</code> | Debug Method | **n** |

## [neotest](https://github.com/nvim-neotest/neotest.git)

Part of [lazyvim.plugins.extras.test.core](/extras/test/core)

| Key                           | Description                   | Mode  |
| ----------------------------- | ----------------------------- | ----- |
| <code>&lt;leader&gt;t</code>  | +test                         | **n** |
| <code>&lt;leader&gt;tl</code> | Run Last (Neotest)            | **n** |
| <code>&lt;leader&gt;to</code> | Show Output (Neotest)         | **n** |
| <code>&lt;leader&gt;tO</code> | Toggle Output Panel (Neotest) | **n** |
| <code>&lt;leader&gt;tr</code> | Run Nearest (Neotest)         | **n** |
| <code>&lt;leader&gt;ts</code> | Toggle Summary (Neotest)      | **n** |
| <code>&lt;leader&gt;tS</code> | Stop (Neotest)                | **n** |
| <code>&lt;leader&gt;tt</code> | Run File (Neotest)            | **n** |
| <code>&lt;leader&gt;tT</code> | Run All Test Files (Neotest)  | **n** |
| <code>&lt;leader&gt;tw</code> | Toggle Watch (Neotest)        | **n** |

## [nvim-dap](https://github.com/mfussenegger/nvim-dap.git)

Part of [lazyvim.plugins.extras.test.core](/extras/test/core)

| Key                           | Description   | Mode  |
| ----------------------------- | ------------- | ----- |
| <code>&lt;leader&gt;td</code> | Debug Nearest | **n** |

<!-- keymaps:end -->
