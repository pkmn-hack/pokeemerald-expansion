# pokemon-eoris

<!-- TODO: One or two sentences pitching the game. -->

Pokémon Eoris is a Pokémon ROM hack for the Game Boy Advance, set in a brand-new Eoris region loosely based on Germany. The journey begins in the small town of **Segfield**.

> ⚠️ **Work in progress.** The game is in early development and not yet playable from start to finish.

## Building

No ROM is distributed; the game is built from source. Follow the setup and build instructions in [`INSTALL.md`](INSTALL.md). In short, once the toolchain is installed:

```bash
make
```

The resulting ROM is `pokeemerald.gba`.

### Tools

- [porymap](https://github.com/huderlem/porymap) for map editing (project settings are tracked in `porymap.project.cfg`)
- [poryscript](https://github.com/huderlem/poryscript) for event scripts (`.pory` files are compiled automatically during `make`)

## Credits

Based off RHH's pokeemerald-expansion 1.17.2 https://github.com/rh-hideout/pokeemerald-expansion/

**pokeemerald-expansion** is built on top of [pret's `pokeemerald`](https://github.com/pret/pokeemerald) decompilation project. Thanks to RHH (Rom Hacking Hideout) and [all contributors](CREDITS.md) of pokeemerald-expansion, and to pret for the original decompilation.

Pokémon is © Nintendo, Creatures Inc. and GAME FREAK inc. This is a non-commercial fan project and is not affiliated with or endorsed by them.
