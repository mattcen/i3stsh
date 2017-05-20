# i3stsh
An [i3st]atus replacement written in ba[sh]

## How to use

**WARNING: use this software at your own risk. There are probably bad bugs as I
wrote it in a rush one afternoon.**

Download `i3stsh` into your local bin, e.g.:

```
cd ~/.local/bin/; wget -c https://raw.githubusercontent.com/cjbayliss/i3stsh/master/i3stsh
```

Next make it exucutible:

```
chmod +x ~/.local/bin/i3stsh
```

Now change the config for i3wm to use `i3stsh`, e.g. in `~/.i3/config` replace
the similar looking part with:

```
bar {
        separator_symbol "|"
        status_command "~/.local/bin/i3stsh"
}
```

Lastly restart i3wm.
