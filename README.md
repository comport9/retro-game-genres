# Retro game genres

One genre for each retro console, handheld and arcade game: 13,557 games in 17 lists.

Most game databases file a large share of retro games under a catch-all "Action". These lists use a fixed set of
narrower genres (Action RPG, Run and Gun, Action Strategy and so on) and give every game exactly one, chosen by how
the game plays, not its theme.

## Lists

| System | Games |
|---|---|
| [Atari 2600](lists/a2600.tsv) | 456 |
| [Atari 7800](lists/a7800.tsv) | 98 |
| [Arcade (every FBNeo board)](lists/arcade.tsv) | 2,416 |
| [ColecoVision](lists/coleco.tsv) | 123 |
| [Famicom Disk System](lists/fds.tsv) | 180 |
| [Game Boy / Game Boy Color](lists/gb.tsv) | 2,186 |
| [Sega Game Gear](lists/gg.tsv) | 378 |
| [Atari Lynx](lists/lynx.tsv) | 104 |
| [Sega Mega Drive / Genesis](lists/md.tsv) | 1,302 |
| [MSX / MSX2](lists/msx.tsv) | 404 |
| [NES / Famicom](lists/nes.tsv) | 2,309 |
| [Neo Geo Pocket / Color](lists/ngp.tsv) | 84 |
| [PC Engine / TurboGrafx-16 (HuCard and CD)](lists/pce.tsv) | 724 |
| [Sega SG-1000](lists/sg.tsv) | 92 |
| [Sega Master System / Mark III](lists/sms.tsv) | 471 |
| [SNES / Super Famicom](lists/snes.tsv) | 2,081 |
| [WonderSwan / WonderSwan Color](lists/ws.tsv) | 149 |

Each list is a tab-separated file, one game per line: `Genre<TAB>Title`. Lines starting with `#` are comments.

- Console and handheld titles are [No-Intro](https://no-intro.org) / [Redump](http://redump.org) names with the
  region, language and version tags dropped, so one line covers every release of a game:
  `Herzog Zwei (USA, Europe)` is listed as `Herzog Zwei`.
- Arcade titles are [FinalBurn Neo](https://github.com/finalburnneo/FBNeo) game names (every board; bootlegs and hacks
  left out). Several sets can share one title.
- The lists were drawn from the full catalogues, not one collection. A game is left out when its genre wasn't known
  well enough to file it, so not every game appears.

## Genres

| Genre | What belongs in it |
|---|---|
| Action | Action that fits nothing narrower: arena, single-screen and early arcade-style action |
| Action-Adventure | Exploration with real-time combat and items, little or no levelling: Zelda, Metroid, Castlevania II, Landstalker-like without stats |
| Action RPG | Real-time combat with levels, stats and gear: Secret of Mana, Ys, Soleil, Beyond Oasis/Story of Thor, Landstalker |
| Role-Playing | Turn-based or menu-based role-playing: Dragon Quest, Final Fantasy, Phantasy Star |
| Tactical RPG | Role-playing fought on a grid or map, unit by unit: Fire Emblem, Shining Force, Langrisser |
| Strategy | Turn-based war, empire and wargames: Romance of the Three Kingdoms, Nobunaga's Ambition, Military Madness, Advance Wars-style |
| Action Strategy | Real-time strategy, and strategy mixed with direct action: Herzog Zwei, Dune II, Rampart, Cannon Fodder, Mega-lo-Mania |
| Simulation | Running or piloting something: city builders, business, flight and life sims, raising sims, train sims, submarine sims |
| Platformer | Running and jumping across platforms: Mario, Sonic, Mega Man |
| Run and Gun | Platform shooting on foot: Contra, Gunstar Heroes, Metal Slug |
| Shoot 'em Up | Scrolling or fixed shooters in a ship or vehicle: Gradius, R-Type, Thunder Force, Galaga |
| Shooter | First-person, rail, gallery and light-gun shooting: Duck Hunt, Operation Wolf, Wolfenstein |
| Beat 'em Up | Brawling through scrolling stages: Streets of Rage, Final Fight, Golden Axe |
| Fighting | One-on-one or versus fighting: Street Fighter, Mortal Kombat |
| Racing | Driving, racing and kart games: F-Zero, OutRun, Super Monaco GP |
| Sports | Real and invented sports, fishing and hunting: football, golf, boxing, wrestling, horse racing |
| Puzzle | Block, logic and puzzle-action games: Tetris, Puyo Puyo, Columns, Lemmings |
| Maze | Maze chase and dig games: Pac-Man, Dig Dug, Bomberman, Lode Runner |
| Adventure | Story-led adventures without action combat: point-and-click, text, visual novels |
| Board and Card | Board, card, mahjong, shogi, casino, pachinko and party games |
| Pinball | Pinball tables |
| Quiz | Quiz and trivia |
| Music | Rhythm and music-making |
| Educational | Learning games for children and adults |
| Compilation | Several separate games on one cartridge or disc |
| Other | Not a game: tools, test carts, demos, music players |

## How they were made

The games were filed with the help of AI, from its knowledge of each game, against the table above; games it didn't
know were left out rather than guessed. Expect some mistakes. Corrections are welcome as issues or pull requests.

## Licence

[CC0 1.0](LICENSE): public domain. Use the lists for anything, with or without credit.
