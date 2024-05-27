# xontrib-fzf-completions

The project is a more updated fork of https://github.com/shahinism/xontrib-fzf-widgets (Hopefully more responsive to
PRs), providing [`fzf`](https://github.com/junegunn/fzf) completions into your [xonsh](https://github.com/xonsh/xonsh)
shell.

## Installation

```shell
# Install the xontrib
xpip install -U xontrib-fzf-completions

# Load it
xpip load fzf-completions
```

Define the key-binding in your `.xonshrc`:

```python
from xonsh.built_ins import XSH

XSH.env['fzf_history_binding'] = "c-r"  # Ctrl+R
XSH.env['fzf_ssh_binding'] = "c-s"  # Ctrl+S
XSH.env['fzf_file_binding'] = "c-t"  # Ctrl+T
XSH.env['fzf_dir_binding'] = "c-g"  # Ctrl+G
```
