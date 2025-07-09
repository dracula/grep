### [grep](https://en.wikipedia.org/wiki/Grep)

#### Theme Configuration

**Important:** The configuration method depends on your grep implementation. Use the appropriate section below based on your system.

##### BSD grep

**Compatible Systems:**

- [FreeBSD grep](https://man.freebsd.org/cgi/man.cgi?grep%281%29);
- [macOS grep](https://ss64.com/mac/grep.html).

###### Configuration

Add the following to your shell configuration file (`.bashrc`, `.zshrc`, etc.):

```shell
# Dracula theme for BSD grep - https://draculatheme.com/grep
export GREP_COLOR="1;38;2;255;85;85"
```

##### [GNU grep](https://www.gnu.org/software/grep/)

###### Configuration

Add the following to your shell configuration file (`.bashrc`, `.zshrc`, etc.):

```shell
# Dracula theme for GNU grep - https://draculatheme.com/grep
export GREP_COLORS="mt=1;38;2;255;85;85:fn=38;2;255;121;198:ln=38;2;80;250;123:bn=38;2;80;250;123:se=38;2;139;233;253"
```

> **Color Scheme Breakdown (GNU grep):**
>
> - **mt** (match): Red (`#ff5555`) - highlighted matches;
> - **fn** (filename): Pink (`#ff79c6`) - file names;
> - **ln** (line number): Green (`#50fa7b`) - line numbers;
> - **bn** (byte offset): Green (`#50fa7b`) - byte offsets;
> - **se** (separator): Cyan (`#8be9fd`) - separators;

#### Activating theme

After adding the configuration, restart your shell or run `source ~/.bashrc` (or your respective config file) to **apply** the changes. 🦇
