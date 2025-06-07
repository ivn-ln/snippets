# My luasnip snippets

Snippets for use with [Neovim](https://neovim.io) and [LuaSnip](https://github.com/L3MON4D3/LuaSnip).

## Features

### GDScript Snippets

#### `###`  
Creates a comment block banner:

```gdscript
###   block name   ###
```

Trigger: Type `###` and expand the snippet.

---

#### `connect`  
Quickly set up a signal connection function:

```gdscript
var _on_<signal_name> = func(<args>):
	<cursor>
	_on_<signal_name>.connect(<signal_name>)
```

This snippet auto-fills the signal name and places the cursor inside the handler body. It also auto-indents the code properly after expansion.

Trigger: Type `connect` and expand.

---
