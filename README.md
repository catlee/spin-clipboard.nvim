# spin-clipboard.nvim

_spin-clipboard.nvim_ is a plugin to configure the clipboard when running in [spin](https://shopify.engineering/shopifys-cloud-development-journey)

This allows copying and pasting using the `*` or `+` registers in your remote nvim session to use your local machine's clipboard.

## Installation

With [Lazy.nvim](https://github.com/folke/lazy.nvim/tree/main):

```lua
{ "catlee/spin-clipboard.nvim", event = "VeryLazy", opts = {} }
```
