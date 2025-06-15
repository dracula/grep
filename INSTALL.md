### [grep](https://en.wikipedia.org/wiki/Grep)

#### Set up the theme

##### BSD grep

This is known to apply at least to the following:

- [FreeBSD grep](https://man.freebsd.org/cgi/man.cgi?grep%281%29)
- [macOS grep](https://ss64.com/mac/grep.html)

Set the `GREP_COLOR` environment variable in your shell and make sure
it is exported, typically for example:

```shell
# https://draculatheme.com/grep
GREP_COLOR="1;38;2;255;85;85"
export GREP_COLOR
```

##### [GNU grep](https://www.gnu.org/software/grep/)

Set the `GREP_COLORS` environment variable in your shell and make sure
it is exported, typically for example:

```shell
# https://draculatheme.com/grep
GREP_COLORS="mt=1;38;2;255;85;85:fn=38;2;255;121;198:ln=38;2;80;250;123:bn=38;2;80;250;123:se=38;2;139;233;253"
export GREP_COLORS
```
