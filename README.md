# Pokémon Gold and Silver: Space World 1997 Demo [![Build Status][ci-badge]][ci]

This is a work-in-progress disassembly of the Pokémon Gold and Pokémon Silver prototypes demoed at Space World 1997.

It builds the following ROMs:

- pokegold-spaceworld-correctheader.gb
- pokegold-spaceworld.gb

You will need to provide a copy of the Pokémon Gold - Spaceworld 1997 Demo (Debug).sgb renamed **baserom.gb** to build the ROMs.
You can get the debug rom [here][romlink]

When building on macOS, make sure to install the latest version of make from homebrew.
When building the Makefile, use `gmake` instead of `make`.

Currently, there's an issue when compiling a map during the first compilation. However, if you run `gmake` a second time, the ROM should compile.

## See also

- **Discord:** [pret][discord]
- **IRC:** [libera#pret][irc]

Other disassembly projects:

- [**Pokémon Red/Blue**][pokered]
- [**Pokémon Yellow**][pokeyellow]
- [**Pokémon Gold**][pokegold]
- [**Pokémon Crystal**][pokecrystal]
- [**Pokémon Pinball**][pokepinball]
- [**Pokémon TCG**][poketcg]
- [**Pokémon Ruby**][pokeruby]
- [**Pokémon FireRed**][pokefirered]
- [**Pokémon Emerald**][pokeemerald]

[romlink]: https://tcrf.net/Proto:Pokémon_Gold_and_Silver/Spaceworld_1997_Demo
[pokered]: https://github.com/pret/pokered
[pokeyellow]: https://github.com/pret/pokeyellow
[pokegold]: https://github.com/pret/pokegold
[pokecrystal]: https://github.com/pret/pokecrystal
[pokepinball]: https://github.com/pret/pokepinball
[poketcg]: https://github.com/pret/poketcg
[pokeruby]: https://github.com/pret/pokeruby
[pokefirered]: https://github.com/pret/pokefirered
[pokeemerald]: https://github.com/pret/pokeemerald
[discord]: https://discord.gg/d5dubZ3
[irc]: https://web.libera.chat/?#pret
[ci]: https://github.com/pret/pokegold-spaceworld/actions
[ci-badge]: https://github.com/pret/pokegold-spaceworld/actions/workflows/main.yml/badge.svg
