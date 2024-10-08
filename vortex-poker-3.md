Vortex Poker 3 Config
=====================

I visualised the config for the layers on my Vortex Poker 3 keyboards with www.keyboard-layout-editor.com. It works by storing your config in a JSON file that you keep in a gist.

The Poker 3 is a 60% keyboard, which means it's missing a bunch of standard keys. There aren't an F keys, no cursor keys, and no numeric keypad. You can access all these features by pressing a special "Fn" (function) key down, to switch the keyboard to a separate "layer".

I have two gists, one for each layer.

- [Alphanumeric layer] — active by default ([gist][alpha gist])
- ["Function" layer] — active when "Fn" is pressed ([gist][fn gist])

My config is as close to "stock" as I felt I could get away with, as programming the Poker 3 is a bit of a chore.

Note the Vim-compatible navigation on the function layer:

- Arrow keys are handled by h, j, k, and l
- PgUp and PgDown are duplicated on C-f and C-b

[alphanumeric layer]: https://www.keyboard-layout-editor.com/#/gists/bf2fa61d4849df71a0f924ff45be9bff
[alpha gist]: https://gist.github.com/gma/bf2fa61d4849df71a0f924ff45be9bff
["Function" layer]: https://www.keyboard-layout-editor.com/#/gists/965e601433f5821fa84e82df3ba4ad1c
[fn gist]: https://gist.github.com/gma/965e601433f5821fa84e82df3ba4ad1c
